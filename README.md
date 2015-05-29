# Uber API CORS Starter Kit
Starter Kit for using the Uber API with Client Side Javascript CORS. Uses JQuery and Vanilla Javascript to send an AJAX request using the developer's server token.

To get started you will first have to register your app via the [Uber developer site](https://developer.uber.com/apps/new). You will need an Uber account to register. After registering keep track of your Server ID as you will have to add this to the index.html file.

Keep in mind that this only uses front-end code, but you will need to be running a server and you will need to add the Origin URI to your registered Uber app.

Also understand that keeping the Server ID on the client-side is inherently vulnerable so it is better to send these requests from a server (see my corresponding node starter kit if you are interested in seeing that).

We use the [sandbox environment](https://developer.uber.com/v1/sandbox/) provided by Uber so that we aren't actually interacting with live uber cars and accidentally charging our users credit cards in development :)

[Uber API Docs](https://developer.uber.com/v1/endpoints/)
