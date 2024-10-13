# Dictate Keyboard (Whisper AI transcription)

[切换到中文版](./README_zh.md)

<a href='https://play.google.com/store/apps/details?id=net.devemperor.dictate'><img alt='Get it on Google Play' width="258px" height="100px" src='https://github.com/DevEmperor/Dictate/blob/d99981575350cfde1fa91d4c449d97483eda14d0/img/google-play-badge.png?raw=true'/></a>

#### Dictate is an easy-to-use keyboard for transcribing and dictating. The app uses [OpenAI Whisper](https://openai.com/index/whisper/) in the background, which supports extremely accurate results for [many different languages](https://platform.openai.com/docs/guides/speech-to-text/supported-languages) with punctuation and custom AI rewording using GPT-4 Omni. Since a picture is worth a thousand words, here is a showcase video and some screenshots:

| <a href='https://youtube.com/watch?v=F6C1hRi1PSI'><img src='https://github.com/DevEmperor/Dictate/blob/624fde1cbc8e29fdb77f334f3edfa6231d27df82/img/dictate_player.png?raw=true'/></a> | ![dictate_keyboard_notes_recording.png](https://github.com/DevEmperor/Dictate/blob/624fde1cbc8e29fdb77f334f3edfa6231d27df82/img/dictate_keyboard_notes_recording.png?raw=true) | ![dictate_settings.png](https://github.com/DevEmperor/Dictate/blob/624fde1cbc8e29fdb77f334f3edfa6231d27df82/img/dictate_settings.png?raw=true) |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| ![dictate_settings_2.png](https://github.com/DevEmperor/Dictate/blob/58fd05bad9b33a91efb51a9506f6d9bf6310ad5b/img/dictate_settings_2.png?raw=true) | ![dictate_prompts_overview.png](https://github.com/DevEmperor/Dictate/blob/624fde1cbc8e29fdb77f334f3edfa6231d27df82/img/dictate_prompts_overview.png?raw=true) | ![dictate_prompts_edit.png](https://github.com/DevEmperor/Dictate/blob/624fde1cbc8e29fdb77f334f3edfa6231d27df82/img/dictate_prompts_edit.png?raw=true) |



## Recent Changes

1. Improved network connectivity handling:
   - Added network availability check before API requests
   - Implemented retry mechanism for failed requests (max 3 attempts)
2. Enhanced error handling and user feedback:
   - Added new error messages for network issues and max retries reached
   - Improved error logging for better debugging
3. Upgraded dependencies:
   - Updated GitHub Actions workflow
   - Added OkHttp library for network requests
4. Refactored network request logic:
   - Replaced Retrofit with OkHttp for more direct control over requests
   - Improved request and response handling

## Installation

**The app is available on [Google Play](https://play.google.com/store/apps/details?id=net.devemperor.dictate)** (for a small fee to support me and the future development), so you get easy installation and free lifetime updates. Just click on the badge above or [on this link](https://play.google.com/store/apps/details?id=net.devemperor.dictate).

## License

Dictate is under the terms of the [Apache 2.0 license](https://www.apache.org/licenses/LICENSE-2.0), following all clarifications stated in the [license file](https://raw.githubusercontent.com/DevEmperor/Dictate/master/LICENSE)
