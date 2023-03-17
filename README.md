# Multistream

you can use this to view 2 twitch streams at once, i do not have a way to change what channel is shown, i am currently working on that.
for now i have included instructions on how to change the streams manually

# change the twitch channels

find line 31 in index.html
it should look like this:

src="https://www.twitch.tv/embed/EzOsito/chat?darkpopout&parent=127.0.0.1"

change "EzOsito" to whatever twitch channel you want to see
you only need to add the streamer's name
this changes the stream but not the chat

Then

find line 40 in index.html (same as before)
it should look like this:

src="https://www.twitch.tv/embed/exositio/chat?darkpopout&parent=127.0.0.1"
