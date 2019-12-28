# Udagram Image Filtering Microservice

This is my submission for Project 2 - Engineering Full Stack Apps in the Cloud, for the Udacity Cloud Developer Nanodegr

It is a Node.js service that takes an image url as a query parameter and returns a formatted image:

`http://{{host}}/filteredimage?image_url={{image_url}}`

For example, running locally:
`http://localhost:8082/filteredimage?image_url=https://icatcare.org/app/uploads/2018/06/Layer-1704-1920x840.jpg`
would return the formatted image from the given `image_url`

## Running the application

To run the application locally:

First run `npm i` to install node modules.
Then running `npm run dev` runs the application locally on port 8082.

## Building the application

Runnning `npm run build` builds the application and zips it to a file in `./www/Archive.zip`

