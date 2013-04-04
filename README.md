Gujarati Fortunes Cookies
=========================

Entire codebase is purly based on Kannada Fortunes Cookies project at,
<https://github.com/aravindavk/fortunes-kn-gaadegalu>

To Create Fortune Database
--------------------------
Add one kahevata per line to kahevato.txt and run following command:

    make

Testing Generated Fortune Database
----------------------------------
To test above generated fortune database run following command:

    fortune kahevato


Generating PHP file of Quotes
-----------------------------
To convert the kahevato as PHP array, run:

    make php

kahevato.php file will be created in the same directory with an array
$kahevato

Generating JSON file of quotes
------------------------------
To convert the kahevato data as JSON, run

    make json

kahevato.json file will be created in the same directory.
