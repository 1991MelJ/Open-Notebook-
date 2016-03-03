APIs are "Application Programming Interfaces," which essentially are commands that allow a website server to "talk" to a program on your computer. This is useful because it allows the commuter to give you the search results in a machine-readable format (ex: JSON) saving you the time of manually entering, searching, copying, and pasting the results. One API option is "retrieving individual item records," and the key term for this is "oocihm." Each individual record in a search result has its own oocihm number. You can use the oocihm number to enter it into the command line and retrieve individual item records. 

An example of this: http://eco.canadiana.ca/view/oocihm.16278/?r=0&s=1&fmt=json&api_text=1 

A few useful commands:

* `curl` is for downloading webpages
* `jq`	is for reading JSON
* `sed` and `awk`  are for searching within text and cleaning up text
* More useful commands for analyzing text, including commands for counting word frequencies can be found [here](http://williamjturkel.net/2013/06/15/basic-text-analysis-with-command-line-tools-in-linux/)

I attempted this exercise, but because I do not own a computer and I am using a computer in the History Department it is difficult for me to complete the exercise. I downloaded the GitHub file, and made changes to the search parameters replacing `montenegr` with `native` and saved it to my [Github Repository](https://github.com/1991MelJ/Open-Notebook-/blob/master/module%202/Exercise-3-APIs-1991MelJ.api-ex-mac.sh). When it came to running the command that can be found below, the command line would not give me permission, and when I used the Admin account it could not locate the file. I tried to save a copy of the file under a folder in the Admin desktop and the command line still could not recognize the file. I'm not sure what I could have done differently, I would have liked to finish this exercise, I am sure I will make use of this for my final project.

![API command][API run program command instructions Screen Shot 2016-03-03 at 2.22.55 PM] 