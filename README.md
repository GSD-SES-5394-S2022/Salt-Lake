# Salt-Lake
This repository contains files generated for assignments and final report of course SES 5294. 

This project's site is the Salt Lake MSA. It studies how permanent closure of a major commercial street, Main Street, for pedestrian use and increased frequency of a bus route running parallel to the street affect travel behaviours within the studied area, including the change in accessibility, regional VMT, and route-level ridership etc. The proposed closure stretches from South Temple to 400 South. In addition, the project changes the frequency of bus route 200 from 15 minutes to 5 minutes.

The hypothesized change is built upon the successful implementation of Downtown SLC Open Streets, a program temporarily closes one block on the Main Street on the weekends (Thursday - Saturday) from 6-10 p.m. You can read more about the background for this project on the local newspapers [here]( https://www.sltrib.com/news/2020/09/15/salt-lake-city-close/) and [here]( https://www.sltrib.com/news/2021/04/28/salt-lake-city-will-close/).

The repository comprises of the following contents:
* RMarkdowns: The outmost layer stores the RMarkdown(.RMD) files for every assignment with codes used to download, clean and analyze data, generate visualizations and build forecast models. The assignment topics are as follows:
  Assignment 2: Zones, population attributes and employment distribution;
  Assignment 4: Existing and alternative street and transit networks;
  Assignment 5: Calculating existing and alternative accessibility;
  Assignment 6: Estimating vehicle ownership;
  Assignment 7: Estimating trip generation;
  Assignment 8: Estimating trip distribution.
* _alternative_ folder: The data subfolder consists of demographic, employment, accessibility and travel skims for our alternative scenario or proposed change.The network subfolder consists of the revised road network data and revised transit GTFS for our proposed change.
* _existing_ folder: The data subfolder consists of demographic, employment, existing accessibility values, travel skims and trip generation and distribution data for our status quo scenario.The network subfolder consists of the existing road network data and existing transit GTFS.
* _images_ folder: This includes all the graphs and diagrams we generated and used in our written report.
* _zones_ folder: This has the geospatial data of our study area other than the transportation network - such as the boundary and zone centroids data. 


