QR Code Encoder
===============

Cloned from [komone/qrcode](https://github.com/komone/qrcode). 

Only qrcode generating module included in this repository. The demo module and identification modules were removed. 

Reference used was ISO/IEC 18004, 1st Edition (2000)

This implementation is informed by my specific needs, i.e. to provide
two-factor authentication for mobile phones running Google Authenticator.

+ "Byte" mode only (don't need e.g. numeric mode or kanji mode).
+ Encode only (no detection/decode).
+ Basic supporting library functions provided (HOTP, PNG image functions) to allow full-cyle demo.


NOTE: This documentation is rather basic as this was open-sourced by specific request!
