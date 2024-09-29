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
