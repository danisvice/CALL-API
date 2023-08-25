# Calling API with GET Method using Tokio, Reqwest, and Serde 🌐

In this guide, we'll dive into how you can seamlessly call an API using the GET method in Rust. We'll leverage the power of the **Tokio** asynchronous runtime, the **Reqwest** HTTP client, and the **Serde** library for working with JSON data. Let's get started! 🚀

## Prerequisites

Before you begin, ensure you have the following dependencies installed:

- [Cargo](https://doc.rust-lang.org/cargo/) (Rust's package manager)
- [Tokio](https://tokio.rs/) (Asynchronous runtime)
- [Reqwest](https://docs.rs/reqwest/) (HTTP client)
- [Serde](https://serde.rs/) (Serialization and deserialization library)

## Installation

1. Start by creating a new Rust project and navigate to its directory:
   ```
   cargo new api-call-example
  
   ```

2. Add the required dependencies to your `Cargo.toml`:

   ```toml
   [dependencies]
   tokio = { version = "0.2.3", features = ["full"] }
   reqwest = { version = "0.10", features = ["json"] }
   serde = { version = "1.0", features = ["derive"] }
   serde_json = "1.0"
   ```

   Save the file and run `cargo build` to fetch and build the dependencies.



3. Run the example using the following command:

   ```
   cargo run
   ```

   You should see the title and body of the fetched post printed in the terminal.

## Conclusion

Congratulations! You've successfully made an API call using the GET method, fetched JSON data, and deserialized it using **Tokio**, **Reqwest**, and **Serde**. This powerful combination of libraries allows you to create robust and efficient asynchronous applications that work seamlessly with APIs.

Feel free to explore more features and functionalities that these libraries offer to enhance your Rust projects.

Happy coding! 🦀🌐

---

**Disclaimer:** This example is meant for educational purposes and demonstrates the usage of Tokio, Reqwest, and Serde. Make sure to review the documentation and terms of use for the APIs you're working with.
