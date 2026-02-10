<a href="https://lnbits.com" target="_blank" rel="noopener noreferrer">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://i.imgur.com/QE6SIrs.png">
    <img src="https://i.imgur.com/fyKPgVT.png" alt="LNbits" style="width:280px">
  </picture>
</a>

[![License: MIT](https://img.shields.io/badge/License-MIT-success?logo=open-source-initiative&logoColor=white)](./LICENSE)
[![Built for LNbits](https://img.shields.io/badge/Built%20for-LNbits-4D4DFF?logo=lightning&logoColor=white)](https://github.com/lnbits/lnbits)

<h1>Decoder extension</h1>

This is an extension to help decode invoices, lnurls and lightning addresses in [LNBits](https://lnbits.com).

## Demo (Video)

https://github.com/bitkarrot/decoder/assets/73979971/9621f31f-052b-46e4-a294-8cd5a17c8d30

## Installation

Install this extension using the manifest from this repository:

[https://raw.githubusercontent.com/bitkarrot/decoder/main/manifest.json](https://raw.githubusercontent.com/bitkarrot/decoder/main/manifest.json)

Add the above link to LNBits on the Admin Panel by Visiting: Manage Server -> Server -> Extension Sources

<img width="480" alt="Screenshot 2024-01-08 at 3 37 25 PM" src="https://github.com/bitkarrot/decoder/assets/73979971/eb782af2-e4ae-4249-8f7d-ffa809693150">

## Example Usage

### Decode a BOLT11 invoice

<img width="620" alt="Screenshot 2024-01-08 at 3 31 09 PM" src="https://github.com/bitkarrot/decoder/assets/73979971/63f8e6e4-1594-4cc8-b277-8ef60d0df1a1">

### Decode a LNURL

<img width="630" alt="Screenshot 2024-01-08 at 3 30 53 PM" src="https://github.com/bitkarrot/decoder/assets/73979971/ce97a651-2f75-401b-887e-3a2ddf6010fe">

### Decode a Lightning Address

<img width="644" alt="Screenshot 2024-01-08 at 3 30 23 PM" src="https://github.com/bitkarrot/decoder/assets/73979971/8e14373b-842c-4529-86c0-50785347a4f0">

## Get Started

Mininum poetry version has is ^1.2, but it is recommended to use latest poetry. (including OSX)

```sh
poetry env use python3.9
poetry install --only main
```

## Powered by LNbits

[LNbits](https://lnbits.com) is a free and open-source lightning accounts system.

[![Visit LNbits Shop](https://img.shields.io/badge/Visit-LNbits%20Shop-7C3AED?logo=shopping-cart&logoColor=white&labelColor=5B21B6)](https://shop.lnbits.com/)
[![Try myLNbits SaaS](https://img.shields.io/badge/Try-myLNbits%20SaaS-2563EB?logo=lightning&logoColor=white&labelColor=1E40AF)](https://my.lnbits.com/login)
