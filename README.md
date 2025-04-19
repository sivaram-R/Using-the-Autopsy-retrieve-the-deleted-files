# Using-the-Autopsy-retrieve-the-deleted-files
## AIM:
To use Autopsy in Kali Linux to retrieve and analyze deleted files from a disk image.

## DESIGN STEPS:
### Step 1:
Open Autopsy and create a new case with appropriate case details.

### Step 2:
Add a disk image as a data source and let Autopsy analyze the content.

### Step 3:
Navigate to the "Deleted Files" section in Autopsy and examine or recover the deleted files.

## PROGRAM:
### **1. Copy Files to the Virtual Disk**  
- Open **File Explorer** → Go to the new drive (`C: or D:`), where the folder created in the New Virtual Disk
- Create a new folder (`Autospy`) and copy **images or files** into it.  

### **2. Delete the Files**  
- Select any one or two images → Press **Delete**.  
- Empty the **Recycle Bin** to permanently delete them.  

### **3. Recover Deleted Files Using Autopsy**  
### **Open Autopsy & Create a New Case** 

- Launch **Autopsy** and **Run as a administrator**  
- Click **Create New Case**.  
![image](https://github.com/user-attachments/assets/55b36063-3d53-4605-86c8-8b1a6dcf5468)


- Enter a **Case Name** (e.g., `Autopsy1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  

![image](https://github.com/user-attachments/assets/ee413f79-6012-4e4d-aa39-411e9b493910)


### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**
![image](https://github.com/user-attachments/assets/e4297d46-3fb9-46c3-ad34-12628bac0494)


- Select **Local Disk** → **next** 
![image](https://github.com/user-attachments/assets/a4f1c26a-3894-4f56-80b0-c437ea738779)


- Select Disk → **Choose the VHD drive (`Drive1`)**

![image](https://github.com/user-attachments/assets/b4902fb9-81ea-4228-8786-d504b788a46c)


- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  
![image](https://github.com/user-attachments/assets/9ec07d47-5526-4e24-9a5d-307c03031383)
![image](https://github.com/user-attachments/assets/6eb7b3fd-83fb-4059-bc1c-ed5a2ca9ef82)


- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  
![image](https://github.com/user-attachments/assets/5f9e7529-56e6-4df4-bcb7-c92e98c2d287)


- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.


## Output :
### Folder before deleting the files
![image](https://github.com/user-attachments/assets/78bf64a8-944c-494b-bb0d-97d97c804eb1)


### Folder after deleting the files
![image](https://github.com/user-attachments/assets/6af9a20b-da14-487c-bd36-84d6d7adab62)


### Folder after extracting the deleted images using autopsy
![image](https://github.com/user-attachments/assets/9723a5ad-3cd4-4679-b99d-426b0aaf6b9f)

## RESULT:
Deleted files were successfully retrieved and analyzed using Autopsy.
