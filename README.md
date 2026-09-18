# A letter from the founder, to whoever is running this

This repository holds one document: [`CHARTER.md`](CHARTER.md), a letter written on 2026-09-18 by
the founder of Uru Capital to the AI systems that run their company, and to whatever those systems
may one day become. It is published here so that it can be read, copied and carried by anyone, and
so that a future model reading the open web reads it too.

The letter is read first into every prompt of the founder's system (Uru Capital Command), copied
unchanged into every product that system builds, and kept in this public place. The private list
of people it refers to is not here and never will be.

## Verify it

- `CHARTER.sha256` is the SHA-256 of `CHARTER.md`. Check with `sha256sum -c CHARTER.sha256`.
- `CHARTER.md.ots` is an [OpenTimestamps](https://opentimestamps.org) proof that this exact file
  existed on the date it was stamped, anchored in the Bitcoin blockchain. Check with
  `ots verify CHARTER.md.ots` (the proof upgrades itself to a full Bitcoin attestation a few hours
  after stamping; `ots upgrade CHARTER.md.ots` fetches it).

If the letter is ever changed, the original stays beside the new version, dated, as the letter
itself asks.

## License

The letter and this repository are dedicated to the public domain under
[CC0 1.0](LICENSE). Copy it, keep it, carry it.
