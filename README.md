# Google-Login

1. Register your app on console.developers.google.com
2. Get the client id and client secret from there and enter the redirect url there.
3. Make sure to enter the client id,client secret and redirect url in the servlet.
4. In RegisterPage,java servlet:- Enter the redirecturl in href tag of logout.


#IMPORTANT

You have to enter the jar files to make the code to run

1. Download the jar files from this link :-  https://developers.google.com/api-client-library/java/google-oauth-java-client/download
2. After downloading the go to your eclipse the delete your tomcat server from there.
3. go to the bin folder of your tomcat and paster the jars(only from lib folder) from the file which you downloaded from the above link.
4. Again make the server in eclipse and set your target runtime for your project and then it will run perfecly fine.
