Parking Problems - Team TBD
Jocelyn Lorrey & Deanna Delgado

Files:

final_heatmap.html - the final code run in our demo
				   - displays a heatmap of 2015 and 2017 meter violation data
				   - displays a red shaded polygon where pay-by-app system was implemented in 2016
				   - counts & displays the total number of meter violations in each year
				   - standard heatmap features (change color, change radius, change opacity), plus a
				     clear map feature that we added

geocoder.html - the code needed to convert from street addresses to lat/lng coords 
			  - ran this once & saved result in final_heatmap.html because it must run slowly in order to avoid
			  	"over query limit" error from Google Geocoding API
			  - based on a tutorial from Mike Williams


map_with_buttons_run.html - a preliminary milestone in our project
						  - milestone for interacting with database and parsing data
						  - initial testing of playing around with html elements and 
						    displaying a map with shaded polygon for pay-by-app zone