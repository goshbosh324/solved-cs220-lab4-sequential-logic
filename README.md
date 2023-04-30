Download Link: https://assignmentchef.com/product/solved-cs220-lab4-sequential-logic
<br>



<h1>Lab #4 (Sequential Logic)</h1>

<strong> </strong>

Name:

Section/Time:

Date:

<ol>

 <li>For the following combinational logic (not gate):

  <ol>

   <li>Label all the ticks and tocks on the clock line.</li>

   <li>Complete (draw) the output line, given the input during that time.</li>

   <li>Circle all the latch points.</li>

  </ol></li>

</ol>




<ol start="2">

 <li>For the following sequential logic (clocked data flip-flop (DFF)):

  <ol>

   <li>Complete (draw) the output line, given the input during that time.</li>

   <li>Circle all the latch points.</li>

  </ol></li>

</ol>







<ol start="3">

 <li>For the following sequential logic (1-Bit Register):

  <ol>

   <li>Complete (draw) the output line, given the input during that time.</li>

   <li>Circle all the latch points.</li>

  </ol></li>

</ol>




<ol start="4">

 <li>Why do we use discrete time steps instead of continuous time?</li>

</ol>




<ol start="5">

 <li><strong>What are the <em>out </em>values for each clock cycle below? </strong>Note: input starts at 527, output starts at 47 (from previous clock cycle).</li>

</ol>

We assume that we start tracking the counter in time unit 22, and the counter’s control bits (reset, load, inc) start at 0. All values below are arbitrary, to test your understanding of clock cycles, latching, etc.




<ol start="6">

 <li><strong>What are the control bits (reset, load, inc) values given the input and output values below? </strong>Note: All control bits start low (0). You can draw the lines and/or put the 0/1 values for each clock cycle and control bit</li>

</ol>




<h1>Lab #4 (Sequential Logic)<strong><sup>                                                                                                                                                           </sup></strong></h1>

<h2>Part 1: Definitions</h2>

<ul>

 <li><strong>Define what a “word” is in computer architecture: </strong></li>

</ul>

<strong> </strong>

<strong> </strong>

<ul>

 <li><strong>What is the term for the size of a “word”? </strong></li>

</ul>

<strong> </strong>

<ul>

 <li><strong>What is the size of the word in the HACK architecture? </strong></li>

</ul>

<h2>Part 2: Bus Sizes</h2>

<ul>

 <li><strong>Label the size of each of the inputs/outputs for the Ram4 chip below (in, address, load, out). You can assume the register sizes are the same as our HACK architecture. </strong></li>

</ul>




<strong> </strong>

<strong><u>Part 3: Reasoning</u> </strong>

<ul>

 <li><strong>Why did you choose the address size above? </strong></li>

</ul>

<strong> </strong><strong> </strong>

<h2>Part 4: Bus Sizes</h2>

<ul>

 <li><strong>Write out the address for each register: </strong></li>

</ul>

<table width="275">

 <tbody>

  <tr>

   <td rowspan="2" width="132"><strong>Register # </strong></td>

   <td colspan="2" width="143"><strong>In Binary </strong></td>

  </tr>

  <tr>

   <td width="72"><strong>[1] </strong></td>

   <td width="71"><strong>[0] </strong></td>

  </tr>

  <tr>

   <td width="132"><strong>0 </strong></td>

   <td width="72"> </td>

   <td width="71"> </td>

  </tr>

  <tr>

   <td width="132"><strong>1 </strong></td>

   <td width="72"> </td>

   <td width="71"> </td>

  </tr>

  <tr>

   <td width="132"><strong>2 </strong></td>

   <td width="72"> </td>

   <td width="71"> </td>

  </tr>

  <tr>

   <td width="132"><strong>3 </strong></td>

   <td width="72"> </td>

   <td width="71"> </td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<ul>

 <li><strong>Each register has it’s own load and in values. Fill out the table below for each situation: </strong></li>

</ul>

