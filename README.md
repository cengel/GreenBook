# GreenBook

This repository contains business addresses I manually extracted from the [Negro Motorist Green Book Collection](http://digitalcollections.nypl.org/collections/the-green-book) of the [Schomburg Center for Research in Black Culture](http://www.nypl.org/locations/schomburg). I also have determined **latitude and longitude** for each address location as best as possible.

There are two kinds of tables.

`GreenBook[year]` contains an individual entry for each business. Tables are separated by year.

The table structure is:

* Service
* Name
* Street
* City
* State
* PageNo
* EditionYear
* Lat (of business)
* Lon (of business)
* Comments

`GreenBook_biz_by_city` contains one entry for each *type* of business per city.

The table structure is:
* State
* City
* Service
* Count
* EditionYear
* Comments
* Lat (of city)
* Lon (of city)

Tables are provided as is, in `.ods` and `.csv` format. If you want to help, get in touch with me.
