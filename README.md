# Bar-Code-Scanner-Circuit

This project aims to implement a basic Barcode Reader. This project had to be carried out respecting the following specifications:
* There are two inputs: EN (an Enable signal, in direct logic) and I (product code in Excess of 3);
* The circuit produces three outputs: P (product code), G (product group) and C (control number, G designation, in ones' complement);
* If the circuit is not enabled, the result on the outputs must be 0;

Taking into account the information that was provided, it was possible to synthesize the truth table of the circuit. From this, it was extracted for each of the outputs, the expression of the function that allows to achieve the desired results, using only basic logic gates.

## Note

The project was carried out in the Xilinx ISE software in the form of an electrical scheme at the level of the logic gate and Verilog (tested .in simulation).

## Authors

* **Pedro Sousa**
