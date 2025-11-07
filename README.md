# Azure and Other Resources



In this tutorial, we observe various Azure configurations to experiment with the cloud and its intracaces.

<img width="493" height="435" alt="image" src="https://github.com/user-attachments/assets/80728eba-6ab6-44d0-878b-0199680ad9fc" />

List:

NEWCOMERS--

Create a free subscription: https://azure.microsoft.com/en-us/free/

Alternatively Create a Pay As You Go

Get logged into the Azure Portal: https://portal.azure.com

Observe the portal (Resource Groups, Virtual Machines, EntraID)


  
Azure 

- <img width="1656" height="1032" alt="image" src="https://github.com/user-attachments/assets/ffea5323-e598-40ff-a945-37f6bacb1d78" />





STEP 1

- In Microsoft Azure create: Resources group, Windows/Linux Virtual Machine (aka client/remote desktop/windows)



<img width="1737" height="735" alt="image" src="https://github.com/user-attachments/assets/6634b315-b396-46b9-8ba9-4af26546a673" />


Within the Azure Portal, Create a Resource Group

Create a Storage Account within the Resource Group 

Create a text file on your local desktop If you’re using a Mac, go to preferences and set it to plain text.

Upload the text file you created to the Azure Storage Account.

Edit the file within the Storage Account (within the Azure Portal)

Download the file

Open the file and observe the changes

Delete the Resource Group created (all) (in order to ensure you don’t incur “cost”)

Verify that the Resource Group has been deleted

Never forget to clean up/delete your resources/resource groups

Check Cost Management -> Cost Analysis



- <img width="1776" height="682" alt="image" src="https://github.com/user-attachments/assets/3c4a6814-5ead-4fbb-a3d4-d8aec86d6c22" />

Resource group

  <img width="1631" height="671" alt="image" src="https://github.com/user-attachments/assets/06205dfe-7c1d-4900-8f99-fb9eef0358cb" />
<img width="1631" height="671" alt="image" src="https://github.com/user-attachments/assets/97d1d477-b8bd-40c6-8014-f9c1b3c66b0e" />
<img width="1646" height="577" alt="image" src="https://github.com/user-attachments/assets/d4fdb49b-fb32-449a-963e-a9155dbfdba6" />

Virtual machine and subnet



-- Next

(Create Virtual Machines)

Create a Resource Group

Create a Windows 10 Virtual Machine (VM)

While creating the VM, select the previously created Resource Group

While creating the VM, allow it to create a new Virtual Network (Vnet) and Subnet

Create a Linux (Ubuntu) VM

While creating the VM, select the previously created Resource Group and Virtual Network—the Virtual Network MUST BE THE SAME.

Authentication type: Username/Password

Ensure both VMs are in the same Virtual Network / Subnet

<img width="1082" height="288" alt="image" src="https://github.com/user-attachments/assets/db4d6cd1-c8ca-4f64-912c-225c3b4c07f6" />
<img width="1320" height="556" alt="image" src="https://github.com/user-attachments/assets/111d25af-80b0-4c16-96e4-ae58ae70edb0" />
<img width="1437" height="346" alt="image" src="https://github.com/user-attachments/assets/d2cb8069-dcf3-4eda-a20b-f5597ffb7a0d" />

<img width="1672" height="707" alt="image" src="https://github.com/user-attachments/assets/81a25bfd-adeb-4d5e-a566-d204d20e68db" />
<img width="1177" height="407" alt="image" src="https://github.com/user-attachments/assets/03d18463-c05e-4903-a004-428f410f264b" />
<img width="1201" height="755" alt="image" src="https://github.com/user-attachments/assets/f51d7961-c464-43ad-bf19-9995deb3a484" />

Password reset

Dealing with Account Lockouts

STEP 2

Get logged into dc-1
Pick a random user account you created previously
Attempt to log in with it 10 times with a bad password

STEP 3

Configure Group Policy to Lockout the account after 5 attempts

<img width="1613" height="683" alt="image" src="https://github.com/user-attachments/assets/dea02d35-795e-4914-938a-ac6fbc1e8f5a" />

Attempt to log in with it 6 times with a bad password

STEP 4

Observe that the account has been locked out within Active Directory
Unlock the account
Reset the password
Attempt to login with it

STEP 5

Enabling and Disabling Accounts
Disable the same account in Active Directory
Attempt to login with it, observe the error message
Re-enable the account and attempt to login with it.

STEP 6

Observing Logs
Observe the logs in the Domain Controller
Observe the logs on the client Machine
Precursor to cybersecurity and security operations

Linux
<img width="1432" height="887" alt="image" src="https://github.com/user-attachments/assets/728e6517-c2be-490d-8c9e-d8f63d3d223d" />

Windows
<img width="1073" height="871" alt="image" src="https://github.com/user-attachments/assets/905b11af-e388-4cbf-abbf-ff1cb537d330" />



