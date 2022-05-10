# ST-Shelly

###Requirements
- Static/Reserved IP for all Shelly devices
  - Used to setup Webhook for devices to send status
  - Used for faster response time for sensors

- Static/DHCP Setup Options
  - Setup a DHCP reservation in your DHCP server or
    router you use based on your device vendor
    instructions.
  - Setup the static IP directly on the Shelly device
    - This is done through the Shelly web interface on
      each device.  Refer to the Shelly manual.

### Parameters
- Enter the IP address for each device
- Device name and type are pulled from the device.  If no
  name is defined the default hostname/deviceId is used.  You can
  change the displayed name in the ISY Admin Console however
  this does not change the name on the Shelly device or
  the displayed name in the Shelly App
- Changing the name from the device web page or from the
  Shelly App does NOT change the name as displayed in the ISY
  Admin Console.
- NOTE: It is best to set the device name before adding to the Node Server

### Supported Devices
- Shelly PlugUS
- Shelly H&T
 
