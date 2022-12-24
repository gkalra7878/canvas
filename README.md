# What is this

Simple kids learning web app which change the background image/color on the key pressed.

all images are placed on `images/background` folder

_bg.json_ has mapping of those images and keys which fetched using mock API

## How to run

- clone this repo and navigate to folder and run

  `npm install`

- build client and server using webpack by running

  `npm run buildDev`

- start the app

  `npm run start`

- run below in another terminal instance

  `npm run mock-server`

now open **<http://localhost:3003>** in browser

## How it works

user press any key

on right side that key name will be appeared in white color with big font size

- if this key is a number than background-color will change and that number of circle appears which key is pressed.
  for eg. if 3 is pressed than 3 circle will appears.

- if this key is any alphabet than background Image will be changed to that background.
  for eg if user press A than background image will be changes to Apple.
  Note: all images are in _.jpg_ format only.
