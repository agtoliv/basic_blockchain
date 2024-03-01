# Simple Blockchain Project

This repository contains a basic implementation of a blockchain, developed as part of my learning journey in the Blockchain Engineering course. The project is written in Python and utilizes the Flask framework for creating a simple web application to interact with the blockchain.

## Features

- Creation of new blocks with a proof-of-work algorithm.
- Verification of the integrity of the blockchain to ensure data integrity.
- Mining new blocks and adding them to the chain.
- Retrieval of the entire blockchain for inspection.

## Technologies

- Python: The core language used to implement the blockchain logic.
- Flask: A micro web framework for Python used to create a simple web API for interacting with the blockchain.
- hashlib, json, datetime: Python libraries used for cryptographic hashing, data serialization, and timestamping, respectively.

## How to Use

1. Clone the repository to your local machine.
2. Run the Flask application with `python <filename>.py`.
3. Access the provided endpoints (`/mine_block` and `/get_chain`) via a web browser or a tool like Postman to interact with the blockchain.

## Endpoints

- `GET /mine_block`: Mines a new block and adds it to the blockchain.
- `GET /get_chain`: Retrieves the current state of the blockchain, including all mined blocks.

This project serves as a foundational step into the world of blockchain technology, demonstrating basic concepts and functionalities of a blockchain system.
