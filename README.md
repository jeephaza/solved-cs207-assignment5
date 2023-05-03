Download Link: https://assignmentchef.com/product/solved-cs207-assignment5
<br>
Provide answers to the following questions:

<ol>

 <li>What is the difference between serial and parallel transfer? Explain how to convert serial data to parallel and parallel data to serial.</li>

 <li>Design a four‐bit shift left register with parallel load using D flip‐flops and gates. There are two control inputs: <em>shift</em> and <em>load</em>. When <em>shift</em> = 1, the content of the register is shifted by one position. New data are transferred into the register when <em>load</em> = 1 and <em>shift</em> = 0. If both control inputs are equal to 0, the content of the register does not change. Briefly describe your design and draw the circuit diagram.</li>

 <li>Design a serial 2’s complementer with a shift register, a flip‐flop and gates. The binary number is shifted out from one side and it’s 2’s complement shifted into the other side of the shift register. Provide the state diagram and draw the circuit diagram.</li>

</ol>

<em>Hint: – 2’s complement of a number can be obtained by keeping the least significant bits as such until the first 1, and then complementing all bits </em>

<em>eg: 001010 → 110110 </em>

<ol start="4">

 <li>List the all unused states in a 4-bit switch‐tail ring counter show in the figure below. Determine the next state for each of these states and show that, if the counter finds itself in an invalid state, it does not return to a valid state. Modify the circuit to avoid this. Show that your modified counter produces the same sequence of states and that the circuit reaches a valid state from any one of the unused states.</li>

</ol>







PART 2: DIGITAL DESIGN LAB

<h1>INTRODUCTION</h1>

In this lab, you are required to use Vivado 2017.4 and Minisys/EGO1 Practice platform (Xilinx FPGA chip Artix 7 inside) to design a Sequential circuit and test it.

<h1>PREAMBLE</h1>

Before working on the course-work itself, you should master the following material.

<ol>

 <li>’CH6-Registers and Counters-SUSTC.ppt’ in Sakai site.</li>

 <li>‘Digital design lab12.pdf’, ‘Digital design lab13.pdf’, ‘Digital design lab14.pdf’ in Sakai site.</li>

 <li>Verilog: http://www.verilog.com</li>

</ol>

<h1>EXERCISE SPECIFICATION</h1>

<strong>TASK1:  </strong>

Use two 74194 shift register to implement a 8-bit serial-parallel converter. Write a circuit to realize this function and test.

<ul>

 <li>Do the design (Using structure design is suggested).</li>

 <li>Write testbench to verify the function of your design.</li>

 <li>Create the constraint file.</li>

 <li>Do the synthetic and implementation, generate the bitstream file and program the device, then test on the Minisys / EGO1 develop board.</li>

</ul>

<strong> </strong>

<strong>TASK2:  </strong>

Using JK flip‐flops, design a counter with the following repeated binary sequence: 0, 1, 2, 3, 4, 5, 6.

<ul>

 <li>Do the design in Verilog.</li>

 <li>Write testbench to verify the function of your design.</li>

 <li>Create the constraint file</li>

 <li>Do the synthetic and implementation, generate the bitstream file and program the device, then test on Minisys /EGO1 the develop board</li>

</ul>