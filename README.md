parse-chat
==========

Parse chat demo is a very simple Parse (https://www.parse.com) demo of a chat client.
Parse does not provide (at this time) instant sync (e.g.: Web Sockets), so I resorted to use polling for the demo.
A Web Socket implementation would have been nice, but this code was written in a single day.

Before using, you'll have to sign up for Parse at their site. Then change the file index.html,
where you find the text
	"!!!!!INSERT YOUR OWN PARSE IDS HERE!!!!!"
and update this text with your own Parse IDs.

This is mostly a very simple proof of concept, and a GitHut test for me. Feel free to fork!
