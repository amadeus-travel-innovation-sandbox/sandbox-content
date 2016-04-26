Travel Innovation Sandbox Content
=================================

This repo contains the content and specifications for the [Amadeus Travel Innovation Sandbox](https://sandbox.amadeus.com).  Check out [our site](https://sandbox.amadeus.com) for more details.

What's in these files?
---------------------
* `affiliate-search-destinations.json` is the list of IATA airport codes supported as an origin or destination for our [Flight Affiliate Search](https://sandbox.amadeus.com/travel-innovation-sandbox/apis/get/flights/affiliate-search). The keys in the JSON file indicate the IATA code of the airlines that serve the value list-of-airports. The corresponding city codes to these airport codes are also accepted.
* `airport-autocomplete-template.html` is a sample usage of our [Airport Autocomplete API](https://sandbox.amadeus.com/travel-innovation-sandbox/apis/get/airports/autocomplete) using [JQuery UI Autocomplete](http://jqueryui.com/autocomplete/)
* `flight-search-cache-origin-destination.csv` is a list of the currently supported origin-destination airport pairs and their respective currencies in the Amadeus Feature Results Public Cache that powers our Flight [Inspiration Search](https://sandbox.amadeus.com/travel-innovation-sandbox/apis/get/flights/inspiration-search) and [Extensive Search](https://sandbox.amadeus.com/travel-innovation-sandbox/apis/get/flights/extensive-search) APIs.
* `swagger.yml` is the [Swagger spec document](http://swagger.io/) for our [current APIs](https://sandbox.amadeus.com/api-catalog)

Can't wait?
===========
[![Run in Postman](https://run.pstmn.io/button.png)](https://www.getpostman.com/run-collection/efa4aae29a15aca1ca64). 
