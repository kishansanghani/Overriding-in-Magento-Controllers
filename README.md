# Overriding-in-Magento-Controllers
In Magento, the controller is responsible for handling incoming requests, and it's a backbone of the Magento routing implementation. To handle probably every request in Magento, the controller defines different actions in the form of controller class methods. The controller action method includes related application logic which interacts with views and models to prepare the output of that particular page. Sometimes, you need to alter the flow of controller execution to inject custom code or change the core code.

# Let's override magento product view page to no route.
# Mage/Catalog/controllers/ProductController.php

# viewAction
