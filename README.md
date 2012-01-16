Ideagora
=========

A place to share good ideas and connect with your fellow RailsCampers.

Done:
---------------

- user auth by email address or twitter handle (no password)
- Simple profiles for each user -- contact info, bio, and skills/interests tagging
- Simple people directory: can search / filter by words in the people directory table
- Events and Talks creation and listing
- Projects creation and viewing
- Message board for organisers to push notices
- Gravatar integration
- Thoughts and ideas (for talk proposals or requests for talks)
- Upvotes for ideas


To-Do:
---------------

- clean up the talk vs. event duplication
- def organisers_for_camp(camp) in user.rb
- user.full_name in urls - instead of id
- create a new talk: only for myself (current user)
- Allow people to attend things:
  - "Collaborate" on projects
  - "Attend" talks and events
  - "Attend" the camp (camps already have this, but could be generified to work with all content types)
- list all the people who liked a thought
- enable thoughts to be turned in to projects or events


Someday Maybe:
---------------

- mobile interface
  - perhaps a downloadable mini-webapp
- (push?) notifications for the app
- notify users who upvoted thoughts if it gets used as the basis of a talk or project
- a more asynchronous/responsive UI with next to no full page requests
- profile picture (not gravatar) with paperclip or carrierwave
- tag projects with keywords that map to skills and interests from users so we can show people projects that match their skills/interests
- collect audio/video/notes taken from talks and expose for viewing by others later (at camp or post-camp)


Credits
---------------

* Written by Elle Meredith and Gabe Hollombe
* With interface design and coding by Chris Darroch
* Additional contributions from Ganesh Shankar
