# sim_rig_smart_lights
Smart lights that respond to braking and acceleration when sim racing

demo video here: 
https://youtu.be/9VD9JGLm2NQ

requires:
* sim hub
* home assistant
* smart lights

1. Install and configure the mqtt publisher plugin on simhub. You'll find it in this repository: https://github.com/SHWotever/SimHub-MQTT-Publisher
2. Enter "simhub" as the mqtt topic in the mqtt publisher plugin. 
3. Install the mosquitto mqtt add-on in home assistant ( instructions here https://github.com/home-assistant/addons/blob/master/mosquitto/DOCS.md )
4. Create sensors for your brake, throttle, and shifter by adding the code from the "sensors" file in this reposotory to the configuration.yaml file in your home assistant installation. ( Instructions on how to access and edit configuration.yaml here https://www.home-assistant.io/docs/configuration/ )
5. Create 4 automations in home assistant by copying and pasting the yaml code in my braking and throttle files

Note: you'll need to add the device id for your lights to the code for the automations. 

I used Govee Glide Lively lights
https://us.govee.com/products/govee-glide-lively-wall-lights
