# HackenFuerMuttiCovid19
Data collection, analysis and visualization of government responses to coronavirus pandemic 2020

https://wirvsvirushackathon.org/  
 https://devpost.com/software/hackenfuermutticovid19

All help is welcome!


## Aim of this project

1. Create, update and maintain a database of government responses to coronavirus pandemic 2020
2. Connect and visualize government response with corona cases of all countries
3. Analyse government response impact on virus growth rates and predict model effectivness of different responses

## Steps

### 1.1
Data scraping 
- Wikipedia e.g. https://en.wikipedia.org/wiki/2020_coronavirus_pandemic_in_South_Korea
- Canceled sport events
- RSS feed dpa

### 1.2
Collect data

Example data structure
| Country | GovernmentResponse | DateComeIntoEffect | DateExpectedToEnd | DateTerminated | Type | Description | Source | Target |
|---------|--------------------|--------------------|-------------------|----------------|------|-------------|------|------ |
|   Belgium	   | quarantine lockdown                   |     2020-03-18               |  2020-04-05  | ? |  lockdown     | nationwide lockdown... | https://www.theguardian.com/world/gallery/2020/mar/18/belgium-enters-lockdown-over-coronavirus-crisis-in-pictures     | nationwide    |
|   Germany	   |  curfew             |     2020-03-20              |  ?  | ? |  lockdown     | Bavaria was the first state to declare a curfew. Fines of up to €25,000  | https://www.thelocal.de/20200320/bavaria-becomes-first-german-state-to-impose-lockdown    | Bavaria   |


Type list:
 - recomendation
 - cancelation
 - travel ban
 - shutdown
 - lockdown
 - other


Target:
 - 

Problems and Ideads to work on: 
https://docs.google.com/spreadsheets/d/1BG8hTdT5hAoZdzdVSOXrmrYjIkzjVLwYz7qtaYoQjG4/edit?usp=sharing


## Useful information 
https://www.zeit.de/gesellschaft/zeitgeschehen/2020-03/coronavirus-ueberblick-eu-grenzkontrolle-ausgangssperre-bussgelder
We want data like this, more detailed and at what time it came into effect

Google docs of related project: https://docs.google.com/spreadsheets/d/1CW99DTTWFO5T3oiERzRaHGqpAQ_J-3PfwaMibUgJp4Y/edit#gid=262317549
