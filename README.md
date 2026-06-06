# splunkBackground
Custom background for Splunk login page.

The included image in this app is from Vecteezy. It's one of the free vector images available for use.
The download file was `vecteezy_vector-abstract-background-with-soft-gradient-color-and_6107730_461`.

## How it works
We're using default pathing for Splunk with a variable for our appname. This is configured in web.conf. `$SPLUNK_HOME/etc/apps/<myApp>/appserver/static/` is the default pathing. We're setting the `logincustombg` folder path and specifying the file name.

This app will require a restart to make it work in my experience. 