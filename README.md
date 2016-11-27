# snitcher-dokku
DeadMansSnitch as a Dokku app.

## Using
1. Push to your Dokku.
2. `dokku config:set YOURAPP SNITCHER=YOURSNITCHNUMBER`
3. Add a cronjob to run `dokku run YOURAPP console`
