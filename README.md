[! [license] [license-badge]] [LICENSE]

### Presentation

This modification was developed in OCMOD format, and enables the order data to be sent to Google Analytics E-commerce.

The information is generated based on the order data that is completed in the store, and the data is sent to Google Analytics through the order confirmation page in the standard OpenCart checkout.

### Installation

 1. Access the link: https://www.opencart.com/index.php?route=marketplace/extension/info&extension_id=22039.
 2. Find the most current version and compatible with your version of OpenCart and download it.
 3. In the store administration, access the menu Extensions → Installer (Extensions → Installer).
 4. On the installer page, click the Upload button, select the 'google-analytics-ecommerce.ocmod.zip' file (which you downloaded from this repository), and wait for the automatic installation to complete.
 5. After installation, access the Extensions → Modifications menu, and click the Refresh button, so that the installed modification is incremented in the store, remembering that it is not the "Update" button of the browser, and yes the "Update" button in blue color next to the orange and red button on the OpenCart screen.

### Usage

- In OpenCart up to version 2.0.3.1:

In order for the information to be sent to Google Analytics, the code generated in your Google Analytics account must be added to the store through the menu Settings → Stores (System → Settings), tab "Server" (Server), and in the field "Customer Code" Google Analytics "(Google Analytics Code), add the code and click the" Save "button.

- In OpenCart from version 2.1.0.1 to 2.2.0.0:

In order for the information to be sent to Google Analytics, the code generated in your Google Analytics account must be enabled in the store through the menu Extensions → Statistics (Extension → Analytics), locate the extension "Google Analytics", click the "Install" button (Install), then the "Edit" button, add the code, enable the extension and click the "Save" button.

- In OpenCart from version 2.3.0.0 to 3.0.x:

For the information to be sent to Google Analytics, the code generated in your Google Analytics account must be enabled in the store through the menu Extensions → Extensions and filter by Statistics (Extension → Extension filter Analytics), locate the extension "Google Analytics", click the "Install" button, then the "Edit" button, add the code, enable the extension and click the "Save" button.

#### Important:

In order for you to be able to view the order data sent to Google Analytics, you must enable the Ecommerce service, for that, access your account in Google Analytics and click on the "Administrator" tab, option "PROPERTY VIEW", menu " View settings ", sub-menu" E-commerce settings ", and enable the" Enable e-commerce "field.

To view the order data, access your account in Google Analytics, and under "Reports", click on the "Conversions" menu, "Electronic Commerce" submenu.

It takes an average of 24 hours for the data sent to start being viewed in your account.

### Uninstallation

To uninstall the modification, in the store administration, go to the menu Extensions → Modifications, locate and select the modification with the name 'Google Analytics E-commerce for OpenCart', then click the Delete button, and the Refresh button.

### Update

Access the store administration and perform the Uninstall procedure, then perform the Installation procedure.

### Doubts

OCMOD (OpenCart Modification) is native to OpenCart, that is, it is not necessary to install any add-on in OpenCart to use modifications or extensions in the OCMOD format, for more information about OCMOD, follow the link for more information:

https://github.com/opencart/opencart/wiki/Modification-System

[license-badge]: https://img.shields.io/badge/licença-GPLv3-blue.svg
[LICENSE]: ./LICENSE
