<table style="width:100%; font-family: Verdana, Tahoma; border: none;">
  <tr>
    <td align="left"><strong>Experiment No:</strong> 01</td>
    <td align="center"><h1>FTK Imager: A Forensic Imaging Tool Overview</h1></td>
    <td align="right"><strong>Date:</strong> </td>
  </tr>
</table>

---

## Acquiring Volatile Memory (RAM) Using FTK Imager

**Installation Link:**  
[Download FTK Imager](https://www.exterro.com/digital-forensics-software/ftk-imager)

---

### Steps to Capture RAM Using FTK Imager  

1. **Run as Administrator**  
   - Open **FTK Imager** with administrative privileges.  
   - Right-click the FTK Imager icon and select **Run as Administrator**.
   - ![Experiment 1 - 01](https://github.com/user-attachments/assets/38a84839-a30e-450e-8b42-c06d12909282)



2. **Initiate Memory Capture**  
   - In the menu bar, go to **File → Capture Memory**.
   - <img width="940" height="528" alt="image" src="https://github.com/user-attachments/assets/19978a1d-e640-43ea-9f0a-970a155b08ff" />


3. **Configure Destination**  
   - **Destination Path:** Select an **external drive** for saving.  
   - **Destination Filename:** Use `memdump.mem` or a descriptive name.  
   - **Optional:**  
     - **Include pagefile.sys** (captures virtual memory).  
     - **Create AD1 File** (saves in AccessData container format).
     - <img width="940" height="528" alt="image" src="https://github.com/user-attachments/assets/c3b226cd-d794-4e38-b087-af58f6426f9c" />


4. **Start Capture**  
   - Click **Capture Memory** to begin acquisition.
   - <img width="940" height="528" alt="image" src="https://github.com/user-attachments/assets/6c95e0f4-939d-411d-a952-e77a5b890c49" />
 

5. **Wait for Completion**  
   - Progress is shown with a bar.  
   - Time depends on RAM size.  
   - Memory dump file will be saved in your chosen folder.  

---

## Acquiring Non-Volatile Memory (Disk Image) Using FTK Imager  

1. **Start the Process**  
   - In FTK Imager, go to **File → Create Disk Image**
   - <img width="940" height="528" alt="image" src="https://github.com/user-attachments/assets/b6807f8c-7a8d-467e-9711-3879752104ed" />
 

2. **Select Source Evidence Type**  
   - **Physical Drive:** Entire disk, partitions, MBR.  
   - **Logical Drive:** Specific partition (e.g., `C:`).  
   - **Image File:** Convert/copy an existing image.  
   - **Folder Contents:** Image a specific folder.
   - <img width="940" height="532" alt="image" src="https://github.com/user-attachments/assets/28c651d0-73d7-4a82-94a5-49b188a288d5" />


3. **Select the Source Drive**  
   - Choose a physical drive (connected via **write-blocker**).  
   - Click **Finish**.
   - <img width="940" height="528" alt="image" src="https://github.com/user-attachments/assets/d0104ec4-bf65-4319-a54f-939f080a8748" />


4. **Configure Image Destination**  
   - Click **Add...** in the *Create Image* window.
   - <img width="940" height="528" alt="image" src="https://github.com/user-attachments/assets/aeec3996-9a23-4b75-8a8d-8fb996b59439" />

   - **Image Type:**  
     - `E01`: Recommended; includes compression, verification.  
     - `Raw (DD)`: Bit-by-bit copy.
     - <img width="940" height="528" alt="image" src="https://github.com/user-attachments/assets/ee09a98b-2564-41d9-ad95-95f44a89a1f2" />

   - **Evidence Item Information:** Case details, examiner name, description.
   - <img width="940" height="528" alt="image" src="https://github.com/user-attachments/assets/1c86e379-d453-42a5-8144-6750be88ff01" />
  
   - **Destination Folder:** Save to a separate drive; name appropriately.  
   - **Image Fragment Size:** Set split size (or `0` for single file).  

5. **Start Imaging**  
   - Click **Finish** and return to the *Create Image* screen.  
   - Enable **Verify images after creation**.  
   - Click **Start**.  
- <img width="940" height="528" alt="image" src="https://github.com/user-attachments/assets/230511d3-fda9-409a-a08c-8abbc1aae675" />

6. **Completion and Verification**  
   - Imaging duration varies with drive size.  
   - FTK Imager verifies **MD5** & **SHA1** hashes.  
   - Matching hashes confirm forensic integrity.  

---

## References  
- [FTK Imager Official Website](https://accessdata.com/product-download/ftk-imager-version-4-5)  
- FTK Imager Documentation  

---

<div align="center" style="font-size:14px; font-family: Verdana, Tahoma; color:gray;">
This Expriment is Done by Nischal S Tumbeti - 99230041300 | 23S19 | CSE Department - SoC | KARE
</div>
