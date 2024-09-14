<h1>Creating a Virtual Machine in Azure</h1>
This tutorial outlines the prerequisites for creating a virtual machine through Microsoft Azure.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Windows 10

<h2>Operating Systems Used</h2>

- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1 - Sign in to the Azure Portal
- Step 2 - Enter "virtual machines" in the search and select virtual machines
  ![image](https://github-production-user-asset-6210df.s3.amazonaws.com/148407820/278899934-4bbca0e8-e7cf-4569-8466-64a538f12705.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240914%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240914T221359Z&X-Amz-Expires=300&X-Amz-Signature=baee1d5c97bb28536976b472c1040ab5201a88636bdc14240b43f6db99237b12&X-Amz-SignedHeaders=host&actor_id=118127699&key_id=0&repo_id=711641284)

- Step 3 - Under create, select "create a virtual machine hosted by azure"
  ![image](https://github-production-user-asset-6210df.s3.amazonaws.com/148407820/278903538-752fe8c3-c4b3-41d2-afdf-8d27012a532d.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240914%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240914T222611Z&X-Amz-Expires=300&X-Amz-Signature=2536e808b4ae36f203bfcface1bf2e71553d6bc4041622761dc724062746e9ed&X-Amz-SignedHeaders=host&actor_id=118127699&key_id=0&repo_id=711641284)

- Step 4 - Under Instance details, enter a name for the Virtual machine and select a region.
  ![image](https://github-production-user-asset-6210df.s3.amazonaws.com/148407820/278903858-99c32169-b844-400a-9b15-dd87a845d509.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240914%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240914T222640Z&X-Amz-Expires=300&X-Amz-Signature=4ad0e50e4958acdc625f42f7ab25ccdd3dd16e41d4ba44c18e0631e9b3a26835&X-Amz-SignedHeaders=host&actor_id=118127699&key_id=0&repo_id=711641284)

- Step 5 - Choose "Windows 10 Pro, version 22H2 -x64 Gen2" for the Image.
  ![image](https://github-production-user-asset-6210df.s3.amazonaws.com/148407820/278905762-c4f6636e-b772-4c4e-a559-240c30138301.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240914%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240914T222716Z&X-Amz-Expires=300&X-Amz-Signature=871f788a1d6f5c53809a8134f5d595be66ea169f05698272a6b627113e162fc9&X-Amz-SignedHeaders=host&actor_id=118127699&key_id=0&repo_id=711641284)

- Step 6 - Choose a size for the virtual machine
  ![image](https://github-production-user-asset-6210df.s3.amazonaws.com/148407820/278906014-3f7a952c-3e42-443f-9a2d-dfeebd0f9734.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240914%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240914T222738Z&X-Amz-Expires=300&X-Amz-Signature=027acea5fcf218f15ee35e5da2ba1f1067e44c0603cdbe882a98f2cde2154ddf&X-Amz-SignedHeaders=host&actor_id=118127699&key_id=0&repo_id=711641284)

- Step 7 - Under Administrator account, create a username and a password (Follow the guideline requirements for creating a username and password)
  ![image](https://github-production-user-asset-6210df.s3.amazonaws.com/148407820/278906088-dd507569-e202-4389-8f06-f6a64a7c2234.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240914%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240914T222802Z&X-Amz-Expires=300&X-Amz-Signature=b4b6199c294eecf61edbe6cab326f2b687b21c846e766ec6ce9adbcc4a991a5b&X-Amz-SignedHeaders=host&actor_id=118127699&key_id=0&repo_id=711641284)

- Step 8 - Under Inbound port rules, Allow selected ports and RDP (3389) should already be selected (If these aren't selected, please proceed to select them both)
  ![image](https://github-production-user-asset-6210df.s3.amazonaws.com/148407820/278906408-6543e060-753e-437e-b96d-bec31d706451.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240914%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240914T222827Z&X-Amz-Expires=300&X-Amz-Signature=46460bed7f25aa12dc914add51ea7552010eeeebecdde79e10c5469fd1dd5813&X-Amz-SignedHeaders=host&actor_id=118127699&key_id=0&repo_id=711641284)

- Step 9 - Under Licensing, make sure to check "I confirm I have an eligible Windows 10/11 license with multi-tenant hosting rights."
  ![image](https://github-production-user-asset-6210df.s3.amazonaws.com/148407820/278907268-9c7de4e4-5c03-4e13-bf76-2d1a134f49b0.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240914%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240914T222854Z&X-Amz-Expires=300&X-Amz-Signature=341ddfa852eb15d031ddc809c655e4e8be401a091f7f2d1b6e9da171d1131de4&X-Amz-SignedHeaders=host&actor_id=118127699&key_id=0&repo_id=711641284)

- Step 10 - Leave the remaining options on their default selections and then select the "Review + create" button at the bottom of the page
  ![image](https://github-production-user-asset-6210df.s3.amazonaws.com/148407820/278907419-e9362617-a2af-4f24-a93c-9b0da967abac.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240914%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240914T222915Z&X-Amz-Expires=300&X-Amz-Signature=f48023e1ea0f948dec9084b6fb6058421a0f1122640a80e4a0113e70fb0269a7&X-Amz-SignedHeaders=host&actor_id=118127699&key_id=0&repo_id=711641284)

- Step 11 - After validation runs, select the "Create" button at the bottom of the page
  ![image](https://github-production-user-asset-6210df.s3.amazonaws.com/148407820/278907380-70f6d7ad-1105-479d-a4ee-982e08cd36b1.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240914%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240914T222937Z&X-Amz-Expires=300&X-Amz-Signature=035903da6b98ce63c885c8abd015c07bcd022157eb150b57fb05c9cf8dadb101&X-Amz-SignedHeaders=host&actor_id=118127699&key_id=0&repo_id=711641284)
