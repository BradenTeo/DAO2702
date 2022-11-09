# DAO2702 Project

The team project requires students to solve ONE practical business problem by exploiting real datasets.

## Our problem statement
Our team aims to identify locations in which Starbucks should open their new stores, so as to stay on top of the coffee industry. 
We seek to rectify the issues of steep competition and cannibalisation that Starbucks faces.

## Our approach
We determine the optimal new store location through critically analysing these 4 different sets of data: 
- Rent 
- Distance to the Nearest Starbucks 
- Customer Volume for Each Area 
- Area Demographics (Age and Income)

1. First, we collect data online (mostly from data.gov.sg).<br>
*Interesting note: For 'Rent', we scraped the data from a [property site](https://www.srx.com.sg/singapore-property-listings/commercial-for-rent)
using [Parsehub](https://www.parsehub.com/).*

2. Then, we perform data cleaning, removing columns or values here and there to prepare for data visualisation.

3. Finally, data visualisation.<br>
We use the `folium` library in Python to create interactive maps.<br>
This is the most fun part of the whole project :grin:
 
## Results
[Click here to see the cool results!](https://bradenteo.github.io/DAO2702/)
