## project 1

This project sets the 15 elementary structure for the Integrated Circuits implemented on the preliminary structure(NAND)

We can divide these into 3 categories -

a. Elementary Logic gates
   ----------------------
1. NOT
2. AND
3. OR
4. XOR
5. MUX
6. DMUX

b. 16 bit variants of above
   ------------------------
1. NOT16
2. AND16
3. OR16
4. MUX16

c. Multi-way Variants
   ------------------
1. OR8WAY
2. MUX4WAY16
3. MUX8WAY16
4. DMUX4WAY
5. DMUX8WAY


### MULTIPLEXER

It's basically kind of a programmable gate where 2 inputs a and b are fed which are selected on the basis of the 3rd input select line value which could be either high or low. If the selector is low it outputs a and if it's high it outputs b.

This is the example of 2-way multiplexor. It acts either as AND gate if sel=0 & as an OR gate if sel=1.

For example if we have 2 gates AND & OR, both the input a and b are fed simultaneously in the AND & OR gate. It's called Fanned-out where one signal line is used to drive multiple input lines of IC. Then we use the Multiplexer in the end which is connected to the output of the both.

### DEMULTIPLEXER

This is kinda intresting as the above one it receives one input signal and one selection signal then it channels the single input to one of the possible output pins. It's kind of a distributor.

Multiplexing and Demultiplexing are used in communication networks for example if we wanted to send multiple messages on a single data line we can use a `MUX` at the source end where the selection line is connected with the oscilator that produces a repetitive train of alternating 0 and 1 signals. At the receiving end we can use a DeMux which distributes the output on different channels. Hence, this enables transmitting multiple messages on a single shared communication line and can be async in nature.


