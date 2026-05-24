# minigrep 🦀

A simple grep-like CLI tool built in Rust.

This project was made while learning Rust fundamentals such as ownership, borrowing, error handling, modules, iterators, and working with command-line arguments.

## Features

- Search for text patterns inside files
- Simple and lightweight CLI
- Case-sensitive search
- Written completely in Rust

## Installation

Clone the repository:

```bash
git clone https://github.com/siddhant-k08/minigrep.git
cd minigrep
```

Build the project:

```bash
cargo build
```

Run the project:

```bash
cargo run <query> <file>
```

Example:

```bash
cargo run frog poem.txt
```

### Example Output

```
Searching for frog
In file poem.txt
How public, like a frog
```

## Project Structure

```
src/
├── main.rs
└── lib.rs
```

## Run Tests

```
cargo test
```