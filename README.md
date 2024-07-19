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
To manually add a new feature, contact the developer, Rachel Pierce, or continue with the following instructions:

    1. While in the github web interface, click on treedata.geojson.
    
    2. Click the pencil icon to edit the dataset.
    
    3. Find the Tree_ID associated with the new sponsorship.

    4. Each record appears with the following attributes: 
      "Tree_ID":1,            //--> integer
      "Diameter1":12,         //--> integer
      "Diameter2":null,       //--> integer
      "MorF":"M",             //--> "M" or "F"
      "Two_Stem":null,        //--> boolean
      "Health_Status":null,   //--> text    
      "Symptom":null,         //--> text
      "Last_Treated":null,    //--> date format as "mm-dd-yyyy"
      "Note":null,            //--> text
      "Species":"White Ash",  //--> text
      "Age":null,             //--> integer
      "Sponsored":null,       //--> booolean "True" or "False
      "Sponsor_Name":null,    //--> text
      "Sponsor_Date":null,    //--> date format as "mm-dd-yyyy"
      "Tree_Nickname":null,   //--> text
      "Link":"insert hyperlink",
      "Payment_ID":null,      //--> format as "LastName_TreeID_mm-dd-yyyy"
      "Longitude":-77.82096667,
      "Latitude":39.4211,
      "Individuals":1
    
    5. All text based entries must be wrapped in double quotation marks.

    6. All numeric entries, such as a new tree ID, will remain a plain number, (i.e., 74).

    7. Boolean expressions (T/F) should be written out as "True" or "False"

    8. If an entry says 'null' no data associated with that record.

    9. Commit any changes to save and update the dataset.

    10. Map markers will show as red if the "Sponsored" attribute is updated to True.
    

To learn about the specifics on geoJSON objects, visit: https://geojson.org/
