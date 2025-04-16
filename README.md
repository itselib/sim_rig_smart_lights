# sim_rig_smart_lights
Smart lights that respond to braking and acceleration when sim racing

demo video here: 
https://youtu.be/9VD9JGLm2NQ

requires:
* sim hub
* home assistant
* smart lights

1. install and configure the mqtt plugin on simhub
2. install the mosquitto mqtt add-on in home assistant
3. in home assistant, create sensors for your brake, throttle, and shifter by editing the configuration.yaml file
4. create automations to trigger the lights
