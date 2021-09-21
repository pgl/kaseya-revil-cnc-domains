# REvil Kaseya Attack CNCs

Sorted list of command and control domains from the REvil Kaseya attack.

Sourced from the config file released here:

 * https://gist.githubusercontent.com/fwosar/a63e1249bfccb8395b961d3d780c0354/raw/312b2bbc566cbee2dac7b143dc143c1913ddb729/revil.json

This file in turn from the Huntress Reddit thread:

 * https://www.reddit.com/r/msp/comments/ocggbv/crticial_ransomware_incident_in_progress/


----

## Update 2021-09-21

Since uploading this list, several companies and organisations have been in touch requesting removal. As you can see from the commit history, I have removed any entries confirming that the domains are now clean. Some of these companies have noted that their systems had been compromised, but a very long time ago.

It's been suggested that this list is just a misdirect, to put security researchers off the track, or at least the domains  weren't used because another part of the config file appears to specify that the C2 servers weren't used at all.

I don't know for sure. I don't see why we should trust one part of the config file, but not the other, but I definitely understand the idea and am absolutely willing to bow to greater wisdom.

However, if we come across an encrypted config file with a list of domains labeled "command and control", unfortunately we can't simply ignore it. Publishing the list on GitHub was an attempt to share the threat intelligence to anyone else who might find it useful.

If anyone has any more information, please don't hesitate to get in touch - pgl@yoyo.org or https://twitter.com/pgl.
