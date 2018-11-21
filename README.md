# Euclid Applications Interview

Hi there!

Thanks for taking the Euclid applications team interview! One of Euclid's major applications is a captive portal that is used to ingest emails when users log on to wifi. The goal of this interview is to build a basic captive portal web app that can accept an email address, verify that it is in the correct format and then post it as a JSON package to Euclid's API: 

Euclid API URL:
```
https://test.euclidporisms.net/captiveportal/interview
```


JSON package:
```
{
	"subscription_id": "interview_emails",
	"device_mac": "AA:BB:CC:DD:EE:FF",
	"ap_mac": "88:15:44:5E:E9:E0",
	"client_name": "euclid_hq",
	"email": "whateveremail@whateverdomain.com"
}
```

A successful payload will post a 200, while anything malformed will post a 401.

We'd also like to display the Euclid logo and a link to the privacy policy; both of which can be found in the assets folder. 

Lastly, upon form submission, we'd like to display a page that thanks the user for submitting their email address. 

# Submission Guidelines
You can use any language/framework that you feel confident in.
We'd like for you to create a new branch as <i>firstname-lastname</i> and commit all of your changes there. We'd also like you to update the Readme for that branch with instructions on how to run your app.

<b>Please take no longer than 24 hours from your start time to complete this interview application, you shouldn't need any longer</b> 
