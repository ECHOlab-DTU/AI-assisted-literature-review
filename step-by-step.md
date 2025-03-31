# Literature Visualizations

The first part of the workshop series focused on finding relevant liteature.
In this session we go through a number of tools and open-source software to visualize the literature scapes in different ways.
Visualizations can help to show relations of aspects such as keywords or authors in the literature, or can give an overview over the development of a body of literature on a certain topic.

### tools used in this tutorial: 

[ScienceScape](https://medialab.github.io/sciencescape/)
[Table2Net](https://medialab.github.io/table2net/)
[GephiLite](https://gephi.org/gephi-lite/)
[Cortext](https://managerv2.cortext.net/login)
[TUT](https://tut.man.dtu.dk)


## Step 1 - Download data as a csv file

In this example we use scientific literature from [Scopus](https://www.scopus.com).
When downloading the list of publciations and entities as a csv file, remember the following:

- select all
- export as csv
- include abstracts & keywords

<img src="images/Screenshot 2025-03-28 at 12.42.25.png" width="600" height="400">


There is a limit to the number of articles that can be downloaded at a time. 
If you wish to include more than the given number in your file, you have to download the results in different steps and merge them into one csv file manually.


## Step 2 - Visualizing in ScienceScape

ScienceScape works with the csv data from Scopus or alternatively Web of Science and turns them into visualizations. 
There are a number of visualization types to choose from.

## Step 3 - Visualizing in Table2Net

As opposed to ScienceScape, [Table2Net](https://medialab.github.io/table2net/) can work with any type of tabular data. So we are less restricted on the input (does not have to be Scopus or WebofScience).
An example could be interview data, that you have curated into a tabular format; say Speaker and Answer in a spreadsheet as a csv file.

Once you open [Table2Net](https://medialab.github.io/table2net/), you have different options to explore, beginning with the type of network. In our case we choose a normal network (one type of node). 
The nodes can represent a variable of your choosing (e.g. author keywords)
For now, we do not add other attributes.

The links between the nodes refer to row numbers in your table.

We do not add temporal data in this case. But again - all variables are customizable to your preferences.

The difference between the tabular data and the network you produce here, is that the network data has attributes - coordinates etc. 
There are relations between the data points, making it possible to place them in a coordinate system.

Table2Net produces a network file that we are visualizing in Gephi or Gephi Lite.

## Step 4 - Gephi or Gephi Lite

Gephi can be downloaded, [GephiLite](https://gephi.org/gephi-lite/) is the browser version of the program.
In this step you need to think about what you want to see




