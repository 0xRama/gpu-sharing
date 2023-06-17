# gpu-sharing
Below are the scripts I use to share my GPU between the host and virtual machine on Hyper-V.

CopyDriverFiles Script
The "CopyDriverFiles" script copies the NVIDIA drivers from the host to the guest virtual machine. Once the script completes the process, you will receive further instructions.

Main Points:

- This script is intended for Windows virtual machines only.
- The guest virtual machine needs to be turned on while using this script.
- Make sure to change the VM name from "Windows 11" to your virtual machine instance name.

GPU Partition Update Script

The "GPU Partition Update" script updates the GPU partition, splitting the GPU resources so that both the host and guest can use the same graphics card simultaneously.

Main Points:

- This script is also designed for Windows virtual machines.
- The guest virtual machine needs to be turned off while executing this script. The script will automatically turn on the guest after successful execution.
- Remember to change the VM name from "Windows 11" to your virtual machine instance name.
