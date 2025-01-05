---
layout: default
title: New Music menu changes in 9.0
---

# New Music borwsing changes in 9.0
Release 9.0 intorduced changes to browsing your music by New Music added to your Lryion music library and offers and additional new browse menu option for viewing music that was most recently updated.  This page is intended to provide clarification about this change and answer server frequently asked questions about this change.

## What's changed in 9.0
### New Music browsing
Selecting browse by New Music will display a list of albums sorted by the actual date that the album was first scanned into your Lyrion library. Technically it is sorting on the oldest date added from the list tracks for a given album as stored in your persist.db (located in your LMS Prefs directory). Since the persist.db survives a "Clear Library and Rescan All" it is able to maintain a correct history of when music was added to your LMS library as long as you also maintain a good back up of your persit.db. If you for some reason start with a new persist.db, you will lose the history of when you music was added to Lyrion which is why you shoudl consider this an important file to back up just like you maintain good backups of all of your music files.

!!! note
        As of the latest 9.0.1 release, the first library scan for a new persist.db will populate the Date Added field for each track with the file modified timestamp. All subsequent scans will populate the Date Added with timestamp the file is being scanned. This helps new users or those who have to start with a fresh persist.db to start out with a best guess at the correct sort for New Music based on file modified timestamps.

### Recently Update Albums browsing
There is addiotnal borwsing option for Recently Updated Albums in 9.0 that will display a list of albums sorted by the file modified timestamp. This is a more accurate description for how the New Music browsing behaved prior to release 9.0. If you prefer to see a list of albums sorted by file modified date like the New Muisc browsing previous to 9.0, then you shoudl use Recently Updated Albums borwsing menu.

You can add this menu for each player via settings > Player > Additional Browse Modes.
