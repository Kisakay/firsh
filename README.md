**Firsh**

## Ferrys 's Inteligent Shell

Firsh is a simple Unix-like shell implemented in Rust, designed to provide basic shell functionality with a focus on performance, safety, and ease of use. It offers a command-line interface where users can interact with the system through various commands and utilities.

## Features

- **Command Execution**: Execute commands entered by the user.
- **Built-in Commands**: Support for basic built-in commands such as `cd`, `ls`, `echo`, etc.
- **Redirection and Piping**: Support for input/output redirection and piping of commands.
- **Tab Completion**: Basic tab completion for commands and file paths.
- **History**: Maintain a command history that can be navigated using arrow keys.
- **Vim Keybind**: Compatible with the vim keybind
- **IA Model Compability**: Use IA with llama for doing some task in the shell

## Installation

To compile and run firsh, ensure you have Rust installed on your system. Then, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/tryedandcatched/firsh.git
   ```
2. Navigate to the project directory:
   ```bash
   cd firsh
   ```
3. Compile the code:
   ```bash
   cargo build --release
   ```
4. Run the shell:
   ```bash
   ./target/release/firsh
   ```

Once the shell is running, you can start entering commands and interacting with the system.
## Contributing

Contributions to firsh are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request on the GitHub repository.

## License

This project is licensed under the Apache 2.0. See the [LICENSE](LICENSE) file for details.