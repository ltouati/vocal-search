# Vocal Search

Simple prototype to do search with voice using the Google Cloud apis.

To make it work, you need to create an API [key](https://cloud.google.com/docs/authentication/api-keys "key") on your cloud console.

In the index.html file, you will need to replace [API-KEY] by the api key you created

Finally due to the browser restrictions, you'll need an https webserver to make the demo work. I am using [NGROK](https://ngrok.com/ "NGROK") that creates an https location from your code.

For example
`ngrok http file://[PATH_TO_YOUR_REPOSITORY]/`

and replace PATH_TO_YOUR_REPOSITORY by the location on your filesystem under which you pulled this repository

Happy testing

This code is not endorsed by Google in any way, and shall not be used in production.