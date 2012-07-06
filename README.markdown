# Guardian.js

jQuery plugin for form spam protection.  Guardian adds a hidden field to your form that counts up from 0.  If the form is submitted before 2 seconds of page load time, it is very likely the user is not human, the submission is ignored.

## Install
*	Add jquery.guardian.js (or minified version) to your javascript assets and

## Usage
 $('.form-class').guard();

or

 $('.form-class').guard({threshold: 10}); // Form will not submit if loaded for less than 10 seconds.

 ## Reccomended


It is strongly reccomended that you monitor the server side submission as well, since many spam bots don't even bother to load the page.