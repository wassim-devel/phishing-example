# phishing-example
A very simple phishing website example who sends the data to a discord webhook.

This is done by doing a POST request to Discord using the built-in javascript fetch() API in order to execute the webhook : https://discord.com/developers/docs/resources/webhook#execute-webhook

It is highly recommended to use a back-end that receives and forwards the request to the webhook, otherwise the webhook will be publicly exposed
(It is very simple to make a DELETE request to a webhook to delete it.)

You can just add CSS to make it look like the website you want.

