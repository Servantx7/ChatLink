# Privacy Policy For ChatLink

This document entails the privacy policy and agreement that you accept when adding ChatLink to a server, or as a member of such a server. This document does not supersede the [Developer Terms of Service](https://discord.com/developers/docs/policies-and-agreements/terms-of-service).

<br>

## Information Collection and Use

We try our best to minimize data collection to only what is strictly necessary for the bot to function. The data we collect is tied to your Discord account, server, or channel IDs and is used solely to operate ChatLink's features. If you delete your Discord account, the data tied to that account cannot be used to identify you.

<br>

We collect and store data when you use specific ChatLink features. Those features are described below.

<br>

> **Warning**
>
> All data listed below is only stored as a result of explicit action taken by a server administrator or user. ChatLink does not collect any data passively or anonymously. Removing a feature (e.g. unlinking a channel) will delete the associated data for that feature.

<br>

+ `Cross Chat Network` : The following data is stored when a channel is linked to a cross chat network:
    + `Guild ID` : to associate the linked channel with a server
    + `Channel ID` : to identify which channel belongs to the network
    + `Network ID` : to route messages between the correct channels
    + `Message Content` : relayed in real time across linked channels; not stored persistently
    + `User ID` : used to enforce bans; stored only when a ban action is performed
    + `Username and Avatar URL` : used temporarily when sending webhook messages across the network; not stored persistently

<br>

+ `Cross Chat Ban System` : The following data is stored when a ban is applied:
    + `User ID` : stored when a user is globally or locally banned from the network
    + `Guild ID` : stored when a server is globally or locally banned

<br>

+ `Voice Bridge` : No data is stored during a voice bridge session. Audio is streamed in real time between two servers and is never recorded or saved.

<br>

## Security

We value your trust in providing us your information, and we strive to use commercially acceptable means of protecting it. However, no method of transmission over the internet or method of electronic storage is 100% secure and reliable, and we cannot guarantee its absolute security.

## Data Deletion

If you would like your data deleted, please contact us at our [support server](https://discord.gg/SdW8pBCUFM). The following applies:

+ **Bans** : User or server ban entries can be removed by a ChatLink administrator upon request.
+ **Network links** : Unlinking a channel via `/network unlink` immediately removes all stored data for that channel.

Please note that if you rejoin or relink to a network after deletion, data collection resumes as normal based on your usage.

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Changes will be effective immediately upon being posted. If you are a regular user of ChatLink, we recommend checking this Privacy Policy periodically. By using the bot, you consent to the collection, use, and transfer of your information in accordance with this Privacy Policy. If you do not agree to this Privacy Policy, please do not use the bot.

## Contact

If you have any questions or concerns about this Privacy Policy, please contact us at our [support server](https://discord.gg/SdW8pBCUFM).
