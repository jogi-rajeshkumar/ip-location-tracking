This is a Python script that uses geojs.io API to get information about IP addresses. The script can retrieve the IP address of the host machine, as well as the country and geolocation of a specific IP address.

The script contains several functions to retrieve the data, as well as helper functions to format and display the data.

The main functions in the script are:

getIP(): retrieves the IP address of the host machine.
getCountry(): retrieves the country of a specific IP address.
getGeoData(): retrieves all available geodata for a specific IP address.
showCountryDetails(): displays all country information for a specific IP address.
showIpDetails(): displays all available information for a specific IP address (country, location, region, etc.).
The script uses the urllib library to make HTTP requests to the geojs.io API and the json library to parse JSON responses.

Overall, this script is useful for retrieving information about IP addresses and can be used in various applications such as cybersecurity, network monitoring, and geolocation services.
