Week 2 – Computer Systems Assignment
Installation Process
Installing Hypervisor
I installed Oracle VirtualBox on my Windows 11 laptop as the hypervisor for creating and managing virtual machines. VirtualBox was selected because it is lightweight, open source, and supports multiple guest operating systems. Before installation, I ensured that virtualization was enabled in BIOS/UEFI. I confirmed this by checking Task Manager → Performance tab, which showed Virtualization: Enabled.
Creating Ubuntu Linux VM
For the first virtual machine, I created an Ubuntu 24.04 LTS VM.
•	CPU Allocation: 2 cores
Reason: Ubuntu is a lightweight OS. Assigning 2 cores provides smooth multitasking without overloading the host system.
•	RAM Allocation: 4 GB (4096 MB)
Reason: Ubuntu desktop runs comfortably with 4 GB, allowing me to run applications and updates while keeping enough memory available for the host machine.
•	Disk Allocation: 20 GB (dynamically allocated)
Reason: The base installation requires around 8–10 GB. I allocated 20 GB to allow room for system updates and additional software.
Creating Windows Server VM
For the second virtual machine, I created a Windows Server 2022 (Trial Edition) VM.
•	CPU Allocation: 2 cores
Reason: Windows Server needs more processing power than Ubuntu. Allocating 2 cores provides stable performance for administrative tasks.
•	RAM Allocation: 8 GB (8192 MB)
Reason: The minimum requirement is 4 GB, but Windows Server with Desktop Experience runs much more smoothly with 8 GB, especially when using Server Manager and other built-in tools.
•	Disk Allocation: 50 GB (dynamically allocated)
Reason: Windows Server requires ~20 GB for installation. I allocated 50 GB to ensure enough room for roles, updates, and log files.
•	Post-Installation
•	Ubuntu Desktop
The Ubuntu VM booted successfully, and I was able to log in to the desktop environment. With 2 cores and 4 GB RAM, the system performed smoothly.
•	Windows Server Desktop
After installation, I logged in with the Administrator account. Server Manager opened by default. With 8 GB RAM, the system was responsive and could handle basic administrative tasks.
•	Observations on Performance
•	Ubuntu VM ran efficiently with minimal lag. Its lightweight design allowed me to allocate fewer resources while still maintaining good performance.
•	Windows Server VM required higher resources, especially RAM, to perform adequately. With 8 GB RAM and 50 GB disk, it handled installations and configurations smoothly.
•	By balancing resource allocation, both VMs could run on the same laptop without exhausting the host system
