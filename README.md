# UFOs

## Introduction

The purpose of this webpage is to provide and interactive tool to allow interactive filtering of UFO sightings by certain filter criteria entered by the user. The following fields have been identified as the fields to allow filter on :-
- Date 
- City
- State
- Country
- Shape

## Webpage layout

The following image shows the main areas of the webpage.

![Webpage Anatomy Image](/Resources/pageAnatomy.PNG)

The page has six main areas :- 

#### Navigation Bar

While there is no current functionality be performed at thios moment the section is created for future development , this will allow us to add fution site navigation without re-designing the overall layout.

#### Page Header

This is the overall header for the page and allows a backgroup graphic with a text header.

#### Ariticle Title

This provides a text block that allows us to put a title for the subsequent article content.

#### Article Paragraph

This povides a text block that allows us to put the content of the article we are wanting to display on the page.

#### Filter for table data

This is a section of the page that allows the user to enter filter critiea to filter the sightings data.

#### Table of sightings data

This is a table of the sightings data and will be filtered by any values entered in the filters area.

## Filtering sightings data

The webpage allows for the filtering of signtings data based on the following data fields :- 
- Date
- City
- State
- Country
- Shape

If there are no entries in the filter criteria all entries will be displayed , if there is an entry in any of the filter criteria elements these will be applied and the filtered data displayed.

It is not necessary to male and entry in all the filter fields ,  the data will be filtered only by the filter data that has been entered.

E.G.

If you wanted to filter for data for the date 1st January 2010 in the city of Benton. You would put an entry :- 

1/1/2010 in the date filter box
benton in the city filter box

The clear an entry in the filter box just blank the entry and press enter , this will reset that particular filter for that box and the filter will be removed from the diplayed data.

### Example of applying a single filter

The image below displays the initial screen without any filters being applied.

![Initial screem Image](/Resources/initialScreen.png) 

The image below displays the screen and the resulting filter being applied and the filter data being shown. The filter entered is on the date filter and the criteria entered is for 5th January 2010.

 ![Webpage Anatomy Image](/Resources/singleFilter.PNG)

Based on the image above it can be seen that the signtings data has been filtered for only date 5th January 2010.

### Example of applying multiple filters

The image below displays the screen and the resulting filter being applied and the filter data being shown. The filter entered is on the date filter and the criteria entered is for 5th January 2010 and state nj.

![Webpage Anatomy Image](/Resources/multipleFilters.PNG)

Based on the image above it can be seen that the signtings data has been filtered for only date '5th January 2010' and state 'nj'

## Summary

While the webpage is functional and provides the desired interaction and resulting filtering. There are some limitations and possible additional functionality that could be developed.

### Limitation

One of the main limitations identiofied is in the filter functionality , at present while you can filter on multiple field values. You can only enter a single value per criteria. 

Example 

Using the multiple filters example above :- 

- We entered the following filteres Date : 1/5/2010 and State : NJ

We cannot enter multiple dates and multiple states

- We cannot enter the following : Date : 1/5/2010 and 1/12/2010 and State : NJ and CA

### Additional functionality recommendations

The following additional functionality is recommended.

1) Allow multiple entries in each of the filter criteria fields.
2) Rather than having to go through each of the filter criterial seperately to clear the filter values , it would be recommend to insert a button with the functionality to reset all filter value to 'blank'.


