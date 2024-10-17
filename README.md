# Simple Blockchain Implementation with Proof-of-Work in Python

## Overview

This project implements a basic blockchain protocol with a Proof-of-Work (PoW) consensus mechanism. The blockchain includes features such as block creation, transaction management, chain validation, and simple node networking using Flask to build a RESTful API.

## Features

- **Proof-of-Work (PoW)**: Uses a simple PoW mechanism to find valid blocks.
- **Block creation**: New blocks can be forged by solving the PoW.
- **Transaction management**: Allows creating transactions between nodes.
- **Distributed network**: Nodes can register and synchronize chains across the network using a basic consensus algorithm.
- **Flask REST API**: Provides a simple HTTP API for interacting with the blockchain.

## Requirements

- **Python 3.x**
- **Flask**
- **Requests library**

### Installing dependencies

```bash
pip install Flask requests
