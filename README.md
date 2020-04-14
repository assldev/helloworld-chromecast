# Introduction
This is a sample Chromecast (Receiver) app deployed on Heroku.

# Usage
## Pre-requisites
- You need to have already registered on `Google Cast SDK Developer Console` to have your own application ID which points to this (static) web-app.
- If you don't intend to publish your app, you will have to register your devices to be able to test it. DONOT forget to restart your devices, once registered.
## Sender App
(Out of scope from this repository, but you will need one with a valid application ID)
## Receiver App
You can use the following URL (check if it works first) in the `Google Cast SDK Developer Console` to test your app.
> `https://helloworld-chromecast-receiver.herokuapp.com/`
NOTE: Make sure to check if the URL is still functional first.

# References
- [DeMille/url-cast-receiver](https://github.com/DeMille/url-cast-receiver)
- [Debugging](https://developers.google.com/cast/docs/debugging)