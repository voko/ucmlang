# ucmlang

Language support files for Ultimate Client Manager Pro.

The tool can be found [here](http://ultimateclientmanager.com).

It supports export and import of cdv files to manage languages.

# Directory Layout
each language has its own directory, e.g. ```de``` contains the translations for german.
I included two files, one open office ```deutsch.ods``` that contains some auto formatting to tell the editor what's translated and what not. (if the Translation does not equal the Word, it will be grayed out).
The csv to be imported into UCM can be created by using the menu ```file :: save as...``` and then selecting the ```csv``` file type. Make sure to save it with UTF encoding and to use comma ```,``` as separator and double quotes ```"``` as text delimiter.

# Get Started
If you start with a blank slate, goto the [demo language settings page](http://ultimateclientmanager.com/demo/config.config_admin/language.language_settings/), select your language and then simply start translating. The choice of editor is completely up to you. 

You can also chose to simply copy the ```en``` folder that contains two clean files ```english.csv``` and ```english.ods``` and start from there.
 
# Team Work
Feel free to clone and to send pull request with new directories or updates. I won't take updates on the ```deutsch.ods``` file but only on the csv file, which is easier to merge. 

**Make sure to order the file after the english word column (left)!**