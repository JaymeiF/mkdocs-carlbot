# Twitch

!!! info
    A number of variables are supported. 

    * **{link}** Links to the stream (you can always click the title to be brought to the stream)
    * **{name}** The streamer's display name
    * **{game}** The game they went live with
    * **{everyone}** @everyone


| Name | Example | Usage |
| :--- | :--- | :--- |
| **twitch &lt;name&gt; \[channel\] \[message\]** | !twitch azortharion #streams The best hunter in the world just went online :pogu: {link} | Adds the streamer. If no channel is specified the channel the command was used in gets used. |
| twitch list | -- | Shows all registered streamers and if they are online |
| twitch online |  | Shows all currently online streamers |
| **twitch add** | -- | Same as !twitch |
| **twitch remove &lt;name&gt;** | -- | Removes a twitch streamer. |
| **twitch move &lt;name&gt; &lt;channel&gt;** | !twitch move azortharion #cool-streamers | Moves the notification to another channel. |
| **twitch fmt &lt;name&gt; &lt;channel&gt;** | !twitch fmt azortharion THE BEST HUNTER IS ONLINE OMG | Changes the notification message. |

