# homework-pkg

The HomeworkData.csv file contains a flattened representation of graves in various parts of the world for a family spanning three generations.  Our ask is that you do the following using these data:

1. Install Arches 4.3 (in development mode) and the Arches "Homework Package" on a server. It will be ideal if the deployment is web-accessible, but it could also just be on your own laptop if you are able to bring it in or do a screenshare to demonstrate.  
 - Arches Code Repo: https://github.com/archesproject/arches 
 - Arches Documentation here: https://arches.readthedocs.io/en/stable/

2. Process the csv file into a format/structure that can be loaded into Arches.  Load the data into the Graves "Resource Model" (which was loaded as part of the Homework package.) If any data integrity issues that prevent loading, document and resolve those issues.  Verify that the data are visible in the Arches search page.
 - Hint: https://arches.readthedocs.io/en/stable/command-line-reference/#import-business-data

3. Visualize the data within Arches using a non-Arches Platform, like: Geoserver/Leaflet, Mapbox, AGOL, QGIS, ArcGIS.  Any chops you want to show off with this external platform are welcome. (Search, cool cartography, data processing).
 - Hint: The Postgres Arches database will contain a materialized view called mv_geojosn_geoms.  Once data are loaded, this view can be used as the basis for a traditional GIS layer containing Postgis data.

4. Create a simple document that:
 - describes your steps to accomplish each task above
 - outlines any challenges or roadblocks encountered along the way
 - estimates the amount of time you spent on each task

5. Given that this is a competitive process, feel free to extend on your Arches deployment in any way that you think demonstrates your technical acumen or vision of what Arches can be used for.  One resource that may help with that are the slides from an Arches Development training course, available here: https://github.com/archesproject/arches-dev-training-pkg

While this is a technical homework assignment, we are equally interested in evaluating your project management instincts, communication style, and ability to address non-technical problems.  Therefore, we encourage you to contact us with thoughtful questions to guide you through the intevitable technical challenges, and to engage with us to set our expectations about timeframes and deliverables.  Further, if you do run into roadblocks that prevent you from making technical progress, make up for it by cogently communicating the issue(s) that prevented progress.
