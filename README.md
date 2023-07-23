# Digital Support Library

The Digital Support Library contains circuits developed for the [Digital](https://github.com/hneemann/Digital) simulator.  
This repo contains useful circuits that make working with Digital easier and extend functionality.

Since Digital has the functionality to export circuits to VHDL or Verilog, some circuits are modeled after the VHDL standard library.  
Most of the circuits are generic, that means you have the possibility to set the bit width or other properties.

---

## Supported circuits

Name                         | Implemented | Documented | Tested   |
-----------------------------|:-----------:|:----------:|:--------:|
**Logic**                    |             |            |          |
And Reduce                   | &#x2611;    | &#x2611;   | &#x2611; |
NAnd Reduce                  | &#x2611;    | &#x2611;   | &#x2611; |
NOr Reduce                   | &#x2611;    | &#x2611;   | &#x2611; |
Or Reduce                    | &#x2611;    | &#x2611;   | &#x2611; |
XNOr Reduce                  | &#x2611;    | &#x2611;   | &#x2611; |
XOr Reduce                   | &#x2611;    | &#x2611;   | &#x2611; |
**Integer**                  |             |            |          |
Adder Subtractor             | &#x2611;    | &#x2611;   | &#x2611; |
Distance                     | &#x2611;    | &#x2611;   | &#x2611; |
Absolute                     | &#x2611;    | &#x2611;   | &#x2611; |
Find Leftmost                | &#x2611;    | &#x2611;   | &#x2611; |
Find Rightmost               | &#x2611;    | &#x2611;   | &#x2611; |
Bit Reverser                 | &#x2611;    | &#x2611;   | &#x2611; |
Barrel Shifter               | &#x2610;    | &#x2610;   | &#x2610; |
Bit Extender                 | &#x2611;    | &#x2611;   | &#x2611; |
Integer Resize               | &#x2611;    | &#x2611;   | &#x2610; |
Square Root                  | &#x2611;    | &#x2611;   | &#x2610; |
**Fixed Point**              |             |            |          |
Fixed Adder                  | &#x2611;    | &#x2611;   | &#x2610; |
Fixed Subtract               | &#x2611;    | &#x2611;   | &#x2610; |
Fixed Multiply               | &#x2611;    | &#x2611;   | &#x2610; |
Fixed Divide                 | &#x2611;    | &#x2611;   | &#x2610; |
Fixed Reminder               | &#x2610;    | &#x2610;   | &#x2610; |
Fixed Modulo                 | &#x2610;    | &#x2610;   | &#x2610; |
Fixed Resize                 | &#x2611;    | &#x2611;   | &#x2610; |
Fixed To Integer             | &#x2611;    | &#x2611;   | &#x2610; |
Integer To Fixed             | &#x2611;    | &#x2611;   | &#x2610; |
**Dynamic Fixed Point**      |             |            |          |
Dynamic Fixed Adder          | &#x2611;    | &#x2611;   | &#x2610; |
Dynamic Fixed Subtract       | &#x2611;    | &#x2611;   | &#x2610; |
Dynamic Fixed Negation       | &#x2611;    | &#x2611;   | &#x2610; |
Dynamic Fixed Absolute       | &#x2611;    | &#x2611;   | &#x2610; |
Dynamic Fixed Multiply       | &#x2611;    | &#x2611;   | &#x2610; |
Dynamic Fixed Divide         | &#x2611;    | &#x2611;   | &#x2610; |
Dynamic Fixed Reminder       | &#x2610;    | &#x2610;   | &#x2610; |
Dynamic Fixed Modulo         | &#x2610;    | &#x2610;   | &#x2610; |
Dynamic Fixed Scalb          | &#x2611;    | &#x2611;   | &#x2610; |
Dynamic Fixed Square Root    | &#x2611;    | &#x2611;   | &#x2610; |
**Complex Fixed Point**      |             |            |          |
Complex Fixed Adder          | &#x2611;    | &#x2611;   | &#x2610; |
Complex Fixed Subtract       | &#x2611;    | &#x2611;   | &#x2610; |
Complex Fixed Multiply       | &#x2611;    | &#x2611;   | &#x2610; |
Complex Fixed Division       | &#x2611;    | &#x2611;   | &#x2610; |
Complex Fixed Magnitude      | &#x2611;    | &#x2611;   | &#x2610; |
Complex Fixed Square         | &#x2611;    | &#x2611;   | &#x2610; |
**Floating Point**           |             |            |          |
Float Adder                  | &#x2611;    | &#x2610;   | &#x2611; |
Float Subtract               | &#x2611;    | &#x2610;   | &#x2610; |
Float Negation               | &#x2611;    | &#x2610;   | &#x2610; |
Float Absolute               | &#x2611;    | &#x2610;   | &#x2610; |
Float Is Negative            | &#x2611;    | &#x2610;   | &#x2610; |
Float Copysign               | &#x2611;    | &#x2610;   | &#x2610; |
Float Multiply               | &#x2611;    | &#x2610;   | &#x2610; |
Float Multiply Add           | &#x2610;    | &#x2610;   | &#x2610; |
Float Divide                 | &#x2611;    | &#x2610;   | &#x2610; |
Float Reminder               | &#x2610;    | &#x2610;   | &#x2610; |
Float Modulo                 | &#x2610;    | &#x2610;   | &#x2610; |
Float Logb                   | &#x2610;    | &#x2610;   | &#x2610; |
Float Scalb                  | &#x2611;    | &#x2610;   | &#x2610; |
Float Square Root            | &#x2611;    | &#x2610;   | &#x2610; |
Float To Integer             | &#x2611;    | &#x2610;   | &#x2610; |
Float To Fixed               | &#x2610;    | &#x2610;   | &#x2610; |
Integer to Float             | &#x2610;    | &#x2610;   | &#x2610; |
Fixed to Float               | &#x2610;    | &#x2610;   | &#x2610; |
Float Comparator             | &#x2611;    | &#x2610;   | &#x2610; |
Float Break Number           | &#x2611;    | &#x2610;   | &#x2610; |
Float Check Round            | &#x2611;    | &#x2610;   | &#x2610; |
Float Classify               | &#x2611;    | &#x2610;   | &#x2610; |
Float Normalize              | &#x2611;    | &#x2610;   | &#x2610; |
**Memory**                   |             |            |          |
Edge Detector                | &#x2611;    | &#x2611;   | &#x2610; |
Trigger                      | &#x2611;    | &#x2611;   | &#x2610; |
Variable Clock Divider       | &#x2611;    | &#x2611;   | &#x2610; |
While Loop                   | &#x2611;    | &#x2611;   | &#x2610; |
For Loop                     | &#x2611;    | &#x2611;   | &#x2610; |
**Control Logic**            |             |            |          |
Counter Asynchronous         | &#x2611;    | &#x2610;   | &#x2610; |
Counter Preset Asynchronous  | &#x2611;    | &#x2610;   | &#x2610; |
Register Asynchronous        | &#x2611;    | &#x2610;   | &#x2610; |
Register Synchronous         | &#x2611;    | &#x2610;   | &#x2610; |
Delay Register               | &#x2611;    | &#x2610;   | &#x2610; |
Shift Register Asynchronous  | &#x2611;    | &#x2610;   | &#x2610; |
Shift Register Synchronous   | &#x2611;    | &#x2610;   | &#x2610; |
FIFO Stack                   | &#x2610;    | &#x2610;   | &#x2610; |
LIFO Stack                   | &#x2610;    | &#x2610;   | &#x2610; |

## Usage

Extract the contents to the Digital lib folder.
The Circuits can be found under Componets->Library or in the Sidebar under Library.

## Contribute

Although this library is not complete, I share it because otherwise I would never get it done.
If you use this project and find it helpful, you could contribute to implmenting, documenting or unit testing new or existing circuits.
