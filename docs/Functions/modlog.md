Modlog System!
Want to create a system that sends things to channels

## Code
```js
modlog(mtype, client, reason, options, fields)
```

## Example
```js
const { modlog } = require("discord.js");
```
```js
const reason = `reason here`;
            await interaction.reply(`done`); // this is your own code
            modlog(interaction, client, reason, {
                channel: "1234", // replace with your channel
                embed: {
                    color: "Blue",
                    // footer: "Example" to remove copyright
                }
            }, { // these all are the fields. Change. reason is not required
                Action: "Action Here",
                Mod: "E1NZ1#4616",
            })
```

## ScreenShots

![modlog](https://github.com/E1NZ1/docs-zeck.js/blob/main/docs/sam/modlog.jpg)
