# Help #

This area will expand over time. At the moment it is piecemeal but will improve.

## VLC / DVD integration ##
You will need to download and install [statusjs.xml](http://code.google.com/p/moosong/downloads/detail?name=statusjs.xml&can=2&q=) from the downloads area.

This provides JSONP output for VLC via its HTTP interface.

This allows moosong to get DVD clip data from your local running copy of VLC.

Drop the attached file into /usr/share/vlc/http/requests or the equivalent before you start VLC.

Turn on the http interface in the preferences.

Restart vlc at this point to make sure the preference sticks.

Then open the DVD you want to play in VLC and get to where you want to play pause and then hit the "Get Start Position from VLC".

If you want to play 1 or more whole chapters select how many.

If you want to play to a particular time play the DVD in VLC until you are there and pause.

Then hit the 'Get from VLC' button next to the end time inputs.