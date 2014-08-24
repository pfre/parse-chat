parse-chat
==========

Parse chat demo is a very simple Parse (https://www.parse.com) demo of a chat
client, based on Parse's own initial demo for a JavaScript Parse client.
Parse does not provide (at this time, August 2014) instant sync
(i.e.: WebSockets), so I resorted to use polling for the demo.
A WebSocket implementation would have been nice, but this code was written in
a single day for a Ph.D. class demo.

Before using it, you'll have to sign up for Parse at their site. Then change
the file index.html, where you find the text
> "!!!!!INSERT YOUR OWN PARSE IDS HERE!!!!!"
and update this text with your own Parse IDs.

This is mostly a very simple proof of concept, and a GitHub test for me.
Feel free to fork!
