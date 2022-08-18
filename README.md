# Kindle EPUB Fix

Amazon Send-to-Kindle service has accepted EPUB, however, for historical reason
it still assumes ISO-8859-1 encoding if no encoding is specified. This creates weird formatting errors for special characters.

This tool will try to fix your EPUB by adding the UTF-8 specification to your EPUB. It currently does
not fix other errors.

This version / fork is a very basic PWA version so that it can be installed.

PWA access is here : 
https://esparont.pythonanywhere.com/

You can access the original tool at https://kindle-epub-fix.netlify.app

**Warning:** This tool come at no warranty. Please still keep your original EPUB.
We don't guarantee the resulting file will be valid EPUB file, but it should.

