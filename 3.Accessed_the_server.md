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

`ssh azureuser@your_server_ip`

**Step 4: Accept the SSH Connection Request**  
If this is your first time connecting to the server, you’ll see a security prompt:  

`Are you sure you want to continue connecting (yes/no)?`

Type: Yes

**Step 5: Enter Your Password (If Required)**

If your VM requires password authentication, enter the administrator password and press Enter.

**Step 6: Verify Connection Success**

Once connected, you should see the Azure VM terminal interface:


