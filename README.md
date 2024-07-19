**Welcome to the readme for Morgan's Grove Park Tree Map Web App!**

**7-19-2023**

VERSION 1.0


**--> Index.html:**
This HTML document contains the javascript code for a leaflet map instance with additional functionality that fetches a geojson called treedata. A user can interact with the point markers and use the sponsorship form to submit their data. If the user pays, then the dataset will be updated (manually).


**--> Sponsorship Form:**

This google form collects the information submitted by a user and updates the spreadsheet mentioned in the next section.

https://docs.google.com/forms/d/e/1FAIpQLSeZpoMxm3kdszubfNOSwOHcV-gypIJlOfYNjateuM69k9zfTg/viewform


**--> Sponshorship Spreadsheet:**

This google spreadsheet is automatically updated when a user submits their sponsorship details using the submit button.

https://docs.google.com/spreadsheets/d/1kU1doW71_tCv0dLAGHlmbJjo33HBaUDyrJssSgFMO5c/edit?usp=sharing


**--> geoJSON Dataset:**

This dataset contains a feature collection of the original 73 points, plus a 74th test point.
To manually add a new feature, contact the developer, Rachel - rpierc21@jhu.edu, or continue with the following instructions:

    1. While in the github web interface, click on treedata.geojson.
    
    2. Click the pencil icon to edit the dataset.
    
    3. Find the Tree_ID associated with the new sponsorship.

    4. One record appears with the following attributes: 
      {"type":"Feature","properties":{"Tree_ID":1,"Diameter1":12,"Diameter2":null,"MorF":"M",
      "Two_Stem":null,"Health_Status":null,"Symptom":null,"Last_Treated":null,"Note":null,
      "Species":"White Ash","Age":null,"Sponsored":null,"Sponsor_Name":null,"Sponsor_Date":null,
      "Tree_Nickname":null,"Link":"insert hyperlink","Payment_ID":null,
      "Longitude":-77.82096667,"Latitude":39.4211,"Individuals":1},
      "geometry":{"type":"Point","coordinates":[-77.82096667,39.4211]},"id":0}
    
    5. All text based entries must be wrapped in double quotation marks.
      All numeric entries, such as a new tree ID, will remain a plain number, such as 74.
      As trees become sponsored, they will receive treatments, so treatment dates will also need to be updated. 
      If an entry says 'null' that means there has been no data associated with that record.
    

To learn about the specifics on geoJSON objects, visit: https://geojson.org/
