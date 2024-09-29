flowchart TD
    A[**Hacker**] 
      --> B(**BotNet**
      The attacker activates a massive network of bots to overwhelm the flow traffic within the targets network )  --<C(Webserver)
    B --> C{**WebServer**
    Once the flood of BotNets reaches the the webserver and floods the network, the server is no longer able to sustain and deliver its services to the internal or external network, thus leaving the server and its devices connected to it unable to communicate externally}
    C -->|1| D[Windows Laptop]
    C -->|2| E[iPhone]
    C -->|3| F[Workstation]
    C -->|4| G[Mac Laptop]

1. In the process of the attacker has already installed a command and controll remote connection to the targeted webserver
2. Once the BotNet is activated and if the target has no IPS or firewall to block the oncoming traffic, the botnet will flood the targeted server
3. When the targeted server recieves all the oncoming traffic from the external sources it will not be able to tolerate all the data traffic from the external or internal network
4. When the targeted server is flooded it is no longer able to provide services such as email, streaming, upload, or download outside the local network. 
