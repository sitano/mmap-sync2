# mmap-sync
[![License](https://img.shields.io/badge/license-Apache%202.0-blue)](LICENSE)

`mmap-sync2` is a Rust crate designed to manage high-performance, concurrent data access between a single writer process and multiple reader processes, leveraging the benefits of memory-mapped files, wait-free synchronization, and zero-copy deserialization like cloudflare/mmap-sync but without timeouts.
