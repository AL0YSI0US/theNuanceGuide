# Setting up a React App

**Step 1.**

+ Create a repository on github

> ⚠️  EXCLUDE
>
> adding any of githubs suggested files
>
> while instantiating your repository

1. Name the Repository
2. Select "Public"
3. Press the "Create repository" button

![](https://scontent.xx.fbcdn.net/v/t1.15752-0/s206x206/164578404_806958730028862_2608796317399280845_n.png?_nc_cat=105&ccb=1-3&_nc_sid=58c789&_nc_ohc=NEplzMDJ7hsAX8ZxH29&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent.xx&_nc_tp=30&oh=0c569a8ba1931bad6ff59c7859b9b7c8&oe=607FE0E0) ![]()

**Step 2.**

From the command line enter the following command:

`````bash
npx create-react-app how-to-code
   *                *
 1 |        2       |    3


1. call npx
2. create-react-app
3. name your react app [helpful to keep it the same name as the repository from github]

* there is a single space between the words npx/create as well as -app/the apps name 
`````

Upon creating the initial repository on github, the README.md that was initially excluded will be in the build from the `npx create-react-application-name` comand. Lots and lots of bells and whistles will be in the application when you first open it, many lines of code will need to be removed.

![](https://scontent.xx.fbcdn.net/v/t1.15752-0/p206x206/164493881_1095072477654966_6584056148184009080_n.png?_nc_cat=100&ccb=1-3&_nc_sid=58c789&_nc_ohc=b9W_V7VuFzUAX_hQkUI&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent.xx&_nc_tp=30&oh=3bbf656468a2b8704e180012c3fc3017&oe=60803324)

**Step 3.**

Back on github you are gifted with a Quick setup guide after your repository was created.

Since a repository has already been created you can enter the following commands in one at a time:

1. git remote add origin https://github.com/AL0YSI0US/how-to-code.git
2. git branch -M main
3. git push -u origin main

**Step 4.**

Next enter the following command:

````javascript
npm start
````

**Step 5.**

+ checkout a working branch

## Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

### Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.
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

<=Available scripts provided from React Documentation=>
