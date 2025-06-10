#  Deploying a Cloud Server on Azure  

##  Setup Instructions

### 1️⃣ **Claim Your Azure Free Credit**
- Sign up at [Azure Student Portal](https://azure.microsoft.com/en-us/free/students/)
- Verify student status to get **$100 free credit**  
 <p align="center">
    <img src="https://github.com/ANGIERUEDAO/Cloud-Server-Project/blob/main/images/example.png" width="600">
</p>


### 2️⃣ **Deploy a Cloud Server in Azure**
- Log into Azure and go to **Virtual Machines**
- Click "**Create Virtual Machine**"
- Choose **Windows Server 2022 Datacenter** as the OS
- Configure **CPU/RAM**: Minimum **2 vCPUs, 4GB RAM** 
- Open **Ports**:
  - **Port 80** → Web server (HTTP)
  - **Port 443** → Secure connections (HTTPS)
  - **Port 1194** → VPN access
  - **Port 22** → Needed for secure remote access if you're using Linux  (SSH).
  - **Port 3389** → Required for connecting to Windows Server through Remote Desktop  (RDP).
  - Click "**Create and review**"
  <p align="center">
    <img src="https://github.com/ANGIERUEDAO/Cloud-Server-Project/issues/2#issue-3132050446" width="600">
</p>

## Deployment Method: Why No Local ISO?  
Unlike traditional VM setups using ISO files on local hypervisors (VirtualBox, VMware), this project deploys a cloud-based server using Azure. 
Since Azure provides pre-configured Windows Server images, there is no need to download an ISO or manually enter a license key.


