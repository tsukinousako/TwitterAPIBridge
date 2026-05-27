# Compatiblity
At present moment, we have only recreated the v1 api, which spans from 2006-2012. Out of this span, only 2010 to 2012 works due to basic authentication

Twitter API v2 is unlikely to be fixed in the future.

## Key
 Key| Meaning |
|---| ------- |
| ⭐ | Actively testing on |
| ✅ | Works |
| ❓ | Untested
| ⚠️ | Partly works (only use this for features which aren't implemented on a specific platform) |
| ❌ | Doesn't work |
| 💾 | Lost |
| 🔒 | Won't Fix |

## iOS

### Twitter for iOS (offical)

⭐✅: 3.3.6, Mostly works

✅: 4.0.1, Near Perfect

⭐✅: 4.1.3, Near perfect. Tweeting with media attached requires the BlueTweety tweak, Retweets made by you fail to appear properly on timeline, pagination broken on some minor elements.

⭐✅: 5.0.0-5.0.3, 5.0.2+ has the aspect ratio change implemented for the iPhone 5. Note: Long URLs break retrieving parent tweets

❌: 5.0.4+ Uses Twitter API v1.1

### Twitter iOS Integration

✅: iOS 5-7, Works through Bluetweety

❌: iOS 8+, Uses Twitter API v1.1

### Tweetie2

### Tweetie
❌: Login works, uses alternate endpoints to most things, pagination completely broken.

### Twitterific
an iOS 2 version: Same as tweetie

### Tweetbot
some ios 5 version or smth: Requires PIN auth, which is unimplemented.

## Android
⭐⚠️: 3.3.0, Partly works, Followers & following timelines do not work, Connect tab is missing follows & retweets. Crashes are common. Requires a patched apk

⚠️: 3.1.2, same as 3.3.0


## Playstation Vita
### Livetweet
⚠️: Can log in, has major (fixable) issues. Also image upload boundary sillyness. Requires the following Vita plugin: https://silica.codes/Li/LiveSky

## Windows Mobile
### HTC Peep
⚠️: 2.5.20172330, Can log in, and most common features work. Investigation on what doesn't work is underway. How to patch (coming soon): https://github.com/htc-remanila/resources