# React Simple YouTube Mockup

---

## Overview

This is a simple YouTube mockup built using ReactJS and YouTube Data API v3.

**Features:**

* Users are able to search videos with the search bar
* Search results are instantly updated with top 5 videos of search term
* Users can click on a video in the list to have the video embed into the media player

## Install
Move to root project folder and with npm:

```
npm install
```

## Usage
**To prepare:**

1. Navigate to `https://console.developers.google.com`
2. Get API Key for `YouTube Data API v3`
3. In `index.js`, assign `API_KEY` with your API Key you just got and save the file.

**To run:** Move to root folder and with npm:

```
npm start
```

## Details
**Libraries Used:**

* Bootstrap v4: Used for general quick styling
* YTSearch: Used to make YouTube search queries
* lodash: Used to debounce and throttle frequency of searching
