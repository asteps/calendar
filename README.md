Calendar for ecosystems
=======================

A collaborative calendar effort to avoid events for public of common interest to be scheduled for the same day and time.

The idea came out as a solution for Brasilia's (Brazil) startup ecosystem's problem of constant event overlay. Even though it's a small scene, sometimes attendees and organizers don't know about all the events.

## Tech ideas

Almost nothing defined yet, not even if it will be just one or two repositories.

- A simple RESTFul API specification (Swagger 2)
- The API server (PHP? NodeJS?)
- A web app, a.k.a. the landing page (Angular?)
- ~~Mobile app~~ (*for now maybe we just need a reliable calendar syncing and some responsiveness*)

## Brainstorming features

- Anyone can add events
- Taggable events
- Moderated by moderators or popular verified votes
- Import/connect to:
    + Facebook events
    + Meetup.com events
    + Meetup.com groups
    + Google Calendar
- Date/time polls (eg.: [Doodle](http://doodle.com/), [UpTo](http://upto.com/))
- Export/sync back to:
    + CalDAV
    + Exchange ActiveSync
    + iCalendar

## Dream features a.k.a. automagics

- Clone/create/update the event on Meetup and Facebook via API
- Create event's banners and a mini media kit
- Connect to social media and apps, like WhatsApp, and shares the events

## To-do

- A cool project name (*just "calendar" is too lame*, as a threat it will be "caleco" if nothing better comes out)
- Host (server) partner to the main deploy
- Choosing initial tech stuff
- Writing (steal) some collaboration guidelines and best practices

## Benchmarking

- [Doodle](http://doodle.com/)
- [UpTo](http://upto.com/)