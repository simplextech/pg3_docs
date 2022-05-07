
# ST-Sonos
#### Documentation is a work in progress

Sonos Player integration with Polisy utilizing the excellent
Jishi node-sonos-http-api (https://github.com/jishi/node-sonos-http-api)

Most (not all) of the features and capabilities of node-sonos-http-api
has been integrated into a Node Server for access through the 
Admin Console interface and for use in programs.

The Jishi interface is automatically installed as part of this Node Server
installation and can be accessed and used as if installed independently.

Substitute 'localhost' with the IP address of your Polisy
Jishi Default Web Interface: (http://localhost:5005)

For a detailed list of Jishi functionality and available actions please
reference the node-sonos-http-api documentation: (https://github.com/jishi/node-sonos-http-api)

#### Disclaimer
- Functionality of this Node Server is dependent on node-sonos-http-api.  Any breaking
changes upstream may have adverse effects on functionalty or usability.  

## Configuration
- Self configuring
  - Sonos Players are discovered and Nodes added automatically or from Admin Console 'Discover Players' button

- Text To Speech
  - 10 slots are provided for adding your own 'phrase' into the value section.