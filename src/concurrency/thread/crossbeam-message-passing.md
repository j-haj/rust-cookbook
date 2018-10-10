## Message passing with Crossbeam channels
[![crossbeam-badge]][crossbeam] [![cat-concurrency-badge]][cat-concurrency]

This example uses the [crossbeam] crate to demonstrate passing messages between
threads. A master thread spawns worker threads who send heartbeats back to the
master every second.

[`crossbeam::scope`]: https://docs.rs/crossbeam/*/crossbeam/fn.scope.html

