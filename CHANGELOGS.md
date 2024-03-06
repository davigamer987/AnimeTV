# Changelogs
- **2.6.0 🍬**
  - Fix history/watchlist timing reset on uncompleted rewatch
  - Fix low-res reccommendation & related thumbnails
  - Use release configuration + minify for apk - file size becoming ~8MB
  - From 2.5.9
    - Add MAL/AniList Update watch progress position settings
    - Add preload data & video for next episode
    - Fix Top Anime low res thumbnails
  - From 2.5.7
    - Fix MAL not loading player
    - Fix No-Transition not saved for next launch
  - From 2.5.6
    - Add support for more softsub languages (if content supported)
    - Change `SOFTSUB` info into `TRANSLATE` if it was translated
    - Update User-Agent
    - Make html5 video load slightly faster
    - Use popup for subtitle selection
    - Add subtitle style popup
    - Wallpaper & Interface Color popup
    - Tweak ui performance
    - Add no Transition animation settings
    - Add css will-change
  - From 2.5.5
    - Add HttpClient selection settings
    - Add cronet engine for HttpClient selection
    - Add generic HttpClient
    - Support playback speed for html5 video
    - Support video scaling for html5 video
    - Disable forcing quality for html5 video
    - Change scrollTo to scrollTop for webview compatibility with older version
    - Fix AniList & POST, PUT requests on non OkHttp client
  - From 2.5.4
    - Add `Use HTML5 Video Player` Settings for stuttering problem
    - Change button title to `Skip Outro` on 2nd skip time
    - Add loading animation on popup
    - Set solid background for Wallpaper 9
    - Preload assets & remove unused placeholder
    - Update http engine to support multiple httpclient backend
  - From 2.5.2
    - Retreive ttip from anime url if ttip unavailable
    - Fix anime url not parsed if there is no ttip
    - Re-search anime without year or season if not-found when matching MAL/AniList content
    - Optimize network loading via okhttp
    - Change domain matching by equals rather than contains to avoid static content loaded by okhttp
- **2.5.0 ✨**
  - **AniList** Integration
  - QRCode Webbased AniList & MAL authorization
  - Use okhttp for connection handler
  - Add DoH (DNS over HTTPS) for ISP that blocked source domain
  - Cleanup settings & grouping
  - Multiple choice item will show popup on settings
  - Fix watchlist & history cannot clicked
- **2.3.0 🏕️**
  - New Settings UI
  - Add progressive cache config
  - Fix MAL current episode not updated
- **2.2.0 ⚡**
  - Add font size settings
  - Add media key (play/pause) handler
  - Tweak image cache
  - Set min-sdk to sdk22
- **2.1.1 🚀**
  - Add informative - compact list view
- **2.1.0 🚀**
  - **Add japan title settings**
  - Move setting from localStorage to Android pref
  - Performance-UI as default
  - Tweak settings popup responsiveness
  - Fix cache too strict + no new update
- **2.0.0 ⭐**
  - Add new source server (check `server.json`) for better performance & without cloudflare validation
  - Add change source settings
  - Add new popup anime detail info before opening player
  - Set `SOURCE 2` as default source for better performance (for now)
- **1.8.2**
  - Fix anime may not load next episode
- **1.8.0**
  - Fix some popup glitch & episode integer
  - Add-remove watchlist & history
  - Add rating and label for adult rating
  - Popup for Resume, Play Next
  - Add button to Add and Remove from Watchlist
  - Add button to Remove from History
  - Add MAL popup menu
  - Add update watched episode for MAL watchlist
  - Add loading screen when matching MAL anime
  - Tweak MAL list fetch
  - Add discord info message from channel ⁠`animetv-info` in homescreen
  - Update homescreen-ui
  - Update episode counting on MAL list
  - Add support for Android 7 sdk24
- **1.6.0**
  - Add auto-update feature
  - Add chinese list at homelist
  - Fix hardsub unavailable (ex: gintama s1)
  - Add performance-ui
  - Add mirror stream server
  - Change main font to Fira Sans
- **1.5.6**
  - Fix change episode stuck at previous video
  - Add softsub non-translated for Arabic, German, Italian, French, Russian & Spanish (If available)
- **1.5.4-beta4**
  - Add button for available stream (soft, sub, dub)
  - Skip time always use hardsub stream
  - Tweak subtitle styling
  - Change stream don't reload content view
  - Add stream quality selection
  - Firestick support (Initial testing)
- **1.5.0**
  - Add settings panel
  - Add multilanguage closed-caption (for softsub content) - auto-translate from english with google translate
  - Remove server change configuration (unusable)
  - Add animation/transition config
  - Move settings items from playback to settings panel
  - Deactivate MP4UPLOAD server fetch for faster load
  - Add subtitle style config (8 styles)
  - Add cc info language tag
  - Fix reload hardsub-dub-softsub switch
  - Add playback speed
  - Add Wallpaper settings
  - Add include non-japan settings