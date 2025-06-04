# Install-Autopsy-and-Analyze-the-Disk-File-and-Folder-Configuration

## NAME : VARSHINI S A
## REGISTER NO : 212222100059


## AIM:
To install Autopsy on Kali Linux and analyze disk images, files, and folder configurations for digital forensic purposes.

## DESIGN STEPS:
### Step 1:
Install Autopsy using the terminal with the command(Kali Linux) or GUI application (windows)

### Step 2:
Launch Autopsy from the terminal or application menu and create a new case.

### Step 3:
Add a disk image or file to the case and analyze the contents such as deleted files, metadata, and folder structure.

## PROGRAM:
### **Install Autopsy for Windows (GUI-based Forensic Tool)**
🔗 **Download Autopsy**: [Click Here](https://www.autopsy.com/download/)  
1. Download the **Autopsy Windows Installer** from the official website.  
2. Extract the ZIP file and open the **bin** folder.  
3. Run `autopsy.exe` and set up a new forensic case for analysis.

### **Install Autopsy for Linux**
1. Open Terminal.
2. Update your package list: sudo apt update
3. Install Autopsy: sudo apt install autopsy
4. Launch Autopsy using: autopsy
5. Open http://localhost:9999/autopsy in a web browser.

### **Create & Configure a Virtual Hard Disk (VHD) in Windows**

1. Press **Win + X**, Select Disk Management.
2. Click Action > Create **VHD**.
3. Choose a location and set a disk size (e.g., 10GB+).
4. Select Fixed Size or Dynamically Expanding and click OK.
5. In Disk Management, find your new disk (marked as "Not Initialized") -> Right-click the new disk → Initialize Disk → Select **MBR**.
6. Right-click Unallocated Space → **New Simple Volume** → Format the disk -> Click next → Finish.


## OUTPUT:
### Autopsy for Windows
![autopsy](https://github.com/user-attachments/assets/2f5bc402-c133-43e3-8b46-75e30d7a986d)

### Autopsy for kali linux
![Output_kali](https://github.com/user-attachments/assets/a668ff40-c619-4f3e-b59a-89b2bc99c985)

![image](https://github.com/user-attachments/assets/7f6280b0-b50c-497d-84fc-b42a39450ffa)

### Analysing the disk file and configuration:
![Screenshot 2025-06-01 202453](https://github.com/user-attachments/assets/a81ac53e-2924-4815-9eb0-2744348c9bc7)

![Screenshot 2025-06-01 202513](https://github.com/user-attachments/assets/d69e9cef-a65e-4fdb-900f-f44cdbdac1d6)

![Screenshot 2025-06-01 202735](https://github.com/user-attachments/assets/41287980-b160-47f1-9e11-f99d76d06f09)

![Screenshot 2025-06-01 202921](https://github.com/user-attachments/assets/b3712a17-00df-41df-92db-9aea375efd2c)

![Screenshot 2025-06-01 203313](https://github.com/user-attachments/assets/e89a0003-9a30-4a06-9991-ed22e42b991c)

![Screenshot 2025-06-01 203332](https://github.com/user-attachments/assets/e0ae9cf3-759b-45b5-b184-1c6323d3ca99)

![Screenshot 2025-06-01 203848](https://github.com/user-attachments/assets/0ea04382-1690-49db-b96e-5cfb17605721)

![Screenshot 2025-06-01 204026](https://github.com/user-attachments/assets/676a00ae-ec94-449f-9558-ed79302911e3)

![Screenshot 2025-06-01 204100](https://github.com/user-attachments/assets/481d902b-2a95-4ebd-a637-1e37ef09d724)


### Timeline:
![Screenshot 2025-06-01 205831](https://github.com/user-attachments/assets/55021b3b-de2e-475e-85d3-cf68999ae4b0)

![Screenshot 2025-06-01 214135](https://github.com/user-attachments/assets/0de2a11f-469c-47bd-8a87-4f5cb450309f)

![Screenshot 2025-06-01 214411](https://github.com/user-attachments/assets/427a9a36-1cab-4b62-9792-2284e91bac9f)

![Screenshot 2025-06-01 214444](https://github.com/user-attachments/assets/0d71fd90-db40-46f0-87c1-da7b3af3b307)




## Data Source Summary Report:
![Screenshot 2025-06-01 215625](https://github.com/user-attachments/assets/d4edcecc-beb4-43f3-b8da-81d0ab080cb4)



## RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.
