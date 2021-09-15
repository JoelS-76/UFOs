# UFOs
Analysis of reported UFO data

## Purpose

The client (Dana) wishes to search through a dataset of UFO sightings by multiple criteria including date, city, state, country, and shape (a short description of the sighting). I have designed a webpage which will display the entire dataset in a table, and filter the table based on user input.

## Results

The webpage will filter the entire table by one or multiple criteria. When opened, the page appears like this:

![image](https://user-images.githubusercontent.com/84299125/133406982-68292ac9-493b-46d1-9993-db4200fa5cee.png)

If you scroll down, you will see the table and filter:

![image](https://user-images.githubusercontent.com/84299125/133407184-791b5116-a70e-468e-9c2b-e7bd0e94e58e.png)

There are placeholders in the input bars. If you type a search parameter into one of the bars, you will see all the sightings corresponding to that entry. For example, if you wish to see only the sightings from fresno, you simply type "fresno" into the search bar for "City" and you will see this:

![image](https://user-images.githubusercontent.com/84299125/133407755-147059ec-f86b-4233-a3c6-67e58435a921.png)

You may wish to search for multiple parameters at once. Below is a search for sightings in El Cajon, CA, on 1/1/2010:

![image](https://user-images.githubusercontent.com/84299125/133408191-25db1f02-406b-4697-ae30-574522b07d72.png)

### Summary

There are some drawbacks to the design of this page and the dataset itself. The data is quite limited; it does not take very long to view the entire dataset in table form. It contains only a few different entries for each filter category. This renders the detailed search of this design somewhat superfluous. The usefulness of the design and the impact for the user would both be served by finding a much larger amount of data from all around the world, rather than such a limited set.

Also, some of the entries in the "Comments" column are incomplete or contain spelling or grammar mistakes. Some even include warnings of hoaxes. This is obviously not what the client is going for. It might be preferable to include links to stories regarding the sightings, rather than a garbled array of comments.

In conclusion, the two recommendations I would suggest are:

1. Find a much larger and more diverse dataset.

2. Remove the comments and instead include links to the stories behind the sightings
