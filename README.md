# mediawiki-teitags
A mediawiki extension to allow support for TEItags.
==========================


Summary
-------
Adding TEITags to our modified [Paul] installation.

Code taken from the [cbp] transcription project. Only the [Mediawiki] TEITags extension was used
which is unable to be forked.

Work by [NLW].

Usage
-------
Drop the folder contents into your Mediawiki extensions/TEITags folder

Add the following code at the bottom of your LocalSettings.php:

```require_once "$IP/extensions/TEITags/TEITags.php";```

Done! Navigate to "Special:Version" on your wiki to verify that the extension is successfully installed.

Copyright
---------
* Copyright National Library of Wales 2015
Forked code copyright as per their respective repositories


[cbp]: https://github.com/onothimagen/cbp-transcription-desk "Transcribe Bentham Project"
[tei]: https://github.com/onothimagen/cbp-transcription-desk/tree/master/w/extensions/TEITags
[MediaWiki]: https://www.mediawiki.org
[Omeka]: https://omeka.org
[Paul]: https://github.com/hotnuts21/plugin-Scripto "Scripto"
[NLW]: http://www.llgc.org.uk "National Library of Wales"
