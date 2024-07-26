# CarnivalPresence

A tiny background app providing Discord Rich Presence for the LittleBigPlanet games on [Carnivalia](https://github.com/LittleBigLiberty/Carnivalia)-based servers.

[![Discord](https://img.shields.io/discord/1049223665243389953?label=Discord)](https://discord.gg/xN5yKdxmWG)

## Compatibility

CarnivalPresence is only designed for the [Carnivalia v3 API](https://github.com/LittleBigLiberty/Carnivalia), so CarnivalPresence will not work with alternative servers.

Additionally, LBP1 will only have limited rich presence.

## Running

### Legalties

> [!WARNING]
> CarnivalPresence is still early in development, as such we cannot make any guarantees about anything. You use CarnivalPresence at YOUR OWN RISK.
> CarnivalPresence is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
> See the [GNU Affero General Public License](https://github.com/LittleBigLiberty/CarnivalPresence/blob/main/LICENSE) for more details.

> [!NOTE]
> CarnivalPresence is free software: you can redistribute it and/or modify it under the terms of the [GNU Affero General Public License](https://github.com/LittleBigLiberty/CarnivalPresence/blob/main/LICENSE) as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

Anyway, with the legal disclaimers out of the way...

### Instructions

#### From Releases

1. [Find the latest release](https://github.com/LittleBigLiberty/CarnivalPresence/releases/latest)
1. Download the version for your OS/CPU, extract it somewhere most convenient to you, and run it.
1. It will open a message box asking if you want to edit the config file, press Yes, then update the `Carnival_presence_config.ini` file to contain your username and preferred settings.
1. Open CarnivalPresence once more, and it should now show your profile on Discord.

To update, you can simply repeat this process, overwriting the previous file.

## It's on fire! What do I do?

CarnivalPresence isn't perfect, so it's not exactly uncommon to run into bugs. If you'd like, you can [create an issue](https://github.com/LittleBigLiberty/CarnivalPresence/issues/new) here on GitHub or join our [Discord](https://discord.gg/xN5yKdxmWG) for support.

Wherever you choose to post, be sure to include details about how to trigger the bug, text logs (not screenshots!), your environment, the bug's symptoms, and anything else you might find relevant to the bug.

## Building & Contributing

To contribute to CarnivalPresence, it may be helpful to refer to our [contributing guide](CONTRIBUTING.md) to get a basic development environment set up. If you're a pro, feel free to skip this as it's just your bog-standard Zig set-up guide.

However, something important for all those involved: we also serve additional documentation relating to CarnivalPresence, Carnivalia, Bunkum, and LittleBigPlanet in general in our [Docs repo](https://LittleBigLiberty.github.io/Docs/).

*Made with :heart: for the LittleBigPlanet community*
