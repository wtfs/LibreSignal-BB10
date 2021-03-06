# Do not use if you can run [MicroG](https://microg.org/)

# LibreSignal for BlackBerry 10 OS

`LibreSignal` was the **Google-Free** fork of the original `Signal` messaging app for simple private communication with friends. `LibreSignal` uses your phone's data connection (WiFi/3G/4G) to communicate securely, optionally supports plain SMS/MMS to function as a unified messenger, and can also encrypt the stored messages on your phone. The project was abandoned because of https://github.com/LibreSignal/LibreSignal/issues/37#issuecomment-217211165

`LibreSignal-BB10` is a fork of `Signal` and `LibreSignal` to provide working version of Signal for Blackberry 10 OS. BlackBerry 10 features an Android runtime to run Android applications, but unfortunately no Google Services. Therefore WebSockets is required to use Signal on BlackBerry 10.
This project will stop the moment WhisperSystems publishes an official Signal-Version compatible with Blackberry 10.

# WebSocket Support
For push notifications, Google Cloud Messaging has been completely replaced by WebSocket to directly connect to Open Whisper Systems's server.
It's done via a modified version of `libtextsecure`, which has been included as a submodule.

## Contributing Bug reports
We use GitHub for bug tracking. Please search the [existing issues](https://github.com/LibreSignal/LibreSignal/issues) for your bug and create a new one if yours is not present.

## Contributing Translations
Interested in helping to translate LibreSignal? Contribute here:

https://www.transifex.com/projects/p/signal-android/

## Contributing Code
Before contributing to LibreSignal, think about adding your code to [Signal-Android](https://github.com/WhisperSystems/Signal-Android/wiki), as we pull from there. Instructions on how to setup your development environment and build LibreSignal can be found in  [BUILDING.md](https://github.com/LibreSignal/LibreSignal/blob/master/BUILDING.md). If you're new to the LibreSignal codebase, we recommend going through our issues and picking out a simple bug to fix (check the "easy" label in our issues) in order to get yourself familiar. Also please have a look at the [CONTRIBUTING.md](https://github.com/LibreSignal/LibreSignal/blob/master/CONTRIBUTING.md), that might answer some questions.

## Contributing Ideas
Have something you want to say about LibreSignal or want to be part of the conversation? Feel invited to [post your new idea](https://github.com/LibreSignal/LibreSignal/issues/new), but please be patient for a reply and don't be mad should developers decide to not implement it or are busy with other things.

Help
====
## Support
For troubleshooting and questions, please read our [FAQ](https://github.com/LibreSignal/LibreSignal/wiki/FAQ) and see our [GitHub Issues](https://github.com/LibreSignal/LibreSignal/issues)!

## Documentation
Looking for documentation? Check out the [original Signal wiki](https://github.com/WhisperSystems/Signal-Android/wiki).

# Legal things
## Cryptography Notice

This distribution includes cryptographic software. The country in which you currently reside may have restrictions on the import, possession, use, and/or re-export to another country, of encryption software.
BEFORE using any encryption software, please check your country's laws, regulations and policies concerning the import, possession, or use, and re-export of encryption software, to see if this is permitted.
See <http://www.wassenaar.org/> for more information.

## License

Licensed under the GPLv3: http://www.gnu.org/licenses/gpl-3.0.html
