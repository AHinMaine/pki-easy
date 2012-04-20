# pki-easy #

This project is a modified version of the openvpn-easy-rsa scripts (pulled
from the OpenWRT repo) for managing your own certificate repository.

## Differences ##

* Start removing the support for unencrypted private keys.
* Fixed a lot of the emphasis on relative paths.
* Fixed the poor location of the private keys.
* Removed the attempt at autodetection of the openssl.cnf file to use.
  Explicity specify it your settings contained in the code(vars) file.
* Made the code(clean-all) script a little safer and more cautious.

## TODO ##

* Strip the pkcs11 business
* Fix the intermediary handling
* Fix the crl handling
* ...more to come

