# Swag_Gen_Factory

This script will take Swagger openapi.json file and generate kotlin network API code. Please find swagger info here https://swagger.io/

This script will help in generating kotlin code for network api call like Data request and responses, also this script will generate the Retrofit interface which includes abscract function with retrofit annotation.


## Prerequisite

You need ruby setup on your machine. 

You can check inside a terminal emulator by typing:

```ruby -v```

This should give some basic version information about ruby if ruby is already installed. 

If ruby is not installed you can refer here for installation process https://www.ruby-lang.org/en/documentation/installation/

## How to use this script

1. Download this script. 
2. Get the openapi.json from swagger editor 
3. Then just execute following script
```ruby gen_network_code.rb openapi.json```
4. After successful execution of script you will get NetworkApi.kt with request, response and retrofit interface.

Please let me know the feedback or raise the issues here.




