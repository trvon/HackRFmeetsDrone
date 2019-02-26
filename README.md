# HackRF meets Drone

## Project Idea
To use a HackRF to capture the communication between a reciever and quad copter and control the quad copter from a hackRF.
Based on this [project](https://ossmann.blogspot.com/2013/06/hackrf-lego-car.html)

## Abstract
Our project for wireless security attempts to build upon the hackrf and lego car project. The lego car project takes a remote controlled car and uses the hackRF to capture each control signal and then replays the signal to control the remote control car. In our project we will utilize a custom quadcopter with generic a firmware to attempt the same feat. Unlike the remote control car project, we will strive to achieve a few more goals prior to attempting to demostrate the ability to control the quadcopter with the hackRF. 

We will attempt to show:
- If there is any steps taken to authenticate the quadcopter and controller?
- If there are steps taken, what does the handshake look like?
- If there isn't, is authentication between quadcopter and controller available anywhere?
- What protocols are used in the quadcopters communication framework?
- What is the overhead of implementing such framework?

### Things to think about
What are potentially end goals?
How will we accomplish this feat?
What will our meeting up schedule look like

## Things to look into
- [ ] Steps taken to authenticate quadcopter and controller?
- [ ] What are methods of authentication implemented?
- [ ] What does the connection handshake consist of?
- [ ] Compare and contrast protocols used and drones and the security they implement 

## Useful Information
HackFR frequency range is 1Mhz to 6GHz and the quadcopter [antenna](https://fpv-flightclub.com/products/lumenier-axii-stubby-5-8ghz-antenna-rhcp/) frequency is 5.8 GHZ.

## Helpful Sources Found

### Protocols
- https://hackaday.com/2016/06/28/reverse-engineering-quadcopter-protocols/
- http://learningrc.com/rc-communication-protocols/
- http://www.jimhung.co.uk/?p=1424
### HackRF and Quadcopter
- https://www.rtl-sdr.com/hackrf-controlling-quadcopter/
- https://www.rcgroups.com/forums/showthread.php?2367199-Controll-Hubsan-X4-with-a-SDR-and-GnuRadio
### Drone hacks
- https://samy.pl/skyjack/
- https://github.com/Howchoo/drone-wars
### Hacking Drones
- https://medium.com/@konrad_it/brief-reverse-engineering-work-on-fimi-a3-5422d93db560

