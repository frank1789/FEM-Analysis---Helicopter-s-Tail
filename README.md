# FEM Analysis - Helicopter's Tail

Study of vibrational tail helicopter behavior [Eurocopter AS350](https://it.wikipedia.org/wiki/Aérospatiale_AS_350_Écureuil) :helicopter:, where all historical and other information is available.

|General characteristics|		|
|-----------------------|--------------:|
|Length   		|	 12.94 m|
|Height			|	  3.34 m|
|Main rotor diameter 	| 	10.69 m |
|Empty weight		| 	1220 kg |
|Max takeoff weight 	| 	2250 kg |
|capability		|	 2500 kg|
|**Propulsion**		|		|
|Powerplant	  	| 1 x Turbine<br> Turbomeca Arriel 1D1|
|Power			|	  546 kW|
|**Performance**		|		|
|Maximum speed  	| 	287 km/h|
|Range	        	| 	476 km	|
|service ceiling 	| 	6100 m  |
    

## Shell model
The geometric model is shared among three different configuration where was enfatizated a different approach to evalute the repsonce of structural elemtents in different condition of approximation. Infact the [first model](first_model) case is an evalution of the simple model where considering only tail like as a cantilever beam. 
While in the [second case](#2ndmodel) considering also the trasmission shaft rigidly linked at the tail and the presence of a lumped mass to simulate the persence of the block of rotor in the proximity the end of tail. 
Finally consider a [third model](#3rdmodel) where we considering the shaft's weight is distributed along the lenght of tail like as lumped mass, we consider as before another concentrated mass to represent the block of rotor at the tail's end.

***

### simple version
<a name="first_model"></a>The result is the following...
![Result](https://github.com/frank1789/FEM-Analysis---Helicopter-s-Tail/blob/develop/Report/imgs/ShellModel/Shellmodel002.png "Shell model - simple version")


***

### shafted version
<a name="2ndmodel"></a>The result is the following...
![Result](https://github.com/frank1789/FEM-Analysis---Helicopter-s-Tail/blob/develop/Report/imgs/ShellModelShaft/ShellmodelShaft004.png "Shell model - shafted version")


***

### lumped mass version
<a name="3rdmodel"></a>The result is the following...
![Result](https://github.com/frank1789/FEM-Analysis---Helicopter-s-Tail/blob/develop/Report/imgs/ShellModelShaftLumped/ShellmodelShaftLumped004.png "Shell model - lumped mass version")


## Macro
+ testperson.mac
+ calcmass.mac
+ distancenode.mac
+ rotor.mac

## Report
The complete report about dynamic analisys for tailboom helicopter is aviable [here](https://github.com/frank1789/FEM-Analysis---Helicopter-s-Tail/)
