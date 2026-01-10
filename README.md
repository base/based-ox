# Ox

**Ox** (⦻) is the foundation of robust Ethereum software written in TypeScript. It is an **Ethereum Standard Library** that provides a set of lightweight, performant, and type-safe TypeScript modules for Ethereum.

It offers core utilities & types for primitives such as: ABIs, Addresses, Blocks, Bytes, ECDSA, Hex, JSON-RPC, RLP, Signatures, Transactions, and more.

## Installation

```bash
npm i ox
# or
pnpm i ox
# or
bun i ox
```

## Example Usage

Below is an example of using the `Hex` and `Rlp` modules of Ox.

```ts
import { Hex, Rlp } from 'ox'

const rlp = Rlp.fromHex([Hex.fromString('hello'), Hex.fromString('world')])
```

## Documentation

Full documentation is available in the [`site`](./site) directory.

## Contributing

1. Clone the repository.
2. Install dependencies: `pnpm install`
3. Check code: `pnpm check`
4. Run tests: `pnpm test`
