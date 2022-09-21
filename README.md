# UFO

## Deliverable 1: Filter UFO sightings on multiple criteria (80 points)

In Deliverable 1, we removed the button feature, and added search criteria for City, State, Country, and Shape, as you can see in the image below an overview of what that looks like on my website.

<img width="1487" alt="Website_Overview" src="https://user-images.githubusercontent.com/103979087/191394480-9d95d1ee-56be-4850-a854-e32e28e4b06d.png">

Here below is the code used to add those search criteria into my HTML document.

![remove_button:add_filters](https://user-images.githubusercontent.com/103979087/191394583-4fa4bfc1-678a-406d-80af-b0c1268c0940.png)


## Deliverable 2: A written Report on the UFO Analysis (20 points)

### Overview
Using JavaScript and HTML, I created more table filters, as well as added filters for the city, state, country, and shape. I also created a new function that saves the element, value, and id of the filters, and one that loops through the dataset and only keeps the results that match the search criteria.

### Results
With the new filters, the user can input a Date, City, State, Country, or Shape, or a combination of any of those filters to get an exact match of UFO sightings. 

For example, I filtered for UFO Sightings only in Texas, and got these results.

<img width="1467" alt="Filtered_for_TX" src="https://user-images.githubusercontent.com/103979087/191393619-4e90b4ab-811a-4437-80bd-fa6bd5fec1e3.png">

However, I could take it a step further and filter for Texas, and filter for UFO's that were specifically "Light" shaped, and these are the results that it yielded.

<img width="1092" alt="TX:Light" src="https://user-images.githubusercontent.com/103979087/191393797-be4e1967-0831-4e6d-a63f-ba0d9173714d.png">


### Summary
A drawback of this table/filter is that not all cities or states have UFO sightings, and so inputing a city often feels like a shot in the dark and comes up with no results. My recommendation would be to add a feature that showed a map of all the UFO sightings so that the user could see an overall view of said sightings. It would also be helpful if the map adapted to the filters that the user set.
