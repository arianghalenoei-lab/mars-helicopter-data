🚁 Mars Helicopter Ingenuity Flight Log Data Viewer code: https://arianghalenoei-lab.github.io/mars-helicopter-data/

This project is a simple, single-page HTML and CSS website designed to display key performance statistics from the early flights of the NASA Mars Helicopter, Ingenuity. The data is presented using structured HTML tables, and the styling uses color-coding to clearly differentiate units of measurement.

📁 File Structure

index.html: The main and only HTML file containing the document structure, headings, and all the flight data presented in two tables.

style.css: The stylesheet responsible for all visual presentation, including setting the table colors and differentiating the unit rows.

📊 Data Presented

The website tracks data across the first six flights (1 through 6), organized into two major metrics:

1. Horizontal Distance

Unit

Flight 1

Flight 3

Flight 4

Feet

0

~328

~873

Meters

0

100

266

This table tracks the total distance traveled horizontally during each flight.

2. Maximum Altitude

Unit

Flight 1

Flight 3

Flight 5

Feet

~10

~16

~33

Meters

3

5

10

This table tracks the highest point the helicopter reached off the Martian surface during each flight.

🎨 Styling and Color-Coding

The style.css file uses distinct colors to improve readability and visually separate the rows containing Imperial measurements (Feet) from those containing Metric measurements (Meters).

Metric

Row

Unit Color

Background Color

Horizontal Distance

Feet

MediumAquamarine





Meters

SeaGreen



Maximum Altitude

Feet

Peru





Meters

#a2662a (Brown/Rust)



Headers

Table Headers (<th>)

SteelBlue

White

This color scheme helps ensure the user can quickly distinguish between the two unit types when reading the log data
