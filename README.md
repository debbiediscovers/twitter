#Host your Twitter Archive on Github Pages


This is the Github Pages hosted version of Martin Hawksey's [Host your Twitter Archive on Google Drive](https://mashe.hawksey.info/2013/01/sync-twitter-archive-with-google-drive/)


Use Martin's latest [script](https://script.google.com/macros/s/AKfycbzbBwpWfqL4VMy9DYmaEaqZucGlXK6yKKEZWFqPzG6o0AKC2OjR/exec) to sync to Github Pages.


## Misc 

The history behind Twitter Archiving Google Sheets [TAGS](https://mashe.hawksey.info/2016/05/twitter-archive-google-sheets-tags-just-got-a-bit-easier-with-an-easy-setup/)

## License

This work is licensed under a [Creative Commons Attribution 3.0 Unported License](https://creativecommons.org/licenses/by/3.0/). CC-BY mhawksey


## Credits

Follow Martin Hawksey: [Twitter](https://twitter.com/mhawksey), [Google+](https://plus.google.com/u/0/+MartinHawksey), [GitHub](https://github.com/mhawksey), [Blog](https://mashe.hawksey.info/)


<br>
<br>
<br>

## How to use your Twitter archive

The simplest way to use your Twitter archive is through the archive browser interface provided in this file. Just double-click `index.html` from the root folder and you can browse your entire history of Tweets from inside your browser.

In the `data` folder, your Twitter archive is present in two formats: JSON and CSV exports by month and year.

* CSV is a generic format that can be imported into many data tools, spreadsheet applications, or consumed simply using a programming language.

## JSON for Developers

* The JSON export contains a full representation of your Tweets as returned by v1.1 of the Twitter API. See https://dev.twitter.com/docs/api/1.1 for more information.
* The JSON export is also used to power the archive browser interface (index.html).
* To consume the export in a generic JSON parser in any language, strip the first and last lines of each file.

To provide feedback, ask questions, or share ideas with other Twitter developers, join the discussion forums on https://dev.twitter.com.
