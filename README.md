# Airport Code Lookup and Popular Cities Analyzer

## Purpose
### Airport Code Lookup analyzes the Statiosn.csv via an IATA code input that generates the location of the input IATA code. Ex: PSG IATA code would display the location of the airport via state and city: Petersburg, AK, Alaska.
### Popular Cities Analyzer looks up popular cities from the CompletedData.csv. This then prompts the user to input how many cities they would like to know about and it will generate two files that show the departing and arriving flights at popular locals.
## Input:
### Airport Code Lookup:
### The user inputs an IATA Airport Code (3-digits). The program is fed an input of a csv file that has Airport location info.
### Popular Cities Analyzer:
### Number of Popular Cities. The program is fed an input of flight info and travel info from a csv.
## Output
### Airport Code Lookup:
### Location of city and State of IATA code.
### Popular Cities Analyzer:
### Renders two tsv files into downloads that have data from the number of cities input. This also incluses their frequency and occurence.
## Execution Type:
### Both of these programs have file opening and processing functionality. They also both require user determined inputs that are relative to their functionality (i.e., iata code or number of cities)
## Potential Improvements
### Stronger documentation would improve the code, greater detailing from other rows and columns could extend the functionality of the Popular Cities Analyzer. We could also extend functionality of the Airport code lookup as well.
