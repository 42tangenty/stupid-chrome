# About
Some stupid facts about Google Chrome. Might help.

# Stupid Chrome
## Chrome cache persisting despite dev tools Disable Cache.
`
It's because of "Enable Local Overrides"!!!! OMG. Once upon a time, I checked this option and created a folder for it. Then Chrome Dev Tools keeps saving random files into it, and then overriding server content with locally saved outdated copies.
`
[on reddit](https://www.reddit.com/r/webdev/comments/1wm0a9/chrome_cache_persisting_despite_dev_tools_disable/)

Stupid one! I laugh out when I refreshed with the dev tool window open and saw a PERFECT page rendered while my node server was off, but it's like 40 minutes before I found the answer. When I found this comment and tested it out, another BIG RELAXING laugh. Bad words for google though.
