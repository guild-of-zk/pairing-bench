# Pairing cryptography benchmarks

This repository aims to provide a comprehensive benchmarks suite of libraries for pairing-based cryptography.

The goals are:
- Providing a reproducible "performance status" of the domain so that
  developers can make informed decisions on throughput, latency and hardware constraints
  their application may have.
- Fostering sharing and refining of existing cryptographic implementations to use available hardware to its utmost limit.
- Providing a benchmark focused on cryptography-relevant primitives to evaluate CPU architectures.
  - For example, the presence of a 64x64 to 128-bit multiplication on x86-64 is a significant advantage compared to ARM64.
  - The limitation of 16 general registers on x86-64 compared the 31 on ARM64 is a significant disadvantage.

## Benchmarks

Benchmarks will be provided over the following categories:

1. Finite-Field arithmetic
2. Extension-Field arithmetic for 𝔾2
3. Extension-Field arithmetic for 𝔾T
4. Elliptic Curve arithmetic on 𝔾1
5. Elliptic Curve arithmetic on 𝔾2
6. Pairings

## License

The benchmarked code is under the license of their respective authors.

The benchmarking code is under the MIT license: [LICENSE-MIT](LICENSE) or http://opensource.org/licenses/MIT