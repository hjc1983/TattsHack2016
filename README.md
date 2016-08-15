# TattsHack2016

A 24hr Team Innovation Event from 3pm 11-12/Aug/2016. 

Make use of Azure Functions - a serverless architecture that can be triggered by event. 
for instance, I have a HTTP endpoint that handles POST requests on Form submission:

POST - https://tattshack.azurewebsites.net/api/HttpPOSTGift

{ "fromName" : "Testing from Azure", "fromLastName" : "LName", "fromEmail" : "abc@abc.com", "fromDOB" : "1/2/1990", "fromLicense" : "Lic34324", "toName" : "Dan", "toEmail" : "your@email.com", "toMessage" : "I have this working.... :p" }
