Simplistic-RSS
==============

This is a very simple RSS library for Android. Supports extracting the url of images if they are present. Its still very early, but it will continue to get better with updates. 

Usage
==============
String that contains the url of the RSS Feed. 
```Java
RssReader rssReader = new RssReader(url);
```

returns a list of Rss Items. 
```Java
ArrayList<RssItem> RssItems = rssReader.getItems();
```
Customization
==============
-If you want to add a new attribute to the Rss item, edit the RssItem class to contain getters/setters for the specific attribue. 

-Then follow basic outline in the RssHandler class. 



![Screenshot](https://raw.githubusercontent.com/ShirwaM/Simplistic-RSS/master/Screenshot_framed.png)
