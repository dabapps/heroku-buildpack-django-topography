# topography buildpack

Heroku buildpack to send the output of [django-topography] to a web service when an app is deployed to Heroku.

Config vars:

* `TOPOGRAPHY_URL` - the full URL to send the data to
* `TOPOGRAPHY_HTTP_METHOD` - the HTTP method to use, default to `PUT`.
