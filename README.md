# 🗳️ CodeAlpha Internship - Task 3

## 📌 Project Title: Polling Smart Contract

This project is a decentralized Polling Smart Contract developed using Solidity as part of the Blockchain Internship at CodeAlpha.

The smart contract allows users to create polls with multiple voting options, cast their votes securely, and ensures that each address can vote only once. It also applies time-based restrictions using `block.timestamp` so that voting is only allowed before the deadline.

This project demonstrates how blockchain technology can be used to build secure, transparent, and tamper-proof voting systems.

---

## 🚀 Features

✔ Create a poll with multiple options
✔ Secure voting mechanism
✔ One vote per user (prevents double voting)
✔ Time-based voting restriction
✔ Store votes using mappings
✔ Retrieve vote count for each option
✔ Determine the winning option after voting ends

---

## 🛠️ Technologies Used

* Solidity
* Remix IDE
* Ethereum Virtual Machine (Remix VM)
* GitHub

---

## 📂 Smart Contract Functions

### 1. createPoll()

Used to create a new poll by providing:

* Poll title
* Voting options
* Voting duration

### 2. vote()

Allows users to vote for one option before the deadline.

### 3. getVotes()

Returns the number of votes received by a specific option.

### 4. getWinner()

Returns the winning option after the poll duration ends.

---

## 👩‍💻 Author

Anushka Khot
Blockchain Technology Intern
CodeAlpha Internship Program
# CodeAlpha_Task3_PollingSystem
