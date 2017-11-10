# EE4 Add-on Renamer
File for facilitating building new Event Espresso 4 add-ons

## Usage

* Choose the EE4 skeleton that most closely meets your needs, all contained in the core event espresso repo in `tests/mocks/addons`. Use `new-payment-method` if you want a new payment method, 
`eea-message-template-pack` if you want to add a message template pack, all others should use `eea-new-addon`.
* Copy that skeleton addon to your `wp-content/plugins` directory (so if you copied the standard add-on, it's main plugin file should be located in `wp-content/plugins/eea-new-addon/eea-new-addon.php`)
* Copy this repo's `renamer.php` file into your new directory, next to the plugin's main file (eg it should become `wp-content/plugins/eea-new-addon/renamer.php`)
* Direct your browser to `http://{yoursite}/wp-content/plugins/eea-new-addon/renamer.php`. You will be given further instructions on how to use the file there. 

