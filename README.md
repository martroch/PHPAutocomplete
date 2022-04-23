# **MARTA PHP STRUCTURE**

PHP is an embedded scripting language; this means that it is possible to write PHP code into an HTML file. The web-server converts and embeds the PHP code into one HTML file before sending it to the browser.

## **HTML tags**
<?php php-code-here ?>
<?php include('php/')?>

PHP echo is used to display the content of certain variables.

### **PHP structure** 

The php files are organized in the php/ folder

## **php nav**

We will find the same nav on all pages and it will change the active page thanks to:
<?php
    switch ($active) {
        case "home":
            $indexActive = "menu__link--active";
            break;
        case "locations":
            $locationsActive = "menu__link--active";
            break;
        case "descure-la-app":
            $discoverActive = "menu__link--active";
            break;
        case "area-de-usuario":
            $userActive = "menu__link--active";
        break;
    }
    ?>

and adding <?php $active="...";?> in each page
