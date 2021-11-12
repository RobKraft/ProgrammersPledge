+++
title = "Commentary"
date = 2021-11-05T10:30:36-05:00
weight = 15
+++

I took some time to review the list of bugs we completed in the last year. I noticed that the majority of bugs found during development and entered into our tracking system were similar to this list:

* Change the dropdown list to be sorted…
* Change the fields on the form to have the correct tab order…
* Change the fields on the form to move and resize appropriately if the form is resized
* Change this to be spelled correctly…
* Change … to be consistent…

Each of these items takes time away from our development in many ways:

* for a tester/QA to recognize it,
* for a tester/QA person to record it,
* for a development team member to confirm it,
* for a development team member to assign it a priority,
* for a development team member to assign it to a person to fix it,
* for the assigned person to make the change,
* for the assigned person to mark it complete in the tracking system,
* for a tester/QA to retest it after the next build  for a tester/QA to mark the item as done.

That is a lot of Project Management for items that are just the result of sloppy programming.  We should strive to reduce these cosmetic “bugs” from ever being included in code that is “ready to test”.

Here is my idea.  Create a pledge that a programmer makes to QA because these are not the kind of “bugs” that QA should need to waste time on testing and tracking. I don’t think this pledge should be formalized and signed by each developer. I hope that it motivates programmers to pass code along to QA only after it is free of cosmetic bugs.

Our team held a meeting to discuss the items on this list. I was surprised that there was little agreement about any items, even items I thought would be non-controversial such as sorting listboxes alphabetically by default. I only led the discussion, I did not try to dictate or persuade, and in the end, after much arguing back and forth, most our of programmers did come to accept most of the items on the list as best practices. I provide our list as a starting point.  I realize that this list is very similar to coding standards, but by phrasing it as a pledge, I hope to increase the adoption of these tenets.
Expectations from developer (I pledge to):  (This is a pledge a programmer makes to QA because these are not the kind of “bugs” that QA should need to waste time on testing and tracking).

Some people consider programmer pledges to be very similar to coding standards. They are.  But the purpose of creating this as a pledge is to encourage the desired behaviors using a different tactic.  To encourage people to work overtime we can either threaten discipline, or reward them.  Likewise, to encourage well-written code we can document coding standards, or ask developers to consider a pledge.  Personally, I don't think this pledge should be signed, or agreed to in person.  I simply think it should be a list of items that any programmer, in your development environment, would agree to for personal reasons.  A programmer that does not adhere to the coding by the rules in the pledge is basically admitting that they are not very good at programming.

I believe each development team should create lists specific to their environment; and that each development team should devote an hour or two to discussing all the ideas on the list relevant to their environment.