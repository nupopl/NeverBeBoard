# NeverBeBoard
A Java program that controls Leap Motion and generates sound feedback for a rehabilitation device

## Background
This project was created in the first quarter of my freshman year for a engineering design class along with my teammates Daniel, Miranda and Rachel. Our task was to design a rehabilitative training device for a patient who had Traumatic Brain Injury (TBI) and poor hand-eye coordination ability. Our client, the Rehabilitation Institute of Chicago (RIC) required us to come up with a solution that has a sound feedback system, which was considered the most effective way of training. Our design Never Be Board won the best design award by the Segal Institute.

## The Software Prototype
I was in charge of the software design of this project. Using the [Leap Motion](https://www.leapmotion.com/), I created a software for our device that recognizes our patient's hand and implements a sound feedback system that guides him to grip an object and drop it at a designated location, a hole in a peg board.

The sound feedback system contains both "beeps", the frequency of which implies distance to destination, and human voice guidance like "left" "forward" that tells the direction to move.

The software was implemented in Java using the Leap Motion API that contains a Listener which captures real-time data from the Leap Motion Device, which is connected through a USB cable. The location data of the training boards was stored in the program.

Since this was only a prototype, there are many future improvements to be considered. For example, the program could record the performance of patient over time. The performace data that includes both the speed and accuracy at which the patient performs a simple motion task can be useful in many ways.

## A Video Demo
[Never Be Board Prototype](https://youtu.be/_LgzY0X4xKs)
