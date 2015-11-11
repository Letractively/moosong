One of the issues with using the rather brilliant [OpenSong](http://www.opensong.org/) is how to get non-techies to set up the services and check the songs are correct before we start on a Sunday morning.
That requires making it accessible from home and we have tried a few ways of doing it and this is the most successful for us.

Based on [MooTools](http://www.mootools.net/) and PHP this code lets you set up a site that allows you to manage OpenSong data and compose Sets/Services.

We have been using and developing MooSong since late 2008. We use it in combination with apache2 servers, ldap authentication and an SVN repository which we then update on our presentation machine (using tortoise).

It is currently very biased towards how [St Polycarp's Church Malin Bridge](http://www.stpolycarpchurch.org.uk/) use OpenSong which I'm sure is weird, but the team would be delighted to extend the code to include other churches ways of doing things.

Current features include:-
  * Drag and drop service editing.
  * Song searching
  * Service templates
  * Reading look up which finds which page in your churches bible the reading is on and puts that up on the screen.
  * Video upload
  * Youtube / Vimeo etc. integration
  * SVN integration so that a team can work on a service at the same time without edit conflict issues.
  * SVN footprint reduction (different data folders can be individual or shared so as to minimize both conflict and file system usage)
  * Fetch notices from a google calendar
  * PDF print outs of the service running order.
  * VLC DVD playback integration



Example (totally unsecured and a bit out of date, no svn or google calendar is configured)
http://stretch.deedah.org/moosong/