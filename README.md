# CNN-Article-Searcher

Dependencies:
jsoup version: 1.9.2
org.json.* package if not already install with your installation of jdk

To run this program, build a gradle project in your favorite IDE, clone this repository, 
and in your build.gradle file under dependencies place the following line of code: 
`compile 'org.jsoup:jsoup:1.9.2'`

For the json package, click <a href="http://www.java2s.com/Code/JarDownload/java/java-json.jar.zip">this</a> link, 
unzip the jar, add it to your build path, and you're good to go.

After adding the dependencies, the program's main is located in the Test.java file.

You can leverage these classes to your own use case/news website by assigning the correct tags/css selectors (this will require research on a site's html layout although most of these sites are quite similar) to the instance variables described in the source code of the NewsWebsite class.

This information could be used for data mining purposes or displayed in a news application.
With a little machine learning and/or string parsing/searching, you could make a program 
that displays the top ten articles you would most like to read for the day. I will eventually get around to using it for this exact purpose.

Finally, not all companies are okay with you searching information on their websites in this way.
I leave it soley to the user of this program do decide if searching a given site is a violation of copyright or other laws. 

