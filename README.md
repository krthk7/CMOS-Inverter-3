# CMOS-Inverter-3
### Inverter Layout
Whooo !! The last part of the project. This the last repository on the inverter where in I've designed the layout of the inverter. For this I've used the Electric VLSI tool and also integrated both LT spice and Electric for Simulation purpose.This part of the project deals in two phases Pre-Layout Simulation and Post Layout Simulation and also ill inculde the propagation dealy.

***
### Contents

- [ 1. Inverter Pre-Layout](#1-Inverter-Pre-Layout)
- [ 2. Inverter Post-Layout](#2-Inverter-Post-Layout)

***

## 1.Inverter Pre-Layout

This part deals with the simulation of inverter in pre-layout part. This is the same simulation that ive dicussed earlier just that it is executed in Electric.
Here is the schematic of the inverter.I've also created the inverter icon/symbol to use the same inverter for other projects. Notice ive changed the width of the inverter.<br />
<br>
**Schematic**
<br>
![CMOS-Inverter-3](./Images/Pre-layout1.png)<br>
<br>
**Output**
<br>
![CMOS-Inverter-3](./Images/Pre-layout2.png)<br>
Lets look into the propagation delay,notice ive not connected any load accross the output terminals of the inverter.<br />
<br>
**Schematic**
<br>
![CMOS-Inverter-3](./Images/Pre-layout3.png)<br>
<br>
**Output**
<br>
![CMOS-Inverter-3](./Images/Pre-layout4.png)<br>
<br>
The propagation delay got is 0.254986 sec or tp=254msec <br>
```
time1: time=35.5 at 35.5
time2: time=35.7552 at 35.7552
tplh: time2-time1=0.25518
time3: time=10.5 at 10.5
time4: time=10.2452 at 10.2452
tphl: time3-time4=0.254792
tp: 0.5*(tphl+tplh)=0.254986

```
***
## 2. Inverter Post-Layout
Now coming to the main part. The layout the electric provides the lamda length 100nm,where in i have used 2lamda/180nm.The stick diagram is also provided for reference.<br>
![CMOS-Inverter-3](./Images/Pre-layout5.png)<br>
**Layout**
![CMOS-Inverter-3](./Images/Post-layout1.png)<br>
<br>

With all these the project comes to an end.<br>
I had great amount learning in this process hope to post more such vlsi projects.<br>
Any suggestions are open.<br>
**Thank You***
