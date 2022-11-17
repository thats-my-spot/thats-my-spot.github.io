# That's My Spot!

## <a href="https://docs.google.com/document/d/1dI2cp2C39PllNA3GIXgPYNJfcSU4MNTPIEO2m2xUdVg/edit?usp=sharing">Team Contract</a>

## Table of contents

* [Overview](#overview)
* [Deployment](#deployment)
* [User Guide](#user-guide)
* [Development History](#development-history)

## Overview
That's My Spot! is an application that generates a parking stall number for students and staff in the UH Manoa zone 20 parking structure.

## Deployment

The application was deployed via a Digital Ocean virtual machine. The running site can be accessed <a href="http://134.209.193.152/">here</a>.

## User Guide

This section provides a walkthrough of the That's My Spot! user interface and its capabilities.

### Landing Page

The landing page is the first page users see upon visiting the site. The page provides users with instructions on how to use the website.

<img width=500 src="../images/landing-top.png">
<img width=500 src="../images/landing-bottom.png">

### Sign in

Click on the "Login" link, then click on the Sign In link to bring up the Sign In page, allowing you to log in with your UH email:

<img width=500 src="../images/tms login.png">

If you do not yet have an account on the system, you can register by clicking on “Login”, then “Sign Up”:

<img width=500 src="../images/tms register.png">

New users can register accounts be adding their UH email, creating a password, and checking whether they have a parking pass.

### Admin

The admin page is only presented to those with admin access. The page displays taken parking spaces and the owner of the space, allowing admins to delete any reserved spots (e.g., in the event of one user owning multiple spots).

<img width=500 src="https://cdn.discordapp.com/attachments/1039313935775576164/1040170234285404231/image.png">

### Availability

To reserve a spot, select one of the available spots.

<img width=500 src="https://cdn.discordapp.com/attachments/1039313935775576164/1040167307365855293/image.png">

### Parking pass holders

If you have a parking pass, you are able to specify a level and side you wish to park so that stalls with your preferences are prioritized.

<img width=500 src="https://cdn.discordapp.com/attachments/1039313935775576164/1040171147750277200/image.png">

### Guest

If you do not have a UH email, you can continue as a guest and generate a random stall from the remaining stalls.

<img width=500 src="https://cdn.discordapp.com/attachments/1039313935775576164/1040187461940285500/image.png">

### Payment

AFter selecting a spot, guests and users without a parking pass proceed to the payment page to purchase their stall.

<img width=500 src="https://cdn.discordapp.com/attachments/1039313935775576164/1040184918883454986/image.png">

## Development History

Throughout development, the project met various milestones to ensure sufficient progress of the application was being made.
### <a href="https://github.com/orgs/thats-my-spot/projects/1/views/1">Milestone 1</a>

The goals of milestone 1 were to create mockup sketches of the site's pages and create some of the actual pages based on the sketches, as well as develop some of the backend by including the parking pass field to the account collection and adding the stalls collection.

### <a href="https://github.com/orgs/thats-my-spot/projects/2/views/1">Milestone 2</a>

The goals of milestone 2 were to continue development of the backend processes and the actual site pages based on the sketches, add a domain name for the website, and employ HTTPS.
