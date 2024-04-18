# RTC Alarm System with 20x4 Character Display using I2C Interface
This project demonstrates a Real-Time Clock (RTC) alarm system using an STM32F4 microcontroller. The system sets an alarm, displays the current time and date on an I2C Display, and toggles an LED upon alarm activation.

## Features:
* Set the current time and date on the RTC.
* Set an alarm time and activate an interrupt.
* Display time and date on an I2C LCD.
* Toggle an LED upon alarm activation.

## How to Use Example

### Hardware Required
* Any STM32 micro controller based development board.
* A USB cable for Power supply and programming
* I2C LCD display (20x4 Character Display).
* An LED connected to GPIOB Pin 14.

### Setup:
* Connect the I2C LCD display to the STM32 Nucleo Development Board:
* SDA - Data pin to PB7
* SCL - Clock pin to PB6
* Connect an LED to GPIOB Pin 14.

## Example Output:

````bash
set_time(): Initializes the RTC with a default time and date.
set_alarm(): Sets an alarm at a specific time.
get_time(): Retrieves the current time and date from the RTC.
lcd_time(): Displays the time and date on the I2C LCD.
Action_On_Alarm(): Toggles an LED and displays a notification on the LCD upon alarm activation.

````
