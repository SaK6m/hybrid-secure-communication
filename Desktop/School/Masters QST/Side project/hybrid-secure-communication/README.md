# Hybrid Secure Communication System 🚀🔒

This project implements a hybrid cryptographic protocol that combines:
- Post-Quantum Cryptography (PQC) for secure key exchange and authentication.
- Quantum Key Distribution (QKD) (simulated BB84 protocol) for physics-guaranteed symmetric key generation.
- Symmetric Encryption (AES-256-GCM, ChaCha20-Poly1305) for secure data transmission.

## Project Structure

- `bb84_simulation/` : Quantum Key Distribution simulation modules.
- `pqc_key_exchange/` : Post-Quantum Key Exchange and Authentication modules (Kyber, Dilithium).
- `symmetric_encryption/` : Symmetric encryption modules for message protection.
- `communication_layer/` : Client-server communication modules.
- `tests/` : Unit tests for key components.

## Technologies Used
- Python 3.10+
- Qiskit (for basic quantum simulation)
- pycryptodome
- Open Quantum Safe (liboqs-python)

## Objective
Build a future-proof secure communication channel resilient to both classical and quantum threats.

---

> **Project under active development - Phase 1: BB84 Simulation**

