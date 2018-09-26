Download the VirtualBox VM in the release section or setup the project with the following steps.

SETUP INSTRUCTIONS

1 - Start a mongodb instance and create three collections (products, travels_test, vehicles) and then insert data through JSON file or 
    or dumps in mongodb folder.

2 - Start MQTT broker on default port 1883. (mosquitto, for example)

3 - Start the Java simualtor. (JDK 8)

4 - Import node-red palettes: node-red-contrib-crypto-js, node-red-contrib-mongodb3, node-red-dashboard

5. Import all node-red flows.

6. Connect to the node-red dashboard at: http://localhost:1880/ui/

This project is licensed under the terms of the Apache 2.0 License.
