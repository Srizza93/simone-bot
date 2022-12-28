Documentation

To run

```
git clone https://github.com/Srizza93/simone-bot.git

npm install

npm run dev
```

# Please create a config.json file with the below variables:

- token
- clientId
- guildId
- adminId

Commands are deployed from deploy-commands.js and then they are executed via index.js.

# Slash Commands

- "welcome" => welcome.js => Creates a private welcome text channel and a default role which will be assigned when entering the server. Then the user can choose their new role and loose the default role via the text channel.
- "roles" => roles.js => Requests an input for the desired role and lists all the members ids of it.
- "channels" => channels.js => Requests an input for the category name and creates a category, a text and a voice channel.
- "invitations" => invitations.js => Generates a link invitation.
- "ping" => ping.js => Pings a user
