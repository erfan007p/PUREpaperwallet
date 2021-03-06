**** LOOKING FOR THE ZIP FILE TO DOWNLOAD? ************************************
If you're on already at https://github.com/erfan007p/purepaperwallet
Then just look for the button that says "Download ZIP". Look to your right -->
*******************************************************************************

*** PUREpaperwallet ***

This project is a fork of bitaddress.org, the original trustworthy
JavaScript powered offline bitcoin address generator. 

This attractive paper wallet design is two-sided and folds up to
hide the private key.

This generator includes the same pseudorandom key generation as bitaddress.org, as
well as support for creating wallets using "vanity keys", passphrases ("brain wallets")
or even rolling dice or shuffling cards.

This generator also includes support and designs for making
Bitcoin, Litecoin and Dogecoin wallets.

Use the "Verify or Decrypt" tab to decrypt a BIP38 password-encrypted wallet, check the
integrity of any private key, or even duplicate an exising wallet by scanning its
QR code.

*** HOW TO USE THIS GENERATOR ***

1) Extract the ZIP file
2) Open up the 'generate-wallet.html' file with your web browser. 
3) If you like you can select a different language or holiday theme
4) Follow the steps for calibrating your printer and then printing
   the front and back of each wallet. Use landscape mode when printing!
   
Rendering and printing seems to work best using: 

   OS X:     Safari or Chrome or Firefox
   Windows:  Firefox or Chrome
   Linux:    Firefox

When using Chrome on Windows, use the Chrome print dialog. Switching to the
Windows system print dialog will produce corrupted/illegible keys.

QR scanning works best using Firefox since Chrome will not access the camera controls
when opening a locally saved HTML file.

*** COMPARED WITH BITADDRESS.ORG ***

Images and resources have been moved out of the .html file (where they were
base-64 encoded) and into an images directory to make the code easier to review.

All cryptographic functions are verifiably identical to those in bitaddress.org.
(Run a "diff" between this project and bitaddress.org if you want to be sure.)

*** HOW TO VERIFY THE AUTHENTICITY OF THIS DOWNLOAD ***

After downloading the ZIP package for this generator, you should find a file 
named generate-wallet.html.sig which you can use to:

* Verify that generate-wallet.html hasn't been tampered with, and
* Get proof that it really was authored by Aliyul Erfan (erfan007p@gmail.com) 
  whose GPG public key and fingerprint should be confirmed.
  
For example, if you have GPG installed, you should be able cd to the appropriate 
directory and type in these two commands:

  gpg --recv-key 363D09AA
  gpg --verify --with-fingerprint generate-wallet.html.pgp generate-wallet.html

If you get warnings like "This key is not certified, there is no indication that
the key belongs to the owner" do not worry, this is normal.


*** DONATIONS ***

To support ongoing development of this project, please consider making a donation to : PV1wwo15CwSRukt2pfyPGMreM5NALg1goR

Special thanks to pointbiz/bitaddress.org and Artiom Chilaru/flexlabs.org for 
their significant contributions to this software.

*** LICENSE ***

© Copyright 2017 Aliyul Erfan. This software may be modified and redistributed as 
per the MIT/GPL/BSD/Apache licenses included in the HTML and JavaScript source. However, 
the bitcoinpaperwallet.com logo, hologram sticker design, and folding paper wallet design 
are copyrighted and may not be modified or redistributed without permission excepting 
for personal use. 


{{{{ THIS SOFTWARE AND SERVICE IS PROVIDED WITHOUT WARRANTY. USE AT YOUR OWN RISK. }}}}

- Aliyul Erfan
erfan007p@gmail


*******************************************************************************

**** LOOKING FOR THE ZIP FILE TO DOWNLOAD? ************************************
If you're on already at https://github.com/cantonbecker/bitcoinpaperwallet
Then just look for the button that says "Download ZIP". Look to your right -->
*******************************************************************************

*** bitcoinpaperwallet.com ***

This project is a fork of bitaddress.org, the original trustworthy
JavaScript powered offline bitcoin address generator. 

This attractive paper wallet design is two-sided and folds up to
hide the private key. Optional tamper-evident hologram tape and/or a live-boot
Ubuntu CD with this software pre-installed can be purchased from bitcoinpaperwallet.com 
to provide additional security against snooping.

This generator includes the same pseudorandom key generation as bitaddress.org, as
well as support for creating wallets using "vanity keys", passphrases ("brain wallets")
or even rolling dice or shuffling cards.

This generator also includes support and designs for making
Litecoin and Dogecoin wallets.

Use the "Verify or Decrypt" tab to decrypt a BIP38 password-encrypted wallet, check the
integrity of any private key, or even duplicate an exising wallet by scanning its
QR code.

*** HOW TO USE THIS GENERATOR ***

1) Extract the ZIP file
2) Open up the 'generate-wallet.html' file with your web browser. 
3) If you like you can select a different language or holiday theme
4) Follow the steps for calibrating your printer and then printing
   the front and back of each wallet. Use landscape mode when printing!
   
Rendering and printing seems to work best using: 

   OS X:     Safari or Chrome or Firefox
   Windows:  Firefox or Chrome
   Linux:    Firefox

