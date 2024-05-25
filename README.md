# Digital-forensics
## Description
In this project i am going to do  Disk and memory forensics with ransomeware infected System 

## Steps
1. Setup up  isolated windows 10 Virutal machine without any internet connection

   ![image](https://github.com/George-1100/Digital-forensics/assets/76154087/2b365fb7-9af3-4f68-bf48-7a147943ca7a)

3. Disable windows defender realtime protection and smartscreen protection
4. Download and run the wannacry ransomeware

   ![image](https://github.com/George-1100/Digital-forensics/assets/76154087/0fdbf265-910c-4dad-b3ea-4403b51757f4)

5. Download and install the FTK imager 
6. Use FTK imager to get Disk and memory image
7. Click file -> Select Create disk image
   
  ![image](https://github.com/George-1100/Digital-forensics/assets/76154087/0ec53541-d60e-4f39-99e3-bc5831c56c94)


7. Select Logical drive
   
   ![image](https://github.com/George-1100/Digital-forensics/assets/76154087/08bbd237-a37a-4bbc-a289-fd90c0f8d3fe)

8. Select specific Drive
   
   ![image](https://github.com/George-1100/Digital-forensics/assets/76154087/fb35ae58-775f-4f77-90a6-44b29a134753)

9. Select File type

  ![image](https://github.com/George-1100/Digital-forensics/assets/76154087/803a345a-76b1-43a3-8997-0f3be4fa3ba8)

10 . Enter evidence item information

  ![image](https://github.com/George-1100/Digital-forensics/assets/76154087/84030f18-5acd-461a-9098-7c03b35cd5cc)

11. Select image destination folder make sure enough space available in that drive (removeble drive preferable for securly analysze a image in remote testing machine from infected machine)
12. Enter image file name without extension
13. Use segmentation (optional)
14. click finish

  ![image](https://github.com/George-1100/Digital-forensics/assets/76154087/017c0783-4aaf-46e6-9357-73ec53e06957)

15. immage genrated successfully in the respective drive/folder
  
   ![image](https://github.com/George-1100/Digital-forensics/assets/76154087/be3e08ac-8e5d-4810-adfd-a7d00d22f6d2)

  ![image](https://github.com/George-1100/Digital-forensics/assets/76154087/9323f36f-46fa-4639-bf1d-7b2622ae6094)

16. click file -> select capture memory

  ![image](https://github.com/George-1100/Digital-forensics/assets/76154087/37f600cd-d8be-4e27-907c-487273fddbf3)

17.  Enter Destination folder to store memory image (removeble drive preferable for securly analysze a image in remote testing machine from infected machine)
18.  click capture memory
     
  ![image](https://github.com/George-1100/Digital-forensics/assets/76154087/fec21965-899e-4e46-826c-b48aeb6ce70f)

  ![image](https://github.com/George-1100/Digital-forensics/assets/76154087/b8b4dde0-eb0f-4c70-85df-cf9c9f1059dd)
  
19. Download and install Autopsy in test machine (isolated from infected machine)

![image](https://github.com/George-1100/Digital-forensics/assets/76154087/668084a1-84e6-4578-b7c3-81345814cd4d)

7. Create a  new Case in Autospy
8. Analyse the Disk image with Autopsy
   

   

