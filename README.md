# Jekyll Conference Talk

Using the conference-talk hypermedia type to format your conference sessions and proposals? Want an easy way to create a page on your Jekyll blog to expose this data? Then you're in the right place! 

## Conference Talk Hypermedia

See: https://github.com/darrelmiller/conference-talk/blob/master/conference-talk.md

## Getting Started

Make sure you have jekyll installed (`gem install jekyll`), and clone this repo.

Add your conference-talk json file to the `_data` directory as `conference_talk.json`. 

Start the server by running `jekyll serve`. On the homepage, you'll see a link in the header called "Conference Talk", and when you click that, you'll see your sessions!

If you want to customize the HTML, you can edit it in `conference_talk.html`.

The top-level "presenter" object in your conference-talk.json file should be you, and if one of your sessions has other presenters, add them in the "presenters" array for that session.