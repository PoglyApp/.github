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
    <!-- <a href="https://github.com/PoglyApp/pogly-standalone"><img src="https://img.shields.io/github/v/release/PoglyApp/pogly-standalone?color=%23ff00a0&include_prereleases&label=version&sort=semver&style=flat-square"></a>
    &nbsp; -->
    <a href="https://github.com/microsoft/TypeScript"><img src="https://img.shields.io/badge/built_with-TypeScript-2F74C0.svg?style=flat-square"></a>
    &nbsp;
    <a href="https://github.com/PoglyApp/pogly-standalone"><img src="https://img.shields.io/badge/built_with-CSharp-6C287D.svg?style=flat-square"></a>
    &nbsp;
    <a href="https://github.com/clockworklabs/spacetimedb"><img src="https://img.shields.io/badge/powered_by-SpacetimeDB-000000.svg?style=flat-square"></a>
</p>

<p align="center">
    <a href="#"><img height="25" src="https://github.com/PoglyApp/.github/blob/main/profile/images/social/discord.svg" alt="Discord"></a>
    &nbsp;
    <a href="#"><img height="25" src="https://github.com/PoglyApp/.github/blob/main/profile/images/social/twitter.svg" alt="Twitter"></a>
    &nbsp;
    <a href="https://github.com/PoglyApp/pogly-standalone"><img height="25" src="https://github.com/PoglyApp/.github/blob/main/profile/images/social/github.svg" alt="Github"></a>
    &nbsp;
    <a href="#"><img height="25" src="https://github.com/PoglyApp/.github/blob/main/profile/images/social/twitch.svg" alt="Twitch"></a>
    &nbsp;
    <a href="#"><img height="25" src="https://github.com/PoglyApp/.github/blob/main/profile/images/social/youtube.svg" alt="YouTube"></a>
    &nbsp;
    <a href="#"><img height="25" src="https://github.com/PoglyApp/.github/blob/main/profile/images/social/linkedin.svg" alt="LinkedIn"></a>
    &nbsp;
    <a href="https://stackoverflow.com/questions/tagged/poglygg"><img height="25" src="https://github.com/PoglyApp/.github/blob/main/profile/images/social/stackoverflow.svg" alt="StackOverflow"></a>
</p>

<br>

## What is [Pogly](https://pogly.gg)?

Pogly is a real-time collaborative stream overlay. Think Figma, but for your OBS overlay sources. 

With the power of Pogly, you can condense your cluttered OBS overlay sources into a single, powerful browser source. But wait, how is that like Figma? [SpacetimeDB](https://spacetimedb.com) enables Pogly to communicate in real-time with multiple users; we call them Editors.

Editors can add, edit, and delete overlay elements, with the changes being displayed in real-time while you stream. Why tab over to your OBS to update an overlay when you can have your moderators do it for you? While they're at it, perhaps they can add a fun emoji or meme to encourage chat interaction. The opportunities for creativity with Pogly are endless!

[Demo.webm](https://github.com/PoglyApp/.github/assets/36650721/b8165015-b016-448c-8ad9-9226730dfb6f)

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

Pop by our [Discord](https://discord.gg/uPQsBaVdB7) and ask some!

## What are the Standalone and Cloud versions?

Pogly *Standalone* is the open-source, self-hosted version of Pogly. We provide the code, instructions, some technical support in our Discord- but the rest is up to you.

Pogly *Cloud* is a managed offering of Pogly, where we handle the hosting, and scaling of your Pogly Standalone instance.

Cloud will be available in two flavors: a free version with a feature parity to Pogly Standalone*, and a subscription-based premium version. The premium version, in addition to having unlimited storage space, will also come with other premium features not found in Pogly Standalone, such as: advanced editor permissions, streamer-safe AI image recognition, advanced image editing features, viewer/chat integration via Pogly bot and chat commands, etc. Subject to change.

\* The free tier of Pogly Cloud will maintain feature parity with Pogly Standalone except for storage. This hasn't been fully decided and is subject to change.

## More Information

More information will be available in the Pogly Standalone repository, currently private, when we launch 1.0 🎉
