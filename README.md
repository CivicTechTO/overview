<div align="center"><img width=40%
src="./images/civictechto-logo-horizontal.png" alt="Civic Tech Toronto logo"></div>

# Overview
[![Slack badge](https://civictechto-slack-invite.herokuapp.com/badge.svg)](https://civictechto-slack-invite.herokuapp.com/)

🎈 A experimental effort to coordinate meetup resources through GitHub.

## Table of Contents
- [Community Infrastructure](#community-infrastructure)
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

   [1]: https://github.com/patcon/trello-powerup-board-copier
   [2]: https://github.com/CivicTechTO/trello-pitch-board
   [3]: https://github.com/CivicTechTO/tweet-stub-helper
   [4]: https://github.com/CivicTechTO/circleci-job-runner
   [5]: https://github.com/CivicTechTO/meetup-attendance-downloader
   [6]: https://github.com/CivicTechTO/event-metadata-parser
   [7]: https://github.com/CivicTechTO/civictechto-scripts
   [8]: https://github.com/CivicTechTO/civictechto-community-toolkit
   [wp-dev]: http://dev-civictechto.pantheonsite.io/
   [wp-test]: http://test-civictechto.pantheonsite.io/
   [wp-prod]: http://civictech.ca
   [pantheon]: https://pantheon.io/features/wordpress-hosting-on-pantheon

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
