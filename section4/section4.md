# Section 4: Project Idea: Caffeinate the World 
## Overview: A small business at business.

Do you find yourself at work wishing you could make more money, but would feel too ashamed and guilty to pretend to sell consumables for a fundraiser? Worry no more! This project will allow you to sell coffee pods to your co-workers at a reasonable price you set. This project sits at the intersection of the newly emergent technologies of 3d printing, IoT and capsulised coffee. The project consists of an internet connected mechanical pod dispenser driven by a Raspberry Pi.

## Motivation: Building a project that requires a cross-section of skills

The near universal prevalence of Nespresso pod machines combined with the laziness of coworkers to organise buying their own supply of pods has created a market for a small portable, PoE coffee pod dispenser with a built in payment platform. From a learning perspective such a device would require utilising a number of skills from back-end programming, database design, interface design, integrating a payment platform (Paypal) and more hands-on skills such as building and assembling the device and electronics.

## Description: The nuts and bolts

The basic coffee pod dispenser already exists online. The below video outlines the mechanical components. We would not use the application supplied, but have to code a new program with the below features.

<a href="https://www.youtube.com/watch?feature=player_embedded&v=9wg3n8JrpgI
" target="_blank"><img src="https://img.youtube.com/vi/9wg3n8JrpgI/0.jpg" 
alt="Basic Dispenser" width="500" border="5" /></a>

### Physical Features:
* PoE with additional non-PoE (outlet) power in WiFi only situations.
* Raspberry Pi 3+ which has WiFi, storage and enough processing power to control the device
* USB toucscreen
* USB micro-servo controller and servos to operate the mechanism.
* Ability to secure the pods to stop theft.

### Software features:
* Web based back-end secured with SSL where users can:
  * Remotely dispense coffee,
  * Add credit to the account,
  * Check their pod history,
  * Update their details.
* Web based back-end where administrators can:
  * Issue refunds, correct database entries
  * Reset the pod counter when pods run out and they restock the device
  * Check the device status
  * Configure alerts
  * Perform system updates.
* Paypay payment system integrated into the back-end
* User and sales tracking with integrated monitoring systems
* Touch enabled interface on the device.

## Tools and technologies

The device would consist of a raspberry Pi 3+ connected to a mechanical dispenser. With power being delivered to the RP3+ via a PoE injector. The RP3 would then power the servos and controller via USB and GPIO pins. Multiple servos and a servo controller are also required as outlined on the dispensers website. 

The bare essentials of the project already exists are are open source. The mechanical dispenser exists on [thingiverse](https://www.thingiverse.com/thing:669792) and with only minor adjustments could be made more secure (lockable) and can be easily interfaced with a RP3+ via USB. Access to a 3d printer for the moving parts and a laser cutter for the plastic frame is also necessary.

On the software side, an understanding of Linux is a clear requirement as it would need to be secured. Programming skills are also required.

### Tools/Software required:
* Access to a workshop with basic drills, cutting equipment and nuts/bots.
* Github access and development environment.

## Skills Required:

The construction and assembly of the mechanical components would require a basic level of mechanical skill. The parts can be ordered online from 3d printing and laser-cutting services. Finding the skills and hardware to assemble the device is fairly easy.

The most technical component would be writing the software to connect the dispenser to multiple databases (sales, product, user database) and a integrating a payment platform. A user-friendly interface would have to be coded for use directly on the dispenser itself and a web based back-end for administration and adding credit to accounts organising refunds etc.

## Outcome: Coffee for all, all of the time

If this project were successfully developed and implemented in a kit form, anybody who worked in an office would be able to setup, with minimal fuss, a coffee-pod micro-shop. Their patrons could load money onto their account to pay for pods and be able to access them whenever they needed a shot of coffee. The owner of the device would then be able to earn a little more cash while at work and their colleagues could enjoy the convenience of coffee pods without having to worry about keeping their own supply at their desk.

| [Section 1: Interest in IT](../section1/section1.html) | [Section 2: Ideal Job](../section2/section2.html) | [Section 3: Personal Profile](../section3/section3.html) | Section 4: Project Idea |