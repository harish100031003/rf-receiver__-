AIM :-

To receive a message using an RF receiver.

Components Required:-

Arduino UNO Board
A RF 433M hz  receiver
Arduino IDE installed in your laptop
Jumper wires

Procedure:-

First identify the pins int the receiver.
Connect the GND pin in the RF receiver to the arduino board. Then connect the data to any pin containing ‘~’ symbol (pmw) in arduino and connected the Vcc pin to 5V .
Download the library from the first link given in references and set it up in your arduino IDE.
Implement the code given in the above repository file.
Run the code and check th emessage in Serial monitor.

Thought Process:-
  
It was my first time using a physical arduino board and I was excited and a bit nervous  for this project.
I already knew the connections of the circuit but I didn’t  know code for the receiver circuit. 
I referred to google for the code and tried to understand how it functions. It was quite interesting and in between I got immersed into it. 
Then I connected the RF receiver to the arduino board and then connected the arduino board to my laptop .
But when I ran the code , I didn’t receive any output which worried me and then I understood that I forgot to install the library. 
Installing the library was a bit of a hectic task but I learnt something new.And then finally when I ran the code got the output , it made me happy.

I felt the joy of understanding something new.We completed the task in an hour and this task helped me to get more interested in this topic.
I am looking forward to work with arduino boards and creating new circuits.

References:-

https://randomnerdtutorials.com/rf-433mhz-transmitter-receiver-module-with-arduino/

https://raw.githubusercontent.com/RuiSantosdotme/Random-Nerd-Tutorials/master/Projects/433MHz/receiver.ino

https://docs.arduino.cc/software/ide-v1/tutorials/installing-libraries/
