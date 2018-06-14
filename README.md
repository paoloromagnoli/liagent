# liagent
vRA Software Component to install vRLI agent

Requisites
- vRA up and running (I developed this using vRA 7.4, should work with previous versions that support Software Components)
- vRLI up and running (I developed this using vRLI 4.6.1, should work with previous versions)
- the VM where you install the agents has to: 
    - reach vRLI appliance on https protocol
    - have vRA agent installed
    - have curl installed
    - have sed installed

Download and Install
Just download this Software Component and import it into your vRA instance using CloudClient
