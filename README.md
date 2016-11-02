List of tech conferences
==========================

How to add an event:
There is a `skeleton.txt` in the root of the repository. Use that to create the appropriate file in data/

Details of the fields
------------------------

```
name:               The name might need to include the country/city and the year. Check similar events.
url:                http://...

start_date:         2016-06-01
end_date:           2016-06-02
cfp_date:           2016-02-23     (Deadline for Call for Presentations if available) 

city:               Name of the city
state:              Relevant in US, Brazil, Australia, India.   Possibly also in UK
country:            Name of the country

topics:             comma separated list
languages:          Portuguese, English
code_of_conduct:    URL to Code of Conduct
accessibility:      URL to document about accessibility
twitter:            handle         (don't include the @)
facebook:
youtube:           Once the event is over, the YouTube playlist of its videos.
```

Generate web site (and check format)
-----------------------------------

$ python3 generate.py


Images
---------
Accessibility logo: http://staff.washington.edu/tft/a11ylogo/

TODO
-----
* For older events: are the videos available online?

* Include logo of each event?
* Improved UI!

* Create separate Twitter account for the site.
* Change the sitemap.xml creating code to use the date of the files for real date.

* Videos: improve how they are collected (date, speaker, youtube code, length?)
* Videos: describe how to add them
* Add tags to videos for better indexing
* Combine the speakers page with the xcast people
* Add JavaScript based searching for videos.
* From individual video page link back to event

* Create event "series" e.g. all the 'frontporch' events.





Other sources
------
https://techpoint.ng/2016/09/14/hackjos-2016-2/

