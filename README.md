# Active-Directory project :)
In this project, I will explore Active Directory and its key features that are essential and widely used across IT environments. The project will cover a range of important use cases and topics, including
# contents 
 [Installing Active Directory tools and configuring a new forest](#installing-active-directory-tools-and-configuring-a-new-forest)
- [Configure network settings for the server](#configure-network-settings-for-the-server)
- [Creating a user](#creating-a-user)
- [Creating Groups](#creating-groups)
- [Creating Organisational Units](#creating-organisational-units)
- [Creating Group Policy Objects](#creating-group-policy-objects)

## Installing Active Directory tools and configuring a new forest
1. Go to **Dashboard > Add Roles and Features**, then keep clicking **Next** until you reach the **Server Roles** section.  
2. Select **Active Directory Domain Services**, click **Add Features**, and continue through the wizard until you reach the **Install** option.  
3. Before leaving, select **“Promote this server to a Domain Controller”**. On the new page, choose **“Add a new forest”** and enter your root domain name (e.g., `idris.com`).  
4. Create a password, then keep clicking **Next** until you can start the installation. The server will restart automatically when it’s done.
   
   ![Image Alt]( https://raw.githubusercontent.com/idris-tech85/Active-Directory-/f8d4769f2667c36c01adecdbf041ed1ed6193bce/1%20image.png)

   ## Configure network settings for the server
A. In **Server Manager**, navigate to **Local Server** on the left-hand side.  
B. Locate the **IPv4 address** listed in the server properties.  
C. Click on the **IPv4 address hyperlink** to open the network settings and configure the server's network properties.

   ![Image Alt]( https://github.com/idris-tech85/Active-Directory-/blob/main/2%20image.png?raw=true)

   1. Select the network adapter you want to configure and open its **Properties**.  
2. In the list of items, locate and select **Internet Protocol Version 4 (TCP/IPv4)**, then click **Properties**.  
3. In the IPv4 Properties window, manually enter the **IP address**, **Subnet Mask**, and **Default Gateway**.  
4. You can use the server’s current IP address, which can be found by running `ipconfig` in the Command Prompt.
       
   ![Image Alt](https://github.com/idris-tech85/Active-Directory-/blob/main/image%203.png?raw=true )
   

## Creating a user
1. Open **Active Directory Users and Computers** using the Windows search.  
2. In the left-hand panel, locate your **domain name** and expand it.  
3. Right-click on the **Users** folder, then select **New > User**.  
4. Enter the user’s details (e.g., first name, last name, username), then click **Next** and set a password for the account.  
5. Under the **General** tab, you can add a description for the user, such as **IT Staff**, to provide additional context.


![Image Alt](  https://github.com/idris-tech85/Active-Directory-/blob/main/image%204%20.png?raw=true )



## Creating Groups

1. Navigate to the location where you want to create the group, such as the **Users** folder under your domain or within an **Organizational Unit (OU)**.  
2. Right-click the desired location and select **Group**.  
3. Enter a **group name** for the new group.  
4. Add existing users to the group as needed, and configure settings such as **permissions**, **security policies**, and other options.  
5. For example, in an IT-specific OU, you can assign a **Group Policy Object (GPO)** to the group to automatically deploy IT-related software or configurations.
   
![Image Alt](https://github.com/idris-tech85/Active-Directory-/blob/main/image%205%20.png?raw=true)

![Image Alt](https://github.com/idris-tech85/Active-Directory-/blob/main/image%206.png?raw=true)    




## Creating Organisational Units






## Creating Group Policy Objects
 

   

   
  
       
