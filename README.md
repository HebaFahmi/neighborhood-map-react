# Neighborhood Map (React)
You will develop a single-page application using React featuring a map of your neighborhood or a neighborhood you would like to visit. You will then add additional functionality to this application, including: map markers to identify popular locations or places you’d like to visit, a search function to easily discover these locations, and a list view to support simple browsing of all locations. You will then research and implement third-party APIs that provide additional information about each of these locations (such as StreetView images, Wikipedia articles, Yelp reviews, etc).

This application follow this [Udacity Project Rubric](https://review.udacity.com/#!/rubrics/1351/view)

## How to download the project
Open the online demo [here](https://github.com/HebaFahmi/neighborhood-map-react-heba)

## How to run the "neighborhood-map-react-heba" project

In the project directory, you can run:

### `npm install`

This command installs a package, and any packages that it depends on.
Install the dependencies in the local node_modules folder.
By default, npm install will install all modules listed as dependencies in package.json.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

## Features in the project

1. Type into the filter/search box to filter the shown locations on the map.
2. Click on the button below the filter/search box to collapse or expand the suggestions list.
3. Click anywhere on the map to close the information window that opens.
4. Click on any marker to see the location details fetched from the [FourSquare APIs](https://developer.foursquare.com/).
5. Click "Show/Hide" to show or the the suggestions list.

## Service Workers
When available in the browser, the site uses a service worker to cache responses to requests for site assets. Visited pages are rendered when there is no network access. For production mode run:

- npm run build
- npm install
- npm start
- open the app on localhost:3000
