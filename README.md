# Magento2 Product List by Region
Magento2 extension to show products based on customer location on the Product List Page.

# Features:
1.	To show products based on customer location at Product List Page.
2.	Fetching customer's address information’s from IP address. Filtering List based on Product Attribute.
3.	Looks like core functionality of Magento (at backend as well as frontend)
4.	Unencrypted code for easy customization.

# Installation Instruction:
- Copy the content of the repo to the app/code/Hapz// folder
- Enable the module by running php bin/magentomodule:enableHapz_RegionBasedProducts
- Run command: php bin/magentosetup:upgrade
- Run Command: php bin/magentosetup:static-content:deploy
- Now Flush Cache: php bin/magentocache:flush
