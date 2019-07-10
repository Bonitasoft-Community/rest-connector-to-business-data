# REST connector with result stored in business variable

This example demonstrate how to use Bonita REST API connector to get some data from a public web service and store them in a Bonita process business variable.
Such approach is recommended if you need to process the web service data within a Bonita process (e.g. to include the data in an email, to use it in gateway conditions...).

If the REST API data only need to be displayed as read only in a web form you should instead use form variables that can be directly initialized using a REST API call.

## Use this example
You can download the .bos file from the release section and import this file in your own Studio workspace.