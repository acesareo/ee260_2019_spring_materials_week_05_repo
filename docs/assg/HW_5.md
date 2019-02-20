---
title: Homework #5
author:Angelica Cesareo
date:1-19-18
---


1.) A museum has three rooms, each with a motion sensor (m0, m1, and m2) that outputs 1 when motion is detected. At night, the only person in the museum is one security guard who walks from room to room. Create a circuit that sounds an alarm (by setting an output A to 1) if motion is ever detected in more than one room at a time (i.e., in two or three rooms), meaning there must be one or more intruders in the museum. Start with a truth table.
 ![hw5_6](https://user-images.githubusercontent.com/46559119/53082441-f1f09b80-34a0-11e9-8a25-eaffb01d8367.JPG)







2.) Create a circuit for the museum of exercise above that detects whether the guard is properly patrolling the museum, detected by exactly one motion sensor being 1. (If no motion sensor is 1, the guard may be sitting, sleeping, or absent). 
 ![hw5_2](https://user-images.githubusercontent.com/46559119/53082417-e7360680-34a0-11e9-90c3-1b680fb65aa8.JPG)






3.) Consider the museum security alarm function of exercise above, but for a museum with 10 rooms. A truth table is not a good starting point (too many rows), nor is an equation describing when the alarm should sound (too many terms). However, the inverse of the alarm function can be straightforwardly captured as an equation. Design the circuit for the 10 room security system, by designing the inverse of the function, and then just adding an inverter before the circuit’s output. 







4.) Two people, denoted using variables A and B, want to ride with you on your motorcycle. Write a Boolean equation that indicates that exactly one of the two people can come (A=1 means A can come, A=0 means A can’t come). Then use XOR to simplify your equation.
  ![hw5_4](https://user-images.githubusercontent.com/46559119/53082423-eac98d80-34a0-11e9-8bbf-999dc333913c.JPG) 






5.) Design a 3x8 decoder using AND, OR and NOT gates.
![hw5_5](https://user-images.githubusercontent.com/46559119/53082435-ef8e4180-34a0-11e9-883b-8c9394ee3f0e.JPG)







6.) Design an 8x1 multiplexer using AND, OR and NOT gates.
 ![hw5_6](https://user-images.githubusercontent.com/46559119/53082441-f1f09b80-34a0-11e9-8a25-eaffb01d8367.JPG)







7.) Design a 4x2 **priority encoder** using AND, OR and NOT gates. If every input is 0, the output should be “00”. (Hint: encoder and priority encoder is not fully discussed in class, but they are easy to understand once you know decoder and multiplexer. Search online for priority encoder to learn its functionalities before attempting the question.)
