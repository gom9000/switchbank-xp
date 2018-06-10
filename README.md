# SwitchBank eXPerience

SwitchBank eXPerience is a home project for a simple classification and implementation of switch-bank circuits.  
Schematics and PCB layouts are designed with ExpressPCB free CAD and Logisim tool software.


***Momentary Switch***:
A switch in which the operable status (contact) is maintained only until the actuating force is applyed (the switch is depressed).


- debounce



## Switch-Bank

A switch-bank is a set of related switches (only momentary switch are considered in this eXPerience), organized as an array or a matrix (an array of switch arrays).
The relation between the switches inside a bank can be:

- ***mutually-inclusive***: when more than one switch can be operable at the same time  
- ***mutually-exclusive***: when only one switch per time can be operable


### Action Modes

- ***momentary***: A switch in which the shorting bar returns from its operated position to its normal or free position when the actuating force is removed.
- ***Maintained***: ...
- ***Alternate***: A switch in which the operable position is maintained after the first actuation, and then disengaged with the second operation



### Operational Modes

- momentary (mo) mutually-inclusive (i) switch-bank (as a polyphonic keyboard)
- alternated (al) mutually-inclusive (i) switch-bank (as a toggle-button bank)
- momentary (mo) mutually-exclusive (x) switch-bank (as a monophonic keyboard)
- maintained (ma) mutually-exclusive (x) switch-bank (as a monophonic keyboard with sustain)
- alternated (al) mutually-exclusive (x) switch-bank (as a ...)

ss

- exclusive-selector = maintained mutually-exclusive switch-bank
- inclusive-selector = alternated mutually-exclusive switch-bank

- lighted selector


.. image:: ./images/alternate-mutually-exclusive-switch-bank.jpg


## Changes
See file [CHANGES](CHANGES) for the project resources change logs


## About
Author : Alessandro Fraschetti (mail: [gos95@gommagomma.net](mailto:gos95@gommagomma.net))


## License
This project is licensed under the [Creative Commons BY-SA 3.0](http://creativecommons.org/licenses/by-sa/3.0/) License