# UFOs

## Overview of Project

### Purpose
The purpose of this project is to provide a simple webpage that will allow users to view and analyse data
of UFO sightings by creating a table for easy viewing of the collected data and allowing users to filter
the data by multiple criteria.

## Results

### Search Overview
The webpage provides a simple interface to allow users to filter the table data of UFO sightings.
users can use the multiple input fields on the left to input data they would like to have the table
filtered by
![image of search inputs](/Resources/search_inputs.PNG)

### Search input
The search fields provide an example of the required input when the page is loaded but the table is not filtered
initally by the sample input.
User can make use of the following search criteria to filter the table:
 - Date: Filter the table by date of the sighting in the dd/mm/yyyy format
	![image of date search input](/Resources/date_search.PNG)
 - City: Filter the table by the city where the sighting occured using the full city name
	![image of city input](/Resources/city_search.PNG)
 - State: Filter the table by the state where the sighting occured using the shortname of the state
	![image of state input](/Resources/state_search.PNG)
 - Country: Filter the table by the country where the sighting occured using the shortname of the country
	![image of country input](/Resources/country_search.PNG)
 - Shape: Filte the table by the shape of the UFO
	![image of shape input](/Resources/shape_search.PNG)

The table will automatically filter as users type into the search input boxes and will look for an exact match.
![example search](/Resources/sample_search.PNG)

## Summary
### Drawbacks
The webpage does have a major drawback that the table my appear empty while searching until the full matching search term has been
typed into the search field.
The example below shows a partial input search on the date field compared to a full search
![search with partial inputs](/Resources/sample_partial_search.PNG)
![search with full inputs](/Resources/sample_full_search.PNG)

### Recommendations
The following recommndation could be used to plan improvement of the site:
 - Improve the search events to allow for partial search terms to be used instead of exact match
 - Provide a feature to export the filtered table for users to download

