# Solana Favorites Program

A Solana program built with Anchor that allows users to store and manage their favorite number, color, and hobbies on-chain.

## 🚀 Features

- Store a favorite number (u64)
- Store a favorite color (string, max 50 chars)
- Store hobbies (vector of strings, max 5 hobbies, each max 50 chars)
- Data is stored in a PDA (Program Derived Address) unique to each user

## 🛠️ Tech Stack

- Solana Blockchain
- Anchor Framework v0.29.0
- Rust (for program logic)
- TypeScript (for tests and client)
