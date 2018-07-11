# Fortune Teller

## Setup

 1. From [your Cloud9 repositories list](https://c9.io/account/repos), set up a workspace [as usual](https://guides.firstdraft.com/starting-on-a-project-in-cloud9).
 1. Set up the project: `bin/setup`
 1. Start the web server by clicking "Run Project".
 1. Navigate to your live application preview.
 1. As you work, remember to navigate to `/git` and **commit often as you work.**
 1. Make new branches freely to experiment! _Especially_ before starting on a new task.
 1. Run `rails grade` as often as you like to see how you are doing, but **make sure you test your app manually first to make sure it matches the target's behavior first**.

## Getting Started video

You'll find a brief Getting Started video for this project in Canvas. You should still read this README thoroughly. (The video is from before we started using Cloud9, so wherever you see `localhost:3000`, instead imagine your Cloud9 Preview URL.)

## Study static routes

This app currently supports two routes: `/lucky_numbers` and `unlucky_numbers`.

Open up the [RCAV Flowchart](https://guides.firstdraft.com/rcav-flowchart.html) and use it as a map to follow how each of these two pages is working, from `config/routes.rb` through the `app/controllers` and finally to the `app/views`.

`unlucky_numbers.html.erb` even demonstrates how to do a `.each` within a `.html.erb` View Template. Ask a question about anything that you don't understand about these two fully-functional RCAVs.

## Debug static routes

I've added a list of nav links to `/zodiacs/leo`, `zodiacs/cancer`, etc.

Currently, none of them work. In `routes.rb`, you'll see that I've added 12 routes but commented them all out. Each RCAV is broken in some way.

Uncomment each one *ONE AT A TIME* and make it work.

Let me say that again:

#### Uncomment each route ONE AT A TIME and debug it

**ONE**

**AT**

**A**

**TIME**

If you uncomment them all at once, you'll have lots of problems because they all have bugs in them.

Refer frequently to the [RCAV Flowchart](https://guides.firstdraft.com/rcav-flowchart.html).

I've planted at least one bug into each RCAV.

**YOUR JOB:** Debug all 12 RCAVs.

For example, the video describes how to fix the first zodiac -- Aries.

## Submitting

`rails grade:all` when you're ready for feedback/to submit.
