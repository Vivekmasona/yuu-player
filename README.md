# [Yuu Player](https://yuu.pages.dev/)
A YouTube playlist player made with React and Tailwind

## Important features
- True shuffle
  - YouTube and YouTube Music only shuffle playlists in a range of ±200 from the current video.
- Unavailable video saving
  - The titles and channels of videos that become unavailable are saved so that the videos don't disappear without a trace.
- No ads
- Playlist progress saving
- Background playing (when screen is off)
  - iOS: Chrome
  - Android: Firefox + desktop mode

## Todo
- Improve UI in general
- See if it is necessary to patch using links with broken playlist ids

## Known bugs
- If you manually end a video while it is loading, the player may begin repeatedly skipping videos
  - This has something to do with the feature that skips unavailable videos, but I'm not sure how to fix it.
