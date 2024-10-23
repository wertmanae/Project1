# Project1
Alexander Wertman
Written 10/21/24
Updated 10/21/24
Dependent on no libraries.
It tells a red light on a microcontroller to turn on and off with the push of one of the side buttons. Same thing for the green code.
#include <msp430.h>
#define RED_LED BIT0 //P1.0
#define GREEN_LED BIT6 //P6.6
#define BUTTON1 BIT1 //push button P4.1
#define BUTTON2 BIT3 //push button P2.3
