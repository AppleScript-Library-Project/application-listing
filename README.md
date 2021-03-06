# Listing of existing AppleScript scriptable applications
(alphabetical order of developer, when possible, for now)

## Apple
### El Capitan 10.11.2
* AppleScript Utility (1 dedicated suite, with 1 class)
* Automator (1 dedicated suite, with 3 commands and 8 classes)
* Bluetooth File Exchange (1 dedicated suite, with 2 commands)
* Calendar (1 dedicated suite, with 6 commands and 8 classes)
  * Calendar scripting:
  * https://www.johneday.com/1086/reference-selected-calendar-events-applescript
* Contacts (2 dedicated suites, with 7 commands and 13 classes)
* Database Events (2 dedicated suites, with 4 commands)
* DVD Player (1 dedicated suite, with 19 commands and 1 class)
* Finder (6 dedicated suites, including a legacy suite, with 11 commands and 25 classes)
* Folder Actions Setup (2 dedicated suites, with 2 commands and 3 classes)
* Font Book (1 dedicated suite, with 3 commands and 9 classes)
* GPS Services (1 dedicated suite, with 1 command)
* HelpViewer (1 dedicated suite, with 6 commands and 1 class)
* Image Events (2 dedicated suites, with 10 commands and 5 classes)
* Instruments (1 dedicated suite, with 1 command and 3 classes)
* iPhoto (1 dedicated suite, with 16 commands and 4 classes)
* iTunes (1 dedicated suite, with 21 commands and 23 classes)
* Keynote (1 dedicated suite, 2 iWorks shared suites, totaling 9 commands and 24 classes)
  * Keynote scripting:
  * https://iworkautomation.com/keynote/
* Mail (2 dedicated suites, with 12 commands and 21 classes)
  * Mail scripting:
  * https://support.apple.com/kb/PH19119?locale=en_US
* Messages (2 dedicated suites, with 11 commands, 9 classes and 18 elements)
* Notes (1 dedicated suite, with 5 classes)
* Numbers (1 dedicated suite, 2 iWorks shared suites and 1 compatibility suite, totaling  14 commands and 27 classes)
  * Numbers scripting:
  * https://iworkautomation.com/numbers/
  * http://www.macworld.com/article/2090831/applescript-makes-a-comeback-in-numbers.html
* Pages (1 dedicated suite, 2 iWorks shared suites, totaling 9 commands and 27 classes)
  * Pages scripting:
  * https://iworkautomation.com/pages/
  * http://www.macworld.com/article/2138687/latest-iwork-update-is-another-win-for-applescript.html
* Photos (1 dedicated suite, with 13 commands and 6 classes)
* QuickTime Player (1 dedicated suite, with 13 commands and 7 classes)
* Reminders (1 dedicated suite, with 1 command and 4 classes)
* Safari (1 dedicated suite, with 5 commands and 3 classes)
* Screen Sharing (1 dedicated suite, with 1 command)
* Script Editor (1 dedicated suite, with 4 commands and 8 classes)
* SpeechRecognitionServer (1 dedicated suite, with 3 commands)
* StandardAdditions (9 dedicated suites, with 55 commands and 4 classes)
* SystemEvents (20 dedicated suite, with 20 commands and 118 classes)
* System Information (1 dedicated suite, with 1 command and 2 classes)
* System Preferences (1 dedicated suite, with 2 commands and 3 classes)
* Terminal (1 dedicated suite, with 1 command and 3 classes)
* TextEdit (1 dedicated suite, with 2 classes)
* VoiceOver (1 dedicated suite, with 14 commands and 9 classes)
* Xcode (7 dedicated suites, with 14 commands and 53 classes)

Applications that are scriptable but that do not have dedicated suites are:
* iBook Author
* iMovie
* Maps
* Preview

For reference, Apple applications that are not scriptable are:
* Calculator
* Chess
* Dashboard
* Dictionary
* FaceTime
* Game Center
* iBooks
* Image Capture
* Launchpad
* Mission Control
* Photo Booth
* Stickies
* Time Machine

and the majority of the CoreServices and utilities.

A lot of the applications come with the Standard Suite (13 commands, 6 classes), the Text Suite (6 classes) and the Type Definitions Suite (1 class).

(Script Editor seems to freeze when trying to open a dictionary for Photo Library Migration Utility)

## Barebones
http://www.barebones.com

* BBEdit

http://www.barebones.com/products/bbedit/

"The leading professional HTML and text editor for the Mac." (only available from the site)

* TextWrangler

http://www.barebones.com/products/textwrangler/

"The super-powerful all-purpose Mac text editor and UNIX server administrator's multitool." (available **for free** from the site and the App Store)

The two applications share 5 suites with 62 commands and 61 classes. Only BBEdit comes with the HTML Scripting Suite that itself has 21 commands and 4 classes.

 * BBEdit and TextWrangler scripting
 * http://bbeditextras.org/wiki/index.php?title=Scripting_and_Automation
 * http://www.mactech.com/articles/mactech/Vol.24/24.08/ASBBEdit/index.html
 * http://nathangrigg.net/2012/06/bbedit-search-with-applescript/
 * http://daringfireball.net/2003/09/select_word_script_for_bbedit (based on a mail Shane wrote in 2002...)
 * https://c-command.com/scripts/bbedit/

## Druide
https://www.druide.com

* Antidote

http://www.antidote.info

A spell checking and grammar checking application for French and English (with version 9), available only from the site. Antidote offers 2 suites (Antidote suite and Visuel suite) totaling 12 commands.

## Evernote
https://evernote.com

* Evernote

A note taking, organizing, and archiving application, available both from the site and the App Store, for free. Evernote offers an Evernote suite with 13 commands and 8 classes, covering the basics of what Evernote does.

## GitX
* GitX (free software, GPL v2)

## Google

## Growl
* Growl (free software, BSD)

## Mailsmith

## Microsoft

## Notational Velocity
* Notational Velocity (free software, GPL v3)

## Qsatoolworks

http://www.qsatoolworks.com

* Helix

http://www.qsatoolworks.com/product/helix62/

Database application development and deployment tools. Helix is "one of the original thirty software products created for the Macintosh platform prior to its debut in 1984.” (1) Available only from the site. Helix comes with full Applescript support. It's dictionary is available online at: http://www.qsatoolworks.com/products/applescript/dictionary/. QSAToolworks also offers scripts at: http://www.qsatoolworks.com/scripting/scripts/ along with a "Learning AppleScript with Helix" newsletter.

(1) Quoted from QSAToolworks' Matt Strange mail to the AppleScript list on December 24 2015.

## Shane Stanley
* ASObjC Explorer 4

https://www.macosxautomation.com/applescript/apps/explorer.html

A script editor built to take full advantage of AppleScript’s ability to call Cocoa methods. Available only from the site. It comes with a dedicated ASObjCEx suite with 4 commands and 8 classes.

## Skype

## Spamsieve

## svnX
* svnX (free software, LGPL)

## Tex-Aid

## Tex-Edit Plus

## The Unarchiver
* The Unarchiver (free software, LGPL v2.1)

## Twitter

## VLC
* VLC (free software, GPL v2)

## Xchat
* Xchat (free software, GPL v2)

https://xchataqua.github.io

An IRC client for OS X based on xchat2. Available from both the site and the App Store. It comes with a simple Xchat suite that offers 2 commands.


