
Concur Disrupt
=========

This page contains information and links to all the resources you need to win the **Concur Contest** in TechCrunch Disrupt 2014 New York.  It is split into the following subsections:

  - Prizes to win
  - What is Concur?
  - What information can I get from the Concur APIs?
  - I'm sold.. How do I get started? 

Prizes to win:
----

Who starts their contest page with prizes? We do!  Here's what you can win:

  - **Maximum $2,500 worth of gift cards**: *Best Re-Polished App using Concur APIs* - planning to re-use a non-Concur app from a previous hackathon?  Feel free to submit them to us, as long as it's using a Concur API (for the first time). Prize distribution is $500 to each winning team member.
    
  - **Maximum $2,500 worth of gift cards**: *Best Use of Concur API* - any new app submission using a Concur API, outside of the Re-Polished category.  Prize distribution is $500 to each winning team member.
    
  - **$100 cash**: *Use of Concur APIs* - first 10 teams that registers/uses/demos the use of Concur APIs, outside of the above categories, gets $100 (per team).
    

What is Concur?
-----------

Over 25 million people in 190 countries and over 65 percent of the Fortune 500 trust Concur to process $50 billion in travel and expense data per year.  We help these 25M business travelers manage their travel bookings and expense reports through the Concur Travel and Expense web/mobile app.  This allows them and their companies to save time, money, gain visibility and enforce employee compliance on expenses.  It's all about giving the business traveler a delightful and worry-free travel experience, which we like to call *The Perfect Trip*.

We also created APIs so that partners can add value and contribute to a business traveler's Perfect Trip.  That's where you come in.

What information can I get from the Concur APIs?
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

I'm sold, how do I get started? (first 1.5 hours)
----

**Get a Developer sandbox account**

A sandbox account allows you to test both the app and APIs, free of charge.  For the purposes of this hackathon, we have set up 50 developer sandbox accounts (with pre-defined non-existent email addresses) so that you can jump in right away.  To get one of these accounts, please email chris.ismael@concur.com with the Subject: Disrupt Sandbox.  

If you prefer to set up your own free sandbox, you can do so by registering [here](https://developer.concur.com/register).  Note that the setup steps right after you login requires you to just keep clicking 'Next' (for the most part) until you get to the end.  Chris also has an iMacro script that automates that part of the developer sandbox registration, so feel free to email him if you want access to that script (chris.ismael@concur.com)

**Install the app**

After you've set up your sandbox account, the first logical thing to do is to familiarize yourself with the app, so that you can map the APIs to sections inside the product.  You can access the web version of Concur at http://concursolutions.com/ or get the mobile app from [App Store](https://itunes.apple.com/us/app/concur-travel-receipts-expense/id335023774?mt=8) or [Google Play](https://play.google.com/store/apps/details?id=com.concur.breeze).

It also helps to watch these [2-min videos](https://www.concur.com/en-us/resource-center/mobile?type[]=video) (snapshot image below) to understand how the Concur app works, as well as get context on how your app will add value to the Concur business traveler (e.g. Our app helps Concur users predict weather conditions for their future travel).

![Concur videos](https://uzzjfa.bn1301.livefilestore.com/y2pKCHzTRnCEe3U2QYSl8PXRlHqocgshxeHPpbNhIp0fvyOg0Sb5ooFlcsbkyZjnpCO68WLs_sgtlVdmNajb3WIgqAx6j8NE3yNq3AZCCSPbXQ/Screen%20Shot%202014-04-21%20at%204.32.17%20PM.png?psid=1)

**Try at least one API first**

The fastest way to get a handle of the APIs would be to try to get a response from one first.  The first step is to authenticate yourself.  Without getting into too much detail, we'll authenticate using Concur's [OAuth Native Flow](https://developer.concur.com/api-documentation/oauth-20-0#nativeexample).  The goal is to get an Access Token that we will use for all our subsequent API calls.

Here are the complete steps, with screenshots, on how to call our first API.

1.  **Get your Consumer Key**  

After logging in to http://concursolutions.com, go to Administration -> Register Partner Application -> Concur Partner Application (Modify)

![Consumer Key](http://chrispogeek.files.wordpress.com/2014/01/untitled.png)

- Swagger
- (To be continued)


**You're set.  Go win this!**



  
