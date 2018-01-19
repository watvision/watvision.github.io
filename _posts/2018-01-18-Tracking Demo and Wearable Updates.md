---
layout: post
title:  "Tracking Demo and Wearable Updates"
author: Lior Lustgarten
---

We're two weeks into the term, time for some updates!

##### First Tracking Demo

Our vision system is now at the stage where we can track the ring and screen at the same time!
 The android app uses the phone's camera to take pictures in real time. Each of these pictures
 is processed through our vision system to locate the markers at the corners of the screen and
 the marker of the wearable. White lines are drawn over the camera’s image to show where the 
 screen was detected. The screen is then normalized to remove perspective. We can use this cleaned
 up screen (seen in the bottom right corner of the app) for element identification.

<img src="/img/BP2-tracking-demo-and-wearable-update/wearable_demo_1.jpg" alt="User holding 
their phone in their right hand and using the Watvision wearable in their left hand to explore
 the screen" class="img-responsive" />
<p>Proof of concept demo for ring and screen tracking</p>

##### Ring Prototype Progress


<div class="row">
    <div class="col-sm-6">
        <img src="/img/BP2-tracking-demo-and-wearable-update/wearable_demo_2.jpg" alt="Closeup of the prototype ring showing where it sits on the finger" class="img-responsive" />
        <p>3D printed finger tracking ring in use</p>
    </div>

    <div class="col-sm-6">
        In December we created two prototype 3D printed rings for finger tracking. The rings are intended
        to be worn just below the fingertip. This allows a user to rest the ring against the screen and 
        then tilt their finger forward when they want to touch the screen. Over the last month, the team 
        has been using these early prototypes to get a sense of how to improve our wearable. A recent 
        addition to the prototype is a strip of microfiber cloth (glasses cleaner material) sewn around 
        the band of the ring. This soft material glides against the touch screen to avoid scratches allowing 
        the user to slide their finger around the screen without touching it accidentally.
    </div>
</div>
<br/>


##### Wearable - Haptic Feedback

One of our goals is to add haptic feedback to our project. Vibration as a mode of communication 
to the user is intuitive and immediate. For example, if a vibration occurs each time the user’s 
finger is over an interactable element, it will allow for the screen to be explored more quickly.
<br/>
The platform for our first haptic prototype is the <strong> Raspberry Pi Zero </strong>. It’s 
relatively small, easy for us to program and has Bluetooth built in for communication with the 
phone. We’re also testing the similar <strong>SparkFun ESP32 Thing </strong> as an alternative.
<br/>
These are the parts we’re using for our proof of concept : 

<div class="row">
    <div class="col-sm-6">
        <img src="/img/BP2-tracking-demo-and-wearable-update/raspberry_pi_zero_battery_haptic_motor.jpg" alt="Raspberry Pi zero powered by small lipo and vibration motor with haptic driver." class="img-responsive" />
        <p>The setup for the use of the app is demonstrated using the Camera App</p>
    </div>

    <div class="col-sm-6">
            <li><a href="https://www.adafruit.com/product/3400">Raspberry Pi Zero</a></li>
            <li><a href="https://www.adafruit.com/product/1578">3.7v 500mAh Lithium Ion Polymer Battery</a></li>
            <li><a href="https://www.adafruit.com/product/3196">Pimoroni LiPo Shim</a></li>
            <li><a href="https://www.adafruit.com/product/1201">Vibrating Mini Motor Disc</a></li>
            <li><a href="https://www.adafruit.com/product/2305">Haptic Motor Controller</a></li>
            <li><a href="https://www.adafruit.com/product/1905">USB LiPo Charger</a></li>
    </div>
</div>
<br/>

##### Moving Forward
As our system takes shape, we’re looking to get more feedback. We have been guided so far by insights
 gained from interviews with people who are blind or visually impaired. Soon we plan to have a functional
 (if rough around the edges) demo and we’re excited to hear what people think! If you are interested in
 trying it out and giving us feedback, reach out to our team email: watvisionteam@gmail.com