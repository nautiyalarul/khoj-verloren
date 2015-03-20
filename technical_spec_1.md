Functional Specification

1. Introduction


1.1 summary
The aim of the project is to make a path finder for the user using GPS . The project is to be develop by Jonathan-David Schröder and Arul Nautiyal in Ecole Centrale d'Electronique in the Embedded Systems majeure 2009 as part of there course .

1.2. Requirements

The user will be provided on his Touch Screen  various options of locations where he might want to go , the Geolocalizer will provide the shortest path to his chosen destination location in real time .

1.3 Existing System

There are quite expensive and heavy applications doing the same thing for the user ,whereas in our project we are try to make a lite process application with easy interface for the user and with lesser time development time ,thus saving the time to market .

1.4  Terminology

SERVER -
GPS Kit -
TOUCH SCREEN
DATABASE

1.5 References

Google Grolocation API
PIC 24 datasheet
GPS kit

2. Functional Description

The user is provided the predefine locations near to his present location in a Real time and ask him for the destination location . The user will be provided with the option of selecting the Search for the shortest path By car or By walk .
After the user select the provided options ,he will be again ask for the final confirmation before the authentic data will be send to the data base server . The server will respond in real time to the user on his touch screen . To see the data the user is again as for his final confirmation.

USE CASE

1. System displays on the screen, “Destination Location ”, “Options”.
2. User touches “Options”
3. System displays options screen with buttons “By car ”, “By walk”, “Don`t care ”, the pre-selected option highlighted.
4. System displays “Cancel” and “Ok” buttons
5. User touches “By car ”
6. System highlights “By car”
7. User touches “Ok”
8. System Send details on to the server .
9. System returns output on to the  screen.

Exception 1: Options- Preselected ( Predefined)

Note -

’Primary’’ actor is one having a goal requiring the assistance of the system -  the User
’Secondary’’ actor is one from which the system needs assistance to satisfy its goal - the server (GPS)

User Community

The Project is made as an experience in the real time path finder , after its success ,the product may be made available to the user .Moreover, the project focus on better understanding of us on the various topics rather then any thing else.

Error Handling and security

We have the feedback system running to check any error ,if found the whole system will reset itself ,saving the user search data . We may user the HTTPS or will ask the user to put the authentic codes to access the data.

Help and Support
The project is open source and develop under the BSD license ,thus the client can get the direct help and continuous feedback and software updates from the open source communities on the web .

Interfaces

USER ( HARDWARE INTERACTION ) - PIC24 , GPS kit

SOFTWARE

Portability
Initially the software will be provided for the PIC24 with touch screen board  ,but in near future can also be made for other hardware interfaces. The Geololization codes and feedback system codes will be hardware independent codes and will be based on re-usability of the codes .

Performance
Capacity - 1 request at a time for the user
Response times - real time

Configuration Management
Jo we have to write what software module we will be using and how we managing them .






