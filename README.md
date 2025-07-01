# 📝 Training-Dairy [TRCS201]

Welcome to my **Training Dairy** — a daily log and report of my hands-on training experience during college. 


## 📚 Syllabus Overview:

| Module | Topic                                            | Key Skills Developed                                                                                                                               |
| ------ | ------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| **1**    | **Fundamentals of Unix/Linux & BASH Essentials** | Build a solid conceptual foundation of Unix/Linux, get hands-on with system installation, and learn how to use the Linux command line effectively. |
| **2**    | **PC & Network Troubleshooting**                 | Equip students with essential skills to diagnose and resolve common hardware and networking issues in a practical environment.                     |
| **3**    | **Introduction to HTML & Web Basics**            | Learn to build basic web pages using HTML.                                                                                                         |
| **4**    | **Introduction to GIT and Version Control**      | Learn and apply Git through CLI in a Linux environment.                                                                                            |

---


## Day 1-Introduction and Installation of Linux(Ubuntu) [25-6-25]
An orientation was organized by the CSE Department in the college auditorium, featuring a briefing on the department, the future scope of our degrees, and recent changes made to the curriculum.
The session provided valuable insights to help students align their academic goals with industry expectations.

![linux-ar21](https://github.com/user-attachments/assets/a2a6f892-7065-4a9b-9a1e-de73d30670bd)

### Linux is an open-source operating system based on Unix, known for its stability, security, and flexibility. It powers everything from servers and smartphones to supercomputers and is widely used in development, system administration, and cybersecurity.
 
 I learned to work with **Linux (Ubuntu)** using two methods:

- 🖥️ Oracle VirtualBox
- 💻 Dual Booting with USB

---
## 🛠️ Installation Steps 

### For installing Ubuntu we have to install following 
#### Method 1 - Using Virtual Box

#### 1. **Installation of Oracle VirtualBox**
   - To install VirtualBox, visit the official site Virtualbox and download the latest version for windows 
   ![Untitled](https://github.com/user-attachments/assets/766cf09f-58eb-4abb-8317-78b05db085af)
   
   - After downloading the setup, Let's **install** it



      ![Untitled1](https://github.com/user-attachments/assets/05cab4a6-1749-4275-9fbe-b87fab54206c)

   - After reading the Terms & conditions and accepting the License agreement, determine the installation path



     ![Untitled](https://github.com/user-attachments/assets/5822c1cf-75a7-4925-92dc-d6f099b29092)

   - Creating Entries and Shortcuts



     ![Untitled](https://github.com/user-attachments/assets/4a1c3997-2ea4-4193-828f-fe550505e3bb)

     
   - Now setup is ready to install, Click install



     ![Untitled](https://github.com/user-attachments/assets/eeecc3a7-a1fb-41dd-967b-e1fba9219786)

   - Installing Files and Packages



     ![Untitled](https://github.com/user-attachments/assets/77b9a592-a587-4c1a-8174-e04e7a6f9dfc)

   - Installation Finished, press  Finish



     ![Untitled](https://github.com/user-attachments/assets/38d3360e-b20d-4cd0-996a-c5f996ce13c9)


   - Then a virtual box will start as shown



     ![image](https://github.com/user-attachments/assets/940937dd-0550-4027-9415-3fca9672de68)


   - Installation of Ubuntu ISO image


     ![Untitled](https://github.com/user-attachments/assets/91fdd545-5952-4cdd-92a8-bf67192caaab)


   - After installing the ISO image, click the NEW option in the Virtual box.
     Then Select Name, Folder and ISO image
     Then press Next


     ![Untitled](https://github.com/user-attachments/assets/2544390c-e348-4dae-b0ae-ab972e85c13f)



   - Then enter the usename and password 
     Then press Next


     ![Untitled](https://github.com/user-attachments/assets/8c824524-4c8e-45a3-8a29-cd49fb302d97)


  - Now allocate desired RAM (Minimum 2GB)
  - Also create a Virtual hard disk (minimum 20GB)
  - Now press start


- **Set Up C++ Extension**  
   For compiling and running C++ code in Linux.
   - Make sure to install VSCode on prior basis
   - Download Microsoft C/C++ Extension

![image](https://github.com/user-attachments/assets/ecf2170e-ac30-41a4-9658-19d91f3a0480)
     


#### 2. **Dual Booting Using USB**  
   Use it to install Ubuntu via dual boot on your actual machine.
   - Connect a USB drive (min 16 GB storage) with your system
   - Install Ubuntu ISO image as given above 
   - Now download Rufus to create the USB dive bootable. You can download desired version but recommended is highlighted as follows:

     ![Untitled](https://github.com/user-attachments/assets/f5dc57bb-896f-415d-9c77-728d23999ab8)
   - Open the Rufus software and select the desired options





     ![Untitled](https://github.com/user-attachments/assets/097709c4-67d0-4e9e-add0-d2c69bfbcf68)


     - After selecting press start and processing will start
     - After processing close rufus and now our pendrive ready
     - Now restart the system and open boot settings and select USB drive for booting
     - Now your Ubuntu will start and you are ready to use

---


