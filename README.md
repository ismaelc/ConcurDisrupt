
<img src="https://jfqcza.bn1.livefilestore.com/y2paqP_3uagi8J3WlP4-pNt4kJoOzRKmuohSQUsrjaegIaoNbNZJ7EXLEflIO6XYAOKM6scpKxbtXPg10RL5OO3A9bc6m-zERVRHUYB1OEGq8s/Concur_Logo_VT_Color_500px.png?psid=1" width="90px" />&nbsp;&nbsp;&nbsp;&nbsp;Concur Disrupt &nbsp;&nbsp;&nbsp;<img src="https://jfqcza.bn1304.livefilestore.com/y2pGKvnveN12SnmoryMSg647qwDe4JMLBQ6nVqhBnsOUXY7O3i-jhRIHQXY2dVO1sU2hECixL7OwrE78ntEx7msUA_YLr15z3TuD7MUTk459f4/Screen%20Shot%202014-04-23%20at%203.23.18%20PM.png?psid=1" width="150px" />
=========
<br/>
This page contains information and links to all the resources you need to win the **Concur Contest** in TechCrunch Disrupt 2014 New York.  It is split into the following subsections:

  - [Prizes to win](#prizes)
  - [What is Concur?](#concur)
  - [What information can I get from the Concur APIs?](#apis)
  - [I'm sold.. How do I get started?](#getstarted)

<a name="prizes">Prizes to win:</a>
----

Who starts their contest page with prizes? We do!  Here's what you can win:

  - **Maximum $2,500 worth of gift cards**: *Best Re-Polished App using Concur APIs* - planning to re-use a non-Concur app from a previous hackathon?  Feel free to submit them to us, as long as it's using a Concur API (for the first time). Prize distribution is $500 to each winning team member.
    
  - **Maximum $2,500 worth of gift cards**: *Best Use of Concur API* - any new app submission using a Concur API, outside of the Re-Polished category.  Prize distribution is $500 to each winning team member.
    
  - **$100 cash**: *Use of Concur APIs* - first 10 teams that registers/uses/demos the use of Concur APIs, outside of the above categories, gets $100 (per team).
    

<a name="concur">What is Concur?</a>
-----------

Over 25 million people in 190 countries and over 65 percent of the Fortune 500 trust Concur to process $50 billion in travel and expense data per year.  We help these 25M business travelers manage their travel bookings and expense reports through the Concur Travel and Expense web/mobile app.  This allows them and their companies to save time, money, gain visibility and enforce employee compliance on expenses.  It's all about giving the business traveler a delightful and worry-free travel experience, which we like to call *The Perfect Trip*.

We also created APIs so that partners can add value and contribute to a business traveler's Perfect Trip.  **That's where you come in**.

<a name="apis">What information can I get from the Concur APIs?</a>
--------------

**Example apps**

Before we get to that question, let's look at 2 examples of apps that our partners have built using Concur APIs.  They're all listed in our [App Center](https://www.concur.com/en-us/app-center):

- [TravelText](https://www.concur.com/en-us/partners/transaction-capture/traveltext) - TravelText allows you to text your expenses right into Concur. No more paper receipts and Excel sheet mayhem!  Don't believe us?  Check out their video demo [here](https://www.youtube.com/watch?v=sxY_PO-QKZ0).

- [Trover](https://www.concur.com/en-us/app-center/listing/nDhf34TiiC9RCocFM2xViin5c/Trover) - it's travel photography + business travel integration in one great app. Because we understand that the business traveler is a person too. Quoting from this [article](http://skift.com/2013/07/25/travel-photography-app-trover-secures-2-5-million-in-funding-from-concur/#/0), what they get for integrating with Concur is *"being able to tap into Concur’s experience, knowledge and “great visibility into travel patterns”"*.

**APIs**

You can find more examples of apps that use our APIs in the App Center link above.  Now let's get to business - what information can you get from the Concur APIs?
- [Itinerary Details of a Concur user](https://developer.concur.com/api-documentation/web-services/itinerary/itinerary-resource/itinerary-resource-get#getitindetails) - there's a ton of information you can get from a Concur user's trip, such as the booking segments the trip, whether it's Air, Car, Hotel, Dining, Ride, Rail, or Parking.  The most common information you'll probably use is a user's travel destination.  From that single piece of info, you can make recommendations to the traveler.  In fact that's what Trover is doing.

- [Expense data history of a Concur user](https://developer.concur.com/api-documentation/web-services/expense-report/expense-report-resource/get-report-digests) - users of Concur expense their purchases using the Concur Travel and Expense web/mobile app, so that they can get reimbursed by their company at the end of the trip.  This gives Concur insight into a user's expense pattern (*e.g. does Joe always get a Starbucks coffee right after landing in SFO?*). This API returns a collection of expense reports that you can use to make the same deduction.  It's also worth noting that there are also APIs to submit expense [entries](https://www.concursolutions.com/api/docs/index.html#!/Entries/Post_content_user_post_2) (e.g. Starbucks coffee, printer ink, etc) and [reports](https://developer.concur.com/api-documentation/web-services/expense-report) (collection of expense entries), as well as [submit images](https://www.concursolutions.com/api/docs/index.html#!/ReceiptImages) of receipts (similar to TravelText above).

*We know you're tempted to stop reading and start coding after clicking those API docs links, but please read on to find out more on how you can win this... ;)*

<a name="getstarted">I'm sold, how do I get started? (first 1.5 hours)</a>
----

**Get a Developer sandbox account**

A sandbox account allows you to test both the app and APIs, free of charge.  For the purposes of this hackathon, we have set up 50 developer sandbox accounts (with pre-defined non-existent email addresses) so that you can jump in right away.  To get one of these accounts, please email chris.ismael@concur.com with the Subject: Disrupt Sandbox.  

If you prefer to set up your own free sandbox, you can do so by registering [here](https://developer.concur.com/register).  Note that the setup steps right after you login requires you to just keep clicking 'Next' (for the most part) until you get to the end.  Chris also has an iMacro script that automates that part of the developer sandbox registration, so feel free to email him if you want access to that script (chris.ismael@concur.com)

**Install the app**

After you've set up your sandbox account, the first logical thing to do is to familiarize yourself with the app, so that you can map the APIs to sections inside the product.  You can access the web version of Concur at http://concursolutions.com/ or get the mobile app from [App Store](https://itunes.apple.com/us/app/concur-travel-receipts-expense/id335023774?mt=8) or [Google Play](https://play.google.com/store/apps/details?id=com.concur.breeze).

It also helps to watch these [2-min videos](https://www.concur.com/en-us/resource-center/mobile?type[]=video) (snapshot image below) to understand how the Concur app works, as well as get context on how your app will add value to the Concur business traveler (e.g. Our app helps Concur users predict weather conditions for their future travel).

<img src='https://jfqcza.bn1301.livefilestore.com/y2plGwIFgIkWPhuXtK609Lokwso2nQKF5qZjZa0lQZI8p2WZl2s2s2VrbHQhyOVE8nJZm1iVnjxfqC4pH_CXEKxiSMcNl_LF2iXW10hfM3YGPk/Screen%20Shot%202014-04-22%20at%2010.37.30%20PM.png?psid=1' width="600px" />

**Try at least one API first**

The fastest way to get a handle of the APIs would be to try to get a response from one first.  The first step is to authenticate yourself.  Without getting into too much detail, we'll authenticate using Concur's [OAuth Native Flow](https://developer.concur.com/api-documentation/oauth-20-0#nativeexample).  The goal is to get an Access Token that we will use for all our subsequent API calls.

Here are the complete steps, with screenshots, on how to call our first API.

1.   **Get your Consumer Key**  

 After logging in to http://concursolutions.com, go to Administration -> Register Partner Application -> Concur Partner Application (Modify).  We need the consumer key so we can call the endpoint that would return the access token.

 <img src='http://chrispogeek.files.wordpress.com/2014/01/untitled.png' width="600px" />

2.  **Call the endpoint to request an access token**

 Here's what the HTTP call looks like to request for an access token:

        GET https://www.concursolutions.com/net2/oauth2/accesstoken.ashx HTTP 1.1
        Authorization: Basic am9obl9kZXZlbG90bWFpbC5jb206VHJhdmVsJkV4cGVuc2UkMjAxMg==
        X-ConsumerKey: eZByXv2X41cJlC21pSVvRi    

 Note that we already have `X-ConsumerKey` from number 1.  To generate the `Authorization: Basic` value, you need to Base64-encode the login ID, colon and password such that john_developer@hotmail.com:Travel&Expense$2012 becomes am9obl9kZXZlbG90bWFpbC5jb206VHJhdmVsJkV4cGVuc2UkMjAxMg==.  If you're not doing this programmatically yet, you can use this [nifty web tool](http://www.base64encode.org/) to generate that value (remember to choose Encode).

 If you're using a Terminal, an equivalent curl statement of the above would be:
        
        curl https://www.concursolutions.com/net2/oauth2/accesstoken.ashx
        -H "Authorization: Basic am9obl9kZXZlbG90bWFpbC5jb206VHJhdmVsJkV4cGVuc2UkMjAxMg=="
        -H "X-ConsumerKey: eZByXv2X41cJlC21pSVvRi"

 If the call is successful, you should get an XML response with a `<Token>` node.  That's your access token. We would also recommend that you use [Postman](http://www.getpostman.com/), a Chrome extension, to help you manage your API calls (not just Concur ones).  Here's what it looks like in action:

 <img src='http://chrispogeek.files.wordpress.com/2014/01/screen-shot-2014-01-13-at-4-45-35-pm.png' width="600px" />

 *Chris has already built a couple of Concur Postman "Collections", email him at chris.ismael@concur.com if you want to get it.*

3.  **Create items to expense and associate them with an expense report**

 We will do this bit using the Concur mobile app.  This would give us data that we can pull using the APIs.  Note that aside from Expense, we can do the same thing for Travel too.  Here's a sequence of screenshots on how to add an expense using the app, then associating them with an expense report.

 <img src='https://jfqcza.bn1303.livefilestore.com/y2pDadi2n4fFfdP7nP7r8tv0mYI0vjDmw1VAHp2h7wAz63qmdTheO7CFZNoMHVUM1AYm9-Ur3YHeR8RrN6yJyw0J_UVEqVwCsTqaxqYte1v6Fg/1.png?psid=1' width="200px"/> <img src='https://jfqcza.bn1302.livefilestore.com/y2pbj4PSh8gAbIicwDnrsPoA2qzBF7mZRE9iN6-tiMl7bE0VpuarZE5fGiQJXBPsZ5bLZoK-POwjWMOeTVh5I-2vr9YMxwnN8zjx08fvWHnE04/2.png?psid=1' width="200px" /> <img src='https://jfqcza.bn1301.livefilestore.com/y2pN7PVESkTt9qgjdCJk-aTmoCdKwZ8HonrNlTzylZPrgs_4rWesCjgd9SBV7xAx7BSaQ4c8wwU9GCCplNeGxfqCQPy-2gcw7c6T5n8O-Bm-y4/3.png?psid=1' width="200px" />
 
 You can keep adding new expenses (and even add a receipt image!) to have a variety of data to pull for your API calls.  After adding expenses, create a report to associate it with by tapping the "Add to Report" button (in the last screenshot above).

4.  **Call the APIs to pull expense report items**

 Since we now have an access token, we can pull an Expense Report Digest, like so (in Terminal):

        curl https://www.concursolutions.com/api/v3.0/expense/reportdigests
        -H "Authorization: OAuth <insert your access token here>"
 
 This would return a JSON response of the Expense Report, with a field called `ID`.  We need this ID to extract the expense line items we created in the app earlier.  To liven things up a bit, let's use the [Swagger](https://www.concursolutions.com/api/docs/index.html#!/Entries) documentation of the "Entries" API to get the individual expense line items:

 <img src='https://jfqcza.bn1302.livefilestore.com/y2pExFhXefF7BWcggCWbeRkUyOUyEf1UdRi0HoCcpj8PKfaGMub-K8xc0BXHsX2NUFlNp54-m6X3aJ7dRNLQiIHfyYJhdtTiEJEArnZJ-r7NCA/Screen%20Shot%202014-04-22%20at%201.21.55%20PM.png?psid=1' width="600px" />

 We highlighted two things here, the (oval) field where you put in your access token, and the (rectangle) field where you put in the `ID` we got from the previous API call.  Note that we can do this same call in curl, or in any fashion you want.  Swagger just provides us a consolidated way to make the API calls.

 To execute the call, click the "Try it out!" button.  You should get a response like this below:

 <img src='https://jfqcza.bn1304.livefilestore.com/y2pty6lMBv5XXLjA_mT5HLpSNea4hVr3AUCRuEI207Wr1otLVxy86klHYuNDP0N-cvb75IFJvicR1jR2K7X3wqJXsH_AQNcEWkp6iO4t3jXRCs/Screen%20Shot%202014-04-22%20at%201.29.22%20PM.png?psid=1' width="600px" />

- Swagger
- (To be continued)


**You're set.  Go win this!**
