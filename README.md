![Completion 1.0.0](https://img.shields.io/badge/completion%20v1.0.0-0%25-red) ![Help Wanted](https://img.shields.io/badge/%20-help--wanted-%23159818) ![Version 0.9.3](https://img.shields.io/badge/version-v0.9.5-blue) ![Sponsors](https://img.shields.io/badge/sponsors-0-red)

# qD Games

# Description

qD Games is a module for [qDesk](https://qDesk.org). It integrates with [qD Messages](https://github.com/QuestNetwork/qd-messages-js) and allows the users in channels or communities to play Unity and Unreal Engine built games together while using qDesk for communication.

qD Games is also a sharing platform and extended from qDesk Apps on which peers can share references to free and premium games hosted on IPFS and allows peers on the network to exchange, discuss, categorize and rate games democratically.

Use [Quest OS](https://github.com/QuestNetwork/quest-os-js) in your applications and you can use the underlying channels and data in your own application by booting with [Quest Games JS](https://github.com/QuestNetwork/quest-games-js).

qD Games offers the ability to play your favorite games with your friends on an open and non-profit social network. qD Games is a module for [qDesk](qDesk) and it's built on [Quest OS](quest-os-js) which makes use of the [Interplanetary Filesystem](https://ipfs.io), [IPFS GossipSub](https://blog.ipfs.io/2020-05-20-gossipsub-v1.1/) and [qDesk](qDesk), our example app based on [Angular10](https://angular.io/).

We have chosen Angular/Electron as an example environment because we believe it offers the best accessibility for developers coming from any other language/framework. The Quest Network is already being used in Python on PyQt5 and we aim to provide the underlying library in Go and wherever possible in Rust as well.

[qDesk](qDesk) works in the browser, as an Electron on Windows, Mac and Linux and Android using Cordova.

Check out other [Awesome Quest Network dApps](https://github.com/QuestNetwork/awesome/blob/master/README.md)!

# Features

See our [Kanban](https://github.com/orgs/QuestNetwork/projects/1) for the development of 0.9.5, feel free to add or pick up features!

qD Games is a module of [qDesk](https://github.com/QuestNetwork/qDesk), so please see https://github.com/QuestNetwork/qDesk#development for instructions.

### Commands

**Prepare Package**

``npm run inst`` Removes `package-lock.json` and runs ``npm install``

We added an example ```swarm.json``` to the ```src/app``` folder with an example node to make reproduction easier, but we strongly recommend to use our [Quest CLI](https://github.com/QuestNetwork/quest-cli) to test and build the app.

Pro Tip: Put a file in your `/bin` that runs the quest-cli like so `node /path/to/quest-cli/index.js` from any folder on your system. It's much nicer!

## Roadmap

**0.9.6**
- Basic functionality
