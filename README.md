# TestControllerStuff
Config files for interfacing some DMMs to TestController. Learn about TestController here:  https://lygte-info.dk/project/TestControllerIntro%20UK.html

ProtekD440.txt is a config file to interface a Protek D440 DMM (with features for automotive maintenance) to TestController.
This works nicely.  One issue: I don't know how to get TestController to recognize RPM data.

The "Metex ME-11" files are several attempts to interface a Metex ME-11 DMM, using different TestController drivers.
At the moment, the only one that sort of works is "Metex ME-11.txt", which uses TestController's SingleValue driver.
It displays all the data, but it is laggy - there is some data communication timing issue.
