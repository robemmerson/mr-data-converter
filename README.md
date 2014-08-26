## DESCRIPTION

Takes CSV or tab-delimited data from Excel and converts it into several web-friendly formats, include JSON and XML.
View it in action here: http://shancarter.github.com/mr-data-converter/




Updated by: Rob Emmerson on 27/08/2014 to support the output from iTunes Connect

Fixes:
- Trim whitespace per cell
- Remove all special characters except +,&
- Make all numbers/floats into strings (JSON will not accept decimal numbers and will throw errors)