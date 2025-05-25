# **Blockchain Demo Project**

## **Overview**
This project implements a simple blockchain using Flask and allows users to mine new blocks, fetch the blockchain, and validate its integrity via API endpoints.

## **Installation & Setup**
### **Prerequisites**
- Python 3.x
- Flask (`pip install Flask==0.12.2`)
- Postman (Download: [https://www.postman.com/](https://www.postman.com/))

### **Installation Steps**
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Lokesh8034/blockchain-demo.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd blockchain-demo
   ```
3. **Install dependencies:**
   ```bash
   pip install Flask==0.12.2
   ```
4. **Run the Flask app:**
   ```bash
   python blockchain.py
   ```
   The server will start on **`http://127.0.0.1:5000`**.

## **Available API Endpoints**
### **1. Mine a New Block**
- **URL:** `/mine_block`
- **Method:** GET
- **Description:** Mines a new block and adds it to the blockchain.
- **Postman Execution:**
  - Open Postman.
  - Select **GET** request.
  - Enter **`http://127.0.0.1:5000/mine_block`**.
  - Click **Send**.

### **2. Get the Blockchain**
- **URL:** `/get_chain`
- **Method:** GET
- **Description:** Returns the full blockchain with all blocks.
- **Postman Execution:**
  - Select **GET** request.
  - Enter **`http://127.0.0.1:5000/get_chain`**.
  - Click **Send**.

### **3. Check Blockchain Validity**
- **URL:** `/is_valid`
- **Method:** GET
- **Description:** Validates whether the blockchain is consistent and correct.
- **Postman Execution:**
  - Select **GET** request.
  - Enter **`http://127.0.0.1:5000/is_valid`**.
  - Click **Send**.

## **Project Structure**
```
├── blockchain.py      # Main script for blockchain functionality
├── README.md          # Project documentation
└── requirements.txt   # Dependencies (Flask)
```

## **License**
This project is licensed under the **MIT License**.

## **Contributors**
- **Lokesh8034** - Blockchain Developer

---
