# EXP 4 : USING THE AUTOPSY RETRIEVE THE DELETED FILES

## AIM:
This experiment aims to demonstrate:

  •	Create a Disk Partition.
  
  •	Adding, deleting, and recovering files using Autopsy.
  
  •	Understanding the forensic recovery of deleted data.
  
  •	Removing the disk partition after the process.

## EQUIPMENTS REQUIRED:
  ●	Hardware: PCs

```
Register Number:212222040128
Name: RAGHUL S
```

## DESIGN STEPS:
### Step 1:
Open Autopsy and create a new case with appropriate case details.

### Step 2:
Add a disk image as a data source and let Autopsy analyze the content.

### Step 3:
Navigate to the "Deleted Files" section in Autopsy and examine or recover the deleted files.


## PROCEDURE:
### Step1: Create a New Disk
  •	The new Disk Partition is created
![image](https://github.com/user-attachments/assets/2c140eae-a965-4ec1-b8a1-e6d92e8623d2)


### Step2: Adding and Deleting Files for Recovery
  •	Open File Explorer → Navigate to the newly created drive (C: or D:).
  
  •	Transfer images or files into it.
 ![image](https://github.com/user-attachments/assets/107ff732-d85c-48ac-9913-71f688543de9)

  
  •	Select one or more files → Press Delete.
  
  •	Empty the Recycle Bin to permanently remove them.
  
### Step3: Recovering Deleted Files Using Autopsy
1. Launch Autopsy and Set Up a New Case:
 
  •	Run Autopsy as Administrator.

  •	Click Create New Case.
  ![image](https://github.com/user-attachments/assets/2a61d108-a014-4d70-a1f4-a58f715649f4)

  •	Enter a case name (e.g., Autopsy1).
  
  •	Select a location for the case folder → Click Next → Finish.

![image](https://github.com/user-attachments/assets/0ce98c3a-5958-412f-be32-3f3d7cc7bfb2)

  

  •	Add optional information
  
![image](https://github.com/user-attachments/assets/bce82ba5-63d3-4324-8c9f-4876949dbef9)


2. Add the Partition as Evidence:
  •	Click Add Data Source → Choose Host.
 ![image](https://github.com/user-attachments/assets/5caee63a-165d-439e-8082-0e229d184406)


  •	Select Local Disk → Click Next.Create a Disk Partition.
![image](https://github.com/user-attachments/assets/940715e0-f54c-42ea-98f6-390f5abfe202)


  •	Choose Disk → Select the VHD drive (Drive1).
![image](https://github.com/user-attachments/assets/5c52ab92-b76f-4518-bc62-3fc7d8ba4ae2)


  •	Click Next → Keep the default settings → Click Finish.
![image](https://github.com/user-attachments/assets/f5cde72b-27d2-42a4-878e-0311dfec2f30)


  •	Allow Autopsy to process the disk.

## OUTPUT: Extract Deleted Files:
  •	In the left panel, navigate to File Views → Deleted Files.
  
  •	Locate your deleted images.
![image](https://github.com/user-attachments/assets/ca21ba88-7d6e-45e3-8032-1b226914503c)


  •	Right-click an image → Click Extract File.
  
  •	Choose a folder for saving the recovered files (e.g., C:\image_recovery).
  
  •	The deleted images are now restored!
![image](https://github.com/user-attachments/assets/52bf8194-1165-42ce-ab27-bf3841806361)


## Removing the Disk Partition (Optional Cleanup)
1.Using Disk Management:

  •	Open Disk Management (Win + X → Disk Management).
  
  •	Identify the created partition.
  
  •	Right-click on the partition → Select Delete Volume.
  
2.Alternative Method via Settings:

  •	Click the Start button → Go to Settings.
  
  •	Select System → Click Storage.
  
  •	Click Advanced Storage Settings → Select Disks & Volumes.
  
  •	View the list of available disks.
  
  •	Select the created partition → Click Properties.
  
  •	Click the Delete option to remove it.


## RESULT:
Deleted files were successfully retrieved and analyzed using Autopsy.
