Virtual Machine Resource Monitoring
A simple bash script for monitoring CPU, memory, and disk usage of a virtual machine. This script leverages built-in Linux commands for quick and efficient resource tracking.

Features
Displays CPU usage, showing the current load in percentage.
Reports memory usage, including total, used, and free memory.
Shows disk usage, detailing partition size, used space, and available space.
Prerequisites
An Ubuntu-based virtual machine or Linux system.
Basic familiarity with Linux terminal commands.
Bash shell (default on most Linux systems).
Setup Instructions
Clone or copy the script to your virtual machine.
Make the script executable:
bash
Copy code
chmod +x monitor_vm.sh
Run the script:
bash
Copy code
./monitor_vm.sh
Usage
Run the script anytime to monitor system resources. The output will display CPU load, memory usage, and disk utilization.

Customization
You can enhance the script by:

Adding logging functionality to save output to a file.
Scheduling it with a cron job for periodic monitoring.
Including additional metrics such as network usage or process details.
Optional Tools
For real-time interactive monitoring, you can also use:

htop: Install with:
bash
Copy code
sudo apt install htop
Run with:
bash
Copy code
htop
