# API Styles and Best Practices

Follow the specifications of the [JSON API spec](http://jsonapi.org/).

# POST requests
+ Should be used to send new data to the server (ie. resource creation)
+ Should be used for non-idempotent operations, even if the POST body is empty
