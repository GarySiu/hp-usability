+++
date = "2016-05-04T18:35:30+01:00"
title = "Pilots"

+++

The pilots link in the topnav takes you to the `Find a Site` page. This isn't consistent with other top level links.

## Find a Site
### Broken
* Missing Google+ link.
* Airfields link seems to link directly to an unstyled page of every airfield in helipaddy on the admin site. Is this intentional?
* Possible to scrape how many/what sites Helipaddy has.

### Usability
* Unclear why you need an email and who the email should refer to.

### Style
* Compared to the text on the [home](../home/) page, the text is tiny and borderline unreadable.
* The call to action does not stand out at all and it is buried at the bottom of the page.

## Free Registration
### Broken
* Live chat covers elements on the bottom of the screen (the submit button!) on smaller screen sizes
* <span style="font-size: larger; color: red;">The https certificate is **not** setup properly.</span> Currently all users are using an unsecure connection. Attempting to manually force a secure connection raises a warning that the certificate is incorrectly configured.

### Usability
* Must `Home` location really be mandatory considering it's sole purpose is use for our marketing?
* No placeholders are set.
* Consider `Display` name instead of `Nickname` and/or clarify how it will be used.
* It is not clear on this page what Helipaddy Premium entails and how long the promo trial period runs for.

### Style
* There is no promotion for Helipaddy Premium on this page and no option to prepay/switch to Premium from the page.

## Go Premium
### Broken
* Missing Google+ link (aren't these in a partial?)

### Usability
**This page doesn't actually let you do anything!** It's simply an ad for a page that you can only visit while signed in with almost identical content. So as a new user that wants to pay for a Premium account, you must: 

1. Read through the entire ad and agree with the proposition
2. Find the link at the bottom
3. Click through to find that you need an account
4. Click through again to sign up
5. Click the "Upgrade to Awesome" button
6. Then go through the payment process

I think you would have a much higher conversion rate if the steps were more like this:

1. Read the ad with a prominent call to action right up front
2. Click the button. If signed in, you are taken immediately to the payment process.
3. If you are not signed it, it will present you with a sign up form or offer the option to sign in to a pre-existing account. Think Paypal. The customer is reassured that any subscription they buy is in addition to the promo period.

### Style
* Where are all the images showing the cool stuff you get for Premium?
* No feature comparison grid. I feel like I have to read the whole page.

> The quotes aren't styled differently to the body text. This makes it much harder to read/distinguish. Note how big a difference styling makes even on a minimally styled document like this.

## Events
### Broken
* Missing Google+ button
* The `full screen` link doesn't just make the calendar full screen as expected: it opens up a new page with a full screen copy of the calendar.
* The `list` link takes us to another completely unstyled list of events (straight from a db query?)
* Calendar overflows it's container in some screen sizes. This adds an additional scrollbar and degree of seperation.

*    > There is a complete list of heli events available in your Pilot Dashboard.

    The `Pilot Dashboard` link does not take you to the events page and there's no indication on where to go on the dashboard page. It's not clear from the `Events` page what the difference logging in or having Premium will make. Viewing this page while logged in doesn't appear to make any difference?

### Usability
* Only site owners can directly add events. This severely limits who can contribute to the calendar. I understand that you want to promote things that you can directly fly to but I think there's a lot of value to being able to see other things that are merely happening near a landing site.
* The instructions for adding an event are quite complicated and are given in one long run on sentence.
* The alternative way to submit an event is completely divorced from the instructions.
* Submission form is missing placeholders.
* There is no validation on the form.

### Style
* `The big heli events` is quite divorced from the rest of the page. There's no indication that there's more content.
* No suggestion that you would receive better service/more events with Premium.
