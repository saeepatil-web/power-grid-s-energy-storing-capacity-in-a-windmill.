Program statement-design a c program to simulate the operation of an electrical switch where the program takes input values of either 0 or 1 representing the switch being OFF or ON respectively .

RESEARCH:
To refine the topic,to ensure the information is credible and relevant and to develop a strong foundation for the arguments and the ideas.

  A basic "switch on and off system" uses an electrical switch to either complete an electric circuit, allowing current to flow and the device to turn on, or open the circuit, stopping the current and turning the device off. The switch has two states: "on" (closed circuit) and "off" (open circuit), where a physical action, like pressing a button or flipping a lever, changes the connection of internal contacts to control the flow of power to a device.  
The Circuit: An electrical circuit needs a closed loop of conductive material to allow electricity to flow from a power source to a device. 
The Switch's Role: A switch acts as a gatekeeper for this circuit. 
"On" Position (Closed Circuit): When you flip the switch to the "on" position, its internal contacts come together, completing the circuit. This allows the electrical current to flow, and the device (like a light or a computer) receives power and functions. 
"Off" Position (Open Circuit): When you flip the switch to the "off" position, the internal contacts separate, breaking the circuit. This prevents the flow of electricity, and the device receives no power and stops working.
 
ANALYSE:
A windmill is a machine that converts the wind’s kinetic energy into mechanical energy or electrical energy. Wind blows over the blades causing them to spin the rotor. This motion turns a shaft,which is connected to a generator,often with a gearbox to increase rotational speed .The generator then produces electricity through electromagnetic induction , which is sent through cables to the power grid.

IDEATE:
HYDROGEN POWER TO GAS(P2G): excess energy from wind turbines is used to split water into hydrogen and oxygen through electrolysis .The stored hydrogen can then be used as a fuel to generate electricity or in other applications when the wind is not blowing.
The green hydrogen can be stored,injected into the natural gas grid ,or combined with carbon dioxide to create methane for storage and transportation.
This c program is built to calculate the energy storage capacity of hydrogen to gas(P2G). This c program uses an if else statement ,the energy capacity is entered in % as input and the program states the hours the windmill is to be kept on .




BUILD:
PROGRAM BUILD:INDICATES THE ENERGY CAPACITY OF THE
ENERGY/POWER GRID IN A WINDMILL THAT PROVIDES ELECTRICITY
TO COMMUNITIES.

#include<stdio.h>
int main(){
    int energy_stored;
    printf("\n enter energy stored in percentage in the hydrogen power to gas(P2G):");
    scanf("%d",&energy_stored);
    if(energy_stored<=75){
        printf("\nwindmill should be kept on for at least 2 hours");
    }
    
    else if(energy_stored<=85){
        printf("windmill to be kept on for at least 1 hour");

    }
    else if(energy_stored<=95){
        printf("windmill to be kept on for at least 30 mins");

    }
    else if(energy_stored==100){
        printf(“hydrogen power to gas(PG2) capacity to store energy is full hence windmill to be switched off");
    }
    else{
        printf("enter agin");
    }

    
    return 0;
}
        

TEST:
Case 1: if energy stored in the hydrogen power to gas is 100%

 enter energy stored in percentage in the hydrogen power to gas(P2G):100
Hydrogen power to gas capacity to store energy is full hence windmill to be switched off

...Program finished with exit code 0
Press ENTER to exit the console.

Case 2: if energy stored in the hydrogen power to gas is less than or equal to 75
enter energy stored in percentage in the hydrogen power to gas(P2G):75

windmill should be kept on for at least 2 hours

...Program finished with exit code 0
Press ENTER to exit the console.

Case 3: if energy stored in the hydrogen to gas is less than or equal to 85%


 enter energy stored in percentage in the hydrogen to gas(P2G):77
windmill to be kept on for at least 1 hour

...Program finished with exit code 0
Press ENTER to exit the console.


