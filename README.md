http-server
===========

[![Build Status][build-status-image]][build-status]

This is a simple, fast and portable HTTP server built in go.

Performance
-----------

This HTTP server is about 7x faster than [node-http-server](//github.com/nodeapps/http-server)
and about 10x faster than `python -m SimpleHTTPServer`.

Installation
------------

    go get github.com/0xcaff/http-server
    http-server

Usage
-----

Run `http-server` from the directory you would like to serve. Check out
`http-server -help` for examples.

[build-status-image]: https://travis-ci.org/0xcaff/http-server.svg?branch=master
[build-status]: https://travis-ci.org/0xcaff/http-server

