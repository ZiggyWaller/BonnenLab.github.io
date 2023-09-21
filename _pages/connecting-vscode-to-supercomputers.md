---
title: "Vision in Action Lab - Connecting VS Code to Supercomputers"
layout: textlay
excerpt: "Connecting VS Code to supercomputers"
sitemap: false
permalink: /resources/connecting-vscode-to-supercomputers
---


##Steps to connect the code editor Visual Studio Code to supercomputers


1. After opening Visual Studio Code, navigate to  ##Extensions
![step1](https://github.com/ZiggyWaller/BonnenLab.github.io/assets/132411379/3f1792f6-62ed-460e-a561-0341507c6657)

2. Enter “remote ssh” in the search bar and install the extension.
![step2](https://github.com/ZiggyWaller/BonnenLab.github.io/assets/132411379/afb986e5-b6e0-426e-850f-ab151590b786)

3. Once the extension is installed, you will now have a “Remote Explorer” button ![step3_cropped](https://github.com/ZiggyWaller/BonnenLab.github.io/assets/132411379/a68514e3-f7a5-4936-ba15-f7174f1412bc) in your activity
bar.

4. To add a connection, click remote explorer, then click the plus sign next to SSH.
![step4_1](https://github.com/ZiggyWaller/BonnenLab.github.io/assets/132411379/4e59b6cd-7032-460f-af2c-0c98b7aa5ac4)

5. You will then be prompted to enter the SSH Connection Command. 
![step5_1](https://github.com/ZiggyWaller/BonnenLab.github.io/assets/132411379/d95622cd-3314-425b-96ab-014a5f1d1a90)

6. Click Connect.
    - You will be prompted to select the operating system of your remote machine. 
![step6_1](https://github.com/ZiggyWaller/BonnenLab.github.io/assets/132411379/5b6cc6c5-8c35-45b5-b12a-639f96c0cc81)


7. Select continue and you will be prompted to enter your password.

If you have 2fa setup, you will see your options in he terminal by navigating to “details”
![step7_1](https://github.com/ZiggyWaller/BonnenLab.github.io/assets/132411379/badfee10-8598-4dbe-8b0d-81a0b8edae87)
This will prompt another “Enter Password” bar where you can enter your pass code or select
the option to send a push.

Note: You can enter your password and 2fa in the terminal; however, you will need to re enter
your password in the bar after the 2fa process.

![step8_1](https://github.com/ZiggyWaller/BonnenLab.github.io/assets/132411379/42680485-5df6-4432-a48a-16bcdaa3c9fd)


You should now see a green check beside your connection and can navigate to desired directories using the vs code terminal as you would in your command line.
![step9_1](https://github.com/ZiggyWaller/BonnenLab.github.io/assets/132411379/9aa48c50-c1a9-4273-80b0-5b13c44edb1a)
