# thingworx-csvparser-javascript-services
Contains ThingWorx JavaScript service replacements for the most widely used CSVParser extension services.

# Description:
This repository contains a single thing which contains ThingWorx Javascript service replacements for the ReadCSVFile and ParseCSVFile services from the CSVParser extension.
These replacements can be used in situations when importing the CSVParser Extension (implemented Java) is not allowed (eg: Windchill+ or other situations).

# How to use:
 - Download the Things_CSVParser.Thing.xml
 - Go to ThingWorx Composer and select Import / From File / Browse and select the file downloaded above

# Services:
  - **ReadCSVFile**: Read CSV content from a file stored in a File Repository to an infotable
  - **ParseCSVFile**: Parse CSV content to an infotable

# Good to know:
 - The available basetypes that should be used in the respective DataShape are: STRING, NUMBER, LOCATION and DATETIME
 - LOCATION basetype parsing is not implemented; all location related fields are not used

In case you encounter any bugs, please raise an issue here: https://github.com/vrosu/thingworx-csvparser-javascript-services/issues

This entity is available as Open Source. Any  improvements can be submitted via a Pull Request, which will be analyzed and incorporated if it's deemed to be useful enough for everyone.
Breaking changes in the existing services will not be accepted; instead add new services (eg: ParseCSVFileV2 or other names as necessary)

### This entity is provided as-is and without warranty or support. 
### It is not part of the PTC product suite. 
### This entity is licensed under the terms of the MIT license.
