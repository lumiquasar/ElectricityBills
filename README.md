# Electricity Bills Checker 🔌🏢

🖱️ This project includes a web automation script using Selenium and Python.

The script checks whether a new electricity bill has been issued for each customer of the shared billings office (the customer entities are represented by a unique RF code, given on an excel file). 

I converted the script (.py file) into an executable file (.exe file) for easier and more flexible use by the office users. 

🗒️ Description of the process:
1) The accountant is executing the DEH_new_bills_checker.exe file.
2) The script checks the last bills that have been issued for each RF code (customers) and updates the excel file respectively. If a new bill is issued by "DEH" organization, then the billing period date and the boolean indicator column of that code, as well as the total number of the new bills are updated.
3) The accountant can see the number of the new bills and proceed with the appropriate accounting actions.



*📝Notes:*
*for faster implementation, less complicated and easier syntax for debugging, the XML path selectors used in this script could be replaced with CSS selectors.*
