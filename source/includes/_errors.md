# Errors

The Wordapp API uses the following error codes:


Error Code | Meaning
---------- | -------
400 | Bad Request -- Your request sucks
401 | Unauthorized -- Your API key is wrong
403 | Forbidden -- You are not allowed to this resource
404 | Not Found -- The specified endpoint could not be found
405 | Method Not Allowed -- You tried to access an url with an invalid method
410 | Gone -- The resource requested has been removed from our servers
418 | I'm a teapot
422 | Unprocessable Entity -- The Wordapp server returns validation errors
429 | Too Many Requests -- You're requesting too many resources! Slow down!
500 | Internal Server Error -- We had a problem with our server. Try again later.
502 | Bad Gateway -- Wordapp's Unicorn server does not respond.
503 | Service Unavailable -- We're temporarily offline for maintenance. Please try again later.
