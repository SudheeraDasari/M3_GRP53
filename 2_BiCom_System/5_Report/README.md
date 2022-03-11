## Description
This Project is an BiCom System,and is designed to remotely know the statuS of your automobiles, BiCom System operates by broadcasting radio waves on a particular frequency Bidirectionally.As we know RKE system which is only unidirectional but here the BiCom system is  bidirectional.

## Introduction

This is similar to RKE which is used for locking and unlocking but it is ubidirectional whereas BiCom System operates in bidirectional which operates by radio waves in a particular frequency. The BiCom System functionality differs from RKE system.It is the extension of the undirectional RKE System.

## Identifying Features
* It will prints window status when user pressed button once.
* It will show alarm status when user pressed button twice.
* It will show car battery information when user presssed button three times.
* It will show the status of Door when user pressed button four times

## High Level Requirements


| ID | High Level Requirement |
|----|------------------------|
|HLR1| It will prints window status when user pressed button once.|
|HLR2|It will show alarm status when user pressed button twice|
|HLR3|It will show car battery information when user presssed button three times.|
|HLE4|  It will show the status of Door when user pressed button four times|

## Low Level Requirements
| ID | Low  Level Requirement |
|----|------------------------|
|LLR1|When prints status of window,all the leds ON at same time|
|LLR2| When prints alarm status,all the leds OFF at same time|
|LLR3|When it will show battery information, all led on in clockwise manner|
|LLR4|When it shows the status of door,all the leds ON in anti-clockwise manner|

## SWOT ANALYSIS

![image](https://user-images.githubusercontent.com/87614111/157808397-f4098f3f-7219-4400-b5c3-8add00c4ad96.png)


# Strength
* Less human interaction.
* Control the car remotely by checking the status of window,battery,door.
* Avoiding the chance of thefts.
 

# Weakness
* Next command will be in processes after completion of previous command.
* There may be problem with locking and unlocking when the distance is beyond threshold.

# Oppurnities
* This type of systems are mainly used for the cars.
 
# Threats
* The key fob doesnot work consistently.
* There may be chance of hacking.\
##  4W's And 1H

![image](https://user-images.githubusercontent.com/87614111/157808679-4d4b7b7f-e078-4ef9-a8d4-a9117bcc981f.png)

# WHAT
A BiCom system controls the vehicle without using a traditional mechanical key.We can remotely access a car.

# WHY
BiCom Systems are used for locking and unlocking a vehicle's doors by controlling the remote.

# WHERE
It is used for car owners where they can make the task self without unecesserly inserting the key.

# WHEN
It is used for cars as there is a chance of thefts.This can be used for locking and locking of doors of a car.

# WHO
BiCom Systems are used by car users which are developed by automative engineers.So they must offer low cost and high reliability.

# HOW
There are functions on a key knob which are used for automatic door locking and unlocking for a car.
# Achitecture
## High Level Behavioural Diagram

![mod3 1](https://user-images.githubusercontent.com/87614111/157807739-99ceae04-9f8c-40b2-9184-1bc1c6ee2938.jpg)

## Low Level Behavioural Diagram

![mod3 1 (1)](https://user-images.githubusercontent.com/87614111/157810073-e43e22b6-057a-419b-8c7e-772264de2af1.jpg)

# High Level Test Plan
 
  |  Test  ID	   |  Description	    | Expected I/P	  |   Expected O/P      |	   Type of Test  |
  |----------|------------------|-----------------|---------------------|----------------|
  |          |                  |                 |                     |                |                |
  |  HP01    |  status of window            |  Switch is pressed once  |   locks the door  |  Requirement   |
  |  HP02    |  shows alarm status            |  Switch is pressed twice  |   unlocks the door  |   Requirement   |
  |  HP03    | shows car battery information            |  Switch is pressed three times  |   buzes the alarm  |   Requirement   |
  |  HP04    | status of door           |  Switch is pressed four times  |  ONs the light |   Requirement   |
  
  
# Low Level Test Plan
   
 | Test ID	   |  Description	    | Expected I/P	  |   Expected O/P      |	   Type of Test  |
  |----------|------------------|-----------------|---------------------|----------------|
  |          |                  |                 |                     |                |                |
  |  LP01    |  status of window            |  Switch is pressed once  |   All leds on at same time  |  Requirement   |
  |  LP02    |   shows alarm status           |  Switch is pressed ontwicw  |   All leds off at same time  |  Requirement   |
  |  LP03    |  shows car battery information             |  Switch is pressed three times  |   All leds on in clockwise manner  |  Requirement   |
  |  LP04    |  status of door          |  Switch is pressed four times  |   All leds on in Aanti-clockwise mannert |   Requirement   |
  
  
