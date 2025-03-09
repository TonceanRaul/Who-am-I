# Who am I?

![Who am I?](https://icp.ninja/examples/_attachments/who_am_i.png)

Who am I? demonstrates how entities on the Internet Computer are identified. Every entity, such as a user or canister smart contract, has a principal identifier. Principals can be used for identification and authentication. Who am I? uses Internet Identity (II) for user authentication, then displays the principal identifier associated with that Internet Identity on the user interface.

This variation of "Who am I" is written in [Rust](https://internetcomputer.org/docs/current/developer-docs/backend/rust/),a programming language designed specifically for developing canisters on ICP. Smart contracts on ICP are called **canisters.**

### Project structure

The `/backend` folder contains the Rust smart contract:

- `Cargo.toml`, which defines the crate that will form the backend
- `lib.rs`, which contains the actual smart contract, and exports its interface

The `/frontend` folder contains web assets for the application's user interface. The user interface is written using the React framework.

## Continue building locally

To migrate your ICP Ninja project off of the web browser and develop it locally, follow these steps.

### 1. Download your project from ICP Ninja using the 'Download files' button.

### 2. Open the `BUILD.md` file for further instructions.
