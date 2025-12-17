# wishlist
Some project ideas I'd work on if I had more freetime/motivation. See other `.md` files and the lists below for specs and ideas.

## Useful Software
- Crowdsourced Logistics App: help get things from point A to where it needs to go
  - use case: recyclables/e-waste - list e-waste/recyclables on the app, someone picks it up, and uses/sells it
  - use case: [CBCM](https://birdmonitors.net) - list bird on app, someone comes to rescue it and/or take it to rehabber
- Google Maps app for Linux that works on Linux phones
- Automated tool that helps you migrate your code from github to codeberg or some other git hosting platform not owned by M$
- Tinder for e-dating (ie - browser extension to highlight single users on social media)
- Federated GitHub alternative
- Trello/jira desktop app/alternative/self-hostable
- [researchinenglish.com](https://researchinenglish.com) browser plugin
- Arch Wiki command line version
- Graph IR: Rewrite Postfix-Haskell IR to be more generic

## Languages, Devtools, APIs, etc.
- Preprocessor for TypeScript
- WASM linker
- GUI LDAP client for Linux Desktop
- Universal CI/CD platform language
  - can run on top of other CI/CD platforms, locally, or self-hosted
  - translate to/from other CI/CD platforms
- [RFC 6265](https://datatracker.ietf.org/doc/html/rfc6265) compliant C++ cookie jar library
- live subtitles for livestreams api
- JavaScript library which converts objects into graphviz dot format
- Guest list widget for website that has actual world map
- TZ database API
- Procedurally generated form based on spec that validates inputs and outputs JSON.
- Android app that runs scripts with access to phone hardware, network, etc. [alternative to to raspberry pi/esp32](https://x.com/i/status/1931937088955351270)

## Useless but Interesting/fun\[ny]
- `diff` except it always just says the entire file changed (unless both files have same inode?)
- Shopping carts with turn signals; grocery stores with traffic signs+lights
- Program which creates animation where one plant turns into a network of plants via asexual reproduction. Inputs: list of coordinates
- digital sliderule
- Phone which electrocutes you if you don't unlock it
- [qr-code watch](https://x.com/hoffridder/status/1747828116804743554): generate text qr code for current time

## Games
- Chemical factory game
- Chemistry lab simulator: construct apparatus, plan chemical reactions, perform exeperiments, etc.
  - maybe like a training simulator
- Racing game with an elo-system
- [man vs tree](https://twitter.com/caravanmalice/status/1544819658980659200)
- trade wargame: you are in control of a country in a small world without war. Your goal is to conquer the world.
- memecoin simulator game:
  - everyone starts with fixed amount of in-game currency
  - "invest" in memecoins and pull out before rug-poll
  - spend in-game currency to create your own memecoins

## Hardware?
- Add reservation/scheduling system for shared equiptment/rooms (could be app but more lame)
  - Hardware:
    - IoT device with screen that lets you make a reservation
    - QR Code for reservation calendar event
    - Check in if not being used
  - Software:
    - tracks utiliation (equiptment owner may care about RoI)
    - notification email/text for reservations, integration with calendar app?
- Stoping cars from running through pedestrian crosswalks
  - Handheld stop sign with a camera so u can send video evidence to police
- Boat/sub drone for shipping
- Drone that can drill through walls and insert things into the hole
- Drone that follows cars, attaches to them with a strong magnet then shoots arresting net

## Business/startup
- Botomate - make custom bots (ie - Discord) with a no-code editor?
- Anti-theft for grocery stores
- Mugshots cafe: convert abandoned prison(s) into cafes. Get a take-home polarioid mugshot before and after. You can hang them on a wall if you want.

## Website
- Regex list: a bunch of useful regex patterns + translations between them
- Convert this a github repo into a website that lets people contribute their own ideas and maybe add bounties too
- [povray](https://www.povray.org/) online ide

---

## Done/WiP
- Federation protocol and platform
  - WiP: https://github.com/dvtate/fediy
- OS that's just conway's game of life
  - MVP: https://github.com/dvtate/conway-os
- [anti-spellcheck](https://twitter.com/hoffridder/status/1362180211392065536): underlines words that are spelled correctly and gives most common mispellings
  - WiP: https://github.com/dvtate/anti-spellcheck
- Git orphanage: for archived projects, also maybe open issue project asking maintainers why they archived it
  - WiP: private, hmu if interested
- Use AI to convert research papers into news articles
  - https://researchinenglish.com
- Subdomain url shortener that works with CNAME rules
  - https://xtie.net

## Shot down
- Twitter archive media extractor
  - seems that twitter does this automatically now... only improvement would be to reconstitute metadata or better UI/API
- self-hostable version of [gemfury.com](https://gemfury.com)
  - viable alternative: just use a VPN
- Self-hosted alternative to Google photos
  - currently using nextcloud and reasonably happy with it.
- Translate code comments to English (ie - vscode translator extension)
  - a bunch of solutions already ^_^: https://marketplace.visualstudio.com/items?itemName=NguynThunTan.CommentTranslator , https://github.com/intellism/vscode-comment-translate/blob/master/doc/README.md
- WebRTC IPC
  - The WebRTC spec is so incredibly cursed that at this point I'd just recommend that people use [peerjs](https://github.com/peers/peerjs) or don't.
- Chrome/firefox console for node.js so you can inspect complex objects
  - Saw this somewhere already, not super important for me rn
- Use ChatGPT, speech recognition and TTS to wait and interact with customer service on your behalf
  - Google bard is doing this now it seems
- GitHub but for CC media. Like Wikimedia but searchable.
  - https://openverse.org/
- Microsoft excel but with a better way to extend functionality
  - 1st party Python in Excel will def get more traction
- web server middleware that blocks/redirects traffic based on IP address (block big tech, public clouds, etc.)
  + probably could just use cloudflare
- chrome plugin that hides posts detected as ai generated
  + detection doesn't work
- Twitter bot that qrt "btw i use arch" every time someone mentions linux or arch linux
  + elon took the fun out of twitter api
- Pill calendar/dispenser that doesn't need reloading and prevents missed/double doses
  + many pre-existing products
- Personal body cam, press button to upload past XX mins + start live streaming
  + I've seen like 12 companies do this concept and it's always flopped
  + Better to make an app for smart glasses some other wearable hardware
