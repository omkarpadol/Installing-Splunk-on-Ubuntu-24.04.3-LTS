## Prerequisites
Before starting the installation of Ubuntu Server and Splunk Enterprise, ensure your system meets the following requirements.

# ✔ System Requirements

### 💻 Hardware Requirements

Minimum recommended for running Ubuntu + Splunk inside VMware Workstation Pro:

* **4 CPU cores** (2 minimum)
* **8 GB RAM** (4 GB minimum)
* **40 GB of free disk space**
* **64-bit processor with virtualization support (Intel VT-x or AMD-V)**
  ➤ Enable this in BIOS if it's turned off

---

## **✔ Software Requirements**

### **1️⃣ VMware Workstation Pro**

You need VMware Workstation Pro installed on your Windows 11 system.

**Download VMware Workstation Pro:**
[https://www.vmware.com/products/workstation-pro.html](https://www.vmware.com/products/workstation-pro.html)

VMware will be used to create the virtual machine where Ubuntu Server will run.

---

### **2️⃣ Ubuntu Server ISO**

Download Ubuntu Server 24.04.3 LTS ISO image:

[https://ubuntu.com/download/server](https://ubuntu.com/download/server)

---

### **3️⃣ Splunk Enterprise .deb Package**

You will download this later during the Splunk installation process from within Ubuntu.

---

## **✔ Network Requirements**

* Internet connection for downloading updates
* DHCP or Static IP address (Static recommended for Splunk access)
* Port **8000** open for Splunk Web Interface
* Port **22** open if using SSH

---

## **✔ Tools (Optional but Useful)**

* **GitHub Desktop** → for version control
* **Git Bash** → to run Linux-style commands
* **Notepad++ / VS Code** → for editing Markdown files

---

## **✔ User Requirements**

* A user account with **administrator rights** on Windows 11
* A basic understanding of:

  * Linux commands
  * Virtualization
  * Networking basics (optional)