<h2>Rust GitHub Stargazers Fetcher</h2>
<p>This project is a simple Rust application that fetches and prints the list of stargazers for a given GitHub repository using the GitHub API. The application demonstrates how to use the reqwest and serde crates to perform HTTP requests and deserialize JSON responses.</p>

<p>Features</p>
<li>Fetches stargazers for a specified GitHub repository.</li>
<li>Utilizes asynchronous programming with tokio.</li>
<li>Demonstrates usage of reqwest for HTTP requests.</li>
<li>Demonstrates usage of serde for JSON deserialization.</li>
<br>
<p>Prerequisites</p>
<p>To run this application, you need to have the following installed:</p>

<li>Rust: Install Rust</li>
<li>Cargo: Comes with Rust installation</li>
<br>
<p>Dependencies</p>
<p>This project uses the following dependencies:</p>

<li>reqwest: HTTP client for Rust</li>
<li>serde: Serialization/deserialization library</li>
<li>tokio: Asynchronous runtime for Rust</li>

<br>
<p>You can add these dependencies to your Cargo.toml:</p>

```sh
[dependencies]
reqwest = { version = "0.11", features = ["json"] }
serde = { version = "1.0", features = ["derive"] }
tokio = { version = "1", features = ["full"] }

```
