"**hello-world**" 

This is a simple hello-world maven based project configured with Jenkins to learn CI.
The objective is gained by configuring Github Webhook in my github repo and exposing 
my local ip adress to public ip.

Used ngrok software to get my public ip.
command to run ngrok
_`ngrok.exe http 8080`_
Please Note: ngrok.io url is dynamic. If session is closed, we need to create the url again 
and make the changes in github repo webhook

Every time a PR is merged to main branch, jenkins job runs.


