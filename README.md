# anstyle

This repo contains:

- [`anstream`](./crates/anstream) for a simple cross platform library for writing colored text to a terminal
- [`anstyle`](./crates/anstyle) for style definitions
- User-styling parsers
  - [`anstyle-git`](./crates/anstyle-git) for parsing `git` style descriptions
  - [`anstyle-ls`](./crates/anstyle-ls) for parsing `LS_COLORS` style descriptions
- Convert to other formats
  - [`anstyle-roff`](./crates/anstyle-roff) for converting ANSI codes to `ROFF`
  - [`anstyle-svg`](./crates/anstyle-svg) for converting ANSI codes to `SVG`
- Styling integration
  - [`anstyle-ansi-term`](./crates/anstyle-ansi-term) for adapting `anstyle` to `ansi_term`
  - [`anstyle-crossterm`](./crates/anstyle-crossterm) for adapting `anstyle` to `crossterm`
  - [`anstyle-owo-colors`](./crates/anstyle-owo-colors) for adapting `anstyle` to `owo-colors`
  - [`anstyle-ratatui`](./crates/anstyle-ratatui) for adapting `anstyle` to `ratatui`
  - [`anstyle-syntect`](./crates/anstyle-syntect) for adapting `anstyle` to `syntect`
  - [`anstyle-termcolor`](./crates/anstyle-termcolor) for adapting `anstyle` to `termcolor`
  - [`anstyle-yansi`](./crates/anstyle-yansi) for adapting `anstyle` to `yansi`
- Utilities
  - [`anstyle-lossy`](./crates/anstyle-lossy) for converting between color types
  - [`anstyle-parse`](./crates/anstyle-parse) for parsing ANSI Style Escapes
  - [`anstyle-wincon`](./crates/anstyle-wincon) for styling legacy Microsoft terminals
  - [`colorchoice-clap`](./crates/colorchoice-clap) for using `color` flag in `clap`
