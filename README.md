# PSTCodeChallange
Details :
• Build restful web-services for Grocer (/mystore/register/grocer) and consumer registration
(mystore/register/consumer). Basic registration can be done using the following • For Grocer : Name, List of 5 items up for sale in the store, Location
• For User : Name , Location
On success, return a uniqueID (alphanumeric) of 16 characters length with appropriate HTTP Status Code. Incase of failure return a HTTP 500.
• Build 2 RESTful APIs ( GET) which do the following
/mystore/stocklist/{location} Returns a list of grocers with available stock in a particular location.
/mystore/stocklist/{item} Return a list of grocers who sells a particular item ( exact match ).
In case of any exception during reading, return a 404.

I have changed /mystore/stocklist/{item} to /mystore/stocklist/items/{item}
