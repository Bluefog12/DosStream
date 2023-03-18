# Yousuck.gg

You can use this to view 2 twitch streams at once. <br/>
<br/>

> **Note** </br>
> I do not have a way to change what channel is shown, i am currently working on that. <br/>
For now i have included instructions on how to change the streams manually
<br/>

# Change the Twitch Streams

Find line 16 and 20 in index.html  
They should look like this:  


<iframe class="stream-1" src="https://player.twitch.tv/?channel=[Channel]&parent=bluefog12.github.io"... <br />
<iframe class="stream-2" src="https://player.twitch.tv/?channel=[Channel]&parent=bluefog12.github.io"... <br />
<br />

Change "[Channel]" to whatever twitch channel you want to see <br />
This changes the stream but not the chat <br />

# Change the Twitch Chats

Find line 31 and 40 in index.html (same as before)
They should look like this:

src="https://www.twitch.tv/embed/[Channel]/chat?darkpopout&parent=bluefog12.github.io"
                                  
Change "[Channel]" to whatever twitch channel you want to see <br />
This changes the chat <br />
