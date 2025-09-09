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
 1) In the Server Manager, navigate to Local Server on the left-hand side. Locate the IPv4 address listed in the server properties, and click on the hyperlink to view orconfigure the network settings.

    ![Image Alt]( https://github.com/idris-tech85/Active-Directory-/blob/main/2%20image.png?raw=true)

    2)   Next, select the network adapter you want to configure and open its Properties. In the list of items, find and select Internet Protocol Version 4 (TCP/IPv4), then   click Properties. This will allow you to manually set the IP address, Subnet Mask, and Default Gateway. You can use the server’s existing IP address, which can be checked by running ipconfig in the Command Prompt .
   ![Image Alt](https://github.com/idris-tech85/Active-Directory-/blob/main/image%203.png?raw=true )
   
  
       
