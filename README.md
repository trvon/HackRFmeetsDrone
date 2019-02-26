# HackRF meets Drone

## Project Idea
To use a HackRF to capture the communication between a reciever and quad copter and control the quad copter from a hackRF.
Based on this [project](https://ossmann.blogspot.com/2013/06/hackrf-lego-car.html)

## Abstract
### Team Members:
Shail Patel, Sneha Rangari, Ruchira Pokhriya, Trevon Williams

### Topic
Our Wireless Security project will attempt to build upon and adapt the hackRF and lego car project. In the lego car project, "MossMan" takes a remote controlled car and uses the hackRF to capture each control signal from the provided controller. "MossMan" then replays the capture signal to the remote control car, proving that he can control it with the replayed signal. 

In our project we will utilize a custom quadcopter with generic a firmware and reciever programming files to attempt a similar feat. Unlike the remote control car project, we will strive to achieve a few more goals prior to attempting to demostrate the ability to control the quadcopter with the hackRF. 

In our paper, we will detail the following findings:
- If there is any steps taken to authenticate the quadcopter and controller?
- If there are steps taken, what does the handshake look like?
- If there isn't, is there any implementation of authentication between quadcopter and controller available?
- What protocols are used in the quadcopters communication framework?
- What is the overhead of implementing such framework?

Given the pace in which we are able to understand and program the hackRF and then decode the signals being sent from the reciever to quadcpter, we plan to gain an understanding of how the reciever communicates with the quadcopter reciever and potentially compare how the implementation of authentication and/or secure communication effects how well the reciever is able to transmit to quadcopter. 

### Game Plan
- [ ] Learn how to use hackRF
- [ ] View and capture handshake between quadcopter and controller
- [ ] Determine if any authentication methods are implemented
- [ ] View if there is any publically implemented authentication measures in drones
- [ ] Compare and contrast found security protocols
- [ ] Determine the viability of controlling the drone through the hackRF
- [ ] Control the drone through the hackRF

### Expected Time Frame
- 6 to 7 Weeks 

### Deliverables
- Paper
- Demo: Working Communication between drone and hackRF 

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

