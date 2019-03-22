<div align="center"><img width=40%
src="./images/civictechto-logo-horizontal.png" alt="Civic Tech Toronto logo"></div>

# Overview
[![Slack badge](https://civictechto-slack-invite.herokuapp.com/badge.svg)](https://civictechto-slack-invite.herokuapp.com/)

🎈 A experimental effort to coordinate meetup resources through GitHub.

## Table of Contents
- [Community Infrastructure](#community-infrastructure)
  - [Philosophy](#philosophy)
- [Resources](#resources)

## Community Infrastructure

Community and operations infrastructure that support both our internal
and outreach processes. We tag these repos with an [`infrastructure`
topic label][infra-topic].

   [infra-topic]: https://github.com/search?q=topic:infrastructure+org:CivicTechTO&type=Repositories

| **Legend** |
|:-----------|
| :microscope: Unofficial/Experimental |
| :pray: Self-hosted |

| | Tool Name | Description |
|---|-----------|-------------|
| :pray: | [**`hubot-toby`**](https://github.com/CivicTechTO/hubot-toby) | Custom chat bot who lives in our slack |
| :pray: | [**`civictechto-slack-invite`**](https://github.com/CivicTechTO/civictechto-slack-invite) | Small app for public Slack sign-up |
| :pray::microscope: | [**`prog-channels`**][prog-channels] | Tool to sync Slack channel list to a public Airtable |
| :pray: | [**`matterbridge-heroku`**](https://github.com/edgi-govdata-archiving/matterbridge-heroku) | Tool to help bridge chat channels between Slacks |
| :pray::microscope: | [**`civictechto-members`**](https://github.com/civictechto/civictechto-members) | Script for aggregating member stats |
| :microscope: | [**`civictech.ca-wordpress`**](https://github.com/civictechto/civictech.ca-wordpress) | [Pantheon-hosted][pantheon] Wordpress website - [dev][wp-dev] [test][wp-test] [prod][wp-prod] |
|  | [**`meetup-attendance-downloader`**][5] | Web app for venue hosts to get attendance list for next Meetup |
|  | [**`event-metadata-parser`**][6] | Small API to parse event data from links |
|  | [**`civictechto-scripts`**][7] | Code scripts for running scheduled housekeeping tasks |
|  | [**`civictechto-community-toolkit`**][8] | Web app for sharing community resources from a spreadsheet |
| :microscope: | [**`trello-pitch-board`**][2] | Proof-of-concept for a hacknight project dashboard backed by Trello |
| :microscope: | [**`trello-powerup-board-copier`**][1] | One-click copying of boards, that notifies team of action |
|  | [**`tweet-stub-helper`**][3] | Simple app for creating tweet stubs from a Google Sheet |
|  | [**`circleci-job-runner`**][4] | Simple API for running CircleCI jobs via public endpoints |
|  | [**`anki-meetup-memorizer`**][9] | Tool to create _spaced repetition_ cards ([video](https://www.youtube.com/watch?v=osK0Agqu7dc)) from Meetup events | 
|  | [**`slack-greeting-bot`**][10] | Slackbot to send a greeting message to a user who joins a channel |
| :microscope: | [**`gdrive-whats-new-app`**[11] | Small app to resolve a Google Drive folder to its newest file. |

   [1]: https://github.com/patcon/trello-powerup-board-copier
   [2]: https://github.com/CivicTechTO/trello-pitch-board
   [3]: https://github.com/CivicTechTO/tweet-stub-helper
   [4]: https://github.com/CivicTechTO/circleci-job-runner
   [5]: https://github.com/CivicTechTO/meetup-attendance-downloader
   [6]: https://github.com/CivicTechTO/event-metadata-parser
   [7]: https://github.com/CivicTechTO/civictechto-scripts
   [8]: https://github.com/CivicTechTO/civictechto-community-toolkit
   [9]: https://github.com/civictechto/anki-meetup-memorizer
   [10]: https://github.com/CivicTechTO/slack-greeting-bot
   [wp-dev]: http://dev-civictechto.pantheonsite.io/
   [wp-test]: http://test-civictechto.pantheonsite.io/
   [wp-prod]: http://civictech.ca
   [pantheon]: https://pantheon.io/features/wordpress-hosting-on-pantheon

### Philosophy

When building community infrastructure, there are several overarching
principles that we try to align with. This is an evolving list primarily
curated by @patcon, but please do contribute feedback and improvements!

1. **Use existing tools as user interfaces.** If your team widely uses a
   tool already -- Google Spreadsheets, Trello, GitHub, Slack, Meetup --
try to make that the interface. Be attentive not to force a tool that's
not already on the team's critical path. Try to choose the tool that has
the most access among organizers, and appropriate permissions. ie. If
only 5 people manage Meetup, it's perhaps best not to make it the
interface.
1. **Don't fight with humans.** Organizers should _never_ have to fight
   with an automated script. If they want to "take over", they should be able to do
so as easily as possible.
1. **Die gracefully when forgotten.** If organizers forget about the
   automation, allow them to easily go back to working with tools
directly.
1. **Be clear about a point of contact for support.** Don't assume
   people know to check Git commit history on code.
1. **Vocalize, but don't spam.** Consider announcing automated actions
   in appropriate communication channels. This is to help ensure the
organization doesn't forget that automation is taking place. Be
thoughtful to include essential details, so that messages don't come to
be seen as repetitive and pointless. eg. Don't simply announce
"New users given permissions to files" every time a script runs, but rather, add
logic to only speak up when significant changes are made, and mention
who was added. Consider making top-level channel post very short, and
hiding details in thread replies.
1. **Assume transience of organization membership.** Assume that the
   things that seem most important and front-of-mind will be forgotten
during leadership transitions.
1. **Leverage tools and spaces people already use.** If organizers are
   using Google Spreadsheets to manage work, don't unilaterally try to
introduce a new tool like Trello.
1. **Keep hardcoded assumptions and configuration out of code when
   possible.** If there's a template file that an organizer should be
able to tweak, reference it in a spreadsheet cell, rather than
hardcoded or set via environment variable. Better still, allow that template
to be a Google Document, rather than a static text file stored at a link
online.

## Resources

This is a list of resources that are available.

### Operations

* [**Service & Access Inventory.**][service-inventory] For tracking what
  services we use, and who has access to what.
* [**Google Drive folder.**][gdrive] For storing all resources related to
  operations of Civic Tech Toronto.
* [**Slack Channel List.**][channels] An auto-updated and categorized
  list of channels for curious folks who haven't yet signed up for
  Slack.
* [**Member attendance count list.**][member-list] Ethercalc spreadsheet
  updated daily from public data on Meetup.com.

<!-- Links -->

   [service-inventory]: https://hackmd.io/s/SJcySi2db
   [gdrive]: https://drive.google.com/drive/folders/0B4jGklalvuvwfjhLekdZdUZKNTN6UlVvdGNjSUZjYU50YXlCMUh5emI1SmhxNWZKU3Q2MXc
   [channels]: https://airtable.com/shrPfXyBSKIu8k49P/tbldBIVlA6XtUMtQW
   [member-list]: https://ethercalc.org/civictechto-members
   [prog-channels]: https://github.com/civictechto/prog-channels
