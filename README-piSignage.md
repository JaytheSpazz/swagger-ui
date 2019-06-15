# piSignage Swagger Documentation

piSignage specific modifications are in pisignage branch

## Generate the distribution
To generate the distribution, run the following commands:
- npm install (first time only)
- gulp clean
- npm run build

## Serve files during development
To serve the files during development, you can use the following command:
- npm run serve

## Deploy the documentation
Copy the files in the dist/ folder to the default public web root of your web server. E.g. in ngnix, this could be /usr/local/ngnix.

A sample *ngnix.conf* file is available in this directory.
