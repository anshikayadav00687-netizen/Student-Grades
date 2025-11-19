# Student Grades

## Project Description
The Student Grades contract provides a simple system for recording and retrieving student grades on the Stellar blockchain. It allows educators to store grade information associated with student IDs, creating an immutable record of academic performance. This contract enables transparent and verifiable grade tracking that cannot be altered once recorded. The implementation uses minimal storage to keep costs low while maintaining data integrity.

This contract revolutionizes how academic grades are recorded and verified. By storing grades on the blockchain, educational institutions can maintain permanent, tamper-proof records of student performance. Students can verify their grades, and institutions can demonstrate transparency in their grading processes. This is perfect for schools, universities, online learning platforms, or any educational institution that wants to provide verifiable academic records to students.

**Key Benefits:**
- **Immutable Records**: Grades are permanently stored and cannot be altered
- **Transparency**: Students can verify their grades on the blockchain
- **Academic Integrity**: Prevents grade tampering or manipulation
- **Verifiable Credentials**: Grades can be verified by third parties
- **Cost-Effective**: Low-cost solution for grade management
- **Long-Term Preservation**: Grades are preserved permanently

![Contract Explorer](img/contract-explorer.png)

**Contract Address:** `CDOZLDJWVOU3ITZH2VO4OL7I6KDA7DRUMZWIH4Q56ID4QTTV3I73UIVR`

**View on Stellar Expert:** [https://stellar.expert/explorer/testnet/contract/CDOZLDJWVOU3ITZH2VO4OL7I6KDA7DRUMZWIH4Q56ID4QTTV3I73UIVR](https://stellar.expert/explorer/testnet/contract/CDOZLDJWVOU3ITZH2VO4OL7I6KDA7DRUMZWIH4Q56ID4QTTV3I73UIVR)

## Features
- Simple getter function to retrieve student grades
- Simple setter function to record grades
- Basic storage model using student ID to grade mapping
- Minimal, gas-efficient logic

## Building the Contract

To build use:
```bash
stellar contract build
```

## Deploy to Testnet
Run:

```bash
stellar contract deploy \
  --wasm target/wasm32v1-none/release/project-13.wasm \
  --source-account alice \
  --network testnet \
  --alias project-13
```


