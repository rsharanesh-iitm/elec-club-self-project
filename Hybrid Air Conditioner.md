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
