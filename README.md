# Digital-Wallet

## Introduction
In the digital age, financial transactions are dominated by centralized banking systems, online payment processors, and digital wallets. While these platforms offer convenience, they compromise user privacy by storing and tracking financial data. Services like PayPal and Venmo maintain full access to transaction histories and balances, making users vulnerable to financial surveillance, data breaches, and corporate tracking. Compliance with Know Your Customer (KYC) regulations further erodes anonymity, leaving individuals with little control over their own financial information.

Our project presents a novel approach: a digital wallet that prioritizes financial privacy by ensuring that even the provider cannot access user balances. Through advanced cryptographic techniques, we enable secure authentication and transaction verification without exposing sensitive financial data. Unlike traditional digital wallets, our solution eliminates centralized tracking while maintaining strong security against fraud and unauthorized access. By bridging the gap between privacy and usability, this project empowers users with true financial autonomy in an increasingly surveilled digital world.

## Homomorphic Encryption with Paillier Cryptosystem

1. User signs up without revealing personal data.
2. Funds are encrypted and stored using the Paillier cryptosystem.
3. All operations (deposit, withdraw, check balance) are computed homomorphically.
4. Server validates actions without decrypting user data.

### Why Paillier?
- Supports addition operations on ciphertexts
- Enables privacy-preserving balance updates
- Ensures data confidentiality, even from the wallet provider

![image](https://github.com/user-attachments/assets/cf508234-9642-49b4-bdeb-36707d3ecaaa)
![image](https://github.com/user-attachments/assets/b98e0649-df86-40af-850a-dbe1fbc451e0)
![image](https://github.com/user-attachments/assets/e64943ec-3ec8-468c-b9a7-b03d82824d10)
![image](https://github.com/user-attachments/assets/b1b84ad8-5f0b-4ca7-84f3-71fc8f6cde57)

## System Architecture
![image](https://github.com/user-attachments/assets/415a1b70-da37-4909-bf7e-6e24b2ea686d)


## References
1. https://www.sciencedirect.com/topics/computer-science/paillier-cryptosystem
2. https://www.cs.tau.ac.il/~fiat/crypt07/papers/Pai99pai.pdf
