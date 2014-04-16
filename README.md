
ncur Disrupt
=========

This page contains information and links to all the resources you need to win the **Concur Contest** in TechCrunch Disrupt 2014 New York.  It is split into the following subsections:

  - Prizes to win
  - What is Concur?
  - What information can I get from the Concur APIs?
  - I'm sold.. How do I get started? 

Prizes to win:
----

Who starts their contest page with prizes? We do!  Here's what you can win:

  - **$2,000 cash**: *Best Re-Polished App using Concur APIs* - planning to re-use a non-Concur app from a previous hackathon?  Feel free to submit them to us, as long as it's using a Concur API.
  - **$2,000 cash**: *Best Use of Concur API* - any "new" app submission outside of the Re-Polished category
  - **$100 cash**: *Use of Concur APIs* - each team that uses and demos the use of Concur APIs gets $100
    

What is Concur?
-----------

If you've heard of TripIt, then there's a remote chance you've heard of us. We help 25M business travelers manage their travel bookings and expense reports through the Concur Travel and Expense web/mobile app.  This allows their companies to save time, money, gain visibility and enforce compliance on their employees' expenses.  It's all about giving the business traveler a delightful and worry-free travel experience, which we like to call *The Perfect Trip*.

We also created APIs so that partners can add value and contribute to a business traveler's Perfect Trip.  That's where you come in.

What information can I get from the Concur APIs?
--------------

**Example apps**

Before we get to that question, here are 2 examples of what our partners have built using Concur APIs.  They're all listed in our [App Center](https://www.concur.com/en-us/app-center):

- [TravelText](https://www.concur.com/en-us/partners/transaction-capture/traveltext) - TravelText allows you to text your expenses right into Concur. No more paper receipts and Excel sheet mayhem!  Don't believe us?  Check out their video demo [here](https://www.youtube.com/watch?v=sxY_PO-QKZ0).
- [Trover](https://www.concur.com/en-us/app-center/listing/nDhf34TiiC9RCocFM2xViin5c/Trover) - it's travel photography + business travel integration in one great app. Because we understand that the business traveler is a person too. Quoting from this [article](http://skift.com/2013/07/25/travel-photography-app-trover-secures-2-5-million-in-funding-from-concur/#/0), what they get for integrating with Concur is *"being able to tap into Concur’s experience, knowledge and “great visibility into travel patterns”"*.

**APIs**

You can find more examples of apps that use our APIs in the App Center link above.  Now let's get to business - what information can you get from the Concur APIs?
- [Itinerary Details of a Concur user](https://developer.concur.com/api-documentation/web-services/itinerary/itinerary-resource/itinerary-resource-get#getitindetails) - there's a ton of information you can get from a Concur user's trip, such as the booking segments the trip, whether it's Air, Car, Hotel, Dining, Ride, Rail, or Parking.  The most common information you'll probably use is a user's travel destination.  From that single piece of info, you can make recommendations to the traveler.  In fact that's what Trover is doing.
- [Expense data history of a Concur user](https://developer.concur.com/api-documentation/web-services/expense-report/expense-report-resource/get-report-digests) - users of Concur expense their purchases using the Concur Travel and Expense web/mobile app, so that they can get reimbursed by their company at the end of the trip.  This gives Concur insight into a user's expense pattern (*e.g. does Joe always get a Starbucks coffee right after landing in SFO?*). This API returns a collection of expense reports that you can use to make the same deduction.  It's also worth noting that there are also APIs to submit expense [entries](https://www.concursolutions.com/api/docs/index.html#!/Entries/Post_content_user_post_2) (e.g. Starbucks coffee, printer ink, etc) and [reports](https://developer.concur.com/api-documentation/web-services/expense-report) (collection of expense entries), as well as [submit images](https://www.concursolutions.com/api/docs/index.html#!/ReceiptImages) of receipts (similar to TravelText above).

*We know you're tempted to stop reading and start coding after clicking those API docs links, but please read on to find out more on how you can win this... ;)*

I'm sold, how do I get started?
----

- Install app
- Swagger
- (To be continued)


**You're set.  Go win this!**



  
