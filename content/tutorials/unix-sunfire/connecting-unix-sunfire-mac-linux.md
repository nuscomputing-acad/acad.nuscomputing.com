---
title: "Connecting to SoC’s Sunfire UNIX server (Mac and Linux)"
description: ""
featured_image: ''
---

*The instructions below are for macOS and Linux users only.*

*For Mac OSX and Linux users, please go to this [link](/tutorials/unix-sunfire/connecting-unix-sunfire-windows).*

Open the **Terminal** application. You can either open it from the Applications folder, or simply search for Terminal using Spotlight.

Type ssh <SOC Username>@sunfire.comp.nus.edu.sg, replacing <SOC Username> with your **SOC Unix user-ID**.

The first time you connect to the Sunfire server, you should see a warning about the RSA key fingerprint.
Make sure that the key is 37:d3:59:84:00:75:09:10:f9:ea:99:ed:97:00:8e:40, and type yes.

You would then be prompted to enter your password.
**NOTE: the password field will not update even as you key in your password (i.e. the usual * characters will not appear as you type in your password).**

Enter your password and hit the Enter key.

You should be able to see the Sunfire shell. Your files and settings on Sunfire should now be available, and any command typed in the terminal would now be executed on Sunfire.