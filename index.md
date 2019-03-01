This claims provider connects SharePoint 2019 / 2016 / 2013 with Active Directory and LDAP servers to enhance people picker with a great search experience in federated authentication (typically ADFS).  
![People picker with LDAPCP](https://raw.githubusercontent.com/Yvand/LDAPCP/gh-pages/assets/people-picker-Yvan.png)

If you want to try and see LDAPCP in action, check [this template](https://azure.microsoft.com/en-us/resources/templates/sharepoint-adfs/) that deploys SharePoint in your Azure tenant, fully configured with ADFS and LDAPCP.

## Features

- Query Active Directory and LDAP servers to get users and groups based on the user input.
- Easy to configure through central administration or using PowerShell.
- Get group membership of federated users.
- Connect to multiple AD / LDAP servers in parallel (multi-threaded connections).
- Populate metadata (e.g. email, display name) of entities.

## Customization capabilities

- Configure the list of claim types, their mapping with LDAP users and groups, and many other settings.
- Enable/disable augmentation, globally or per LDAP connection.
- Customize display of results in the people picker.
- Developers can deeply customize LDAPCP to meet specific needs.
