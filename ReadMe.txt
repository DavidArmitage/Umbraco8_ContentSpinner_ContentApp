-----------------------------------------------
Umbraco8 ContentSpinner ContentApp
-----------------------------------------------

This is a content app to assist with spinning content. This is a great tool for bloggers who want unique content but don't want to write this themselves. If you find an article you like online then you can simply copy and paste this into the content app. The app will then spin this into unique words.

The app is free but relies on SpinBot api which is a very cheap paid API service.

For trial purposes I have added an API key with some credits. Once you have reviewed the app please create your own API key.

-------------------------------------
CONFIGURATION INSTRUCTIONS
-------------------------------------

SPINBOT API 
-------------------------------------
Please note this content app utilises spinbot API. You can find more information regarding the API here.
https://spinbot.com/API


CREATE AN API KEY
-------------------------------------
You are required to create your own API Key to use within this content app. You can create an API Key for Spinbot here.
https://spinbot.com/Register - first register
https://spinbot.com/ManageDevelopers - then get your API key here


ADD THE API KEY TO YOUR WEB.CONFIG
-------------------------------------
Once you have created an API Key you are required to add this to your web.config file within the <appSettings> section.
EG.

<appSettings>
  <add key="SpinbotApiKey" value="YOUR API KEY TO GO HERE" />
</appSettings> 


PURCHASE CREDITS
-------------------------------------
Spinbot is a paid service. When creating this app I had a good look around at all the options available. Some were free and some not. I tried and tested a few and decided this to be the best option.

This was based on quality and price. The API worked very well and the price was very cheap. You can find information regarding the pricing here.
https://spinbot.com/PricingApi

Here are the prices the last time I checked.

1,000 Credits for $5.00 USD
2,000 Credits for $10.00 USD
5,000 Credits for $20.00 USD (20% discount)
10,000 Credits for $40.00 USD (20% discount)
20,000 Credits for $80.00 USD (20% discount)
50,000 Credits for $200.00 USD (20% discount)
100,000 Credits for $400.00 USD (20% discount)
200,000 Credits for $800.00 USD (20% discount)
500,000 Credits for $2,000.00 USD (20% discount)


IMPORTANT! WHAT IS TEST MODE?
-------------------------------------
For the purpose of evaluating this content app I have added my own API Key. This is encrypted and compiled within a dll so you wont be able to see this in your web.config. 

If you don’t add an API key in your <appSettings> then this content app will assume you are using it for evaluation purposes. You will still have full functionality but there will be a red message at the top of the app reminding you that you’re still in ‘TestMode’. Once you add your API Key into your <appSettings> file then this message will disappear.

I’m happy for everyone to use my API Key for evaluation purposes but please do not abuse it. I have added 1000 credits and I may top up from time to time as long as people are not abusing the service and eating up all the credits. 

Once you have reviewed the app then please try and create your own API Key as soon as possible.

If you need help with this, please don’t hesitate to drop me an email at.
david@recsitedesign.com


PLEASE SUPPORT THIS APP MY UP VOTING 
-------------------------------------
If you like this content app then please feel free to show your appreciation by voting.


WHERE TO REPORT ISSUES
-------------------------------------
You can either drop me an email at david@recsitedesign.com or you can log a issue at the following URL.
https://github.com/DavidArmitage/Umbraco8_ContentSpinner_ContentApp/issues


LATEST VERSION
-------------------------------------
The latest version of the app can be found here
https://github.com/DavidArmitage/Umbraco8_ContentSpinner_ContentApp



