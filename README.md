# Encryption of text files
This repository contains two windows applications (exe) that are interdependent on each other. One app will be used to create encrypted text files and the other will be used to decrypt the encrypted text files.
<br>
The file extension of the encrypted text file is **.enct**.
<br>
**ENCT** - **Enc**rypted **T**ext
## Instructions
### EnctCreator.exe
This application is used to create encrypted text files.
<br>
First you need to enter your desired text in the input area.
<br>
Then click on the **Encrypt & Save File** button present at the bottom-center in the GUI.
<br>
Name your file, for example - *Test*, and click on **Save**.
<br>
The file will be saved as **Test.enct**.
<br>
<br>
The GUI of this application is simple & easy to use. Here's a snip of the GUI -
<br>
<br>
<img width="301" alt="image" src="https://user-images.githubusercontent.com/85285702/229550332-de264dc6-d4c3-4890-ab78-994865d5a68b.png">
<br>
<br>
<br>
<hr>

### EnctViewer.exe
This application is used to decrypt the encrypted text files.
<br>
First click on the **Open .enct File** button located at the bottom-center in the GUI.
<br>
Select your .enct file.
<br>
Click on **Open**.
<br>
You will now see the decrypted text in the input field.
<br>
<br>
The GUI of this application is simple & easy to use. Here's a snip of the GUI -
<br>
<br>
<img width="301" alt="image" src="https://user-images.githubusercontent.com/85285702/229552017-c5feb27e-d4c0-4cd7-8f40-5608227dea95.png">
<br>
<br>
<br>
<hr>

# FAQ
**Q1.** I have created an encrypted text file but anybody can view it using *EnctViewer.exe*. What should I do ?<br>
**Ans -** You can hide your **EnctViewer.exe** file by following the instructions below -<br>
1. Open **cmd**.
2. **cd** into the directory in which the **EnctViewer.exe** is located.
3. Type **attrib +h EnctViewer.exe** and hit enter.
4. Your *EnctViewer.exe* gets hidden, **not deleted**.
<br>
<br>

**Q2.** I have followed the steps you mentioned in *Answer 1*, but now how do I access the **EnctViewer.exe** ?<br>
**Ans -** You can access the *EnctViewer.exe* file by following the steps below -
1. Open **cmd**.
2. **cd** into the directory in which you hid your **EnctViewer.exe** file.
3. Type **EnctViewer.exe** and hit enter.
4. The file opens !
<br>
<br>

**Q3.** Now I want to make my *EnctViewer.exe* file visible, what should I do ?<br>
**Ans -** You can make your **EnctViewer.exe** file visible by following the steps below -
1. Open **cmd**.
2. **cd** into the directory in which you hid your **EnctViewer.exe** file.
3. Type **attrib -h EnctViewer.exe** and hit enter.
4. The file is now visible !
<br>
<br>

**Q4.** Does any of these applications stores any type of data ?<br>
**Ans -** No, not at all. None of your data is saved by any of these applicaitons.
<br>
<br>

**Q5.** Which operating systems are supported by these applications ?<br>
**Ans -** Till now, only **Windows** is supported.
