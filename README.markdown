(Warning: This is a chrome plugin I wrote in 5 minutes)

This extension will read in the body of every webpage you go to and naively replace every instance of the word 'defiantly' with 'definitely'. I can imagine quite a few situations where this might break the web, so install with caution. Disable it (and file bugs) if anything weird happens.

The entire extension right now is basically this one line of code.
code document.body.innerHTML = document.body.innerHTML.replace(/defiantly/ig, 'definitely');

INSTALLATION
In Chrome, go to chrome://settings/extensions, enable developer mode and load this unpacked extension.
