# tech-environment-setup
My first 3MTT DevOps mini project

## Step-by-Step Installation & Configuration Guide

This guide walks you through installing and configuring essential tools for development and DevOps on Windows.

---
### 1. Visual Studio Code (VS Code)
**Purpose:** A lightweight, extensible code editor for writing, debugging, and managing code.

#### Steps:

1. Go to (https://code.visualstudio.com).
2. Click Download for Windows.
3. Once the .exe installer downloads, double-click it.
4. Go through the installer wizard:
   - Accept the license agreement.
   - Choose your installation directory or leave it as default.
   - Check the option to “Add to PATH” (recommended for command-line use).
    - Optionally enable:
      - “Add ‘Open with Code’ action to Windows Explorer.”
      - “Register Code as editor for supported file types.”
5. Click Install and wait for the process to finish.
6. After installation, launch VS Code.
7. On first launch, you’ll see the Welcome Screen:
    - You can choose to install recommended extensions or explore themes.

VS Code Welcome Screen 
![VSCODE](https://github.com/user-attachments/assets/f827c998-ab28-46d6-97fb-0eabc3913843)

## 2. Git  
**Purpose:** A version control system to track code changes and enable collaboration.

### Steps:

1. Visit [https://git-scm.com](https://git-scm.com).
2. Click **Download for Windows**.
3. Run the downloaded `.exe` file.
4. Go through the installer:
   - **Select components** → leave defaults checked.
   - **Choosing the editor** → you can pick VS Code as Git’s default editor.
   - **Adjusting PATH environment** → use the recommended option.
   - **Choosing HTTPS transport** → select the recommended option.
5. Complete installation by clicking **Install**.
6. After installation, open **Command Prompt** or **MobaXterm**.
7. Verify Git is installed by typing:
   ```bash
   git --version
Git Installation Confirmation
![MOBAXTERM](https://github.com/user-attachments/assets/bcc671b7-f192-4120-9996-7d6879445306) 

## 3. VirtualBox  
**Purpose:** A virtualization platform to run virtual machines (VMs) like Ubuntu.

### Steps:

1. Go to [https://www.virtualbox.org](https://www.virtualbox.org).
2. Click **Downloads**, then **Windows hosts**.
3. Run the downloaded `.exe` installer.
4. Go through the setup wizard:
   - Accept default settings.
   - Allow installation of networking features (when prompted, click **Yes**).
   - Click **Install** and wait.
5. After completion, launch **VirtualBox**.
6. Verify that VirtualBox opens without errors.

VirtualBox Installation Confirmation
![VIRTUAL BOX MANAGER](https://github.com/user-attachments/assets/ff894c47-e65e-4b8e-a7ff-a097eff853f4)

---

## 4. Ubuntu on VirtualBox  
**Purpose:** A Linux-based OS commonly used for backend development and DevOps tasks.

### Steps:

1. Download the latest Ubuntu Desktop ISO from [https://ubuntu.com/download/desktop](https://ubuntu.com/download/desktop).
2. Open **VirtualBox**.
3. Click **New**:
   - **Name** → Ubuntu
   - **Type** → Linux
   - **Version** → Ubuntu (64-bit)
4. Allocate at least 2GB (2048MB) RAM.
5. Choose **Create a virtual hard disk now** → Recommended size: 20GB or more.
6. Click **Create**.
7. Select the new VM → Click **Start**.
8. When prompted, attach the Ubuntu ISO file you downloaded.
9. Go through the Ubuntu installation inside the VM:
   - Select language, keyboard layout.
   - Choose **Normal installation**.
   - Select **Erase disk and install Ubuntu** (this only affects the virtual disk).
   - Create a username and password.
10. After installation, the VM will restart.
11. Login with the credentials you created to access the Ubuntu desktop.

Ubuntu Installation Confirmation
![Ubuntu](https://github.com/user-attachments/assets/67152700-733d-4d4f-b43d-b420f9f6730f)

---

## 5. GitHub Account  
**Purpose:** A cloud platform to store and manage Git repositories and collaborate on projects.

### Steps:

1. Visit [https://github.com](https://github.com).
2. Click **Sign up**.
3. Enter:
   - Username.
   - Email address.
   - Password.
4. Complete captcha and email verification.
5. After login:
   - Set up your profile (optional).
   - Go to **Repositories → New** to create your first repository.
6. You can now **clone**, **push**, and **pull** repositories from your local machine using Git.

GitHub User Account Setup confirmation
![GITHUB](https://github.com/user-attachments/assets/da75cfd7-fc12-4064-a675-da615fec5428)

---

## 6. AWS Management Console  
**Purpose:** A web interface to manage AWS cloud resources like EC2, S3, and IAM.

### Steps:

1. Go to [https://aws.amazon.com](https://aws.amazon.com).
2. Click **Sign In to the Console → Create a new AWS account**.
3. Fill in:
   - Email. 
   - Account name. 
   - Password.
4. Provide contact information and billing details (requires a credit/debit card).
5. Choose a support plan (**basic/free** is usually fine).
6. After setup: 
   - Login to the **AWS Management Console**.
   - Explore services like **EC2** (servers), **S3** (storage), and **IAM** (user management).

AWS User Account Setup comfirmation
![AWS](https://github.com/user-attachments/assets/0d4af573-d133-482d-bca6-d0c9787b6db9)



