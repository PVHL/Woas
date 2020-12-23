Woas
====

Woas is a complete, multipage wiki in a single HTML file that works in every major browser, including older versions. It can:

* parse marked-up text as individual wiki pages complete with Javascript and CSS (similar to Markdown but using early Creole syntax);
* store and display images or text/binary files within itself;
* run special system and user macros; and
* is incredibly useful for research, teaching, and documentation.

Woas development was hurt by repeated changes to browsers to stop local saving (though it continued to be able to display pages and import local WSIF files, allowing non-browser editing by the skilled, readable by any browser). Why they didn't allow local SPAs to save to the directory they were launched from when given permission is a mystery to everyone I've asked!

The IE ```.hta``` extension hack and Firefox TiddlyWiki browser extension kept things working for some, but Woas was no longer the ubiquitous tool it once was.

Woas 2 will change all that (and eventually allow plugin parsers like Markdown while maintaining backwards-compatibility with the original Woas markup syntax, or will at least provide import and conversion of earlier Woas files to Markdown syntax, given Creole never came to much as a universal markup language for wikis, but Markdown did).

Current work is in the Woas2 directory.
