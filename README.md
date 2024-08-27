Step-by-Step Solution:
Create the Script File:

Open a terminal on your Linux system.
Create a new file named processrunning.sh using a text editor like vi or nano.
bash
Copy code
vi processrunning.sh
Write the Script:

Add the following lines to the file:
bash
Copy code
#!/bin/bash
echo "Displaying all running processes:"
ps aux
echo "Total processes running: $(ps aux | wc -l)"
Save and close the file.
Make the Script Executable:

Change the permissions of the script to make it executable:
bash
Copy code
chmod +x processrunning.sh
Execute the Script:

Run the script on your system:
bash
Copy code
./processrunning.sh
The script will display a list of all running processes, followed by the total number of processes.
Review the Output:

The script will first output a detailed list of running processes using the ps aux command.
It will then count the total number of processes and display this count.
Test the Script:

Ensure the script runs correctly and provides accurate information.
If needed, modify the script for additional functionality or to refine the output.
Conclusion:
This project involves creating a simple but effective shell script to monitor system processes, which can be useful for understanding system performance and managing resources. By following these steps, you’ll have a functional script that meets the problem's objectives.
