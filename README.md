# Azure-VM-Tools

<h1>Creating a Virtual Machine</h1>
This tutorial outlines the prerequisites for creating a virtual machine through Microsoft Azure.<br />

<h2>Video Demonstration</h2>

- ### [YouTube: How To Create Virtual Machine in Azure](https://www.youtube.com/watch?v=dP0vNd5K2x8)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Windows 10

<h2>Operating Systems Used</h2>

- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1 - Sign in to the Azure Portal
- Step 2 - Enter "virtual machines" in the search and select virtual machines
  ![image](https://github.com/Gleejr/Azure-creating-a-virtual-machine/assets/148407820/4bbca0e8-e7cf-4569-8466-64a538f12705)

- Step 3 - Under create, select "create a virtual machine hosted by azure"
  ![image](https://github.com/Gleejr/Azure-creating-a-virtual-machine/assets/148407820/752fe8c3-c4b3-41d2-afdf-8d27012a532d)

- Step 4 - Under Instance details, enter a name for the Virtual machine and select a region.
  ![image](https://github.com/Gleejr/Azure-creating-a-virtual-machine/assets/148407820/99c32169-b844-400a-9b15-dd87a845d509)

- Step 5 - Choose "Windows 10 Pro, version 22H2 -x64 Gen2" for the Image.
  ![image](https://github.com/Gleejr/Azure-creating-a-virtual-machine/assets/148407820/c4f6636e-b772-4c4e-a559-240c30138301)

- Step 6 - Choose a size for the virtual machine
  ![image](https://github.com/Gleejr/Azure-creating-a-virtual-machine/assets/148407820/3f7a952c-3e42-443f-9a2d-dfeebd0f9734)

- Step 7 - Under Administrator account, create a username and a password (Follow the guideline requirements for creating a username and password)
  ![image](https://github.com/Gleejr/Azure-creating-a-virtual-machine/assets/148407820/dd507569-e202-4389-8f06-f6a64a7c2234)

- Step 8 - Under Inbound port rules, Allow selected ports and RDP (3389) should already be selected (If these aren't selected, please proceed to select them both)
  ![image](https://github.com/Gleejr/Azure-creating-a-virtual-machine/assets/148407820/6543e060-753e-437e-b96d-bec31d706451)

- Step 9 - Under Licensing, make sure to check "I confirm I have an eligible Windows 10/11 license with multi-tenant hosting rights."
  ![image](https://github.com/Gleejr/Azure-creating-a-virtual-machine/assets/148407820/9c7de4e4-5c03-4e13-bf76-2d1a134f49b0)

- Step 10 - Leave the remaining options on their default selections and then select the "Review + create" button at the bottom of the page
  ![image](https://github.com/Gleejr/Azure-creating-a-virtual-machine/assets/148407820/e9362617-a2af-4f24-a93c-9b0da967abac)

- Step 11 - After validation runs, select the "Create" button at the bottom of the page
  ![image](https://github.com/Gleejr/Azure-creating-a-virtual-machine/assets/148407820/70f6d7ad-1105-479d-a4ee-982e08cd36b1)
