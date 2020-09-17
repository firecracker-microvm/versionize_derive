# versionize_derive

## Important note

This crate is currently used for cross-version serialization with the [Firecracker snapshot-restore dev preview](https://github.com/firecracker-microvm/firecracker/tree/v0.23.0), but has not been tested for other use cases. It should be considered **experimental software** outside the Firecracker context. It’s likely that this crate will see both interface and implementation changes in the future.

## Description

Exports the Versionize derive proc macro that generates the Versionize implementation for structs and enums by using annotations.
