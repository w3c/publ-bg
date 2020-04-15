---
layout: default
---

# Information on Meetings
{: .no_toc}

* TOC
{:toc}

## Teleconferences

The weekly teleconferences are held every four weeks on Tuesdays (at the moment this corresponds to the ”even” weeks, ie, week #14, #18, etc.)  at *noon US Eastern time* (1600 UTC)  and every four weeks on Wednesdays on weeks #16, #20, etc.) at 9am Japan time (0000 UTC). See the ["noon" time zone calculator](https://www.timeanddate.com/worldclock/fixedtime.html?iso=20200428T1600) and the [9am Japan time zone calculator](https://www.timeanddate.com/worldclock/fixedtime.html?iso=20200415T0000) for the corresponding times in your time zone. See the [separate page](https://lists.w3.org/Archives/Member/internal-publishingbg/2020Apr/0000.html) for the connection information.

The Group also uses IRC for during the calls for minute taking, queue control, and general chit-chat. See the [separate page at W3C](https://www.w3.org/Project/IRC/) for further details. This Working Group uses the `#pbg` channel, and makes use of two bots on IRC:

* `zakim` for queue control (see the separate [manual pages](https://www.w3.org/2001/12/zakim-irc-bot.html) for  further details.)
* `rrsagent` for scribing and minute generation (see the separate [manual pages](https://www.w3.org/2002/03/RRSAgent) on how to control the access rights and storage of the IRC logs, and the separate [`scribejs` features](https://github.com/w3c/scribejs/blob/master/features.md) for the scribe instructions).

## Meeting Minutes

Meeting minutes are listed [separately](./Minutes/).

### Minute taking

Minutes are taken using IRC, and is based by a collective effort: one of the participants should be the scribe for (part of) a session. The `rrsagent` bot is used to archive the IRC log at the end of the call, and a separate tool (called [`scribejs`](https://github.com/w3c/scribejs/)) is used to generate the cleaned-up minutes that are published on the Business Group’s Web site.

Minute taking and cleanup is greatly helped by:

* the scribe should used a number conventions, documented [`scribejs` features](https://github.com/w3c/scribejs/blob/master/features.md) separately.
* to help minute taking and cleaning them later, please use a consistent IRC handle; scribes should use that handle to identify the person speaking. `scribejs` automatically replaces the handle with the person’s full name, making the minutes more readable to outsiders.
    * note that in most IRC clients the `TAB` key can be used to expand to an existing irc handle

* *Each participant should type `present+ <name>` (or simply `present+` for himself/herself) in the irc channel immediately upon joining the call.* (This will help the minute taker and improve the generated minutes.)

### Updating the minutes

The minutes themselves are stored, in Markdown (more exactly in “Kremdown”) on the WG’s core [github repository](https://github.com/w3c/publ-bg) in the `Meetings/Minutes/2017`, `Meetings/Minutes/2018`, etc., folders.
