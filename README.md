# StreamDeckJS - Example StreamDeck JS Plugin

This repository contains the source code and assets for a very simple StreamDeck plugin written in JavaScript. Its purpose is to serve as an example of how the assets are structured on disk and to document the format of the manifest and main code files. This compliments the official documentation, which is rather terse regarding project structure and how to get started.

Instructions for developing StreamDeck plugins are here: https://developer.elgato.com/documentation/stream-deck/sdk/overview/

## Behavior

This StreamDeck plugin will report when its action button has been pressed and released. It uses a JavaScript timer to return to a default state after the button has been released for 1 second.

## Deployment

To test this plugin during development, copy it to the folders listed below:

* Windows: %appdata%\Elgato\StreamDeck\Plugins
* OSX: ~/Library/Application Support/com.elgato.StreamDeck/Plugins/

Official instructions are available here: https://developer.elgato.com/documentation/stream-deck/sdk/create-your-own-plugin/

## Distribution

Instructions for packaging and distribution are available here: https://developer.elgato.com/documentation/stream-deck/sdk/exporting-your-plugin/