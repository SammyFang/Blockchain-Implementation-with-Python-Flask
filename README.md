# ⛓️ Blockchain Implementation with Python & Flask

## 📌 Project Overview  
This repository provides a **lightweight blockchain implementation** using **Python** and **Flask**. It includes a simple **Proof-of-Work (PoW) algorithm**, block mining, and a basic **REST API** for blockchain interaction. This project demonstrates core blockchain principles, such as block hashing, mining, and validation.

## Run the Blockchain API
Start the Flask server to interact with the blockchain:
```bash
python 002.py
```
Once the server is running, you can use the following endpoints:
```bash
GET /mine_block → Mines a new block
GET /get_chain → Retrieves the blockchain
```
## Run the Standalone Blockchain
For local testing without an API, execute:

```bash
python 001.py
```

This runs a simple blockchain that allows block creation and verification.

##  📊 API Endpoints

Method	Endpoint	Description
GET	/mine_block	Mines a new block
GET	/get_chain	Retrieves the blockchain
Test with Postman or cURL:

```bash

curl http://127.0.0.1:5000/get_chain
```
##  🔥 Future Enhancements
###### ✅ Improve Mining Algorithm - Enhance efficiency for Proof-of-Work
###### ✅ Add Transaction Support - Implement wallet and transaction handling
###### ✅ Implement Consensus Mechanism - Enable distributed validation
###### ✅ Develop Frontend Dashboard - Visualize blockchain interactions
##  🎯 Technologies Used
###### Python - Main programming language
###### Flask - API framework
###### Hashlib - Cryptographic hashing for Proof-of-Work
##  🎓 References
###### Bitcoin Whitepaper
###### Flask Documentation
###### Python Official Docs
