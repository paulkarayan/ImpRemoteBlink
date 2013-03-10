ImpRemoteBlink
==============

control blinking on a remote board using Electric Imp(s) and a potentiometer.

logic is written in Squirrel (i.e. is on the Imp) rather than on the Arduino.
see for details of the hardware setup:
http://paulkarayan.tumblr.com/

1) Board A with potentiometer hooked up to pin 1 is programmed to be an "output" node  

2) Board A's node wakes up every 0.2 secs and sends the value to Board B's "input" node

3) Board B writes the rate to pin 5 and pin 9 (where 9 is a board-mounted LED on the Imp's shield)


