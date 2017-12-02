---
title: "Connecting to SoC’s Sunfire UNIX server (Windows)"
description: ""
featured_image: '/images/connecting-unix-sunfire.jpg'
---

*The instructions below are for Windows users only.*

*For Mac OSX and Linux users, please go to this [link](/tutorials/unix-sunfire/connecting-unix-sunfire-mac-linux).*

## [SSH Secure Shell Client](http://www.comp.nus.edu.sg/~cs1010/2_resources/SSHSecureShellClient-3.2.9.exe)

Download the SSH Secure Shell software to log into Sunfire.

## Instructions

- Click on Quick Connect button. A small window Connect to Remote Host will pop up.
- Under Host Name, enter sunfire.comp.nus.edu.sg (if you are using NUS WiFi, then just enter sunfire will do.)
  - Under User Name, enter your SoC UNIX user-id. Note that UNIX is case-sensitive.
  - Ensure that the Port Number is 22. Then click on the Connect button.
  - If you encounter any pop-up window with a “Yes” button, just click “Yes“.
- A window will appear to prompt you for your password. Note that the user-id and password are case-sensitive.
  - If you forgot your password, you can recover it here.
- Once you have logged into Sunfire, you are automatically placed in your home directory. You will see the display similar to the image above. Note that your UNIX prompt is shown as ```“your_userid@sunfire [time] ~ $”``` indicating a successful login. You are now at the home directory of your Sunfire account.