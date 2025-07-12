## LLRA: A Lightweight Leakage-Resilient Authentication Key Exchange Scheme for Smart Meters

This repository contains resources for a project developed as part of the CS 428 Design of Secure Protocols course.
The project explores a novel protocol for key exchange called **Lightweight Leakage-Resilient Authentication Key Exchange
(LLRA)** that addresses long-term private key leakage due to side-channel attacks in smart meters.

## Project Tasks
Presentation: Created a detailed presentation in LaTeX Beamer to explain the protocol's structure and its secure authentication and key generation mechanisms.
Implementation: The protocol’s security is validated through formal verification using he ProVerif tool, ensuring the reliability of its cryptographic claims.

## Paper Overview

The primary reference for this project is the paper:

https://www.researchgate.net/publication/382895727_LLRA_A_Lightweight_Leakage-Resilient_Authentication_Key_Exchange_Scheme_for_Smart_Meters

The paper introduces LLRA (Lightweight Leakage-Resilient Authentication Key Exchange), a protocol designed to secure authentication between smart meters and Neighbourhood Area Network (NAN) gateways against side-channel attacks.

## Key contributions of this paper :

LLRA is leakage-resilient, even against attacks occurring after authentication.

It is analyzed using extended BPR (CLR-eBPR) and GNY (CLR-eGNY) security models.

It shows provable security, logical soundness, and good practical performance.

Authentication delay is reduced by at least 14%, and energy consumption is reduced by at least 7%, compared to existing protocols.

## Citation 

If referencing this work, please use the following citation:

@article{article,
author = {Cheng, Ran and Yang, Yukun and Zhang, Zhengzhuo and Sun, Xiaoxin and Huang, Xin and Wu, Xiaohua and Zhao, Liangbin},
year = {2024},
month = {11},
pages = {1-1},
title = {LLRA: A Lightweight Leakage-Resilient Authentication Key Exchange Scheme for Smart Meters},
volume = {PP},
journal = {IEEE Transactions on Smart Grid},
doi = {10.1109/TSG.2024.3435548}
}
