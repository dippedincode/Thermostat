# Thermostat
```
888   888                                                 888           888    
888   888                                                 888           888    
888   888                                                 888           888    
88888888888b.  .d88b. 888d88888888b.d88b.  .d88b. .d8888b 888888 8888b. 888888 
888   888 "88bd8P  Y8b888P"  888 "888 "88bd88""88b88K     888       "88b888    
888   888  88888888888888    888  888  888888  888"Y8888b.888   .d888888888    
Y88b. 888  888Y8b.    888    888  888  888Y88..88P     X88Y88b. 888  888Y88b.  
 "Y888888  888 "Y8888 888    888  888  888 "Y88P"  88888P' "Y888"Y888888 "Y888 
 ```
This program models a thermostat. The specification is:

- Thermostat starts at 20 degrees
- You can increase the temperature with an up function
- You can decrease the temperature with a down function
- The minimum temperature is 10 degrees
- If power saving mode is on, the maximum temperature is 25 degrees
- If power saving mode is off, the maximum temperature is 32 degrees
- Power saving mode is on by default
- You can reset the temperature to 20 with a reset function
- You can ask about the thermostat's current energy usage: < 18 is low-usage, < 25 is medium-usage, anything else is high-usage.
- (In the challenges where we add an interface, low-usage will be indicated with green, medium-usage indicated with black, high-usage indicated with red.)

### Model
![model-image](https://github.com/ejennings95/Thermostat/raw/master/public/images/thermostat-model-controller.png)