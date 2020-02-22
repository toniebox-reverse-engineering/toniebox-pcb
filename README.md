

# Toniebox PCB

Repository which will lead to a complete schematic of a Toniebox PCB. The schematic is done with KiCad.

View this project on [CADLAB.io](https://cadlab.io/project/2472). 

Source of CC3200 footprint: https://raw.githubusercontent.com/Turegano/CC3200/master/lib/CC3200.lib



## Table Of Contents
- [Toniebox PCB](#toniebox-pcb)
  - [Table Of Contents](#table-of-contents)
  - [Folders](#folders)
  - [Status](#status)
  - [Testpoints](#testpoints)


## Folders

* [datasheets](datasheets/)
* [doc](doc/): documentation
* [library](library/): KiCad libraries

## Status


![Top](doc/progress_top.png)

![Bottom](doc/progress_bottom.png)

* red dot: fully documented
* blue dot: partially documented

### Remaining Work

* create subsheets for logical blocks
* create pinout of ASICs
* document remaining testpoints
  

## Testpoints

| TP    | Connected to | Comment           |
| ----- | ------------ | ----------------- |
| TP1   |              |                   |
| TP2   |              |                   |
| TP3   | K2 pin 9     | SD detect         |
| TP4   |              |                   |
| TP5   |              |                   |
| TP6   |              |                   |
| TP7   | U3 pin 6     | SCK               |
| TP8   | U3 pin 5     | SI                |
| TP9   | U3 pin 2     | SO                |
| TP10  | U3 pin 8     | VCC               |
| TP11  |              |                   |
| TP12  |              |                   |
| TP14  |              |                   |
| TP15  |              |                   |
| TP16  |              |                   |
| TP17  | K9 pin 3     | speaker           |
| TP18  | K9 pin 2     | speaker           |
| TP19  | U1 pin 31    | DAC !RESET        |
| TP20  |              |                   |
| TP21  |              |                   |
| TP22  |              |                   |
| TP23  |              |                   |
| TP24  |              |                   |
| TP25  | U4 pin 3     | Accelerometer DNC |
| TP26  | K4 pin 1     | ears              |
| TP27  | D10 pin 1    | LED red -         |
| TP28  | D10 pin 2    | LED green -       |
| TP29  | D10 pin 3    | LED blue -        |
| TP30  |              |                   |
| TP31  | K4 pin 3     | ears              |
| TP32  |              |                   |
| TP33  |              |                   |
| TP34  |              |                   |
| TP35  |              |                   |
| TP36  |              |                   |
| TP37  |              |                   |
| TP38  |              |                   |
| TP39  |              |                   |
| TP41  |              |                   |
| TP42  |              |                   |
| TP43  |              |                   |
| TP45  |              |                   |
| TP46  |              |                   |
| TP47  |              |                   |
| TP48  | U2 pin 61    |
| TP49  |              |                   |
| TP50  |              |                   |
| TP51  |              |                   |
| TP52  |              |                   |
| TP53  |              |                   |
| TP54  |              |                   |
| TP55  |              |                   |
| TP65  |              |                   |
| TP66  |              |                   |
| TP67  |              |                   |
| TP68  |              |                   |
| TP69  |              |                   |
| TP70  |              |                   |
| TP71  |              |                   |
| TP72  |              |                   |
| TP73  |              |                   |
| TP74  |              |                   |
| TP75  |              |                   |
| TP300 |              |                   |
| TP301 |              |                   |
| TP320 |              |                   |
| TP321 |              |                   |
| TP322 |              |                   |
| TP341 |              |                   |
| TP342 |              |                   |
| TP350 | U2 pin 3     | I2C_SCL           |
| TP351 | U2 pin 4     | I2C_SDA           |
| TP355 |              |                   |
| TP356 |              |                   |
| TP357 |              |                   |
| TP358 |              |                   |
| TP360 | K2 pin 4     | SD VDD            |
| TP361 |              |                   |
| TP370 | SOP1         |                   |
| TP371 | SOP0         |                   |
| TP372 |              |                   |
| TP373 |              |                   |
