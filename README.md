
This code snippet provides functions to retrieve data related to the global and country-specific cases, deaths, recovered, and active cases of COVID-19. 

## Modules Used:
- `requests`

## Functions Used:
- `get_global_data()`: Retrieves the global COVID-19 data.
- `get_country_data(country)`: Retrieves the COVID-19 data for a specific country.
- `get_global_cases()`: Retrieves the total number of global COVID-19 cases.
- `get_global_deaths()`: Retrieves the total number of global COVID-19 deaths.
- `get_global_recovered()`: Retrieves the total number of global COVID-19 recoveries.
- `get_country_cases(country)`: Retrieves the total number of COVID-19 cases for a specific country.
- `get_country_deaths(country)`: Retrieves the total number of COVID-19 deaths for a specific country.
- `get_country_recovered(country)`: Retrieves the total number of COVID-19 recoveries for a specific country.
- `get_country_active(country)`: Retrieves the total number of active COVID-19 cases for a specific country.

>The data is retrieved from the "https://coronavirus-19-api.herokuapp.com" API.

## Example usage

```import kovid

# To get global data
print(kovid.get_global_data())

# To get data from a country
print(kovid.get_country_data('USA'))

# To get global cases
print(kovid.get_global_cases())

# To get global deaths
print(kovid.get_global_deaths())

# To get global recovered
print(kovid.get_global_recovered())

# To get a country cases
print(kovid.get_country_cases('USA'))

# To get a country deaths
print(kovid.get_country_deaths('USA'))

# To get a country recovered
print(kovid.get_country_recovered('USA'))

# To get a country active
print(kovid.get_country_active('USA'))
```