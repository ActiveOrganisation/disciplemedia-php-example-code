# disciple-php-example-code

This is a simple example of PHP code for Encrypting and Decrypting Authenticated Links from Disciple Media.
This repository is set up to, hopefully, save other people some time.

1. Disciple Media need to switch on Authenticated Links - Make sure they have actually done this.
2. Disciple Media need to provide you with a SECRET KEY - - This is different to your API Key (not to be confused) - make sure they provide this.



# Existing Docs
The Disciple Media team may have pointed you to this:

https://github.com/Disciple-Media/disciple-sample-code/tree/master/symmetric-encryption/php

However, this code is really for testing via command line and not relevant for this use case.

It says that you need a dependency: https://github.com/paragonie/random_compat (PHP 5.x). This is not the case when doing it via a web URL so just ignore the random dependency.

# How to use this - Decrypt
Simply download the code and swap out your secret key (provided by Disciple Media) with the "XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX" in 'auth-link.php' file. And your Authenticated Links iFram URL will work.

# How to use this - Encrypt
Coming soon...
