<table style="width:100%; font-family: Verdana, Tahoma; border: none;">
  <tr>
    <td align="left"><strong>Experiment No:</strong> 02</td>
    <td align="center"><h1>TestDisk: Open-Source Data Recovery Tool</h1></td>
    <td align="right"><strong>Date:</strong> </td>
  </tr>
</table>

---

## Recover a Missing Partition and Repair a Corrupted One Using TestDisk

**Installation Link:**  
[Download TestDisk](https://www.cgsecurity.org/wiki/TestDisk_Download)

---

### Steps to Recover and Repair Partitions Using TestDisk

1. **Create a Log File**  
   - Launch TestDisk:  
     - Linux/macOS: `sudo testdisk`  
     - Windows: `testdisk_win.exe`  
   - Select **[Create]** to generate a recovery session log file.  
   - <img width="1365" height="718" alt="Image" src="https://github.com/user-attachments/assets/0dde6bc8-7136-4017-b53d-f2a74620c554" />

---

2. **Select the Drive to Analyze**  
   - Highlight the drive containing your lost data.  
   - Select **[Proceed]** to continue.  
   - <img width="1365" height="719" alt="Image" src="https://github.com/user-attachments/assets/0378240e-650c-4aff-9c8b-cd8155f90e1b" />

---

3. **Choose Partition Table Type**  
   - TestDisk auto-detects the partition type (Intel/PC, EFI GPT, etc.).  
   - Confirm default selection and press **Enter**.  
   - <img width="1365" height="719" alt="Image" src="https://github.com/user-attachments/assets/380e7a23-0a5a-48cf-aa46-752be3313767" />

---

4. **Analyze Current Partition Structure**  
   - Choose **[Analyse]** to detect missing or damaged partitions.  
   - <img width="1365" height="725" alt="Image" src="https://github.com/user-attachments/assets/6d592668-952c-479b-a322-441884c8a192" />

---

5. **Perform a Quick Search**  
   - Run **[Quick Search]** to locate partitions quickly.  
   - Press `p` to list files, `q` to go back.  

---

6. **Perform a Deeper Search**  
   - Select **[Deeper Search]** for a full disk scan if needed.  
   - <img width="1365" height="716" alt="Image" src="https://github.com/user-attachments/assets/9eae95d3-3170-4a76-9a15-1aacb96a97be" />

---

7. **Modify Partition Status**  
   - Use arrow keys to mark partitions:  
     - `P`: Primary  
     - `*`: Bootable  
     - `L`: Logical  
     - `D`: Deleted  
   - Ensure required partitions are **Primary/Logical**.  
   - <img width="1365" height="715" alt="Image" src="https://github.com/user-attachments/assets/2c5c19bf-4de7-48db-8b3f-380b8e995b02" />

---

8. **Write the Partition Table**  
   - Select **[Write]** and press `y` to confirm.  
   - <img width="1365" height="716" alt="Image" src="https://github.com/user-attachments/assets/c5252718-9600-47a5-b35e-92d32db052e7" />

---

9. **Recover Files**  
   - Navigate partitions, select files with `:`, copy with `C`.  
   - Save files to a separate storage device.  
   - <img width="1365" height="727" alt="Image" src="https://github.com/user-attachments/assets/c02571bf-3c5e-4ac9-bebe-d77ab1647847" />

---

10. **Exit and Restart**  
    - Select **[Quit]** to close TestDisk.  
    - Restart system if partition table was modified.  

---

## References
- [TestDisk Download](https://www.cgsecurity.org/wiki/TestDisk_Download)  
- [TestDisk Documentation](https://www.cgsecurity.org/testdisk_doc/)

---

<div align="center" style="font-size:14px; font-family: Verdana, Tahoma; color:gray;">
This Experiment is Done by Nischal S Tumbeti - 99230041300 | 23S19 | CSE Department - SoC | KARE
</div>
