# The Truth is Out There: Utilizing JavaScript to Sort Data

## Purpose
The purpose of this project is to integrate JavaScript, HTML, CSS and Bootstrap to create a dynamic webpage for searching and filtering data. The result is
a mock-up of a data journalism project on UFO sightings, and it allows users to sort entries based on date, location, and shape of aircraft.

## Overview
This webpage contains multiple options for sorting and filtering a small database of UFO sightings. Users can type in dates, cities, states, countries, shapes
of the objects, or one of each, in order pare down the results. Entries need only be properly-formatted (date) or match one of the criteria in the database to get results.
Say we wanted to see how many sightings took place on New Year's Day, 2010:

![image](https://user-images.githubusercontent.com/1015285/125172060-10908380-e17d-11eb-91e0-b2930d58e63e.png)

As long as the search is in the proper format (M/D/YYY), and there are corresponding data, the returns should be valid. Indeed, *most* of the data in this small set of records are from 1/1/2010, so there are plenty of results to thumb through.

We can also filter based on multiple, or all, of the criteria:

![image](https://user-images.githubusercontent.com/1015285/125172151-9a405100-e17d-11eb-9804-97502f9e4ec2.png)

Again, because the data is somewhat limited, there will only be a few results which satisfy all search criteria. Below is one more exmaple in which we use multiple 
searches -- the country (US) and shape (triangle):

![image](https://user-images.githntent.com/1015285/125172231-1fc40100-e17e-11eb-956f-61415bdc552a.png)

### Summary
This project is a useful mock-up of an interactive database that might be used in journalism, or other domains. It introudces the data through text, color and imagery, and uses a readable, intuitive design that most users would be able to easily operate. I alluded to what I believe is the primary drawback earlier -- the small dataset, which doesn't really allow for nuanced analysis or conclusions. However, this is merely a starting point, and isn't *truly* the purpose of the project -- to practice using HTML and JavaScript. That problem could also easily be addressed and incorporated into the framework of the page if desired.

More to the point, two components for further development that I believe could really help the page are error messages for invalid searches and interactive column sorting. As it stands, the current page doesn't make clear when there's merely a lack of matching results, or there's an issue with the search itself. Interactive column sorting (i.e., the ability to sort words alphabetically, or numbers by ascending/descending order) would make the results more readable and easier to analyze on the fly.


