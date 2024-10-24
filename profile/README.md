<p align="center">
    <a href="https://pogly.gg#gh-dark-mode-only" target="_blank">
	<img width="128" src="https://github.com/PoglyApp/.github/blob/main/profile/images/dark/Pog.png" alt="Pogly Logo">
    </a>
    <a href="https://pogly.gg#gh-light-mode-only" target="_blank">
	<img width="128" src="https://github.com/PoglyApp/.github/blob/main/profile/images/light/Pog.png" alt="Pogly Logo">
    </a>
</p>
<p align="center">
    <h1 align="center">
        <b>Pogly</b> Standalone & Cloud
    </h1>
    <h3 align="center">
        Real-time collaborative stream overlay.
    </h3>
</p>

<p align="center">
    <a href="https://github.com/microsoft/TypeScript"><img src="https://img.shields.io/badge/built_with-TypeScript-2F74C0.svg?style=flat-square"><img src="https://img.shields.io/badge/CSharp-6C287D.svg?style=flat-square" /></a>
    &nbsp;
    <a href="https://github.com/clockworklabs/spacetimedb"><img src="https://img.shields.io/badge/powered_by-SpacetimeDB-000000.svg?style=flat-square" /></a>
    &nbsp;
	<img src="https://img.shields.io/badge/version-v0.1.1_beta-9f9f9f.svg?style=flat-square" />
    &nbsp;
    <a href="https://github.com/PoglyApp/pogly-standalone/blob/master/LICENSE"><img src="https://img.shields.io/badge/license-Apache%202.0-50C878.svg?style=flat-square" /></a>
</p>

<p align="center">
    <a href="https://discord.gg/CXCj2TGS6b"><img height="25" src="./images/social/discord.svg" alt="Discord" /></a>
    &nbsp;
    <a href="https://www.twitch.tv/poglygg"><img height="25" src="./images/social/twitch.svg" alt="Twitch" /></a>
    &nbsp;
    <a href="https://www.youtube.com/watch?v=c19tKRKa2ik"><img height="25" src="./images/social/youtube.svg" alt="YouTube" /></a>
    &nbsp;
    <a href="https://x.com/PoglyApp"><img height="25" src="./images/social/twitter.svg" alt="Twitter" /></a>
</p>

<br>

## What is [Pogly](https://pogly.gg)?

Pogly is a real-time collaborative stream overlay. Think Figma, but for your OBS overlay sources. 

With the power of Pogly, you can condense your cluttered OBS overlay sources into a single, powerful browser source. But wait, how is that like Figma? [SpacetimeDB](https://spacetimedb.com) enables Pogly to communicate in real-time with multiple users; we call them Editors.

Editors can add, edit, and delete overlay elements, with the changes being displayed in real-time while you stream. Why tab over to your OBS to update an overlay when you can have your moderators do it for you? While they're at it, perhaps they can add a fun emoji or meme to encourage chat interaction. The opportunities for creativity with Pogly are endless!

[Example.webm](https://github.com/PoglyApp/.github/assets/36650721/838f0050-ed6d-4391-9e91-76319fdffe1c)

## Features

Please click on the feature you'd like to learn more about.

- Realtime state sync between all connected clients
- Self-host or use SpacetimeDB's free test environment (Testnet)
- Canvas Elements
    - [Text Elements](https://github.com/PoglyApp/pogly-documentation/blob/main/use/textElement.md) - Text, Font, Size and Color configurable
    - [Image Elements](https://github.com/PoglyApp/pogly-documentation/blob/main/use/imageElement.md) - File upload or URL
    - [Widget Elements](https://github.com/PoglyApp/pogly-documentation/blob/main/use/widgetElement.md) - Fully customizeable HTML widget, allows for CSS and Javascript
    - 7TV Channel Emotes - Automatically pull the streamers 7TV emotes for use as an Image Element
- [Context menu](https://github.com/PoglyApp/pogly-documentation/blob/main/use/contextMenu.md) for modifying Canvas Elements
- OBS/streamlabs Browser Source overlay compatibility
- Full support for Firefox & Chromium based browsers
- Stream preview on editor canvas
- Configurable Guest nicknames
- Instance configuration
    - [Authentication](https://github.com/PoglyApp/pogly-documentation/blob/main/use/authentication.md)
    - [Refresh rate](https://github.com/PoglyApp/pogly-documentation/blob/main/use/refreshRate.md)
    - [Strict Mode](https://github.com/PoglyApp/pogly-documentation/blob/main/use/strictMode.md) - User based permissions
    - Various debug modes for developers
- Export/Import all Canvas Elements

## To be implemented soon
- In-depth Audit Log
    - Every reducer call & every state change
    - Inspect an element to see audit log for that particular element, or
    - View the general audit log to see all changes, and filter as needed
- Chat - simple in-browser chat for editors to collaborate and discuss
- Advanced permissions - currently [Strict Mode](https://github.com/PoglyApp/pogly-documentation/blob/main/use/strictMode.md) features only one permission level.
- Image compression to help with load times
- Additional element types (text effects and others)
- Direct paste image onto canvas without adding

### Planned
- tbd ^_^

If you have any questions or concerns, pop by our [Discord](https://discord.gg/uPQsBaVdB7) and ask!

## What are the Standalone and Cloud versions?

Pogly *Standalone* is the open-source, self-hosted version of Pogly. We provide the code, instructions, some technical support in our Discord- but the rest is up to you.

Pogly *Cloud* is a managed offering of Pogly, where we handle the hosting, and scaling of your Pogly Standalone instance. No decisions on how monetization of cloud have been made, or if there will be any extra features not found in standalone.

## More Information

More information will be available in the Pogly Standalone repository, currently private, when we launch 1.0 🎉
