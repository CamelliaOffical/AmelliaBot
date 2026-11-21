# AmelliaBot (formerly xdnako)

![aml logo](banner.png)

# AmelliaBot

AmelliaBot is a Geometry Dash botting and macro utility. It specializes in Botting & Rendering Levels

## Compatibility

- Geometry Dash 2.2081
- Windows and Android
- Geode 5.10.0 or newer

## Features

- Super-fast rendering. If your PC supports NVENC, you’re in luck
- Native rendering on Android. Android recording no longer depends on FFmpeg libraries. It uses the phone’s native media encoder, giving a major performance boost and making 4K recording possible even on some weaker devices
- Real-time Pathfinder is in development. It won’t be available in the initial release. Support for roughly half of the game modes is already implemented, and the feature is planned for a future beta once it’s ready
- Tiny macro files. AmelliaBot stores inputs compactly: a macro that takes kilobytes in some other bots can take only bytes here
- I’m not sure what to list that other bots don’t already have, so this list is short, but these features are genuinely different

## Rendering

On Windows, rendering uses FFmpeg libraries loaded by the mod. The menu includes controls for installing and managing those libraries.

On Android, rendering uses the device's native media encoder. Available encoding options depend on the device.

**Android rendering note:** The renderer uses your phone’s native encoder. Rendering at high resolutions can make your phone very hot. If it overheats, the phone may slow down and rendering may take longer

## Installation

1. Install Geode for Geometry Dash 2.2081.
2. Download `cml.amelliabot.geode` for your platform.
3. Place the file in Geode's `mods` folder.
4. Launch Geometry Dash and open the AmelliaBot menu.

## Community

- Telegram: https://t.me/gdmacros
- Discord: https://discord.gg/GsvGnqYvaz
- GDModding: https://t.me/gdm_modding
