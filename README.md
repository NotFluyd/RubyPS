![RubyPS](https://raw.githubusercontent.com/NotFluyd/RubyPS/main/rubypsbanner.png)

## About RubyPS

RubyPS is a version of Cvolton's GDPS master, but to be designed more securely and run more efficently

- Secure: RubyPS includes many features to ensure your players have the best experience
- C

Among JS was designed with browser support in mind, meaning when the Hazel library supports WebSocket transports you'll be able to run Among Us bots and clients fully on the web *as well as* Node.js!

In it's current state not all packets and events are supported but I'm focusing on rapid iteration. Every current feature is fully manually tested and stable. Currently unit test coverage is low but increasing.

You can find more information about the protocol in this [freshly made wiki](https://wiki.weewoo.net/wiki/Protocol) I helped create.

They're a bit of a WIP, but feel free to [read the documentation](https://among-js-docs.vercel.app/). If you have any feedback, create a GitHub issue or shoot be a DM on Discord @Kognise#6356.

## Requirements
- Node.js 12.x or higher

## Development
    git clone https://github.com/kognise/among-js.git
    cd among-js
    yarn install && yarn dev
    node example.js (to run the example file)
