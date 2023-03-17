# Multistream

You can use this to view 2 twitch streams at once. <br/>
<br/>

> **Note** </br>
> I do not have a way to change what channel is shown, i am currently working on that. <br/>
For now i have included instructions on how to change the streams manually
<br/>

# Change the Twitch Streams

Find line 16 and 20 in index.html  
They should look like this:  


<iframe class="stream-1" src="https://player.twitch.tv/?channel=[Channel]&parent=127.0.0.1"... <br />
<iframe class="stream-2" src="https://player.twitch.tv/?channel=[Channel]&parent=127.0.0.1"... <br />
<br />

Change "[Channel]" to whatever twitch channel you want to see <br />
This changes the stream but not the chat <br />
> **Note** </br> 
> You only need to add the streamer's name <br />
> Remove these "[ ]"


# Change the Twitch Chats

Find line 31 and 40 in index.html (same as before)
They should look like this:

src="https://www.twitch.tv/embed/[Channel]/chat?darkpopout&parent=127.0.0.1"
                                  
Change "[Channel]" to whatever twitch channel you want to see <br />
This changes the chat <br />
> **Note** </br>
> You only need to add the streamer's name <br />
> Remember to remove these "[ ]"
