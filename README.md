# Short iPython notebook that uses the Google Translate API and openpyxl to programatically translate Excel files

### A few notes:
* openpxyl maintains Excel formatting!
* checks for alpha characters in a cell phrase before translating, to reduce unnecessary api calls
* keeps a dict of translated phrases and checks prior to executing a new api call, again to reduce unnecessary api calls
