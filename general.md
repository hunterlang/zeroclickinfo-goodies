{\rtf1\ansi\ansicpg1252\cocoartf1038\cocoasubrtf360
{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
\margl1440\margr1440\vieww9000\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\ql\qnatural\pardirnatural

\f0\fs24 \cf0 What is this?\
===========\
[DuckDuckGo](https://duckduckgo.com/) is a general purpose search engine. We've created a platform called DuckDuckHack that enables developers to write open source plugins on top of the search engine (like [add-ons for Firefox](https://addons.mozilla.org/en-US/firefox/addon/duckduckgo-ssl/?src=search)). DuckDuckGo plugins react to search queries and provide [useful](https://duckduckgo.com/?q=%40duckduckgo) [instant](https://duckduckgo.com/?q=roman+xvi) [answers](https://duckduckgo.com/?q=private+ips) above traditional links.\
\
DuckDuckHack is very much a work in progress. Some plugin types have better interfaces than others. We will be improving the platform based on [your feedback](https://fiesta.cc/~duckduckhack).\
\
This site will always have the latest platform information.\
\
* For new plugins, follow [@duckduckhack](https://twitter.com/duckduckhack)\
* For ongoing discussion: [DuckDuckHack list](https://www.listbox.com/subscribe/?list_id=197814)\
\
\
Why should I make plugins?\
===\
We hope you will consider making DuckDuckGo plugins to:\
\
* Improve results in areas you personally search and care about, e.g. [programming documentation](https://duckduckgo.com/?q=perl+split), [gaming](https://duckduckgo.com/?q=roll+3d12+%2B+4) or [entertainment](https://duckduckgo.com/?q=xkcd).\
* Increase usage of your own projects, e.g. data and [APIs](https://duckduckgo.com/?q=cost+of+living+nyc+philadelphia).\
* Learn something new.\
* Attribution [on our site](https://duckduckgo.com/goodies.html) and [Twitter](https://twitter.com/duckduckhack) (working on more).\
* See your code live on a [growing](https://duckduckgo.com/traffic.html) search engine!\
\
Overview\
====\
There are currently four types of DuckDuckGo plugins:\
\
### Goodies &mdash; calculations and cheat sheets.\
\
 * Examples: [reverse](https://duckduckgo.com/?q=reverse+test), [private ips](https://duckduckgo.com/?q=private+ip), [dice](https://duckduckgo.com/?q=throw+5+dice), [roman](https://duckduckgo.com/?q=roman+cvi), [passphrase](https://duckduckgo.com/?q=passphrase+4+words), [etc.](https://github.com/duckduckgo/zeroclickinfo-goodies/tree/master/lib/DDG/Goodie)\
 * Status: v1!\
 * Language: Perl\
 * Involves: processing the search query.\
\
### Spice &mdash; external API calls.\
\
 * Examples: [xkcd](https://duckduckgo.com/?q=xkcd), [alternative to](https://duckduckgo.com/?q=alternative+to+picasa), [twitter](https://duckduckgo.com/?q=%40duckduckgo), [wordnik](https://duckduckgo.com/?q=random+word+3-5), [expatistan](https://duckduckgo.com/?q=cost+of+living+nyc+philadelphia), [etc.](https://github.com/duckduckgo/zeroclickinfo-spice/tree/master/lib/DDG/Spice)\
 * Status: v1 release candidate\
 * Language: JavaScript\
 * Involves: processing data from APIs.\
\
### Fathead &mdash; keyword databases.\
\
 * Examples: [git](https://duckduckgo.com/?q=git+branch), [perl](https://duckduckgo.com/?q=perl+split), [final fantasy](http://duckduckgo.com/?q=gippal), [emoticons](http://duckduckgo.com/?q=%28%3E_%3C%29), [http](http://duckduckgo.com/?q=http+304), [etc.](https://github.com/duckduckgo/zeroclickinfo-fathead)\
 * Status: alpha\
 * Languages: Perl, Node, Ruby, Python (maybe others)\
 * Involves: generating information about specific queries.\
\
### Longtail &mdash; full-text data.\
\
 * Examples: [wikipedia](https://duckduckgo.com/?q=snow+albedo), [lyrics](https://duckduckgo.com/?q=what%27s+my+age+again+lyrics), [stack overflow](https://duckduckgo.com/?q=nginx+apache), [etc.](https://github.com/duckduckgo/zeroclickinfo-longtail)\
 * Status: alpha\
 * Languages: Perl, Node, Ruby, Python (maybe others)\
 * Involves: formatting data sets to answer general queries.\
\
\
Getting Started\
===\
\
**Step 1.** &nbsp;Decide what you want to work on. If you don't have any ideas, [start here](http://ideas.duckduckhack.com/).\
\
**Step 2.** &nbsp;Figure out your plugin type (see Plugin Types above). If the right type is not obvious, please <a href="https://github.com/duckduckgo/duckduckgo/FAQ.md">ask us</a>. Sometimes multiple plugin types could work, and we can help you figure out which one would work best.\
\
**Step 3.** &nbsp;Fork the right repository ([GitHub instructions](http://help.github.com/fork-a-repo/)):\
\
 * [Goodies](https://github.com/duckduckgo/zeroclickinfo-goodies) (Perl functions)\
 * [Spice](https://github.com/duckduckgo/zeroclickinfo-spice) (JavaScript functions)\
 * [Fathead](https://github.com/duckduckgo/zeroclickinfo-fathead) (Keyword data)\
 * [Longtail](https://github.com/duckduckgo/zeroclickinfo-longtail) (Full-text data)\
\
**Step 4.** &nbsp;Now it's choose-your-own-adventure time!\
\
 * For **Goodie** or **Spice**, proceed to the [Plugin tutorial](https://github.com/duckduckgo/zeroclickinfo-goodies) at the Goodies repository.\
\
 * For **Fathead**, check out the Readme in the [fathead repository](https://github.com/duckduckgo/zeroclickinfo-fathead).\
 * For **Longtail**, check out the Readme in the [longtail repository](https://github.com/duckduckgo/zeroclickinfo-longtail).}