[![Build Status](https://travis-ci.org/rvolosatovs/systemgo.svg?branch=master&bust=1)](https://travis-ci.org/rvolosatovs/systemgo)
[![Coverage Status](https://coveralls.io/repos/github/rvolosatovs/systemgo/badge.svg?branch=master&bust=1)](https://coveralls.io/github/rvolosatovs/systemgo?branch=master)
[![Go Report Card](https://goreportcard.com/badge/github.com/rvolosatovs/systemgo)](https://goreportcard.com/report/github.com/rvolosatovs/systemgo)
[![GoDoc](https://godoc.org/github.com/rvolosatovs/systemgo?status.svg)](https://godoc.org/github.com/rvolosatovs/systemgo)
[![GSoC Project abstract](http://b.repl.ca/v1/GSoC_Project-abstract-orange.png)](https://summerofcode.withgoogle.com/archive/2016/projects/5164267334533120/)
# Description
An init system in Go, intended to run on [Browsix](https://github.com/plasma-umass/browsix) and other Unix-like OS(GNU/Linux incl.)
# Features
* Fast and concurrent
* Handles dependencies well
* [Systemd](https://github.com/Systemd/Systemd)-compatible

# Progress
- [x] Logging
- [x] Dependency resolution
    - [x] Wants
    - [x] Requires
    - [x] After
    - [x] Before
- [x] Systemctl

# Supported Systemd functionality
## Commands
- [x] start
- [x] stop
- [ ] reload
- [x] restart
- [x] status
- [x] isolate
- [x] list-units
- [x] enable
- [x] disable

## Unit types
- [ ] Service
  - [x] Simple
  - [ ] Forking
  - [x] Oneshot
- [ ] Mount
- [x] Target
- [ ] Socket
