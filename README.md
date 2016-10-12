# MavenWagonPlayground

A simple project to test some maven wagon settings. The project was created to be able to test different settings in order to 
solve the following problem -> http://stackoverflow.com/questions/39973743/setting-custom-headers-for-http-put-requests-not-set-for-wagonupload

In order to setup the http headers that are to be set, you have to edit the **servers** configuration in the maven settings.
To run the upload task you can use the command:

mvn -Pwagontest wagon:upload

