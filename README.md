# Site Arch Prototyping Tool

## Overview

The project had to be designed to be locally run, and contained in one portable file. The only file you need to run the program is sitemaper.html. The porgram needed to convert Excel documents into HTML sitemaps with interactive UI, and graphics. All of this needs to be done with one file and no data connection. 

## Using it.
The Site Arch Prototyping Tool must be run in Chrome, but the client side output can be seen in any browser.

in your Excel file, copy the columns that are relevant to the sitemap
paste those specific columns into a new file (keep this file open if there are errors)

export the new file as a CSV (file > export > change export options, pick CSV)
save the CSV somewhere accessible

open the sitemaper.html file

click UPLOAD CSV FILE - find the previously saved file - the upload button vanishes as your file is processed.

Look over the file, correct any mistakes on your Excell file and reexport as a CSV - to re-upload the CSV, refresh sitemapper (F5)

When you are happy with the file, in chrome, save the web page (ctrl-s, or hamburger > save page as...) NOTE: Whatever nodes you have open will be saved as well. Close or open any nodes as you need them.

Chrome will create a single file that is your client's sitemap

Open that new file in a web editor and change the client's name, last updated, and title (found on line 299- 301)

save the file and present to your client.
