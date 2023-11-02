# Rust Cargo Build Trunk Serve Scripts

A collection of scripts to facilitate using Cargo with Trunk to build and serve Rust projects for local testing.

## Description

This repository contains shell scripts for macOS/Linux and PowerShell scripts for Windows that automate the process of cloning a Rust project from a private repository, building it using Cargo, compiling with Trunk, and copying the resulting build's unique identifier to the clipboard for easy access.

## Getting Started

### Dependencies

- Rust and Cargo must be installed on your system. You can install them from [here](https://www.rust-lang.org/tools/install).
- Trunk must be installed. Instructions can be found [here](https://trunkrs.dev/#installation).
- For macOS/Linux: `xclip` is required for clipboard functionality.
- For Windows: PowerShell is used to run the script.

### Installing

- Clone the repository to your local machine:
```bash
git clone https://github.com/ffm5113/rust_cargo_build_trunk_serve.git
