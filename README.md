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

#Vedic Mathematics

Vedic mathematics is part of four Vedas (books of wisdom). It is part of Sthapatya- Veda
(book on civil engineering and architecture), which is an upa-veda (supplement) of
Atharva Veda. It gives explanation of several mathematical terms including arithmetic,
geometry (plane, co-ordinate), trigonometry, quadratic equations, factorization and
even calculus. His Holiness Jagadguru Shankaracharya Bharati Krishna Teerthaji
Maharaja (1884- 1960) comprised all this work together and gave its mathematical
explanation while discussing it for various applications. Swamiji constructed 16 sutras
(formulae) and 16 Upa sutras (sub formulae) after extensive research in Atharva Veda.
Obviously these formulae are not to be found in present text of Atharva Veda because
these formulae were constructed by Swamiji himself. Vedic mathematics is not only a
mathematical wonder but also it is logical. That’s why it has such a degree of eminence
which cannot be disapproved. Due these phenomenal characteristics, Vedic maths has
already crossed the boundaries of India and has become an interesting topic of research
abroad. Vedic maths deals with several basic as well as complex mathematical operations.
Especially, methods of basic arithmetic are extremely simple and powerful.

#Vedic Sutras

The word “Vedic” is derived from the word “Veda” which means the store-house of
all knowledge. Vedic mathematics is mainly based on 16 Sutras (or aphorisms) dealing with
various branches of mathematics like arithmetic, algebra, geometry etc.
These Sutras along with their brief meanings are enlisted below alphabetically.
Department of ECE St. Peter’s Engineering College Page No.4
1. (Anurupye) Shunyamanyat – If one isin ratio, the other is zero.
2. Chalana-Kalanabyham – Differences and Similarities.
3. Ekadhikina Purvena – By one more than the previous One.
4. Ekanyunena Purvena – By one less than the previous one.
5. Gunakasamuchyah – The factors of the sum is equal to the sum of the factors.
6. Gunitasamuchyah – The product of the sum is equal to the sum of the product.
7. Nikhilam Navatashcaramam Dashatah – All from 9 and last from 10.
8. Paraavartya Yojayet – Transpose and adjust.
9. Puranapuranabyham – By the completion or noncompletion.
10. Sankalana- vyavakalanabhyam – By addition and by subtraction.
11. Shesanyankena Charamena – The remainders by the last digit.
12. Shunyam Saamyasamuccaye – When the sum is the same that sum is zero.
13. Sopaantyadvayamantyam – The ultimate and twice the penultimate.
14. Urdhva-tiryagbhyam – Vertically and crosswise.
15. Vyashtisamanstih – Part and Whole.
16. Yaavadunam – Whatever the extent of its deficiency.

##BASIC CONCEPTS

#VERILOG Introduction
    
Hardware Description Language
Two things distinguish an HDL from a linear language like “C”: Concurrency:
• The ability to do several thingssimultaneously i.e. different code-blocks can run concurrently.
Timing:
• Ability to represent the passing of time and sequence events accordingly
• Verilog HDL is a Hardware Description Language (HDL).
• A Hardware Description Language is a language used to describe a digital system; one may
describe a digital system at several levels.
• An HDL might describe the layout of the wires, resistors and transistors on an Integrated
Circuit (IC) chip, i.e., the switch level.
• It might describe the logical gates and flip flops in a digital system, i.e., the gate level.
• An even higher level describes the registers and the transfers of vectors of information
between registers. This is called the Register Transfer Level (RTL).
• Verilog supports all of these levels.
• A powerful feature of the Verilog HDL is that you can use the same language for describing,
testing and debugging your system.

#VERILOG Features

• Strong Background: Supported by open verilog international and Institute of Electrical and
Electronics Engineering standardized.
• Industrial support: Simulation is very fast and synthesis is very efficient. • Universal: Entire
process is allowed in one design environment.
• Extensibility: It also allows Verilog PLI for extension of Verilog capabilities

