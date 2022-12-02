# sf-murals Project - Backend

This README is a two parter, one for the backend and one for the frontend which is [here](https://github.com/SeldomseenSchweig/sf-murals-frontend/blob/main/README.md).

## Purpose and Process

The purpose of this project was to create a site where thpeople who are interested in finding murals and public art San Francisco could find it, and add to it if they felt like it. The API that was used for this was from [SFdata](https://data.sfgov.org/Culture-and-Recreation/StreetSmArts-Murals/wg8w-68vc). This API had some issues, the first was that I was not getting the data I wanted from the call. So what I did was seeded my database with the data from the API. This also allowed me to add murals to the database, which is a part of this project. Go to the site, sign up, and find some murals in the city, take some pictures, and suggest some links to the pictures. I will be happy to add Them to the database.

## Tools Used for the Backend

The backend was built using Postgresql and node.js.

To create the back end, you will need to npm intall in the folder. 

You will have to create a database in Postgres and seed the database with the sfMurals.sql file.

To start the app type npm start while in the frontend folder. Make sure that the frontend and the back end are in the same folder.

## Future Upgrades

There are several things that I would like to add in the future. Users adding comments to murals that are on the site. A list in the profile section of murals users have suggested, both apporoved and denied. Mapping capabilites. I attempted to use react-simple-maps to create small maps of where the murals were in the city. The formatting though was off, the maps were really tiny. If you, the reader, would like to try, please, be my guest, I will work on it after the others.
