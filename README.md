# Stockbit React Test for ReactJS Developer Position


### Author
* Name: Ahmad Ichsan Baihaqi
* E-mail: ahmadichsanbaihaqi@gmail.com 


### Requirements
#### Goal
Create a simple React app for movies that consume data from http://www.omdbapi.com. API key informed via email and won't published in this README.

#### Features to be implemented:
* Display List of movies
* Use Infinite Scroll without plugin for search result with > 5
* Search movies by keyword
* Single Page for Single Movie Detail
* Show Movie Poster in a popup modal window when image from the list is clicked
* Unit test for components
* Autocomplete searchbox implementation is a big plus

#### Project must use/have:
* ReactJS
* Redux
* Axios
* Good, sensible file structuring that promotes modularity and good separation of logical/UI
layers
* Written Test Cases for the components
* Showing some display of React Hooks knowledge is a plus

#### Changing in Requirement by Author
Dear HR Stockbit, the requirement to display the movie list is by using OMDBApi. But, unfortunately, I had trouble with the API. The pagination seems not work properly. So, I tried to use another open API with the same concept and I found TMBDApi is quite easy to use. Here is the documentation https://developers.themoviedb.org/. I hope you will be okay with this changes.


#### Step by step to Run Locally
1. git clone or download the zip file
2. if you choose to download the zip file, once downloaded, extract the zip
3. open the program folder with your favorite code editor
4. create ```.env``` file in the root project by copying file ```.env.example``` and remove the ```.example``` extension. The value of the API key (```REACT_APP_API_MOVIEDBKEY```) will be informed via email
5. do ```npm install``` to install all dependencies
6. do ```npm start``` to run the app. **Note**, if query search is not provided, it will display now playing movie

#### Live Demo
Here is the link to see the live demo of this app, https://themoviedb-react.netlify.app/

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
