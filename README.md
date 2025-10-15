# Manage-Encryption-by-Using-an-Azure-Key-Vault
As an Administrator for an organisation that needs to manage its Azure environment.

You have accomplished the following:
1. Created and configured an Azure Key Vault.
2. Created a customer-managed encryption key.
3. Configured a storage account to use a customer-managed encryption key.



In this project, we will secure an Azure storage account by using Azure Key Vault. 
1. First, you will create and configure an Azure Key Vault.
2. Next, you will create a customer-managed encryption key.
3. Finally, you will configure a storage account to use the customer-managed encryption key


## 1. Create and configure an Azure Key Vault
>>> Sign in to the Azure® portal as Admin
>> Create an Azure Key Vault by using the values in the following table. For any property that is not specified, use the default value.

Property -----------  Value
1. Resource group:	AZ900RGlod**********
2. Key vault name:	KeyVaut......*58
3. Region	East US 2
4. Pricing tier:	Standard
5. Permission model:	Vault access policy
6. Azure Disk Encryption for volume encryption	selected
7. Enable public access	selected

>>>An Azure Key Vault can be used to encrypt keys and store small secrets and passwords that are used in Azure applications-including hybrid applications.

>>>You can also use Azure keys for hardening hardware security modules.

>>>Microsoft doesn't see or extract your keys at any time.

>>>You can monitor, log, and audit your keys, and you can customise the keys to meet company compliance and standards requirements.


## 2. Create a customer-managed encryption key
1. Create a customer-managed encryption key named SAKey-55552808 in the KeyVault55552808 Key Vault.

1. Prior to using an Azure Key Vault, you had to include keys in all your configuration files for the purpose of identifying a user. 
2. You had to change and maintain the keys in the configuration files throughout the life of the application or resource. 
3. This was time-consuming and difficult to centralise. Azure Key Vault saves you time and allows you to be consistent in your key usage.
4. Once you store an encryption key in a Key Vault and associate the key with an Azure resource, the URL of the Azure resource will no longer contain the key.
5. This allows web applications to come to the vault at runtime for key, secret, and password information, which provides for a safer surface and less vulnerability to attack.



## Locate and record the Key Identifier for the SAKey-55552808:
>> Key Identifier 



## 3. Configure a storage account to use a customer-managed encryption key
>>Configure an existing storage account named sa55552808 to use the encryption key named SAKey-55552808 that is stored in the KeyVault55552808 Key Vault.

>>By default, the data in a storage account is encrypted by using Microsoft-managed encryption keys. 

>>When encrypting Azure blobs and files, you can choose to use your own key rather than the Microsoft-managed key; however, tables and queues are always encrypted by using Microsoft-managed keys.

>>Azure Key Vault is a prerequisite for using your own keys to encrypt Azure blobs and files.

## 4. Summary
Congratulations

