# Portland Homeless Resources Gap Analysis

![Portland homeless camp](homeless-image.jpg)

**Homelessness in Portland, Oregon has been rated by the city’s voters as the city’s #1 problem.**

As part of a group project done for a class with Oregon Institute of Technology we tackled this question: What neighborhoods of Portland lack nearby resources for their homeless population?

We studied this by combining the city’s homeless campsite reports data from 2024 with data pulled manually from 211info on available resource providers. With this data we were able to compute which neighborhoods have the least-favorable homeless population to resources ratios and created a GIS map for a graphical overview.

Our data sources were:

- Impact Reduction Program Campsite Reports 2024 from Portland Open Data: https://gis-pdx.opendata.arcgis.com/datasets/b7965b3e95db40c0bcb92e36ab7d3357_1396/explore
- 211info, a private, non-profit organization that connects residents in Oregon and Southwest Washington (Clark and Skamania counties) with local health and social service resources: http://211info.org

## Findings

- We see resource concentration.  Only half of Portland's neighborhoods have all of the resource types we measured. The other half are missing one or more.

- Neighborhoods with high homeless population to resources ratio are:
  - Lents
  - Lloyd
  - Parkrose
  - Brooklyn

Explore our data's view of Portland with our live GIS map here: https://tikimojo.com/share/oit-class/web-map-8-12-15/#11/45.5121/-122.5437

<img width="400" height="301" alt="Map of portland neighborhoods showing homeless camps vs resources" src="https://github.com/user-attachments/assets/4bd9a074-c4b6-496a-89d2-43c7214ab600" />


For more information on our findings, our process, and more data plots please visit: [Google Slides](https://docs.google.com/presentation/d/1PIuivEgIJSWo67WqCAsMTqDvn2cOjN8q_nPbniBCANQ/edit?usp=sharing)

## Limitations

Measuring a homeless population is difficult due to the transient nature of the subjects.  This study faces the following limitations:

- The campsite data does not give us a count of individuals as it is a count of campsites.  As such our results do not show actual population numbers.
- We were unable to get a dataset from 211info.org.  As a result the data was compiled by hand.
- Our resource calculation for each neighborhood was somewhat arbitrary.  This could be better informed with additional research.

## Conclusions

This is an interesting and informative first dive into the subject.  For greater clarity more research is needed.  It is our hope that this information can help guide city leaders in addressing the existing need in our communities.

The top four neighborhoods in need of additional resources are: 
1. Lents
2. Lloyd
3. Parkrose
4. Brooklyn

For anyone considering increasing resources to assist Portland's homeless population, based on our data, these are the areas to focus on.

## Roles

- I led the team, designed the analysis, performed the data cleaning and data analysis work.
- The GIS map was built by Ben Gold.

## In This Repo

- QGIS files: our source files for QGIS
- Datasets: our compiled data set
- Plots: images of the graphs we drew to analyse our data
- Project files: the python Jupyter Notebooks used to clean and compile the data
- These are project files from a class project.  Setup notes to come.

This information is also available on my web site: https://www.tikimojo.com/portland-homeless-resources/
