# topography buildpack

Heroku buildpack to send the output of [django-topography](https://github.com/dabapps/django-topography) to a web service when an app is deployed to Heroku.

Config vars:

* `TOPOGRAPHY_URL` - the full URL to send the data to
* `TOPOGRAPHY_HTTP_METHOD` - the HTTP method to use, default to `PUT`.

## Code of conduct

For guidelines regarding the code of conduct when contributing to this repository please review [https://www.dabapps.com/open-source/code-of-conduct/](https://www.dabapps.com/open-source/code-of-conduct/)
