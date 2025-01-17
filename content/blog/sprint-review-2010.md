Title: Wazo Platform 20.10 Released
Date: 2020-07-20
Author: The Wazo Authors
Category: Wazo Platform
Tags: wazo-platform, development
Slug: release-review-2010
Status: published

Hello Wazo Platform community!

Here is a short review of the Wazo Platform 20.10 release.

## Technical features

* **Asterisk**: Asterisk was upgraded to 17.5.1. See the [Asterisk release announcement](https://www.asterisk.org/downloads/asterisk-news/asterisk-1751-now-available)
* **Multi-tenancy**: We have improved the consistency of the database for multiple tenants. User credentials will now get deleted from the database after the tenant gets deleted.

## Ongoing features

* **SIP lines and trunks**: We are currently rewriting the SIP configuration API to match PJSIP options and be multi-tenant.

For more details about the aforementioned topics, please see the changelog linked below.

See you at the next sprint review!

## Resources

* [Install Wazo Platform](/install)

* [Upgrade Wazo and Wazo Platform](/uc-doc/upgrade/). Be sure to read the [breaking changes](/uc-doc/upgrade/upgrade_notes#20-10)

Sources:

* [Upgrade notes](/uc-doc/upgrade/upgrade_notes#20-10)

* [Wazo Platform 20.10 Changelog](https://wazo-dev.atlassian.net/secure/ReleaseNote.jspa?projectId=10011&version=10111)

## Discussion

Comments or questions in [this forum post](https://wazo-platform.discourse.group/t/blog-wazo-platform-20-10-released).
