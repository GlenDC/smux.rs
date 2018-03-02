# smux.rs

Smux ( **S**imple **MU**ltiple**X**ing) is a multiplexing library for Rust. It relies on an underlying connection to provide reliability and ordering, such as TCP or KCP, and provides stream-oriented multiplexing.

This library is a port of the original SMUX library, written in Golang, and which can be found at [github.com/xtaci/smux](https://github.com/xtaci/smux).

The original intention of this library is to power the connection management for [rs-rivine](https://github.com/GlenDC/rs-rivine).