#DESIGN FLOW
The typical design flow is shown in figure,
Department of ECE St. Peter’s Engineering College Page No.16
Design Specification
• The project Specifications and requirements are written first
• The digital circuit functionality is explained for the architecture to be designed.
• Specification: It uses wave former, test bencher or word for drawing waveform.
RTL Description
• CAD Tools are used for coding format for the Conversation of Specification.
Coding Styles:
• Gate Level Modeling
• Data Flow Modeling
• Behavioral Modeling

#Functional Verification &Testing

• The method of coding with respective inputs and outputs are going to be tested.
• Check the RTL Description once again if testing fails.
• Simulation: Using Xilinx , Verilog-XL ,ModelSim.

#Logic Synthesis

•	RTL description into Gate level -Net list form conservation.

•	The circuit is described as a function of gates and connections.

•	Synthesis: Synthesis is done by Altera and Xilinx ,Simplify Pro, Leonardo Spectrum Design Compiler, FPGA Compiler.

#Logical Verification and Testing

•	Simulation and synthesis are used for functional Checking of HDL coding. Check the RTL description if fails.

#VLSI DESIGN FLOW :
<img width="396" height="436" alt="image" src="https://github.com/user-attachments/assets/d3875960-9830-41ba-aad7-3b076e607ba6" />

#Physical Layout

•	The process of describing a circuit description into the physical layout is called the Physical design, it explains the interconnections between the cells and routes position.

#Layout Verification

•	Under layout verification first the physical layout structure has to be verified
<img width="635" height="313" alt="image" src="https://github.com/user-attachments/assets/bf0dcef2-1865-44a0-86d4-9e4ed6c12b65" />

##METHODOLOGY

#DESIGN IMPLEMENTATION
The Arithmetic module is split into smaller modules, which is multiplierand arithmetic module. These three modules are implemented using Verilog HDL.The 2x2 bit multiplier is obtained by "Vertical- crosswise Algorithm" based on Urdhva Tiryakbhyam Sutra. The basic2x2 bit multiplier is designed first using verilog code and then,4x4 blocks were designed using 2x2 blocks further 8x8 bitsmultiplier from 4-bit multiplier blocks and conclusivelyMultiplication of 16x16 bit is obtained with final 16-bitmultiplier.

Design of 2x2 vedic multiplier:
<img width="354" height="286" alt="image" src="https://github.com/user-attachments/assets/8ed070a0-c8f8-49b7-9d11-ac230bbeb191" />
2x2 vedic multiplier
<img width="415" height="196" alt="image" src="https://github.com/user-attachments/assets/cee6f203-b519-4571-8aaf-ee6a1f223755" />

Figure illustrates the steps to to multiply two 2 bit numbers . Converting the above figure to a hardware equivalent we have 3 and gates which will act as 2 bit multipliers and two half adders to add the products to get the final product. Here is the hardware detail of the multiplier.

#Design of 4X4 multiplier:

Using 4 such 2x2 multipliers and 3 adders we can built 4x4 bit multipliers as shown in the design. Proper instantiating of the 2x2 multipliers and adders. We have to first write code for 4bit and 6 bit adders. Its your choice to choose your adders. If in case you want to have better performance you can replace these normal adders with CSA or compressors. For a simpler design we have used the "+" operator which is supported by the XST synthesis tool which by default selects a low hardware adder. Arrangement of the adders and the addition is explained from the figure shown below:
4X4 multiplier:
<img width="859" height="607" alt="image" src="https://github.com/user-attachments/assets/d32e6d33-47fc-41bc-ae7e-d67b71233247" />

