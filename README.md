# Movies

Movies App

Hello everyone

I am Akhil. I love watching movies but many a times i faced problems to find the upcoming movies and their related trailers.I felt many might be facing the same problem.So i got an idea of making a movies app which shows upcoming movies ,movies released this week,and a fully functional search of all movies .
Lets dive into the description of the app.
To make the app look attractive I used material design library.


**App Preview**

![screenshot_2016-08-21-18-45-23-min](https://cloud.githubusercontent.com/assets/21156001/17837656/0c442352-67d6-11e6-9da0-703a1996816c.jpg)


I used a library 'it.neokree:MaterialTabs:0.11' for displaying the Scroll Tabs in the app.

**TabPreview**

![screenshot_2016-08-21-18-46-35](https://cloud.githubusercontent.com/assets/21156001/17837448/e90f1b58-67d0-11e6-8b1b-f401d1b2ed44.jpg)

I created fragment for each tab.There are 3 tabs in the app - Upcoming Movies , Movies Released this week,Movies Search (In order)
**Upcoming Movies Tab**
I extracted data from https://developers.cinemalytics.com/ with the help of Volley Library and displayed the data by creating recycler view.


![screenshot_2016-08-21-18-45-23](https://cloud.githubusercontent.com/assets/21156001/17837476/bc6fb534-67d1-11e6-9804-bbc96b9988f3.jpg)

By clicking on a film we can  know more info  about the film such as Release date ,Genre,Censor Rating,Synopsis of the film, trailer link.


![screenshot_2016-08-14-22-11-55](https://cloud.githubusercontent.com/assets/21156001/17837495/696314fc-67d2-11e6-89fb-fe2e6a280038.jpg)

**Movies Released This Week**

In this Tab ,You can view the list of movies which released this week. I used same procedure for extracting and displaying data as in Upcoming Movies tab.

![screenshot_2016-08-21-18-46-11-min](https://cloud.githubusercontent.com/assets/21156001/17837548/9e09acf6-67d3-11e6-854f-8c4e47557dc4.jpg)

**Movie Search Tab**
You can type in any movie name in the search box to get info about the film.I extracted info from omdbapi.com.


![screenshot_2016-08-21-18-46-11-min](https://cloud.githubusercontent.com/assets/21156001/17837578/55a010e4-67d4-11e6-9ab4-47352fd83419.jpg)


I customized the search box as follows
I took  an image of search box from <a href="http://bomagazine.com/wp-content/uploads/2015/08/bomagazine_2015-08-08_14-19-08.jpg">here</a> and divided the image into three parts - search icon ,text field ,go icon using photoshop.After that , I added an imageView of src search icon followed by an Edit text having background of text filed then imageView2 of src go icon.

![screenshot_2016-08-21-18-47-10](https://cloud.githubusercontent.com/assets/21156001/17837629/76ddd330-67d5-11e6-9df9-b052b93ab98c.jpg)

Thats it about my app.
Thanks for reading about my app..









