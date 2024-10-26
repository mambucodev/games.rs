# Games.rs

This repository is a collection of games implemented in Rust. Each game is contained within its own submodule. Currently, the repository includes the following games:

- [Wordle](https://github.com/m0squdev/wordle.rs): A command-line implementation of the popular word-guessing game.
- [Guess](https://github.com/mambucodev/guess.rs): A number guessing game.

## Setup

1. Ensure you have Rust installed on your system.
2. Clone this repository along with its submodules:
   ```sh
   git clone --recurse-submodules https://github.com/mambucodev/games.rs.git
   ```
3. Navigate to the project directory:
   ```sh
   cd games.rs
   ```

## Games

### Wordle

Wordle is a command-line implementation of the popular New York Times word game. The game challenges players to guess a five-letter word in six attempts, providing feedback using color-coded letters.

For more details, visit the [Wordle repository](https://github.com/m0squdev/wordle.rs).

### Guess

Guess is a simple number guessing game where the player tries to guess a randomly generated number within a specified range.

For more details, visit the [Guess repository](https://github.com/mambucodev/guess.rs).

## How to Play

### Wordle

1. Navigate to the `wordle.rs` directory:
   ```sh
   cd wordle.rs
   ```
2. Run the game using Cargo:
   ```sh
   cargo run
   ```

### Guess

1. Navigate to the `guess.rs` directory:
   ```sh
   cd guess.rs
   ```
2. Run the game using Cargo:
   ```sh
   cargo run
   ```

## Contributing

Feel free to contribute to this collection by adding new games or improving existing ones. Fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

Enjoy playing and developing games in Rust!
