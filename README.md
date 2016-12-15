# DzPrototype
  
## Version 0.1

![schema prototype](https://hackpad-attachments.imgix.net/hackpad.com_d55JBV5B1Vy_p.602889_1472755256932_14215184_10154001154263915_845143439_o.jpg)

### Hardware
- Citizen Watt sensors
- Pine64+ boards with arduino to communicate with Citizen Watt sensors
- Arduino with relay shield
- Light bulb 

### Software
- CitizenWatt part
    - Sensor sketch  
https://github.com/CitoyensCapteurs/CitizenWatt-sensor  
    - CitizenWatt application (PINE64+ and arduino)  
https://github.com/DAISEE/CitizenWatt-Base-PINE64  
https://github.com/DAISEE/CitizenWatt-ArduinoBase   
- Ethereum part  
    - geth  
    https://github.com/ethereum/go-ethereum  
    - decentraliased application  
    https://github.com/DAISEE/DzApp  
- Connections between CitizenWatt and the DApp  
https://github.com/DAISEE/DzScripts  

The tag for DAISEE sources is **v0.1-beta** (pre-release).  

### Documentation
https://github.com/DAISEE/UrbanEntrepreneurs/wiki (in french)  

## Version 0.2 

In progress :)
  
TO DO   
- [ ] Back to Raspberry Pi 3 ( #1 )  
- [ ] Use of Parity instead of geth ( #2 )  
- [ ] Define a new algorithm for energy exchanges (management of pseudo real time) ( #3 )  
- [ ] Modify the data storage ( #4 )  
