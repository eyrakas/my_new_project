| Variable   | Description                                 |         Source                             | 
|--------|---------------------------------------------|---------------------------------------------|
| journeyId	|The unique identifier for each journey ID, whether it's trip start or trip end   |[wejo data](/home/capstone/amenity_gap_data/data/wejo_clean)                                             |
| capturedTimestamp|The date and time the event was recorded |[wejo data](/home/capstone/amenity_gap_data/data/wejo_clean)|
| latitude|The geographic coordinate position for North/South position|[wejo data](/home/capstone/amenity_gap_data/data/wejo_clean)|
| longitude	     |The geographic coordinate position for East/West position  | [wejo data](/home/capstone/amenity_gap_data/data/wejo_clean)|
| event         | The type of event recorded, such as trip start or trip end  | [wejo data](/home/capstone/amenity_gap_data/data/wejo_clean)                                           |
| geometry | Geometric coordinates of the neighbourhood|[demographic dataset](https://data-sccphd.opendata.arcgis.com/datasets/demographic-statistics-zip-code/data)   |
| zip_code  | The actual zip code of the area |        [demographic dataset](https://data-sccphd.opendata.arcgis.com/datasets/demographic-statistics-zip-code/data)                                    |
| total_pop   |  The total population of the zip code   | [demographic dataset](https://data-sccphd.opendata.arcgis.com/datasets/demographic-statistics-zip-code/data) |
| african_american  | The percent of African American population in the zipcode | [demographic dataset](https://data-sccphd.opendata.arcgis.com/datasets/demographic-statistics-zip-code/data) |
|  asian_pacific_islander | The percent of Asian Pacific & Islander population    |[demographic dataset](https://data-sccphd.opendata.arcgis.com/datasets/demographic-statistics-zip-code/data) |
| latino |  The percent of Latino population |[demographic dataset](https://data-sccphd.opendata.arcgis.com/datasets/demographic-statistics-zip-code/data) |
| white |     The percent of White population    |[demographic dataset](https://data-sccphd.opendata.arcgis.com/datasets/demographic-statistics-zip-code/data) |
| foreign_born|   The percent of foreign born people  |[demographic dataset](https://data-sccphd.opendata.arcgis.com/datasets/demographic-statistics-zip-code/data) |
| single_parent   | The percent of single parents in the neighbourhood | [demographic dataset](https://data-sccphd.opendata.arcgis.com/datasets/demographic-statistics-zip-code/data) |
| with_children |  The percent of parents with children in the neighbourhood|[demographic dataset](https://data-sccphd.opendata.arcgis.com/datasets/demographic-statistics-zip-code/data) |
| age0_5 | The percent of population aged upto 5 years old |[demographic dataset](https://data-sccphd.opendata.arcgis.com/datasets/demographic-statistics-zip-code/data) |
|  age0_17 |  The percent of population aged upto 17 years old|[demographic dataset](https://data-sccphd.opendata.arcgis.com/datasets/demographic-statistics-zip-code/data) |
|age6_11 |The percent of population aged between 6 and 11 years| [demographic dataset](https://data-sccphd.opendata.arcgis.com/datasets/demographic-statistics-zip-code/data) |
|age12_17| The percent of population aged between 12 to 17 years|d[demographic dataset](https://data-sccphd.opendata.arcgis.com/datasets/demographic-statistics-zip-code/data) |
|age18_24|The percent of population aged between 18 to 24 years|[demographic dataset](https://data-sccphd.opendata.arcgis.com/datasets/demographic-statistics-zip-code/data) |
|age25_34|The percent of population aged between 25 to 34 years|[demographic dataset](https://data-sccphd.opendata.arcgis.com/datasets/demographic-statistics-zip-code/data) |
|age35_44|The percent of population aged between 35 to 44 years|[demographic dataset](https://data-sccphd.opendata.arcgis.com/datasets/demographic-statistics-zip-code/data) |
|age45_54|The percent of population aged between 45 to 54 years|[demographic dataset](https://data-sccphd.opendata.arcgis.com/datasets/demographic-statistics-zip-code/data) |
|age55_64|The percent of population aged between 55 to 64 years|[demographic dataset](https://data-sccphd.opendata.arcgis.com/datasets/demographic-statistics-zip-code/data) |
|age64plus|The percent of population aged more than 65 years|[demographic dataset](https://data-sccphd.opendata.arcgis.com/datasets/demographic-statistics-zip-code/data)|
|median_household_income|The median income for each family in the zipcode|[economic data](https://data-sccphd.opendata.arcgis.com/datasets/economics-education-statistics-zip-code/data)|
|unemployed_age_16|Percent of unemployed aged 16 and less|[economic data](https://data-sccphd.opendata.arcgis.com/datasets/economics-education-statistics-zip-code/data)|
|high_school_grad_or_less|Percent that graduated high school or lower|[economic data](https://data-sccphd.opendata.arcgis.com/datasets/economics-education-statistics-zip-code/data)|
|high_school_grad|Percent of high school graduates|[economic data](https://data-sccphd.opendata.arcgis.com/datasets/economics-education-statistics-zip-code/data)|
|associate_degree|Percent with associate degrees in the neighbourhood|[economic data](https://data-sccphd.opendata.arcgis.com/datasets/economics-education-statistics-zip-code/data)|
|college_grad|Percent with college graduate degrees in the neihbourhood|[economic data](https://data-sccphd.opendata.arcgis.com/datasets/economics-education-statistics-zip-code/data)|
|area|The area of the neighbourhood in Acres|[economic data](https://data-sccphd.opendata.arcgis.com/datasets/economics-education-statistics-zip-code/data)|
|length|The perimeter of the neighbourhood|[economic data](https://data-sccphd.opendata.arcgis.com/datasets/economics-education-statistics-zip-code/data)|
|Council_District|The Council District No in which the park is found|[Parks Data](https://koordinates.com/layer/95883-city-of-san-jose-parks/)|
|Main_District|The Main District No, in which the park is found|[Parks Data](https://koordinates.com/layer/95883-city-of-san-jose-parks/)|
|Park_Type|The type of park. i.e. Neighbourhood Parks, Park Chains, etc.|[Parks Data](https://koordinates.com/layer/95883-city-of-san-jose-parks/)|
|Park Name|The specific name of the park|[Parks Data](https://koordinates.com/layer/95883-city-of-san-jose-parks/)|
|Owner|The registered owner of the park|[Parks Data](https://koordinates.com/layer/95883-city-of-san-jose-parks/)|
|Municipality|The city adminstrator under which the park is registered|[Parks Data](https://koordinates.com/layer/95883-city-of-san-jose-parks/)|
|Area_in_Acres|The actual area of the parks in Acres|[Parks Data](https://koordinates.com/layer/95883-city-of-san-jose-parks/)|
|CFD|Community Facilities Districts|[Parks Data](https://koordinates.com/layer/95883-city-of-san-jose-parks/)|
|PROCHN|Park Chains|[Parks Data](https://koordinates.com/layer/95883-city-of-san-jose-parks/)|
|OS|Open Space Parks|[Parks Data](https://koordinates.com/layer/95883-city-of-san-jose-parks/)|
|SPRT|Sports Parks|[Parks Data](https://koordinates.com/layer/95883-city-of-san-jose-parks/)|
|PRKCH|Park Chains with recreational facilities|[Parks Data](https://koordinates.com/layer/95883-city-of-san-jose-parks/)|
|JU|Joint Use Parks|[Parks Data](https://koordinates.com/layer/95883-city-of-san-jose-parks/)|
|REG|Gathering Public Parks|[Parks Data](https://koordinates.com/layer/95883-city-of-san-jose-parks/)|
|NAT|National Parks|[Parks Data](https://koordinates.com/layer/95883-city-of-san-jose-parks/)|
|CTY|City Parks or County Parks|[Parks Data](https://koordinates.com/layer/95883-city-of-san-jose-parks/)|
|DOT|Recreation areas embedded to schools|[Parks Data](https://koordinates.com/layer/95883-city-of-san-jose-parks/)|
|FACID|Facility ID, unique idenfitier for health center|[Healthcare Dataset](https://data.ca.gov/dataset/licensed-and-certified-healthcare-facility-listing)|
|FACNAME|Name of the Facility|[Healthcare Dataset](https://data.ca.gov/dataset/licensed-and-certified-healthcare-facility-listing)|
|FAC_FDR|Designation of Facility|[Healthcare Dataset](https://data.ca.gov/dataset/licensed-and-certified-healthcare-facility-listing)|
|LTC|Longterm Care Medical center|[Healthcare Dataset](https://data.ca.gov/dataset/licensed-and-certified-healthcare-facility-listing)|
|ADDRESS|The physical address of the center|[Healthcare Dataset](https://data.ca.gov/dataset/licensed-and-certified-healthcare-facility-listing)|
|ZIP|The zipcode of the area the center is found|[Healthcare Dataset](https://data.ca.gov/dataset/licensed-and-certified-healthcare-facility-listing)|
|COUNTY_NAME|The name of the county the health center is found|[Healthcare Dataset](https://data.ca.gov/dataset/licensed-and-certified-healthcare-facility-listing)|
|LATITUDE|The geometric latitude the center is located|[Healthcare Dataset](https://data.ca.gov/dataset/licensed-and-certified-healthcare-facility-listing)|
|LONGITUDE|The geometric longitude the center is located|[Healthcare Dataset](https://data.ca.gov/dataset/licensed-and-certified-healthcare-facility-listing)|
|parking_lot|Designated parking lot|[Healthcare Dataset](https://data.ca.gov/dataset/licensed-and-certified-healthcare-facility-listing)|
|num_events|Number of trips that start or end at the center|[Healthcare Dataset](https://data.ca.gov/dataset/licensed-and-certified-healthcare-facility-listing)|
|avg_trip_duration|Average trip duration from origin zip code to the center|[Healthcare Dataset](https://data.ca.gov/dataset/licensed-and-certified-healthcare-facility-listing)|
|median_trip_duration|Median trip duration from origin zip code to the center|[Healthcare Dataset](https://data.ca.gov/dataset/licensed-and-certified-healthcare-facility-listing)|
|origin_zip|The zipcode the trip is originated|[Healthcare Dataset](https://data.ca.gov/dataset/licensed-and-certified-healthcare-facility-listing)|
|          	     |                                     |                                             |








