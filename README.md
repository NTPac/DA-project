# (Dataset Exploration Title)
## by (your name here)


## Dataset

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.


## Summary of Findings

> Summarize all of your findings from your exploration here, whether you plan on bringing them into your explanatory presentation or not.
#### Duration_sec
<p align = "center">
  <img src="https://c424b21b95de446b824f9d87634b4986.udacity-student-workspaces.com/view/image/duration_Sec.png">
</p>
- The average ride time is quite short, about 1000s
- some trips take up to 80000s

#### start_station_id
<p align = "center">
  <img src="https://c424b21b95de446b824f9d87634b4986.udacity-student-workspaces.com/view/image/start_station_id.png">
</p>
- the starting positions are mostly positions from 0 to 140
- in particular, there is a spike in positions from 230 to 260, from 315 to 375

#### end_station_id
<p align = "center">
  <img src="https://c424b21b95de446b824f9d87634b4986.udacity-student-workspaces.com/view/image/end_station_id.png">
</p>
- the starting positions are mostly positions from 0 to 140
- in particular, there is a spike in positions from 240 to 260

#### start_station_latitude
<p align = "center">
  <img src="https://c424b21b95de446b824f9d87634b4986.udacity-student-workspaces.com/view/image/start_station_latitude.png">
</p>
- the starting station latitude fluctuates quite low, from 37.3 to 37.9

#### start_station_longitude
<p align = "center">
  <img src="https://c424b21b95de446b824f9d87634b4986.udacity-student-workspaces.com/view/image/start_station_longitude.png">
</p>
- The starting point's longitude also fluctuates low, the distance between the two largest and smallest points is only ~0.6

#### end_station_latitude
<p align = "center">
  <img src="https://c424b21b95de446b824f9d87634b4986.udacity-student-workspaces.com/view/image/end_station_latitude.png">
</p>
- the distribution of the data is very similar to the start_station_latitude plot

#### end_station_longitude
<p align = "center">
  <img src="https://c424b21b95de446b824f9d87634b4986.udacity-student-workspaces.com/view/image/end_station_longitude.png">
</p>
- the distribution of the data is very similar to the end_station_latitude plot

#### Start locations density
<p align = "center">
  <img src="https://c424b21b95de446b824f9d87634b4986.udacity-student-workspaces.com/view/image/coordinates_start_point.png">
</p>
- The starting position has the highest concentration at the position with x coordinates from about 37.7 to 37.8, y coordinates from about -122.5 to about -122.4.
- The starting position has the second highest concentration at the position with x coordinates from about 37.8 to 37.9, y coordinates from about -122.25 to about -122.3.

#### End locations density
<p align = "center">
  <img src="https://c424b21b95de446b824f9d87634b4986.udacity-student-workspaces.com/view/image/coordinates_end_point.png">
</p>
- The coordinates at the end position have the same dispersion as the coordinates at the starting position
- The starting position has the highest concentration at the position with x coordinates from about 37.7 to 37.8, y coordinates from about -122.5 to about -122.4.
- The starting position has the second highest concentration at the position with x coordinates from about 37.8 to 37.9, y coordinates from about -122.25 to about -122.3.

#### frequent trips
<p align = "center">
  <img src="https://c424b21b95de446b824f9d87634b4986.udacity-student-workspaces.com/view/image/relationship_start_id_end_id.png">
</p>
- Trips usually start in the range start_station_id 0 to 160 and arrive in the range end_station_id 0 to 160

#### match localtion start and end
<p align = "center">
  <img src="https://c424b21b95de446b824f9d87634b4986.udacity-student-workspaces.com/view/image/match_start_end_location.png">
</p>
- the coordinates of the start_station and the end_station actually coincide, and have almost the same density

#### check the range by coordinates end and start
<p align = "center">
  <img src="https://c424b21b95de446b824f9d87634b4986.udacity-student-workspaces.com/view/image/distance.png">
</p>
- short distance from start and end point


## Key Insights for Presentation

> The dataset provides the start and end locations of each trip, so I came up with the idea, analyzing this dataset to get the starting density, endpoint density, and frequent trips.
The idea is that I will use a Heat Maps to show the density as well as the distribution of the points, and I have been trying to do an analysis of the Start locations density, End locations density , frequent trips