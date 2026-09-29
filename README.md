# Lab 05 - Combinatorial Logic

In this lab, you’ve learned real world applications of digital logic, as well
as how to assemble your own Verilog modules. In addition, you’ve learned how
the constraints file maps your inputs and outputs to real pins on the FPGA.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Name G10 - Taog Anderson & Joshua Milbourne

## Lab Summary
We learned how to connect multiple modules from different .v files together in a top.v file and assign digital inputs and outputs to physical inputs and outputs using a constraints file. We also learned how to test the truth tables using simulations.
## Lab Questions

### 1 - Explain the role of the Top Level file.
The top level file assigns inputs to outputs and defines which function(s) will be used to determine what inputs give what outputs.
### 2 - Explain the function of the Constraints file.
The constraints file assigns the inputs and outputs as we use them in verilog (leds, wires and switches) in the top file to correspond to the pins on a physical circuit board, in our case a Basys-3 board.
### 3 - Was the selection of Minterm and Maxterm correct for each circuit? What would you have chosen?
It makes more sense to choose Minterm for A than the Maxterm we used, you could use Maxterms to verify the input but if you are only doing one it makes more sense to use Minterms as there are fewer outputs equal to 1. For B, either is optimal as there are an equal number of 1 outputs as 0 outputs.
