#Host your Twitter Archive on Github Pages


##Intro
This is the (UPDATED 08/16) Github Pages hosted version of Martin Hawksey's [Host your Twitter Archive on Google Drive]  (https://mashe.hawksey.info/2016/08/keeping-your-twitter-archive-fresh-and-freely-hosted-on-github-pages/). Useful youtube video on how to use Github Pages if you are new to it)  

##Instructions
1. Request for your Twitter Archive from Twitter under [Settings](https://twitter.com/settings/account#tweet_export)
2. Make a copy of Martin's spreadsheet and follow the instructions to host your Twitter archive on Google Drive
3. Use Martin's latest [script](https://script.google.com/macros/s/AKfycbzbBwpWfqL4VMy9DYmaEaqZucGlXK6yKKEZWFqPzG6o0AKC2OjR/exec) to sync to Github Pages.
4. Create a new Github repository.
5. Commit (upload) Twitter Archive files to Master using Terminal or Github's desktop app - youtube video shows you how, also on my [Github home page](https://debbiediscovers.github.io)
6. Update the Title and Description of Page 
7. Update the footer (else it says "offline")
7. Add your custom favicon to the repository and this line of code before the closing tag of the header <code>&lt;/head&gt; </code> in the index.html file (add <code>&lt;link rel="shortcut icon" type="image/png" href="/favicon.png"&gt;</code>)
8. Update the README.md file (if you did not create one when you initialised the repository, you can copy and modify this version)

## Free Domain for All University Students
Namecheap is giving away a .me domain to all University students from four countries (UK, US, Canada and Australia) for one year. To get your domain, go to [nc.me][nc.me]

If you are not from one of the four countries, don't fret. [Github Education](https://education.github.com/pack) has an even better offer (worth over $2,000) where you get
- a free .me domain
- an Atom text editor
- AWS
- Digital Oceon hosting accounts
- SendGrid emails
- waiver of Stripe fees, 
- free courses from Thinkful 
- Udacity
- Microsoft's Visual Studio

*Eligibility:* Any student age above 13 who is enrolled in a full time degree or diploma course is eligible to apply for the Github Education Student Pack. 

Read more about it on my blog post: [Free Domain for Students: But What's the Catch?](http://debbiediscovers.com/blog/free-domain-for-students/). 

##Custom Domain
To add an "apex domain" (i.e. <code>"example.com"</code>), add two A records and point them to the following IP addresses:
<pre><code>
192.30.252.153<br>
192.30.252.154
</code></pre>

To add a "sub-domain" (e.g."twitter.debbiediscovers.com"), point your CNAME (without the WWW) to your Github Pages default domain (debbiediscovers.github.io).(Note that your CNAME cannot point to more than one domain.If, like mine, it is already pointing somewhere else, you have to do a redirect instead of changing your DNS records. 

Go to Settings and fill in your custom domain.


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
