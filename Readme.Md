Development:
Create a JS bundle with Webpack

$ npm run build - Create a JS bundle with Webpack
$ npm run start - Start the Webpack development server on ‘localhost:5000’
$ npm run test – Run tests

Task:
Build a small web app that will find the cheapest flights around Europe.

Styling:
Apply a styleguide following the i.e Ryanair branding (colors) – Please use one of LESS or SASS

Components:
An airport selector which will display the list of airports and allow the user to select an airport. Keep in mind that origin is different from destination but the component needs to be reusable for both scenarios. The component needs to be a custom select with autocomplete support.

Flight List
A component that will show all the information relative to the flights between the
origin and destination selected.

Requirements:
OneWay Dataflow

Services:
In order to get the list of Iata codes ( airport codes )  with the relative destinations the webapp will get those information from the following API:

https://murmuring-ocean-10826.herokuapp.com/en/api/2/forms/flight-booking-selector/
Instead to get the list of cheap flights:

https://murmuring-ocean-10826.herokuapp.com/en/api/2/flights/from/DUB/to/STN/2014-12-02/2015-02-02/250/unique/?limit=15&offset-0
where DUBis the originating IATA code, STNis the destination IATA code,
the first date range is the start of the period, and the second is the end.

Routing
The flight list page needs to be a child route of the home page, the search widget needs to be accessibile even after a search
The flight list page needs to be deep linked, so I can share the URL and access directly the flights that I am looking for.
