# 🔐 Cryptography Algorithms

<div align="center">

<br/>

[![Version](https://img.shields.io/badge/version-4.2.0-0A2463?style=for-the-badge&logo=semanticrelease&logoColor=white)](https://github.com)
[![Python](https://img.shields.io/badge/Python-3.11+-1E3A8A?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![License](https://img.shields.io/badge/license-MIT-3E92CC?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](LICENSE)
[![Algorithms](https://img.shields.io/badge/algorithms-25%2B-4CC9F0?style=for-the-badge&logo=letsencrypt&logoColor=white)](https://github.com)

<br/>

### 🧠 A comprehensive library of classic & modern cryptography algorithms — implemented, explained & tested

*🔑 Symmetric • 🔐 Asymmetric • ✍️ Signatures • #️⃣ Hashing • 🧪 Fully Tested*

<br/>

<a href="https://share.google/vyf4I6C7PWRSZvOCe">
  <img src="https://img.shields.io/badge/📥_GET_CODE-0A2463?style=for-the-badge&logo=github&logoColor=white&labelColor=071A48" alt="Get Code" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/vyf4I6C7PWRSZvOCe">
  <img src="https://img.shields.io/badge/🚀_TRY_DEMOS-1E3A8A?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=152A63" alt="Try Demos" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/vyf4I6C7PWRSZvOCe">
  <img src="https://img.shields.io/badge/📚_DOCS-3E92CC?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=2E6D99" alt="Docs" height="45"/>
</a>

</div>

<img width="900" height="500" alt="Algorithms-and-Cryptography1" src="https://github.com/user-attachments/assets/8f9fe5f4-3c5a-4fd9-8626-bb0b12c5a38c" />


<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🌟 About

**Cryptography Algorithms** is a **well-organized, educational codebase** that implements 25+ classical and modern cryptographic algorithms — from Caesar and Vigenère to RSA, ECC, AES, ChaCha20, and post-quantum primitives.

Every algorithm ships with a clean implementation, unit tests based on official test vectors, and a plain-English explanation of how it works. It's a **learning resource**, a **reference implementation**, and a **playground** — all in one repo.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 What's Covered

<div align="center">

| 🔑 **Symmetric** | 🔐 **Asymmetric** | ✍️ **Signatures** |
|:---:|:---:|:---:|
| AES, ChaCha20,<br/>DES, Blowfish | RSA, ECC (secp256k1),<br/>ElGamal, DH | ECDSA, EdDSA,<br/>RSA-PSS |

| #️⃣ **Hashing** | 🕰️ **Classical** | 🌌 **Post-Quantum** |
|:---:|:---:|:---:|
| SHA-2, SHA-3,<br/>BLAKE2, Argon2 | Caesar, Vigenère,<br/>Enigma, One-Time Pad | Kyber (KEM),<br/>Dilithium basics |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🏆 Why This Repo

<div align="center">

| 💎 **Advantage** | 📝 **Description** |
|:---|:---|
| ✅ **Test-Vector Verified** | Every algorithm is tested against NIST / RFC published test vectors |
| 📖 **Explained Clearly** | Each file starts with a plain-English explanation of the math and use case |
| 🧩 **Modular Design** | Each algorithm is independent — copy one file and it just works |
| 🎓 **Educational Focus** | Ideal for crypto courses, security students, and curious engineers |
| 🔍 **Consistent API** | Same `encrypt`/`decrypt`/`sign`/`verify` interface across all algorithms |
| 🧪 **Fully Tested** | 1,000+ unit tests and property-based tests guarantee correctness |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎬 Repo Preview

<div align="center">

```ascii
╔══════════════════════════════════════════════════╗
║  🔐  Cryptography Algorithms  v4.2.0             ║
╠══════════════════════════════════════════════════╣
║  📂 symmetric/                                   ║
║    ├ aes.py               ✅ 128/192/256         ║
║    ├ chacha20.py          ✅ RFC 7539            ║
║    └ blowfish.py          ✅ Schneier vectors    ║
║                                                  ║
║  📂 asymmetric/                                  ║
║    ├ rsa.py               ✅ PKCS#1              ║
║    ├ ecc.py               ✅ secp256k1           ║
║    └ elgamal.py           ✅ FIPS 186            ║
║                                                  ║
║  📂 signatures/                                  ║
║    ├ ecdsa.py             ✅ RFC 6979            ║
║    └ ed25519.py           ✅ RFC 8032            ║
║                                                  ║
║  📂 hashing/  📂 classical/  📂 post-quantum/    ║
║                                                  ║
║  ✅ 1,248 tests passed   📖 25+ algorithms       ║
╚══════════════════════════════════════════════════╝
```

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧩 Project Structure

```
🔐 cryptography-algorithms/
├── 🎯 src/
│   ├── symmetric/             # AES, ChaCha20, DES, Blowfish
│   ├── asymmetric/            # RSA, ECC, ElGamal, DH
│   ├── signatures/            # ECDSA, EdDSA, RSA-PSS
│   ├── hashing/               # SHA-2, SHA-3, BLAKE2, Argon2
│   ├── classical/             # Caesar, Vigenère, Enigma, OTP
│   ├── post-quantum/          # Kyber, Dilithium (basics)
│   └── utils/                 # Padding, encoding, helpers
├── 🧪 tests/                  # NIST & RFC test vectors
├── 📖 docs/                   # Per-algorithm explanations
└── 🎓 examples/               # Usage snippets per algorithm
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🛠️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![PyCryptodome](https://img.shields.io/badge/PyCryptodome-0A2463?style=for-the-badge&logo=letsencrypt&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🤝 Community

Found a bug? Want to add a new algorithm or scheme?

<div align="center">

<a href="https://share.google/vyf4I6C7PWRSZvOCe">
  <img src="https://img.shields.io/badge/💬_Join_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" height="35"/>
</a>
<a href="https://share.google/vyf4I6C7PWRSZvOCe">
  <img src="https://img.shields.io/badge/🐞_Report_Issue-0A2463?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>
<a href="https://share.google/vyf4I6C7PWRSZvOCe">
  <img src="https://img.shields.io/badge/⭐_Star_Repo-4CC9F0?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.


<br/>

<div align="center">

### 🔐 Made with 🧠 by the Cryptography Algorithms Team

*If this repo helped you understand crypto — star it!*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,19,11&height=120&section=footer" width="100%"/>

</div>
