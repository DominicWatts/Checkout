# Magento 2 Checkout Usability Update

Usability update for Magento 2 checkout

  - Checkout removal of add / update address button 
  - Payment button not disabled
  - Payment button automatically confirms selection of address on guest checkout
  - Scroll to error payment field if failing validation

  ![Screenshot](https://i.snipboard.io/bTy2Ij.jpg)

  ![Screenshot](https://i.snipboard.io/LRvk49.jpg)

# Install instructions #

`composer require dominicwatts/checkout`

`php bin/magento setup:upgrade`

`php bin/magento setup:di:compile`

`php bin/magento setup:static:content:deploy`