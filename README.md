# Electricity Bills Checker 🔌🏢

🖱️ This project includes a web automation script using Selenium and Python.

The script checks whether a new electricity bill has been issued for each customer of the shared billings office (the customer entities are represented by a unique RF code, given on an excel file). 

I converted the script (.py file) into an executable file (.exe file) for easier and more flexible use by the office users. 

🗒️ Description of the process:
1) The accountant is executing the DEH_new_bills_checker.exe file.
2) The script checks the last bills that have been issued for each RF code (customers) and updates the excel file respectively. If a new bill is issued by "DEH" organization, then the billing period date and the boolean indicator column of that code, as well as the total number of the new bills are updated.
3) The accountant can see the number of the new bills and proceed with the appropriate accounting actions.


*📝Note 1: for faster implementation, less complicated and easier syntax for debugging, the XML path selectors used in this script could be replaced with CSS selectors.*

*📂Note 2: Convert Python Script to .exe File*
- Step 1: Install PyInstaller - Type below command in the command prompt: pip install pyinstaller
- Step 2: Navigate to Your Script's Directory - Go into the directory where your '.py' file is located.
- Step 3: Open PowerShell - Press the shift⇧ button and simultaneously right-click at the same location. Click on 'Open PowerShell window here'.
- Step 4: Run PyInstaller - Type the following command: pyinstaller --onefile -w 'filename.py' in that PowerShell window. The --onefile option ensures that PyInstaller creates a single executable file rather than a directory with multiple files. After typing the command 'Hit the Enter'.
- Step 5: Locate the directory of your executable file and open the 'dist' folder. Here you will get your '.exe' file.
