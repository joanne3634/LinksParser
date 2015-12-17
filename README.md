# LinksParser

http://joanne3634.github.io/LinksParser/parse.html

Sometimes people share links to friends in the facebook messenger. The aim of this small tool is to parse the links from user's facebook messages history into a list of urls sorted by reverse time. 

Steps
---
1. Download the export from the [Facebook Settings](https://www.facebook.com/settings) menu.
2. Unzip the export and open the messages.htm from the html folder.
3. paste whole or part of messages into the textarea and click the parse button.
4. done! 

Suggestions
---
LinksParser is a really simple tool just using regular expression to match the url. You'd better paste the text under 2M.
Here are some tools may help you split the file first if you have the problem to open too large file.

* Under OSX

```
split -a 2 -b 1m messages.htm 
usage: split [-a sufflen] [-b byte_count] [-l line_count] [-p pattern] [file [prefix]]
```

* Under Linux 

``` 
split –bytes=1000000 messages.htm output 
```
