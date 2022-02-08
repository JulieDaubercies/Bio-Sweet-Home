# LeBioChezMoi
An description of my app (for the moment in private files)

From scratch, I build an app which allows users to know what kind of acteurs work in organic activities in their city.
The data come from api.gouv.fr and Agence Bio.

## First page

The first page ask to enter a departement number : 

<img width="265" alt="Capture d’écran 2022-02-08 à 21 39 02" src="https://user-images.githubusercontent.com/79853433/153072216-483152a7-2144-414e-a87d-58988bf79998.png">

When it's done a pickerView with the list of all the cities of the department appear : 

<img width="265" alt="Capture d’écran 2021-12-07 à 22 16 15" src="https://user-images.githubusercontent.com/79853433/145107450-50049823-79a8-4cda-90b9-e21f72e012bc.png">

User can make multiple kind of research with the searchBar : 
- Enter a precise name of city
- Enter some key word (cities wich contains "Saint" for exemple)
- Research by postal code

Precise name               |  Key word                 |      Postal code 
:-------------------------:|:-------------------------:|:-------------------------:
<img width="265" alt="Capture d’écran 2021-12-07 à 22 20 58" src="https://user-images.githubusercontent.com/79853433/145107988-9f5bd301-53fa-442f-94a8-44e9e709dbbb.png"> | <img width="265" alt="Capture d’écran 2021-12-07 à 22 22 34" src="https://user-images.githubusercontent.com/79853433/145108140-ae3acfd3-ba38-4c39-873d-b4d988895f71.png"> | <img width="265" alt="Capture d’écran 2021-12-07 à 22 23 31" src="https://user-images.githubusercontent.com/79853433/145108261-0342b758-2c7a-4c7a-99e3-06c3208e871b.png">

For cities with district, user must choose one (app is checking if it is an available district) : 

<img width="265" alt="Capture d’écran 2021-12-07 à 22 28 40" src="https://user-images.githubusercontent.com/79853433/145109031-678c1ac2-5453-4f9e-8e5b-c40146c3ec98.png">

## Second page

The second page is a tableView of all entities in the city selected by user (here example of Lyon 5ème)

List for a city            |  SearchBar controller with scope                
:-------------------------:|:-------------------------:
<img width="265" alt="Capture d’écran 2021-12-07 à 22 33 45" src="https://user-images.githubusercontent.com/79853433/145109841-ffca7f9e-a9d2-4a83-a8a1-c38cd73cd0b1.png"> | <img width="265" alt="Capture d’écran 2021-12-07 à 22 34 15" src="https://user-images.githubusercontent.com/79853433/145109869-543b3583-9b4d-4001-b545-016a973da6c4.png">


## Third page

When user select an entity in the list, he obtain a detail of the business : 

<img width="265" alt="Capture d’écran 2021-12-07 à 22 40 56" src="https://user-images.githubusercontent.com/79853433/145110666-d3ffc0cd-eef0-4a4d-9b14-30a8707295a3.png">

"Consulter le certificat" button allow user to go on certification organism website and consult the certificate for biological activities of the chosen enterprise.

In futur, this app can be enrich with news options! see you soon.
