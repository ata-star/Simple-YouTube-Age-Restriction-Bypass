# Simple YouTube Age Restriction Bypass
 A very simple userscript to bypass YouTube's age verification by retrieving the video info from YouTube's unrestricted ``/get_video_info`` endpoint. This allows you to watch age-restricted videos without age verification. The videos will be unlocked automatically.

## Installation
1. Install the [Violentmonkey extension](https://violentmonkey.github.io/)
2. Add "Simple-YouTube-Age-Restriction-Bypass.user.js" by clicking [this link](https://github.com/zerodytrash/Simple-YouTube-Age-Restriction-Bypass/raw/main/Simple-YouTube-Age-Restriction-Bypass.user.js).
3. Done.

## Usage
No further actions are necessary. All age restricted videos are automatically unlocked.

## Known issues
- ~~If the "Allow embedding" option is disabled by the uploader, the ``/get_video_info`` endpoint will respond with an error and the playback fails.~~ This should be fixed, but a login is required.

## Alternative mirrors
Greasyfork: https://greasyfork.org/en/scripts/423851-simple-youtube-age-restriction-bypass <br>
OpenUserJS: https://openuserjs.org/scripts/zerodytrash/Simple_YouTube_Age_Restriction_Bypass
