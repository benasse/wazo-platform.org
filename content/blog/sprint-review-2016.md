Title: Wazo Platform 20.16 Released
Date: 2020-12-01 12:00:00
Author: The Wazo Authors
Category: Wazo Platform
Tags: wazo-platform, development
Slug: release-review-2016
Status: published

Hello Wazo Platform community!

Here is a short review of the Wazo Platform 20.16 release.

## New features in this release

* **Contact Center Stats API**: In addition to queue statistics, Wazo Platform 20.16 now offers agent statistics. Those may be aggregated by hour, day or month to provide better insights.

* **Contact Center Stats API**: Queue statistics may now be retrieved according to a physical timezone, to take into account Daylight-Saving-Time changes.

## Bug fixes

* **Voicemails**: The message waiting indicator (MWI) for voicemail messages is now functional on physical phones.

## Technical features

* **Asterisk**: Asterisk has been upgraded to 17.9.0. See the [Asterisk release announcement](https://www.asterisk.org/asterisk-news/asterisk-17-9-0-now-available/)

* **Performance**: Internal workings of token creation and validation, voicemail and directory lookup API have been improved, making them significantly faster than previous versions of Wazo Plaform.

## Ongoing features

* **Contact Center Stats API**: We are working to expose all the statistics for queues and agents through REST API.

For more details about the aforementioned topics, please see the roadmap linked below.

See you at the next sprint review!

## Resources

* [Install Wazo Platform](/install)

* [Upgrade Wazo and Wazo Platform](/uc-doc/upgrade/). Be sure to read the [breaking changes](/uc-doc/upgrade/upgrade_notes#20-16)

Sources:

* [Upgrade notes](/uc-doc/upgrade/upgrade_notes#20-16)

* [Wazo Platform 20.16 Changelog](https://wazo-dev.atlassian.net/secure/ReleaseNote.jspa?projectId=10011&version=10136)

## Discussion

Comments or questions in [this forum post](https://wazo-platform.discourse.group/t/blog-wazo-platform-20-16-released).
