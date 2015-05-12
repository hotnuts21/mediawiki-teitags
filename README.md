# mediawiki-teitags
A mediawiki extension to allow support for TEItags.
==========================


Summary
-------
Adding TEITags to our modified [Scripto](https://github.com/hotnuts21/plugin-Scripto) installation.

Code taken from the [scripto](https://github.com/onothimagen/cbp-transcription-desk) transcription project. Only the [MediaWiki](https://www.mediawiki.org) [TEITags](https://github.com/onothimagen/cbp-transcription-desk/tree/master/w/extensions/TEITags) extension was used
which is unable to be forked.

Work by [National Library Wales](http://www.llgc.org.uk).

Usage
-------
Drop the folder contents into your Mediawiki extensions/TEITa[tei](https://github.com/onothimagen/cbp-transcription-desk/tree/master/w/extensions/TEITags)gs folder

Add the following code at the bottom of your LocalSettings.php:

```require_once "$IP/extensions/TEITags/TEITags.php";```

Done! Navigate to "Special:Version" on your wiki to verify that the extension is successfully installed.

Copyright
---------
* Copyright National Library of Wales 2015

Forked code copyright as per their respective repositories




[NLW]: http://www.llgc.org.uk)
