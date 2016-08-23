Ethereum Classic Network Stats
============
[![Build Status][travis-image]][travis-url] [![dependency status][dep-image]][dep-url]

This is a visual interface for tracking ethereum network status. It uses WebSockets to receive stats from running nodes and output them through an angular interface. It is the front-end implementation for [etc-net-intelligence-api](https://github.com/mikeyb/etc-net-intelligence-api).

![Screenshot](https://raw.githubusercontent.com/cubedro/eth-netstats/master/src/images/screenshot.jpg?v=0.0.6 "Screenshot")

## Prerequisite
* node
* npm

## Installation

Make sure you have node.js and npm installed.

Clone the repository and install the dependencies

```bash
git clone https://github.com/mikeyb/etcstat.us.git
cd etcstat.us
npm install
sudo npm install -g grunt-cli
```

## setup ssl

edit `app.js` with ssl certificate info

##Build the resources
etcstat.us features a full and lite version.  Read below for compilation.


To build the full version run
```bash
grunt
```

To build the lite version run
```bash
grunt lite
```

If you want to build both versions run
```bash
grunt all
```

##Run

```bash
npm start
```

see the interface at http://localhost:3000

## Attribution

Forked from https://github.com/cubedro/eth-netstats

[travis-image]: https://travis-ci.org/mikeyb/etcstat.us.svg
[travis-url]: https://travis-ci.org/mikeyb/etcstat.us
[dep-image]: https://david-dm.org/mikeyb/etcstat.us.svg
[dep-url]: https://david-dm.org/mikeyb/etcstat.us