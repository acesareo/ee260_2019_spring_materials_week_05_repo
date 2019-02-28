# Lab-3

Lab3_1_1
    module decoder(sel,out1);
    	    input [2:0] sel;
    	    output reg [7:0] out1;
    	    always @(sel,out1)
      	    case (sel)
         	    3'b000  : out1 = 8'b00000001;
         	    3'b001  : out1 = 8'b00000010;
         	    3'b010  : out1 = 8'b00000100;
         	    3'b011  : out1 = 8'b00001000;
         	    3'b100  : out1 = 8'b00010000;
         	    3'b101  : out1 = 8'b00100000;
         	    3'b110  : out1 = 8'b01000000;
         	    default : out1 = 8'b10000000;
      	    Endcase
    endmodule

We figured out our code by looking at the truth table and implementing the numbers that matched which switch would turn on.

Objective
This code is for the first part of Lab 3. In this part we tried to design a code that would turn on a 7 LED light that is control by 3-bit inputs switches. 

Challenges
The first real challenge that we run into is figuring out use some to the code from lab 2 to help write the code for lab 3 because lab 2 and lab 3 basically use the same concept as each other but just different outputs. After figuring that out we had to translate everything into code. We got everything to work properly after trying a few different variation of code.

What we learn
In this lab we learned that we just need to take the first leap into the lab and not hesitate because we ended up finishing the lab and it was rather easy. We will be applying what we learn in this lab to the other labs because we found a method that works for us.






Lab3_2_1
   module prio_enco_8x3(dout, din);
    output [2:0] dout;
    input [7:0] din ;
    assign dout = (din[7] ==1'b1 ) ? 3'b111:
           	    (din[6] ==1'b1 ) ? 3'b110:
           	    (din[5] ==1'b1 ) ? 3'b101:
            	(din[4] ==1'b1) ? 3'b100:
            	(din[3] ==1'b1) ? 3'b011:
           	    (din[2] ==1'b1) ? 3'b010:
            	(din[1] ==1'b1) ? 3'b001:
                	(din[0] ==1'b1) ? 3'b000: 3'bxxx;
    Endmodule

We figured out the code by using the same thing in the previous taske but we just reversed it.

Objective
This code is for the second part of Lab 3. In this part we tried to design a code that would turn on a 3 LED light that is control by 7 inputs switches. 

Challenges
The first real challenge that we run into is figuring out how to switch the code from the first part of the lab. After figuring that out we had to translate everything into code. We got everything to work properly after trying a few different variation of code.

What we learn
In this lab we learned that we just need to take the first leap into the lab and not hesitate because we ended up finishing the lab and it was rather easy. We will be applying what we learn in this lab to the other labs because we found a method that works for us.
