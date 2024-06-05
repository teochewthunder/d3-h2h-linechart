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

## JavaScript

## Chart
