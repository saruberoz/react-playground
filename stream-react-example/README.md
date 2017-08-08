# 8 Step - React/Redux tutorial series

This example application created by [getstream.io](https://getstream.io/?ref=github_stream_react_example) teaches you how to to build an Instagram style application with activity streams and newsfeeds.

Visit [cabin.getstream.io](http://cabin.getstream.io/) for an overview of all 8 tutorials and a [live demo](http://cabin.getstream.io/demo). If you enjoy this tutorial please star this repo.

<p align="center">
  <img src="https://stream-cabin.s3.amazonaws.com/defaults/Cabin_Github@2x.png" alt="Examples of what you can build" title="What you can build"/>
</p>

## Blog Posts

1. [Introduction](http://blog.getstream.io/cabin-react-redux-example-app-introduction/)
2. [React & Redux](http://blog.getstream.io/cabin-react-redux-example-app-react/)
3. [Redux](http://blog.getstream.io/cabin-react-redux-example-app-redux/)
4. [Stream](http://blog.getstream.io/cabin-react-redux-example-app-stream/)
5. [Imgix](http://blog.getstream.io/cabin-react-redux-example-app-imgix/)
6. [Keen](http://blog.getstream.io/cabin-react-redux-example-app-keen/)
7. [Algolia](http://blog.getstream.io/cabin-react-redux-example-app-algolia/)


## Integrations

* [Keen](https://keen.io/)
* [ImgIX](http://imgix.com/)
* [Algolia](https://www.algolia.com/)
* [Mapbox](https://www.mapbox.com/)
* [Digital Ocean](https://www.digitalocean.com/)
* [Stream](https://getstream.io)

## To Run the app
- Start the API. Let’s start it up. Ensure you are in the /app directory:
 1. run `cd ../api`
 2. Run the index.js file `source ../env.sh; node index.js`
- Running Webpack is key to running our application. Follow the steps below!
 1. Install Webpack, Globally `npm install -g webpack`
 2. Run Webpack & Check Out Your App. Before you even understand Webpack, let’s just run the darn thing. Ensure you are in the app `cd ../app`
 3. Run Webpack `source ../env.sh; webpack --watch --progress`
 4. And one last step, open a new terminal window and run npm start `npm start`
 5. Head over to http://localhost:3000.
