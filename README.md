# Design-and-Implementation-of-ALU-using-Verilog-HDL
#INTRODUCTION
One of the arithmetic operations is multiplying one number by another. Operations like
multiplication are mostly required functions, presently enforced in several DSPs for
applications like convolution, FFTs, filters and ALU (Arithmetic Logic Unit) of
Microprocessor. A recurrently preferred operation is multiplication, it's necessary to design
multiplier with reduced delay and efficient power utilization. Arithmetic calculations are
working for many operations considering from simple routine work such as counting or
multiplying to advanced science and business calculations. Hence, there is requirement of a
fast and effective arithmetic unit in computers. Array Multiplication takes less time when
compared to the partial product parallel calculation method. The delay produced is the time
required for the signals to pass through the gates of multiplication array . Booth multiplier uses
massive booth arrays for multiplier designs and exponents calculations with prime speed that
successively demands parti -al add and partial carry registers. Two n-bit operands
multiplication employing a radix-4 booth recording multiplier factor wants around n-bits/ (2k)
clock cycles to get part of the final product, where k indicates the number of booth recorder
adder stages. Urdhva Tiryakbhyam Sutra based "Verticalcrosswise Algorithm" can be used to
design digital multiplier like the Array multiplier. The ancient formula(sutra) provides the way
to find product of N x N, of N bits each multiplicand by considering smaller parts of size (N/2
= n, say. These parts will once more be fragmented into smaller numbers (n/2 each) until it
tends to reach 2x2 size. Thus, it is streamlining the operation into tree like structure.

#Introduction to VLSI
Digital systems are highly complex at their most detailed level. They may consist of millions
of elements i.e., transistors or logic gates. For many decades, logic schematics served as then
Gur Franca of logic design, but not anymore. Today, hardware complexity has grown to such a
degree that a schematic with logic gates is almost useless as it shows only a web of connectivity
and not functionality of design. Since the 1970s, computer engineers, electrical engineers and
electronics engineers have moved toward Hardware description language (HDLs).
Digital circuit has rapidly evolved over the last twenty five years. The earliest digital
circuits were designed with vacuum tubes and transistors. Integrated circuits were then
invented where logic gates were placed on a single chip. The first IC chip was small scale
integration (SSI) chips where the gate count is small. When technology became sophisticated,
designers were able to place circuits with hundreds of gates on a chip. These chips were called
MSI chips with advent of LSI; designers could put thousands of gates on a single chip. At this
point, design process is getting complicated and designers felt the need to automate these
processes.
With the advent of VLSI technology, designers could design single chip with more
than hundred thousand gates. Because of the complexity of these circuits computer aided
techniques became critical for verification and for designing these digital circuits.
Department of ECE St. Peter’s Engineering College Page No.3
One way to lead with increasing complexity of electronic systems and the increasing
time to market isto design at high levels of abstraction. Traditional paper and pencil and capture
and simulate methods have largely given way to the described UN synthesized approach.
For these reasons, hardware description languages have played an important role in
describe and synthesis design methodology. They are used for specification, simulation and
synthesis of an electronic system. This helps to reduce the complexity in designing and
products are made to be available in market quickly.
The components of a digital system can be classified as being specific to an
application or as being standard circuits. Standard components are taken from a set that has
been used in other systems. MSI components are standard circuits and their use results in a
significant reduction in the total cost as compared to the cost of using SSI Circuits. In contrasts,
specific components are particular to the system being implemented and are not commonly
found among the standard components.
The implementation of specific circuits with LSI chips can be done by means of IC
that can be programmed to provide the required logic.
