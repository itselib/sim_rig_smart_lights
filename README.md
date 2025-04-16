# sim_rig_smart_lights
Smart lights that respond to braking and acceleration when sim racing

demo video here: 
https://youtu.be/9VD9JGLm2NQ

requires:
* sim hub
* home assistant
* smart lights

1. Install and configure the mqtt plugin on simhub. Set "simhub" as the mqtt topic. 
2. Install the mosquitto mqtt add-on in home assistant
3. Create sensors for your brake, throttle, and shifter by adding the code in my "sensors" file to the configuration.yaml file in your home assistant installation
4. Create 4 automations in home assistant by copying and pasting the yaml code in my braking and throttle files

Note: you'll need to add the device id for your lights to the code for the automations. 

I used Govee Glide Lively lights
https://us.govee.com/products/govee-glide-lively-wall-lights
