# college-google-map
Description
Use Python? Want to geocode something? Looking for directions? Maybe matrices of directions? This library brings the Google Maps Platform Web Services to your Python application.

The Python Client for Google Maps Services is a Python Client library for the following Google Maps APIs:

Directions API
Distance Matrix API
Elevation API
Geocoding API
Geolocation API
Time Zone API
Roads API
Places API
Maps Static API
Keep in mind that the same terms and conditions apply to usage of the APIs when they're accessed through this library.

Support
This library is community supported. We're comfortable enough with the stability and features of the library that we want you to build real production applications on it. We will try to support, through Stack Overflow, the public and protected surface of the library and maintain backwards compatibility in the future; however, while the library is in version 0.x, we reserve the right to make backwards-incompatible changes. If we do remove some functionality (typically because better functionality exists or if the feature proved infeasible), our intention is to deprecate and give developers a year to update their code.

If you find a bug, or have a feature suggestion, please log an issue. If you'd like to contribute, please read contribute.

Requirements
Python 3.5 or later.
A Google Maps API key.
API Keys
Each Google Maps Web Service request requires an API key or client ID. API keys are generated in the 'Credentials' page of the 'APIs & Services' tab of Google Cloud console.

For even more information on getting started with Google Maps Platform and generating/restricting an API key, see Get Started with Google Maps Platform in our docs.

Important: This key should be kept secret on your server.

Installation
$ pip install -U googlemaps
Note that you will need requests 2.4.0 or higher if you want to specify connect/read timeouts.
