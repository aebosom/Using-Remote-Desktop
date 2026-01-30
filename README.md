<p align="center">
<img width="584" height="663" alt="image" src="https://github.com/user-attachments/assets/d7ed97c6-b68e-4675-8330-8e5a34e9038b" />
</p>

<h1>Using Remote Desktop (Azure)</h1>
This tutorial outlines how to implement and use Remote Desktop by making a Virtual Machine inside of Microsoft Azure.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 11 Home
- Windows 10 Enterprise, version 22H2 - x64 Gen2

<h2>Deployment and Configuration Steps</h2>

- Step 1
  - Search "Virtual Machine"
  <img width="711" height="172" alt="image" src="https://github.com/user-attachments/assets/a49dc963-f116-442a-bf38-6f8663888964" />

- Step 2
  - Click Create, Virtual Machine
  <img width="448" height="258" alt="image" src="https://github.com/user-attachments/assets/dcdbb63d-2370-455d-a139-3e67caed4a21" />

- Step 3
  - Fill in Necessary info
    - Subscription - Azure Subscription 1
    - Create new Resource Group
      - Windows-VM
    - Virtual machine name - Test
    - Region - (Asia Pacific) East Asia - note that other regions may work, but this one has shown the most success for me while using the free version of Azure
    - Image - Windows 10 Enterprise, version 22H2 - x64 Gen2 (free services eligible) - note that other images may be used depending on your needs and subscription
    - Size - Standard_D2s_v3 - 2 vcpus, 8 GiB memory (Price unavailable)
    - Username - Labuser
    - Password - Cyberlab123!
    - Confirm Passowrd - Cyberlab123!
    - Licensing, Confirm by clicking on the box on the bottom left
      <img width="806" height="1014" alt="image" src="https://github.com/user-attachments/assets/6770de09-9226-4999-98fa-48298bfb14ba" />
      <img width="841" height="877" alt="image" src="https://github.com/user-attachments/assets/4c00796c-92f5-49ab-b240-d9eabff141f9" />

  - For these purposes, we can leave Disks, Networking, Management, Monitoring, and Advanced.

- Step 4
  - Hit review and create

    <img width="719" height="64" alt="image" src="https://github.com/user-attachments/assets/91ad5903-9fce-42d0-b18e-9c2582727b8d" />

- Step 5
  - Wait for Validation to pass, may take few seconds
  - Once validated hit Create on the bottom

    <img width="323" height="54" alt="image" src="https://github.com/user-attachments/assets/83d2662a-08d8-4e1f-b97d-e00d96a40868" />
    
  - Wait for deployment to finish, this can take a few minutes.

    <img width="844" height="124" alt="image" src="https://github.com/user-attachments/assets/2e0a782e-9282-4bc0-b450-d8951904e2c8" />

  - Go back to Virtual Machines and copy the public IP Address
 
    <img width="158" height="137" alt="image" src="https://github.com/user-attachments/assets/58c6d8b2-7508-4702-9b53-270ac19b35dc" />

- Step 6
  - Search up and open Remote Desktop Connection on the windows search normally located at the bottom of the screen
  - Paste IP Address of your new VM and click connect

    <img width="405" height="239" alt="image" src="https://github.com/user-attachments/assets/29f92eef-6cbb-4a09-94a8-cff6c3e305b9" />

  - Click More Choices, Use different account
  - Type in Username and Password from earlier, hit ok

    <img width="447" height="581" alt="image" src="https://github.com/user-attachments/assets/91bd03e4-5fdb-4235-86d7-bf4a62b0025b" />

- Step 7
  - After it begins logging you in, uncheck the privacy settings for the device when it pops up, hit accept
  - Observe Remote Desktop.

    


    
    



      



