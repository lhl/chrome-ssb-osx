chrome-ssb
==========
Simple script for making Chrome SSBs on OS X

This is an update of [Bracken King](https://twitter.com/brackenthebox)'s original script published in [this 2010 article](http://www.lessannoyingcrm.com/articles/149/Create_application_shortcuts_in_Google_Chrome_on_a_Mac).

I've updated it a bit to work better:
* Allow spaces in all variables
* Properly Trim spaces for easy drag and dropping of icon paths
* Properly look for Chrome location in /Applications (it uses the first one it finds)
* Make the new App wherever it's called from
* Your Profile is placed in the correct location (in the Bundle) no matter where you move the app

## Usage
* Place chrome-ssb.sh in your path or somewhere convenient to call from
* Run chrome-ssb.sh wherever you want

**Note:** Finder may not pick up the icon (shows up as invisible) if you have the creation target folder active/open. You can make it show up by moving the App to a different folder. If you know a workaround, please send a pull request...

## TODO
* Better Icon Processing
  * : http://www.amnoid.de/icns/makeicns.html
  * http://superuser.com/questions/133784/manipulate-mac-os-x-file-icons-from-automator-or-command-line

## License
Do as you will
