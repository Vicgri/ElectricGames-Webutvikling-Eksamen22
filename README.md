# Assignment

We have gotten a big gaming company as customer. The company is called ElectricGames and wants to be a new platform for games from different platforms (Xbox, Playstation, Nintendo Switch). They want a Web Api with a database which has information about Games and GameCharacters. They also want a frontend solution which makes use of the Web Api, and which is both informative and fun (possibly some quiz for example).

A Game should at least have the following information:

Id, Title, Platform (for example Playstation 5), ReleaseYear, Image
A GameCharacter should at least have the following:

Id, Name, Game (which game the character is from), Image
In addition, they also want a HTML page in wwwroot which describes how to use the Web Api: which endpoints are available, how to use the endpoints, which information is available etc.

The main functionality is based on that the Web Api has methods that do CRUD (Create, Read Update, and Delete) to the Database. The methods in the Web Api are used from the frontend through HTTP requests (GET, POST, PUT, DELETE). The main functionality in the Web Api is this:

Get all of something
Get something by id
Get something by other property than id, for example GetByName
Delete something
Create something (including image upload)
Update something
The functionality in the frontend makes use of the above methods and in addition not the point about being informative and fun from the email “which is both informative and fun (possibly some quiz for example).” The amount of implemented functionality and the quality of the solution affects the grade.

If you work 3 together you are expected to have both Game and GameCharacter and add a 3 rd model class. This is of course not obligatory but will affect the grade.



# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

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

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
