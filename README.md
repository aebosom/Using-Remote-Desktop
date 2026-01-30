<p align="center">
<img width="584" height="663" alt="image" src="https://github.com/user-attachments/assets/d7ed97c6-b68e-4675-8330-8e5a34e9038b" />
</p>

<h1>Using Remote Desktop (Azure)</h1>
This tutorial outlines how to implement and use Remote Desktop by making a Virtual Machine inside of Microsoft Azure.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 11 Home
- Windows (CHANGE LATER)

<h2>Deployment and Configuration Steps</h2>

- Step 1
  - Search "Virtual Machine"
  <img width="711" height="172" alt="image" src="https://github.com/user-attachments/assets/a49dc963-f116-442a-bf38-6f8663888964" />

- Step 2
  - Click Create, Virtual Machine
  <img width="448" height="258" alt="image" src="https://github.com/user-attachments/assets/dcdbb63d-2370-455d-a139-3e67caed4a21" />

- Step 3
  - Fill in Necessary info on Basics
    - Subscription - Azure Subscription 1
    - Create new Resource Group
      - Windows-VM
    - Virtual machine name - Test
    - Region - (Asia Pacific) East Asia - note that other regions may work, but this one has shown the most success for me while using the free version of Azure
    - Image - Windows 10 Enterprise, version 22H2 - x64 Gen2 (free services eligible) - note that other images may be used depending on your needs and subscription
    - Size - Standard_D2s_v3 - 2 vcpus, 8 GiB memory (Price unavailable)
    - Username - Labuser
    - Password - Password1
    - Confirm Passowrd - Password1
    - Licensing, Confirm by clicking on the box on the bottom left
      <img width="806" height="1014" alt="image" src="https://github.com/user-attachments/assets/6770de09-9226-4999-98fa-48298bfb14ba" />
      <img width="816" height="967" alt="image" src="https://github.com/user-attachments/assets/b293b70c-e891-4b14-a6a8-05c1943615ce" />


