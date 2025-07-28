# Chip-8 Emulator in Rust

This project is a Chip-8 emulator written in the Rust programming language. It aims to replicate the behavior of the Chip-8 virtual machine, allowing you to play classic games.

This project was developed following the excellent guide provided in the **[Chip-8 guide by aquova.net](https://aquova.net/emudev/chip8/)**.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

* **Rust:** If you don't have Rust installed, you can get it from the official Rust website: [rust-lang.org](https://www.rust-lang.org/)
* **Cargo:** Cargo is Rust's package manager and build tool, which is installed along with Rust.

### Building the Emulator

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/LuizSSampaio/chip8-emulator.git
    cd chip8-emulator
    ```

2. **Build the Emulator:**
    Use Cargo to build the project:

    ```bash
    cargo build --release
    ```

    This will compile the emulator and place the executable in the `target/release/` directory.

### Running the Emulator

To run a Chip-8 ROM, you can execute the compiled emulator with the path to your ROM file as an argument:

```bash
./target/release/chip8-emulator path/to/your/rom
```

* You can find many Chip-8 ROMs online to test with.
* The emulator will open a window displaying the Chip-8's output.

## Acknowledgments

* [aquova.net - Chip-8 Guide](https://aquova.net/emudev/chip8/): For the invaluable resource and tutorial that guided the development of this emulator.
