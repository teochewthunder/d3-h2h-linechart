# d3-h2h-linechart (in progress)
A dynamic line chart that plots goals scored between teams in head-to-head encounters.

## Data 
Teams are represented as an array. Each element has
- `name`: Acts as a foreign key when accessing goals data.
- `logo`: The visual representation on the dashbpard.
- `color` Color used when displaying that football club's data.

Goals are represented as a JSON object. It is divided into seasons.
- Each season is an array.
- Each element of that array is an object containing objects `home` and `away`. Both of these have
    - `team`: Team name.
    - `goals`: Goals scored.
 
## HTML/CSS
- dashboard containing two drop-down lists.
    - These have the same options - the names of the teams whose head-to-head record will be compared. Comparing two identical teams will result in a failure message.
    - Changing the value will result in different logos being displayed.
- chart area which houses the SVG that will be generated.

## JavaScript
- properties
    - `teams`: (see section `Data` above).
    - `data`: (see section `Data` above).
    - `currentData`: a subset of `data` used for visualization, an empty array by default.
    - `margin`: An integer used to determine the amount ofspacing around the borders of the chart.
-  methods
    - xx
    - xx
    - xx
    - xx
    - xx
    - xx
 
## Chart
