Thanks for pointing that out. I'll update the instructions with a direct guide for the current version of the Hubitat Package Manager.

### **Updated Installation Instructions for "Simple Zen32 Button LED and Device Sync"**

## **Option 1: Installing via Hubitat's Built-in Interface (Manually)**
This method involves directly adding the Parent and Child Apps using Hubitat's code editor.

#### **Step 1: Access Hubitat's App Code Section**
1. Open your Hubitat Elevation Dashboard.
2. In the left-hand menu, click on **"Apps Code."**

#### **Step 2: Add the Parent App**
1. Click the **"New App"** button.
2. Copy the **Parent App Code** (the first script you provided) and paste it into the editor.
3. Click **"Save"** to store the Parent App code.
4. Make sure the Parent App is saved correctly by checking for any error messages.

#### **Step 3: Add the Child App**
1. Click the **"New App"** button again.
2. Copy the **Child App Code** (the second script you provided) and paste it into the editor.
3. Click **"Save"** to store the Child App code.
4. Ensure the Child App is saved without errors.

#### **Step 4: Install the Parent App**
1. Go to the **"Apps"** section from the left-hand menu.
2. Click the **"Add User App"** button.
3. Select **"Simple Zen32 Button LED and Device Sync"** (the Parent App you added).
4. Configure the settings as needed. You can now create and configure Child Apps directly within the Parent App.

## **Option 2: Installing via Hubitat Package Manager (HPM)**
If you have Hubitat Package Manager (HPM) installed, you can use it to automate the installation process.

### **Step 1: Install Hubitat Package Manager (If Not Already Installed)**
1. Go to the [Hubitat Community Forum](https://community.hubitat.com/) and search for the latest version of **Hubitat Package Manager**.
2. Follow the instructions provided in the forum to download and install the latest version of HPM.
   - This usually involves going to the **"Apps Code"** section in your Hubitat dashboard.
   - Click **"New App"** and paste the HPM code found on the forum.
   - Save and install HPM from the **"Apps"** section.

### **Step 2: Open Hubitat Package Manager**
1. In your Hubitat dashboard, go to the **"Apps"** section.
2. Open **Hubitat Package Manager** from your installed apps list.

### **Step 3: Install "Simple Zen32 Button LED and Device Sync" via HPM**
1. Click on **"Install"**, then choose **"Search by Keywords"**.
2. Enter **"Simple Zen32 Button LED and Device Sync"** as the keyword.
3. If the package is available, follow the on-screen instructions to complete the installation. HPM will automatically handle the Parent and Child Apps setup.

### **Configuration After Installation**
Once the apps are installed, you can configure them as needed:
1. **Creating Child Apps**: Use the Parent App to create multiple instances of the Child App. Each instance can be customized to sync different Zen32 buttons with specific devices.
2. **Adjusting LED Settings**: Configure LED colors and brightness for each button's ON/OFF state, and assign devices to sync their states with Zen32 buttons.

Let me know if you need any more information or clarification!
