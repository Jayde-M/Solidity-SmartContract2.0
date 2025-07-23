# Kayak Rental Smart Contract

This project is a blockchain-based kayak rental system built using Solidity. It was developed in collaboration with a teammate as part of a university course focused on cryptocurrency and blockchain development.

The smart contract manages availability, booking, and payments for kayak rentals, demonstrating core concepts of decentralized applications on the Ethereum blockchain.

---

## Overview

The contract allows a seller to:
- Set a daily rental rate.
- Mark a kayak as available.
- Allow customers to book the kayak and pay in Ether.

It uses modifiers to restrict access to certain functions and logs key interactions through events.

---

## Features

- **Access Control** using modifiers (`onlyOwner`, `onlySeller`)
- **Event Logging** via `Log()` event
- **Secure Ether Transfers** using `call`
- **Dynamic Pricing** with `updateRate()`
- **Availability Management** with `makeKayakAvailable()`

---

## Technologies Used

- **Solidity (v0.8.x)**
- **Visual Studio Code**
- **Node.js + NPM** 
- **Remix IDE** (optional for testing/debugging)

---

## How to Run (Remix IDE)

1. Copy the contents of `KayakRental.sol` into [Remix](https://remix.ethereum.org).
2. Select Solidity compiler `0.8.x`.
3. Compile and deploy using the JavaScript VM.
4. Use the deployed contract interface to:
   - Update rental rate
   - Mark kayak availability
   - Book the kayak using Ether

---

## License

[GNU GPL v3](https://www.gnu.org/licenses/gpl-3.0.en.html)

---

## Authors

- **Jayde Magee**  
- **Avrie White**

Developed as part of a hands-on course to explore real-world smart contract functionality using Ethereum-based tools.
