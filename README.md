# wishlist
Some project ideas I'd work on if I had more freetime/motivation. See other `.md` files and the lists below for specs and ideas.

## Useful Software
- Regex list: a bunch of useful regex patterns + translations between them
- Preprocessor for TypeScript
- WASM linker
- Automated tool that helps you migrate your code from github to codeberg or some other git hosting platform not owned by M$
- Convert this a github repo into a website that lets people contribute their own ideas and maybe add bounties too
- JavaScript library which converts objects into graphviz dot format
- Guest list widget for website that has actual world map
- Tinder for e-dating (ie - browser extension to highlight single users on social media)
- Track server usage (similar to AWS EC2 console stats)
  + Track: load average, disk utilization, temperature, network usage, etc.
  + Integrations: send message when threshold crossed
- ipinfo.io desktop app
  + read log files
- GUI LDAP client for Linux Desktop
- federated GitHub alternative
- load average tracker+notifier
- trello/jira desktop app/alternative/self-hostable
- chrome plugin that hides posts detected as ai generated

## Useless but Interesting/fun\[ny]
- Twitter bot that qrt "btw i use arch" every time someone mentions linux or arch linux
- `diff` except it always just says the entire file changed (unless both files have same inode?)
- Shopping carts with turn signals; grocery stores with traffic signs+lights
- Program which creates animation where one plant turns into a network of plants via asexual reproduction. Inputs: list of coordinates
- digital sliderule

## Games
- Chemical factory game
- Chemistry lab simulator: construct apparatus, plan chemical reactions, perform exeperiments, etc.
  - maybe like a training simulator
- Racing game with an elo-system
- [man vs tree](https://twitter.com/caravanmalice/status/1544819658980659200)
- economic GSG: you are in control of a city-state in a small world without war
  - The goal is to conquer the world.
  - One must leverage trade surpluses and good industrial policy to win
  - When a city-state goes bankrupt its territories are auctioned to other cities.
  - Cities can sell land to neighbors to avert bankruptcy.
  - Trade agreements, restrictions, tariffs, etc.
  - Transportation infrastructure, taxes, etc.
  - Natural resources, pollution, disasters, etc.
  - banking system? population?
  - Problem: maybe un dues/starting loan slowly bankrupt afk players?
  - Problem: lots of stuff to trade irl... can't make game 100% realistic

## Maybe Hardware?
- Add reservation/scheduling system for important equiptment (could be app but more lame)
- pill calendar that doesn't need reloading
- Stoping cars from running through pedestrian crosswalks
  - Water gun to spray washable paint on cars who drive through pedestrian crossway
  - Handheld stop sign with a camera so u can send video evidence to police
- Phone which electrocutes you if you don't unlock it
- Life alert/body cams for people at risk
- qr-code watch https://x.com/hoffridder/status/1747828116804743554?s=20
- smart torpedo:
  + sub releases torpedo(es) along with position and velocity of target. 
  + sub escapes, torpedo activates, boom
- boat/sub drone for shipping

## Business/startup
- botomate - make custom bots with no-code editor?
- anti-theft for grocery stores
- Mugshots cafe: convert abandoned prison(s) into cafes. Get a take-home polarioid mugshot before and after. You can hang them on a wall if you want.
- Convert abandoned prison(s) into restaurant. Mugshot on entry, eat in cell/cafeteria.

## Done/WiP
- OS that's just conway's game of life
  - Mostly Done: https://github.com/dvtate/conway-os
- [anti-spellcheck](https://twitter.com/hoffridder/status/1362180211392065536): underlines words that are spelled correctly and gives most common mispellings
  - WiP: https://github.com/dvtate/anti-spellcheck
- github orphanage: for archived projects, also maybe open issue project asking maintainers why they archived it
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
