# LeBioChezMoi
An description of my app (for the moment in private files)

From scratch, I build an app which allows users to know what kind of acteurs work in organic activities in their city.
The data come from api.gouv.fr and Agence Bio.

## First page

The first page ask to enter a departement number. The pickerView display all the cities of the department ask :

<img width="265" alt="Capture d’écran 2022-02-08 à 21 39 02" src="https://user-images.githubusercontent.com/79853433/153072216-483152a7-2144-414e-a87d-58988bf79998.png">

User can make two kinds of research with the searchBar : 
- Enter key word
- Research by postal code

|  Key word                 |      Postal code          |        No result
|:-------------------------:|:-------------------------:|:-------------------------:
<img width="265" alt="Capture d’écran 2022-02-08 à 21 39 38" src="https://user-images.githubusercontent.com/79853433/153072535-fb8fe301-94cd-45a3-8fb5-43c8708fe3e9.png"> | <img width="265" alt="Capture d’écran 2022-02-08 à 21 45 27" src="https://user-images.githubusercontent.com/79853433/153072684-fc03909a-e91d-41b2-8ead-e90a2147b316.png"> | <img width="265" alt="Capture d’écran 2022-02-08 à 21 49 00" src="https://user-images.githubusercontent.com/79853433/153073160-2a022ff5-e819-4f3f-947e-de80b5c01af1.png">

For cities with district, user must choose one (app is checking if it is an available district). Note that keyboard is handle for this view :

<img width="265" alt="Capture d’écran 2022-02-08 à 21 40 03" src="https://user-images.githubusercontent.com/79853433/153072781-77ce9f41-cb30-46d1-b992-f9045442129a.png">

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
