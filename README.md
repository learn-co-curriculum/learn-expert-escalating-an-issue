# Escalating a Chat

![escalation](http://i.giphy.com/ToMjGpjpXMFPshSYGLm.gif)

## Types of Escalation

Sometimes as a Learn expert, you will encounter questions that are beyond your scope to answer. In these cases, you'll need to report the issue.

- Admissions
- Personal Escalation
- All other issues (Jira)

>Note: for tracks that we support, there is no longer an option for students to 'Report a Bug'. We are now in charge of reporting the bugs. This makes it so that all questions can come in through one source so that we don't get the same questions coming in through multiple sources.

## What kinds of issues should be reported?

### Admissions - Through the Assign Button

- Questions about the course and admissions
  - How long does the course take?
  - What courses do you offer?
  - Do you offer scholarships

Occasionally someone asks non-technical questions such as "How long does this course take to complete?", "Do you offer scholarships?", "Can you explain the job guarantee to me?", etc. If you feel like you know the answer, please **do not try and answer these questions**. Simply let the student know that this is a great question for our admissions team and that you're going to close this chat question and forward the question to them. Once you get confirmation from the student that this is OK, hit the Assign button and expert-chat will take care of the rest!

### Personal Escalation - Through Slack

Students get a little frustrated all the time, but if a student seems to be really disheartened, or if they mention even in passing that they might (quit | leave | stop) the course, immediately send a DM to @avidor, @kaitlin, and @peterbell in the flatiron staff slack. Paste the message that concerned you and a link to the question so we can easily get in touch and review. THIS IS REALLY IMPORTANT

If in doubt, send too many of these. If necessary we'll refine the instructions but we'd rather get too many false positives than fail to help a student who's having a hard time.

### All other issues - Through Jira

- IDE: Any issues related to the Learn IDE
  - Example: IDE is slow, user cannot login.
- Chat: Issues related to the /expert-chat, Ask A Question, DM, or Lobby features in Learn
  - Examples: Chat is totally empty, notifications not showing up for chat.
- UI: Buttons not working, problems with the site, pages 500ing.
- Account: Billing, feature access, github name change, blogs.
- Lights: Lights not turning on
- Other: Everything else not specified
  - User is having trouble [setting up local env](https://github.com/flatiron-labs/learn-support/blob/master/environment-setup.md)
  - Unable to help student solve a lab

## How to report an issue through Jira

If you are running into an issue that is beyond your ability, hit the Log Bug Report button in /expert-chat.

![log button](https://s3.amazonaws.com/learn-experts/jira-log-bug-report.png "log button")

This will bring you to Jira, where you need to press the Create button at the top of the screen.

![create issue](https://s3.amazonaws.com/learn-experts/jira-create-issue.png "Create Issue")

This will bring up a modal for you to create a ticket based on issue type.

Select the appropriate issue type and fill in all required and optional fields.

![issue modal](https://s3.amazonaws.com/learn-experts/jira-issue-modal.png "Issue Modal")

### Priority Level

There are a few different priority levels and it's important to pick the right one. Check out this spread sheet to figure out which would be the best level for you to use: https://docs.google.com/a/flatironschool.com/spreadsheets/d/1_yr-CsT0hIfSEcz9vv9yjkRGWQLeKmG40SNjywphoOc/edit?usp=sharing

Note: If this is a Blocker level issue, there are [some things](#pre-blocking-checklist) that will need to be done before submitting. Also, you will need to know if the student is a paying student or not to properly determine the priority level. Check out [this guide](#free-v-paid) to help figure this out!

#### BLOCKER

##### Things that are _NOT_ blocking

- Unable to help a student solve a lab. They can just move on to the next one for the time being.
- Student changed their github username
  - Have them change it back, log an issue as Medium and some one will schedule a time for them to make the change.

##### Pre-Blocking Checklist

As reporting blocking issues is a heavy load on our development team there are steps that must be taken before reporting _any_ blocking issue:

- [ ] Make sure you or the student (whoever is experiencing the issue) has tried fully refreshing the page
- [ ] Browse <a href="https://github.com/flatiron-labs/learn-support">the learn-support repo</a> to see if you can find a solution
- [ ] If you cannot find a solution, **SEARCH** <a href="https://github.com/flatiron-labs/learn-support">the learn-support repo</a> using key words and error messages
- [ ] If the student is having an issue in the Learn IDE, you should be able to re-create this same issue **IN YOUR OWN LEARN IDE**.
- [ ] Do an `@here` in the `#learn-experts` channel to see if any of the other learn experts can help.
- [ ] If the student can _move forward_ (just got to the next lesson for now) then this is _not_ a blocking issue and can be logged as High, Medium, or Low.


#### Free V Paid

A lot of theses escalation levels rely knowing the difference between a Free student and a Paid student. We can easily figure this out by looking at what batch the question is being asked in.

The following are the only paid batches:

- js-cert-000
- ruby-cert-000
- html-000
- v-000
- wdf-000

All other batches are Free.locking issue and can be logged as High, Medium, or Low.

## Resources

- [Escalation in Reference Guide](https://github.com/flatiron-labs/learn-support/blob/master/escalation.md)

<p class='util--hide'>View <a href='https://learn.co/lessons/learn-expert-escalating-an-issue'>Escalating an Issue</a> on Learn.co and start learning to code for free.</p>
