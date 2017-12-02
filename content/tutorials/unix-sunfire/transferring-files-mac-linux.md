---
title: "Transferring Files (Sunfire <-> Mac/Linux)"
description: ""
featured_image: ''
---

Download and Install [CyberDuck](http://cyberduck.ch/).
If your machine is missing the Java runtime, you would be prompted to download the Java runtime. Install the Java runtime.

Tap on the + button at the bottom left.

The add new connection popup should appear. Fill in the fields as follows:

- Type: SFTP (SSH File Transfer Protocol)
- Nickname: <Anything you want. But preferably something like sunfire>
- Server: sunfire.comp.nus.edu.sg
- Port: 22
- Username: <Your SOC UNIX Account Name>

The newly created connection should appear in the bookmark window. Double click on the one that you just created.

A login window should appear. Enter your password. Checking the “Add to Keychain” box would save your password on your device, and you would not need to enter your password again.

The directory listing of the remote folder should appear. You can drag the files from the remote server to your local machine to download the file, or drag the files from your machine to the Cyberduck window to upload the files to the remote server.