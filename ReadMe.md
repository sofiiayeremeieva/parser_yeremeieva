# URL Parser

A Rust library for parsing URLs from strings or files.

## Features

- Parse URLs from strings.
- Support for basic URL components such as scheme, host, port, path, query, fragment, and user information.
- Command-line interface (CLI) for parsing URLs.

## Getting Started

### Installation

Add the following dependencies to your `Cargo.toml` file:

```toml
[dependencies]
clap = "2.33.0"
thiserror = "1.0.44"
```
### Usage

To parse a URL from the command line:

`cargo run -- parse https://www.ukma.edu.ua`

For more information, run:

`cargo run -- help`