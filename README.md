## Steps

1. [Clone the repo](#1-clone-the-repo)
2. [Install app dependencies](#2-install-app-dependencies)
3. [Deploy app and classify](#3-deploy-app-and-classify)

### 1. Clone the repo

Clone the `tfjs-web-app` locally. In a terminal, run:

```
git clone https://github.com/gurumukhi/tfjs-web-app
```

Now go to the cloned repo directory:

```
cd tfjs-web-app
```

### 2. Install app dependencies

In the project directory, run:

```
yarn install
```

> **Note**: If you don't have yarn installed, instructions can be found
> [here](https://yarnpkg.com/lang/en/docs/install/). You can alternatively use `npm`.

### 3. Deploy app and classify

You can either deploy in development mode or production mode. Service workers and offline usage
will only work if you deploy the app in production mode.

#### Development Mode

In the project directory, run:

```
yarn start-dev
```

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits to the UI. You will also see any lint errors in the console.

The API server is hosted on `http://localhost:5000` by default.

#### Using the App

The app allows you to either use your device's camera to snap an image or select a local image from
the device's filesystem. Select an image of an object or put the object in frame using your camera,
then click classify. Local inference will then be performed, and the top five results will be given.

![Classify with App](doc/images/app-classify.png "Classify with App")
![App Predictions](doc/images/app-predictions.png "App Predictions")

## Links

- [TensorFlow.js](https://www.tensorflow.org/js)
- [React](https://reactjs.org/)
- [Progressive Web Apps](https://developers.google.com/web/progressive-web-apps/)
- [Service Workers](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API)
- [Web App Manifest](https://developers.google.com/web/fundamentals/web-app-manifest/)
- [IndexedDB](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API)
- [React Bootstrap](https://react-bootstrap.github.io/)
