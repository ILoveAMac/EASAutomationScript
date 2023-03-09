# EASAutomationScript

### Important: Ensure to change the embedded_path variable on line 21 to point to the embeddded folder for the Intel EDS on your system.
### Important: This script is to be run in a linux environment such as WSL or any linux shell.

Simply put the automate.py file into the Quartus Directory and run it with "python3 automate.py", after you have done configuration in Platform designer.

The goal of this script is to automate the process of creating the "hps_0.h" file for the HPS and to compile the HPS code.
This script is intended to run on a Linux machine or in WSL with Quartus installed.
The script should be run in the same directory as the Quartus project.

```
The script will create the directory structure as shows below:
Quartus_Project/
├─ automate.py
├─ C Code/
│  ├─ hps_0.h
│  ├─ main.c
│  ├─ Makefile
Only the C Code directory will be created by the script.
```
