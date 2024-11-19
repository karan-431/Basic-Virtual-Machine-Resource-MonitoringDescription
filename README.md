Virtual Machine Resource Monitoring Guide
This guide provides a step-by-step setup for a Bash script to monitor CPU, memory, and disk usage in a virtual machine.
Features:
 CPU Usage: Displays the current load in percentage.
 Memory Usage: Reports total, used, and free memory.
 Disk Usage: Shows partition size, used space, and available space
 
Prerequisites:
 An Ubuntu-based virtual machine or Linux system.
 Basic familiarity with Linux terminal commands.
 Bash shell (default on most Linux systems).
 
 Setup Instructions
 
Step 1: Clone or Create the Script
Write or copy the Bash script (monitor_vm.sh) to your virtual machine.

Step 2: Make the Script Executable
Open a terminal.
 Navigate to the directory where the script is saved:
 syntax of code:cd /path/to/script
 Make the script executable
 syntax of code:chmod +x monitor_vm.sh

 Step 3: Run the Script
 Execute the script:
 syntax of code:./monitor_vm.sh


 Usage
 Run the script anytime to display system resource usage.
 The output includes:
  CPU load in percentage.
  Total, used, and free memory.
  Disk usage statistics for each partition.


