# Hybrid Air Conditioner
### Description
As the name suggests, the idea of the project is to make a Hybrid Air Conditioner that can be both used as a fan and a air conditioner. To add on, it can also be used as a room heater. The basic underlying principle in it is the Thermoelectric Cooling effect (TEC) using a peltier module. Also, it can be a portable Air Conditioner.

### Working Principle
The working is based on the peltier cooling effect. The peltier module is just a combination of many P-N junction diodes that are arranged in a sequential manner. It states that when power is applied to a peltier module then there is a current flow across it and heat is transferred from one side to the other. So, in this process one side of the module gets heated and other side gets cold. We utilize the cold side of it for the cooling purpose and expel the heat from the other side of it using a Heat sink. The important part in this process is to remove the heat from the other end and send it outside of the room. In fact the efficiency of the system depends on how we effectively we move the heat outside the cooling area. 

***To add the extra additional features we use arduino nano as the control unit.***

##### How is it hybrid?
The meaning of hybrid in this context is that it can be used as a cooler as well as a heater. Also, the AC can be used as fan without powering the peltier module. These options are made available in the remote. In order to use it as a heater, we can just reverse the current direction in the peltier module which would work in the exact opposite way.

##### Additional features
***Swing control***
To add a feature of swing control we use the servo motor along with a cardboard designed flaps attache to the servo. With the help of the arduino, as per the user's choice the swing control can be done.
***Remote control***
We use the IR communication principle in order to communicate from the remote to the main unit. We use an already existing remote in the market and use the defined pins in it as per our requirements.With those pins we add functionality as per our requirements.
***LCD display as the UI***
In order to display the temperature, mode of operation and the swing mode and the fan speed to the user, we use an 16X2 LCD display and then print the required information in it.

### Why Should I do this?
I am now currently living in a remote village, where the summer heat is breaking into my home, I need this so as to hava it as a Personal cooler so that I can use it during the noon when I work with my system. Also, it could be made as aportable cooler and can be taken anywhere if there is a power supply for it. My current situation motivates me to do this project.

### Limitations
The limitations of this are
1. It isn't that efficient as compared with the normal compression cooling sytsem.
2. There is a PWM mode of operation of the Peltier module, but in that case the efficiency and the life of the module is further decreased as compared to the normal constant current mode of operation. So in case if we need to control the temperature of cooling it's pretty difficult.

### Does a normal human being like it ?
Obviously, it will be liked by everyone because the current situation is that the average temperature of the earth is increasing and it will become a basic need for everyone to have a personal AC. Instead of buying a normal AC with refrierants that keeps on polluting the environment, one could use this. For bahelors who are in a singe room, it will be efficient and also the price is minimal. It can also be used as a portable one, which is a further advantage. So, a normal human being will like it.

#### Cost
The average estimate of it will be around ***Rs.4000 - Rs.5000***. The cost here depends on the components we use. For a good efficient one, high quality components needs to be used and so the cost is also higher. The efficiency of the product is highly decided by the components that are used.

