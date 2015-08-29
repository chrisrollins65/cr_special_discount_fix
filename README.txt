Fix for conflicting special and discount prices in Opencart 2


INTRODUCTION
--------------------------------------------------------------------
Ever want to give users a special price for buying 1 product, but also give them lower discount prices if they buy more than 1? By design, Opencart doesn't allow this and will always ignore the discount price if a special price is specified. This extension fixes this by comparing the special and discount prices and always choosing the lower of the two prices.


INSTALLATION
--------------------------------------------------------------------
Requires vQmod (https://github.com/vqmod/vqmod/wiki/Installing-vQmod-on-OpenCart)

Installation: upload the vqmod folder into your root website directory (there should already be a vqmod folder there. Merge this one with that one.)

Uninstallation: go to "vqmod/xml" in your website directory and delete the file "cr_special_discount_fix.xml"


CONTACT
--------------------------------------------------------------------
Contact me through github: https://github.com/chrisrollins65/cr_special_discount_fix

Or through the comments on the Opencart extension page.