# Fortune Teller

## Setup

 1. Ensure that you've forked this repo to your own GitHub account.
 1. Set up [a Cloud9 workspace as usual](https://guides.firstdraft.com/getting-started-with-cloud-9.html) based on this repo.
 1. `bin/setup`
 1. Run Project
 1. Navigate to the live app in Chrome.

## Getting Started video

You'll find a brief Getting Started video for this project in Canvas. You should still read this README thoroughly.

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

Use the [Continuous Integration workflow](https://guides.firstdraft.com/continuous-integration.html) to save and submit.
