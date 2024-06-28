# Website Starter Kit
A starter kit containing my preferred setup for styles and JavaScript using vite as a build tool.

## Installation
```
npm install
```

## Styles
Styles are written in CSS utilising PostCSS on build to pull any imported CSS into one file and process nesting into a more compatible format.

### Editing
The main file is main.css which imports the indexes for each folder, the index inside each folder is named the same as the folder and imports anything inside it to keep things tidy.

Styles folder is split into categories depending on what you are styling.

## JS
JS is handled using modules that get imported and called by main.js, an example is provided of logging to the console.

JS is organised in this way so that logic can be broken into individual files whilst all being called in one place. This helps keep the JS more organised than a free for all.

## Vite
Vite is being used as an example, running it will spin up a live server with live reloading but this setup probably won't do everything you need.

Run dev server:
```
npm run dev
```

Build:
```
npm run build
```
