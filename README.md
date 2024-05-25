# Digital-forensics
## Description
In this project i am going to do  Disk and memory forensics with ransomeware infected System 

## Steps
1. Setup up  isolated windows 10 Virutal machine without any internet connection
2. Disable windows defender realtime protection and smartscreen protection
3. Download and run the wannacry ransomeware

   ![image](https://github.com/George-1100/Digital-forensics/assets/76154087/0fdbf265-910c-4dad-b3ea-4403b51757f4)

4. Download and install the FTK imager 
5. Use FTK imager to get Disk and memory image
6. Select Create disk image
   
   ![image](https://github.com/George-1100/Digital-forensics/assets/76154087/3037d867-da1c-43b6-a31c-2bd264e64c5f)

7. Select Logical drive
   
   ![image](https://github.com/George-1100/Digital-forensics/assets/76154087/08bbd237-a37a-4bbc-a289-fd90c0f8d3fe)

8. Select specific Drive
   
   ![image](https://github.com/George-1100/Digital-forensics/assets/76154087/fb35ae58-775f-4f77-90a6-44b29a134753)

9. Select File type

  ![image](https://github.com/George-1100/Digital-forensics/assets/76154087/803a345a-76b1-43a3-8997-0f3be4fa3ba8)

10 . Enter evidence item information

  ![image](https://github.com/George-1100/Digital-forensics/assets/76154087/84030f18-5acd-461a-9098-7c03b35cd5cc)

11. Select image destination folder make sure enough space available in that drive (removeble drive preferable for securly analysze a image in testing machine)
12. Enter image file name without extension
13. Use segmentation (optional)
14. click finish

  ![image](https://github.com/George-1100/Digital-forensics/assets/76154087/017c0783-4aaf-46e6-9357-73ec53e06957)

15. immage genrated successfully in the respective drive/folder
  
   ![image](https://github.com/George-1100/Digital-forensics/assets/76154087/be3e08ac-8e5d-4810-adfd-a7d00d22f6d2)

  ![image](https://github.com/George-1100/Digital-forensics/assets/76154087/9323f36f-46fa-4639-bf1d-7b2622ae6094)

  ![image](https://github.com/George-1100/Digital-forensics/assets/76154087/b8b4dde0-eb0f-4c70-85df-cf9c9f1059dd)
  
5. Download and install Autopsy
6. Create a  new Case in Autospy
7. Analyse the Disk image with Autopsy
   

   