#### Bill of Materials
|S.No|	Category|	Name|	Description|	Quantity|	Cost|	Price|
|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
|1|	Adjustible (If no need of a remote then no need for arduino, just an On/Off switch)|[Arduino Nano](https://robu.in/product/arduino-nano-board-3-0-with-ch340-chip-unsoldered/)|	Nano Board R3 with CH340 chip without USB Cable compatible with Arduino|	1	|220|	220|
|2|	Required|[Peltier Module](https://robu.in/product/tec1-12710-40x40-mm-heatsink-thermoelectric-cooler-cooling-peltier-plate-module/)|	TEC1-12710 40x40mm Thermoelectric Cooler 10A Peltier Module|	3	|350|	1050|
|3|	Required|[Cpu Cooling System(Banggood)](https://www.banggood.in/Aurora-CPU-Cooler-RGB-Cooling-Fan-4Pin-For-Intel-LGA-775-1150-1151-1155-1156-1366-AMD-p-1544768.html?gmcCountry=IN&currency=INR&createTmp=1&utm_source=googleshopping&utm_medium=cpc_bgs&utm_content=lijing&utm_campaign=pla-ing-ele-pc&cur_warehouse=CN)|	Aurora CPU Cooler RGB Cooling Fan 4Pin For Intel LGA 775 1150 1151 1155 1156 1366 AMD|	1|	1294|	1294|
|4|	Required|[Heat sink](https://robokits.co.in/3d-printer/accessories/heat-sink-for-stepper-motor-nema17-404011mm?gclid=CjwKCAjw5cL2BRASEiwAENqAPhb0KEFEPHPh7qaB_wxQuIEEUePhzuNxoxB7iOi3oYAg8i_9CkL4jxoCD0AQAvD_BwE)|	HEAT SINK FOR STEPPER MOTOR NEMA17 40*40*11MM|	2	|177|	354|
|5|	Required|[12V DC Fan](https://www.amazon.in/Electronicspices-Cooling-Cooler-Radiator-CONNECTOR/dp/B07ZTN54QK/ref=sr_1_5?dchild=1&keywords=12V+DC+Fan&qid=1590252998&replacementKeywords=12v+fan&sr=8-5&vehicle=DC%3AAvanti)|	Electronicspices DC 12V Cooling Fan for PC Case CPU Cooler Radiator WITH (JST CONNECTOR)|	3|	185|	555|
|6| Required|[12V 10A SMPS](https://www.trpmart.com/power-supply-smps/12-volt-15-amp-180w-smps-12v-15a-power-supply-smps-driver/)|	12V 10A - 120W - AC to DC Switching Mode Power Supply - SMPS - Dual Rail Output|	1|	520	|520|
|7|	Required|	[Servo Motor](https://robu.in/product/towerpro-sg90-9g-mini-servo-9-gram/)	|TowerPro SG90 Mini Servo – 180 degree Rotation – Standard Quality	|1|	100|	100|
|8|	Adjustible (if arduino isn't used then this can be compromised)	|[IR Remote contol](https://robu.in/product/hx1838-vs1838-nec-infrared-ir-wireless-remote-control-sensor-module-arduino/?gclid=Cj0KCQjwwr32BRD4ARIsAAJNf_3kCvsSDDRyXi4mDNhyIc0WHh6VnjDV0UWZDrDbVlMYGuTxLXJbx1IaAqcHEALw_wcB)|	HX1838 VS1838 NEC Infrared IR Remote Control Sensor Module For arduino|	1|	130|	130|
|9|	Adjustible (if arduino isn't used then this can be compromised)	|[LCD Display](https://www.amazon.in/xcluma-Adjustable-Serial-Module-Arduino/dp/B071Z8VMWJ/ref=sr_1_5?crid=38A3B8GBSFEIA&dchild=1&keywords=lcd+display+for+arduino&qid=1590725586&s=industrial&sprefix=lcd%2Cindustrial%2C361&sr=1-5)|	xcluma Adjustable Back Light Iic/I2C/Twi/Spi Serial Module Arduino With Blue 1602 Lcd|	1|	302|	302|
|10|	Required|[Temperature sensor](https://robu.in/product/dht-11-digital-temperature-humidity-sensor/?gclid=Cj0KCQjwwr32BRD4ARIsAAJNf_2HPfG8Lp045axetvQamiVWeDEf4TBN0h_XI8VqMBTwyBM-RdI2qNwaAtZNEALw_wcB)|	DHT-11 Digital Temperature And Humidity Sensor|	1|	100|	100|
|11|	Required|	[Water cooling system](https://www.banggood.in/4080120160200mm-Aluminium-Alloy-CPU-Water-Cooling-Block-Water-Blocks-Radiator-Liquid-Cooler-p-1301782.html?rmmds=detail-top-buytogether-auto&ID=42256&cur_warehouse=CN)|	Aluminium Alloy CPU Water Cooling Block Water Blocks Radiator Liquid Cooler- 40mm|	1	|417|	417|
|12|	Required|	[Radiator for efficient water cooling](https://www.banggood.in/90120240360mm-Computer-Aluminum-PC-Water-Cooling-System-Equipment-Heat-Dissipation-Radiator-p-1439319.html?gmcCountry=IN&currency=INR&createTmp=1&utm_source=googleshopping&utm_medium=cpc_bgs&utm_content=lijing&utm_campaign=pla-ing-&ID=567406&cur_warehouse=CN)|	Computer Aluminum PC Water Cooling System Equipment Heat Dissipation Radiator - 120mm|	1|	1295|	1295|
						
***Total (Including Adjustibe) = Rs 6337 (Approx = 6500)***

***Total (Excluding Adjustibe) = Rs 5680 (Approx = 5600)***	


