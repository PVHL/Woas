Purpose
=======

I'll be developing a final Woas here while moving on to my new, as-yet-unpublished project.

* First version (2.0) implements what I want as an HTA file, Microsoft's Internet Explorer application runner. This allows editing and saving (even binary saves in some locales) in about every Windows ever created (as least back to IE6), including Windows 10. *I will only be testing using the IE11 engine.*
  * Fixes for earlier versions will be considered as offered.
  * Version is not complete until:
    * HTML version of the file (a simple file extension edit) works with IIS Express and an associated load/save plugin, including full WSIF functionality;
    * new parser and macro functionalities are complete and correct;
    * plugin modules work properly (may continue to use plugin nomenclature to distinguish from generic JS modules); and
    * the IE load/save local/cloud modules are available as a working plugin, though cloud may only include the IIS Express capability at this time.

* Second version (2.1) takes the completed work and adds plugins for more cloud services (with a focus on GitHub) and for Firefox load/save, probably via a browser extension considering an example extension for TiddlyWiki (TW) already exists, and almost no-one is using the older Firefox versions that worked without an extension. My extension will also work for TW.

* Third version (2.2) will complete with an electron/nw.js/deno reader/writer/server app for all browsers, including the built-in browser in all but the Deno app.
  
  *Deno will probably not be chosen if it cannot have an embedded browser (believed to be coming). I will not be developing a new Java load/save plugin until and unless a deep need is felt and expressed. I would prefer to use both Deno and Typescript if possible; Deno scratches most of the Node.js itches I have, though more research is needed and it is a very recent startup.*

* Fourth and final version (2.3) will add a few Woas 2 page apps (Journal, Passwords, To-do lists, etc.), throw in some new macros, and complete work on the help/tutorial plugin and content.

* I am working on starting a related project called SHOWER: Social Heuristics Optimizing World Environment Reifier (not yet online). Shower is my priority, but much of this Woas completion work will be of use in Shower, I hope.

Cheers, Paul pvhl.
