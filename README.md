## malgo
[![Build Status](https://github.com/companyzero/malgo/actions/workflows/build.yml/badge.svg)](https://github.com/companyzero/malgo/actions)
[![GoDoc](https://godoc.org/github.com/companyzero/malgo?status.svg)](https://godoc.org/github.com/companyzero/malgo) 
[![Go Report Card](https://goreportcard.com/badge/github.com/companyzero/malgo?branch=master)](https://goreportcard.com/report/github.com/companyzero/malgo) 
<!--[![Go Cover](http://gocover.io/_badge/github.com/companyzero/malgo)](http://gocover.io/github.com/companyzero/malgo)-->

Go bindings for [miniaudio](https://github.com/dr-soft/miniaudio) library.

Requires `cgo` but does not require linking to anything on the Windows/macOS and it links only `-ldl` on Linux/BSDs.

### Installation

    go get -u github.com/companyzero/malgo

### Documentation

Documentation on [GoDoc](https://godoc.org/github.com/companyzero/malgo). Also check [examples](https://github.com/companyzero/malgo/tree/master/_examples).

### Platforms

* Windows (WASAPI, DirectSound, WinMM)
* Linux (PulseAudio, ALSA, JACK)
* FreeBSD/NetBSD/OpenBSD (OSS/audio(4)/sndio)
* macOS/iOS (CoreAudio)
* Android (OpenSL|ES, AAudio)