<table width="670">

 <tbody>

  <tr>

   <td width="117"> </td>

   <td colspan="2" width="96"><strong>Register 0 </strong></td>

   <td colspan="2" width="96"><strong>Register 1 </strong></td>

   <td colspan="2" width="97"><strong>Register 2 </strong></td>

   <td colspan="2" width="95"><strong>Register 3 </strong></td>

   <td rowspan="2" width="169"><strong>RAM4 OUTPUT (out, after end of cycle) </strong></td>

  </tr>

  <tr>

   <td width="117"> </td>

   <td width="48"> </td>

   <td width="48"> </td>

   <td width="48"> </td>

   <td width="48"> </td>

   <td width="48"> </td>

   <td width="49"> </td>

   <td width="47"> </td>

   <td width="48"> </td>

  </tr>

  <tr>

   <td width="117"><strong>Situation: </strong></td>

   <td width="48"><strong>in </strong></td>

   <td width="48"><strong>load </strong></td>

   <td width="48"><strong>in </strong></td>

   <td width="48"><strong>load </strong></td>

   <td width="48"><strong>in </strong></td>

   <td width="49"><strong>load </strong></td>

   <td width="47"><strong>in </strong></td>

   <td width="48"><strong>load </strong></td>

   <td width="169"> </td>

  </tr>

  <tr>

   <td width="117"><strong>Store -15 in Register 0 </strong></td>

   <td width="48"> </td>

   <td width="48"> </td>

   <td width="48"> </td>

   <td width="48"> </td>

   <td width="48"> </td>

   <td width="49"> </td>

   <td width="47"> </td>

   <td width="48"> </td>

   <td width="169"> </td>

  </tr>

  <tr>

   <td width="117"><strong>Store -15 in Register 1 </strong></td>

   <td width="48"> </td>

   <td width="48"> </td>

   <td width="48"> </td>

   <td width="48"> </td>

   <td width="48"> </td>

   <td width="49"> </td>

   <td width="47"> </td>

   <td width="48"> </td>

   <td width="169"> </td>

  </tr>

  <tr>

   <td width="117"><strong>Store -15 in Register 2 </strong></td>

   <td width="48"> </td>

   <td width="48"> </td>

   <td width="48"> </td>

   <td width="48"> </td>

   <td width="48"> </td>

   <td width="49"> </td>

   <td width="47"> </td>

   <td width="48"> </td>

   <td width="169"> </td>

  </tr>

  <tr>

   <td width="117"><strong>Store -15 in Register 3 </strong></td>

   <td width="48"> </td>

   <td width="48"> </td>

   <td width="48"> </td>

   <td width="48"> </td>

   <td width="48"> </td>

   <td width="49"> </td>

   <td width="47"> </td>

   <td width="48"> </td>

   <td width="169"> </td>

  </tr>

  <tr>

   <td width="117"><strong>Store -15 in Register 1 and 2 </strong></td>

   <td width="48"> </td>

   <td width="48"> </td>

   <td width="48"> </td>

   <td width="48"> </td>

   <td width="48"> </td>

   <td width="49"> </td>

   <td width="47"> </td>

   <td width="48"> </td>

   <td width="169"> </td>

  </tr>

 </tbody>

</table>

<strong> </strong><strong> </strong>

<ul>

 <li><strong>When does the load value matter? When doesn’t it?</strong></li>

</ul>

<strong> </strong>

<ul>

 <li><strong>What chip (that we’ve built in the course so far) would help for handling the load?</strong></li>

</ul>

<strong> </strong>

<ul>

 <li><strong>When does the in value matter? When doesn’t it? </strong></li>

</ul>

<strong> </strong>

<ul>

 <li><strong>What chip (that we’ve built in the course so far) would help for handling the in?</strong></li>

</ul>

<strong> </strong><strong> </strong>

<strong>Write the following numbers in binary (NO CALCULATOR! Use back of paper): </strong>

<ul>

 <li><strong><em>Tip: put a space between every 4 digits (grouping from right to left) </em></strong></li>

</ul>

<table width="576">

 <tbody>

  <tr>

   <td width="174"><strong>Decimal Number: </strong></td>

   <td width="402"><strong>Binary number: </strong></td>

  </tr>

  <tr>

   <td width="174"><strong>7 </strong></td>

   <td width="402"> </td>

  </tr>

  <tr>

   <td width="174"><strong>63 </strong></td>

   <td width="402"> </td>

  </tr>

  <tr>

   <td width="174"><strong>511 </strong></td>

   <td width="402"> </td>

  </tr>

  <tr>

   <td width="174"><strong>4095 </strong></td>

   <td width="402"> </td>

  </tr>

  <tr>

   <td width="174"><strong>16383 </strong></td>

   <td width="402"> </td>

  </tr>

 </tbody>

</table>

<strong><em> </em></strong>

<ul>

 <li><strong>The above values can be thought of as the last register in a specific RAM chip </strong>

  <ul>

   <li><strong>Ex: RAM8 = 8 registers = 0, 1, 2, 3, 4, 5, 6, 7 are possible registers </strong> <strong>What would be the address sizes for the following n Registers: </strong></li>

  </ul></li>

</ul>

<table width="576">

 <tbody>

  <tr>

   <td width="202"><strong>RAMn (n = num. of registers) </strong></td>

   <td width="374"><strong>Number of bits for address (think highest value</strong><strong>…) </strong></td>

  </tr>

  <tr>

   <td width="202"><strong>RAM8 </strong></td>

   <td width="374"> </td>

  </tr>

  <tr>

   <td width="202"><strong>RAM64 </strong></td>

   <td width="374"> </td>

  </tr>

  <tr>

   <td width="202"><strong>RAM512 </strong></td>

   <td width="374"> </td>

  </tr>

  <tr>

   <td width="202"><strong>RAM4K (n=4096) </strong></td>

   <td width="374"> </td>

  </tr>

  <tr>

   <td width="202"><strong>RAM16K (n=16384) </strong></td>

   <td width="374"> </td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<ul>

 <li><strong>How does one calculate the size of the address (number of bits) from the word size for the registers? </strong></li>

</ul>