#Design of 8X8multiplier:
8X8 multiplier:
<img width="938" height="656" alt="image" src="https://github.com/user-attachments/assets/77296968-8081-4ff0-9292-0ce86a7638b9" />
similar to the previous design of 4x4 multiplier , we need 4 such 4x4 multipliers to develop 8x8 multipliers. Here we need to first design 8bit and 12 bit adders and by proper instantiating of the module and connections as shown in the figure we have designed a 8x8 bit multiplier. At this point of time its necessary for you to even verify the RTL code and check if the hardware is as per your design. PlanAhead tool by xilinx gives better view of the hardware design with design elaborate option(will explain this in my next posts). Refer the addition tree diagram to know the process for 8x8 multiplier:
 
#Design of 16x16 multiplier:
<img width="600" height="388" alt="image" src="https://github.com/user-attachments/assets/e3c77a7b-3f0a-4424-8421-3e99ef03d4c1" />
16x16 multiplier:

#32X32 Multiplier:
Design:
32X32 Multiplier
<img width="500" height="201" alt="image" src="https://github.com/user-attachments/assets/364ca11c-b18d-41a1-a987-22768b23d513" />

#64x64 Multiplier
Design:
64x64 Multiplier
<img width="450" height="360" alt="image" src="https://github.com/user-attachments/assets/14fe0118-4cfa-4e39-92e8-d3f03df236a2" />

#Arithmetic module

The arithmetic module makes use of 4 components, which are adder, subtractor, multiplier. As a result, the arithmetic unit can perform fixed point addition, subtraction, multiplication on 64 bits data. The Arithmetic unit uses conventional adder and subtractor, while the multiplier are made using Vedic Mathematics Sutras. Two control lines are used for different operations as shown in table.
 

S0	S1	Modules
0	0	Multiplier
0	1	Adder
1	1	Subtractor

#BLOCK DIAGRAM OF 64 BITS ARITHMETIC MODULE:
<img width="753" height="412" alt="image" src="https://github.com/user-attachments/assets/cb9e912f-6bf3-4d9a-8dd4-be139505edd1" />

#RESULTS
The implemented Arithmetic Logic Unit (ALU) was successfully designed and tested using Verilog. The simulation results verified the correct functionality of all arithmetic and logical operations. The ALU accurately performed addition, subtraction and multiplication operations as per the design specifications.The integration of the Vedic multiplier enhanced the efficiency of multiplication operations, demonstrating improved performance compared to conventional multiplication techniques. The propagation delay was minimized due to the optimized design approach.The ALU was synthesized using a standard cell library, and the area utilization was analyzed. The synthesis report showed an efficient utilization of logic gates with minimal hardware overhead. The timing analysis revealed that the design met all setup and hold time requirements, ensuring reliable operation.The power analysis indicated a low dynamic power consumption, making the design suitable for low-power applications. The critical path delay was optimized, resulting in improved speed performance. The functional verification was conducted using a testbench, and the ALU successfully passed all test cases... The ALU exhibited stable performance across different input scenarios, validating its robustness.The comparison with existing ALU designs highlighted a reduction in computation time due to the Vedic multiplier. The accuracy of operations was verified through extensive simulations, ensuring correctness under all conditions. The overall design complexity was managed effectively to balance performance and resource constraints.The ALU was tested under varying clock frequencies, and it maintained stability without significant glitches. The synthesis results confirmed that the design could be efficiently mapped to ASIC technology if required. The logical correctness of the design was validated using waveform analysis.. The results demonstrate that the proposed ALU design is efficient, reliable, and suitable for VLSI implementations.

#OutPut
<img width="555" height="291" alt="image" src="https://github.com/user-attachments/assets/91983a23-6e35-463a-8d2d-a97d46234d67" />

#RTL Schematic
<img width="603" height="368" alt="image" src="https://github.com/user-attachments/assets/4a7e246a-0984-4fb3-91f1-90e409288631" />

#Tech Schematic
<img width="601" height="387" alt="image" src="https://github.com/user-attachments/assets/5171c688-e79f-4b44-9fcc-2d86cbeb64f6" />

#Synthesis Report
<img width="608" height="455" alt="image" src="https://github.com/user-attachments/assets/73b2b779-cf67-4741-a24f-ecfd87b91276" />





