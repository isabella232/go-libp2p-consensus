# go-libp2p-consensus

[![](https://img.shields.io/badge/made%20by-Protocol%20Labs-blue.svg?style=flat-square)](http://ipn.io)
[![](https://img.shields.io/badge/project-libp2p-yellow.svg?style=flat-square)](http://github.com/libp2p/libp2p)
[![](https://img.shields.io/badge/freenode-%23libp2p-yellow.svg?style=flat-square)](http://webchat.freenode.net/?channels=%23libp2p)
[![GoDoc](https://godoc.org/github.com/libp2p/go-libp2p-raft?status.svg)](https://godoc.org/github.com/libp2p/go-libp2p-consensus)
[![Build Status](https://travis-ci.org/libp2p/go-libp2p-consensus.svg?branch=master)](https://travis-ci.org/libp2p/go-libp2p-consensus)
[![Discourse posts](https://img.shields.io/discourse/https/discuss.libp2p.io/posts.svg)](https://discuss.libp2p.io)

> A Consensus interface for LibP2P

The LibP2P Consensus interface allows to abstract different consensus algorithms implemented for libp2p with an standarized layer so they can be swapped seamlessly.

## Table of Contents

- [Install](#install)
- [Usage](#usage)
- [Contribute](#contribute)
- [License](#license)

## Install

Simply `go-get` the module:

```
go get -u github.com/libp2p/go-libp2p-consensus
```

You can run `make deps` and `make test`, although they do very little because this module only declares some interfaces.

## Usage

In a different project just:

```
import "github.com/libp2p/go-libp2p-consensus"
```

This module is published as a GX dependency. So you can also import in GX with:

```
> gx import github.com/libp2p/go-libp2p-consensus
```

The code is documented in [godoc.org/github.com/libp2p/go-libp2p-consensus](https://godoc.org/github.com/libp2p/go-libp2p-consensus).

## Contribute

PRs accepted.

Small note: If editing the README, please conform to the [standard-readme](https://github.com/RichardLitt/standard-readme) specification.

## License

MIT © Protocol Labs, Inc.

---

The last gx published version of this module was: 0.0.3: QmZ88KbrvZMJpXaNwAGffswcYKz8EbeafzAFGMCA6MEZKt
