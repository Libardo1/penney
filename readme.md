JCPenney Store Closings - March 2017
-------------------------------

A simple data analysis and plot of 138 JCPenney store closings for March, 2017.

This project reads the official JCPenney store closing PDF file, extracts the list of store locations, and plots the results on a US state map.

## The Dataset

Data was collected from the official JCPenney store closing [PDF](http://www.jcpnewsroom.com/news-releases/2017/assets/0317_list_of_store_closures.pdf) file. A local copy is also [available](https://raw.githubusercontent.com/primaryobjects/penney/master/data/store_closures.pdf).

The dataset contains the following fields:

Mall/Shopping Center
City
State

Geo-location coordinates for latitude and longitude are obtained from a Google geo-coding API, based upon the store City and State. The number of store closures per state are shaded on the US map, with darker colors representing more closures within that state.

## Results

![March 2017 JCPenney Store Closures - Overview](https://raw.githubusercontent.com/primaryobjects/penney/master/images/jcpenney.png)

![March 2017 JCPenney Store Closures - Detailed](https://raw.githubusercontent.com/primaryobjects/penney/master/images/jcpenney-detail.png)

## References

[Yahoo Finance](http://finance.yahoo.com/news/138-jc-penney-stores-close-130436124.html)

[JCP Newsroom](http://www.jcpnewsroom.com/news-releases/2017/assets/0317_list_of_store_closures.pdf)

## Copyright

Copyright (c) 2017 Kory Becker http://primaryobjects.com/kory-becker

## Author

Kory Becker
http://www.primaryobjects.com