When using Chrome on Windows, use the Chrome print dialog. Switching to the
Windows system print dialog will produce corrupted/illegible keys.

QR scanning works best using Firefox since Chrome will not access the camera controls
when opening a locally saved HTML file.

*** COMPARED WITH BITADDRESS.ORG ***

Images and resources have been moved out of the .html file (where they were
base-64 encoded) and into an images directory to make the code easier to review.

All cryptographic functions are verifiably identical to those in bitaddress.org.
(Run a "diff" between this project and bitaddress.org if you want to be sure.)

*** HOW TO VERIFY THE AUTHENTICITY OF THIS DOWNLOAD ***

After downloading the ZIP package for this generator, you should find a file 
named generate-wallet.html.sig which you can use to:

* Verify that generate-wallet.html hasn't been tampered with, and
* Get proof that it really was authored by Canton Becker (canton@gmail.com) 
  whose GPG public key and fingerprint should be confirmed at http://cantonbecker.com
  and/or by searching bitcointalk.org, etc.
  
For example, if you have GPG installed, you should be able cd to the appropriate 
directory and type in these two commands:

  gpg --recv-key 36E1D9B6
  gpg --verify --with-fingerprint generate-wallet.html.sig generate-wallet.html 

And then verify the resulting signature's fingerprint against Canton Becker's
published fingerprint at http://cantonbecker.com

If you get warnings like "This key is not certified, there is no indication that
the key belongs to the owner" do not worry, this is normal.


*** DONATIONS ***

To support ongoing development of this project, please consider making a donation or
purchasing wallet-making supplies or the Ubuntu LiveCD with this software here:

https://bitcoinpaperwallet.com/#purchase
https://bitcoinpaperwallet.com/#donate

Special thanks to pointbiz/bitaddress.org and Artiom Chilaru/flexlabs.org for 
their significant contributions to this software.

*** LICENSE ***

© Copyright 2014 Canton Becker. This software may be modified and redistributed as 
per the MIT/GPL/BSD/Apache licenses included in the HTML and JavaScript source. However, 
the bitcoinpaperwallet.com logo, hologram sticker design, and folding paper wallet design 
are copyrighted and may not be modified or redistributed without permission excepting 
for personal use. 


{{{{ THIS SOFTWARE AND SERVICE IS PROVIDED WITHOUT WARRANTY. USE AT YOUR OWN RISK. }}}}

- Canton Becker
http://cantonbecker.com
canton@gmail.com



----------------------------------------------------------
--- The original bitaddress.org README continues below ---
----------------------------------------------------------

Now Bitcoin addresses and their corresponding private key can be conveniently 
generated in a web browser.

The bitaddress.org project provides an all-in-one HTML document with embedded
JavaScript/Css/Images. The JavaScript is readable not minified and contains no
XMLHttpRequest's (no AJAX). The benefit of this technique is you can load the 
JavaScript locally and trust that the JavaScript did not change after being 
loaded. 

Here is a link to the BitcoinTalk.org forum topic discussing this project:
https://bitcointalk.org/index.php?topic=43496.0


Please send DONATIONS for this project to Bitcoin Address: 
1NiNja1bUmhSoTXozBRBEtR8LeF9TGbZBN


END USER NOTES: 
 1) To print QRCode in IE8 you must enable the "Print Background Colors and 
    Images" checkbox on the "Page Setup" screen.
 2) For Bulk Wallet I recommended using Google Chrome, it's the fastest.
 3) Requires IE8+, Firefox, Chrome or sufficient JavaScript support.
 4) Mobile Safari only works with iPhone4 or newer devices.
    Older devices timeout while executing JavaScript.
 5) DO NOT use Opera Mini it renders JavaScript output server side, therefore
    they might record the private key you generated.
 6) Art Wallet does not work properly in IE8 due to CSS limitations.


Notice of Copyrights and Licenses:
---------------------------------------
The bitaddress.org project, software and embedded resources are copyright bitaddress.org. 
The bitaddress.org name and logo are not part of the open source license.

Portions of the all-in-one HTML document contain JavaScript codes that are the copyrights 
of others. The individual copyrights are included throughout the document along with their 
licenses. Included JavaScript libraries are separated with HTML script tags.

Summary of JavaScript functions with a redistributable license:
JavaScript function		License
-------------------		--------------
Array.prototype.map		Public Domain
window.Crypto			BSD License
window.SecureRandom		BSD License
window.EllipticCurve		BSD License
window.BigInteger		BSD License
window.QRCode			MIT License
window.Bitcoin			MIT License

The bitaddress.org software is available under The MIT License (MIT)
Copyright (c) 2011-2012 bitaddress.org

Permission is hereby granted, free of charge, to any person obtaining a copy of this 
software and associated documentation files (the "Software"), to deal in the Software 
without restriction, including without limitation the rights to use, copy, modify, 
merge, publish, distribute, sublicense, and/or sell copies of the Software, and to 
permit persons to whom the Software is furnished to do so, subject to the following 
conditions:

The above copyright notice and this permission notice shall be included in all copies 
or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, 
INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A 
PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT 
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION 
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE 
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
