+++
title = 'Managing Events'
weight = 12
+++

# Managing Events

We have a simple event management system that allows for creating events with:

- Start and End Datetimes
- Location/Venue field
- Calendar View
- Ticketing system integrated with WooCommerce

## Adding a new Event

Adding a new event is simple, but make sure you follow the steps below:

1. On your Wordpress Admin Dashboard, click on `Events` > `Add New Events`

2. Fill up **only** the following:

   - **Title**.

   ![alt text](/title.png)

   - **Description**. Put all other miscellaneous information (agenda, speakers, additional images, etc.) on your description too.

   - **Start and End Date Times**. Make sure it's an upcoming date and the Start Time is not after the End Time.

   ![alt text](/datetime.png)

   - **Location/Venue**. ONLY use the first `Location/Venue` field, as seen below. the other fields (`street`, `city`, `state`, etc) will **not** show up on the event page.

   ![alt text](/location.png)

   - **Assign Tickets To Events**. Under `Ticket & Pricing`, click on the `Add New Ticket Type` button.

   ![alt text](/add-ticket.png)

   Fill up the `Name`, `Price` (in Ringgit), and `Capacity` fields.

   ![alt text](/add-ticket-2.png)

3. That's it, nothing else is required. You can go ahead and save and publish the event to start selling it.

4. Optionally, you could include one `Featured Image` for the event. Look for the `Events Feature Image` Section, which should be located on the right:

   ![alt text](/eventsfeatureimage.png)

   If you have additional images, one suitable place would be under `Description`.

### New Event Checklist

Here is a checklist to go through before saving and publishing your newly-created event.

- [ ] Event has a Title
- [ ] Event has a Description
- [ ] Event has a Valid Location only under `Location/Venue` field.
- [ ] All Start/End Date & Time fields are correctly filled. And it must be a future date.
- [ ] Tickets Types are created properly with a `Name`, `Price` and `Capacity`.

Optional:

- [ ] Give the event a Featured Image. Additional images can be placed under `Description`.

## Checking Event Bookings

On the Wordpress Admin Dashboard, you can click on `WooCommerce` > `Orders`, or, `Analytics` > `Orders`.

### Get order list for a specific event

1. On the Wordpress Admin Dashboard, click on `WooCommerce` > `Orders`. Here, you'll see a filter tool for all your orders.

   ![alt text](/order-filters.png)

2. Select the Event that you want to filter by, and click `Filter`.

   ![alt text](/event-dropdown.png)

3. You'll be able to see a list of customers that bought tickets to the selected Event. You can further filter by the customers' `Email` or `Name` to confirm attendance.

   ![alt text](/customerfilter.png)

### Disable Tickets Selling for a Particular Event

If by any chance you decide to not sell tickets/seatings using the website, you can turn it off by:

1. On the Wordpress Admin Dashboard, click on `Events`. Look for your event and click `Edit`.

2. On the Edit page, scroll down a little and look for the `Ticket and Pricing` submenu.

   ![alt text](/turnoffregistration.png)

3. inside `Ticket and Pricing`, there will be a Registration Off/On toggle switch. Turning this off will disable the ticket selling functionality only for this event.

4. By doing so, users will not be able to purchase or book tickets for this event and ticketing-related text such as `Sorry, there are no seats available` will not appear.
