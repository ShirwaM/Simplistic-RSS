Simplistic-RSS
==============

This is a very simple RSS library for Android. Supports extracting the url of images if they are present. Its still very early, but it will continue to get better with updates. 

[Sample App](https://github.com/ShirwaM/Simplistic-RSS-Demo)
![Screenshot](https://raw.githubusercontent.com/ShirwaM/Simplistic-RSS/master/Screenshot_2014-08-07-03-47-10_framed.png)

Usage
==============
Create an RssReader by passing in the url of the RSS feed 
```Java
RssReader rssReader = new RssReader(url);
```

Get a list of all the items that have been extracted from the Rss feed
```Java
ArrayList<RssItem> RssItems = rssReader.getItems();
```
Customization
==============
*If you want to add a new attribute to the Rss item, edit the RssItem class to contain getters/setters for the specific attribue. 

*Then follow basic outline in the RssHandler class. 
