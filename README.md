# Photo Gallery

In this exercise, we'll render a grid of photos from Picsum Photos in an infinitely-scrolling FlatList.

![Photo gallery](./assets/picture.png)

## Project set up

Start by initializing a new project. You can use either approach described in the Environment section. If you're using Expo (recommended for beginners), run:

```sh
expo init PhotoGallery --template blank
```

## Project Structure
In this app, we'll follow the suggested structure from the Project Structure section, and divide our files into 3 directories:

- api - for fetching remote data
- components - presentational components
- reducers - for managing app data with useReducer

The final directory structure will look like this:

PhotoGallery

├── api

│   └── picsum.js

├── components

│   └── PhotoGrid.js

├── reducers

│   └── photos.js

└── App.js

## Original link
https://www.reactnative.express/exercises/photo_gallery

## Contributors

@belushkin
