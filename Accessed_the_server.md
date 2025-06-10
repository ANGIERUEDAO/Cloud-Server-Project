## **Accessed the server via RDP/SSH for manual configurations**
------------------------------------------------------

### 3️⃣ **Connect to Your Server**  
**If using Windows (RDP):**  
1. Open **Remote Desktop Connection (`mstsc`)**  
2. Enter your **VM's Public IP Address**  
3. Click **Connect**, enter your credentials  

**If using Linux (SSH):**  

We will be using this option:
 **Connect to the Server from Ubuntu (Linux Terminal)**  
**Step 1: Find Your Azure VM Public IP Address**  
- Log into **Azure Portal** → [https://portal.azure.com](https://portal.azure.com)  
- Navigate to **Virtual Machines** → Select your VM  
- Under **Networking** or **Overview**, locate your **Public IP Address**  
 **In this case:** `20.123.45.67`  

**Step 2: Open Ubuntu Terminal**  
- Click **Activities** → Search for **"Terminal"** → Open it  

**Step 3: Connect to Your Server via SSH**  
Replace `your_server_ip` with **the Public IP** from Step 1:  
```bash
ssh azureuser@your_server_ip

