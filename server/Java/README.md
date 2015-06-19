Java Friendly Ping Server.

This Friendly Ping Server uses the [Smack XMPP library (v4.1.0)][1] to manage connections to CCS. All
messages are sent and received via CCS.

##Build
./gradlew build

In `FriendlyPingServer.java`, replace the `<SENDER_ID>` and `<API_KEY>` placeholders with the values
for your project. 

##Run
./gradlew run

[1]: https://community.igniterealtime.org/blogs/ignite/2015/03/29/smack-410-released