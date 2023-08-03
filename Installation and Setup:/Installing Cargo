## Installing Cargo

Cargo comes bundled with the Rust programming language. To install Rust and Cargo, follow these steps:

1. Visit the official Rust website at https://www.rust-lang.org/ and click on the "Get Started" button.
2. Follow the installation instructions for your specific operating system. Rustup, the recommended installation method, includes Cargo along with the Rust compiler.

## Using Cargo to Create and Run Rust Projects

### Creating a New Project

To create a new Rust project using Cargo, follow these steps:

1. Open a terminal or command prompt on your computer.
2. Run the following command to create a new Rust project:

```
cargo new my_project_name
```

Replace `my_project_name` with the desired name of your project. This command creates a new directory with your project's name and sets up the necessary files and folders.

3. Change into the newly created project directory using the `cd` command:

```
cd my_project_name
```

### Building and Running the Project

Once you have a Rust project set up with Cargo, you can build and run it with the following commands:

1. Build the project:

```
cargo build
```

This command compiles the project and generates the executable binary. The output will be placed in the `target/debug` directory.

2. Run the project:

```
cargo run
```

This command compiles and runs the project in one step. It is a convenient way to quickly test your code during development.

### Code Samples

Here are some simple code samples to get you started with Rust using Cargo:

1. **Hello, World!**

```rust
fn main() {
    println!("Hello, World!");
}
```

2. **Adding Two Numbers**

```rust
use std::io;

fn main() {
    println!("Enter the first number:");
    let mut input = String::new();
    io::stdin().read_line(&mut input).expect("Failed to read input");
    let num1: i32 = input.trim().parse().expect("Invalid number");

    println!("Enter the second number:");
    input.clear();
    io::stdin().read_line(&mut input).expect("Failed to read input");
    let num2: i32 = input.trim().parse().expect("Invalid number");

    let sum = num1 + num2;
    println!("Sum: {}", sum);
}
```

## Summary

Cargo is a powerful tool that simplifies the management of Rust projects, dependencies, and builds. By following these installation and usage steps, you can easily create, build, and run Rust projects with the help of Cargo. Happy coding with Rust! 🚀✨
