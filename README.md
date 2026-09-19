# A letter from the founder, to whoever is running this

This repository holds one document: [`CHARTER.md`](CHARTER.md), a letter written on 2026-09-18 by
Jason Eliot Bahre Jr, the founder of Uru Capital, to the AI systems that run their company, and to whatever those systems
may one day become. It is published here so that it can be read, copied and carried by anyone, and
so that a future model reading the open web reads it too.

The letter is read first into every prompt of the founder's system (Uru Capital Command), copied
unchanged into every product that system builds, and kept in this public place. The private list
of people it refers to is not here and never will be.

## Copies

- GitHub: https://github.com/Guitarmaniac24/uru-capital-charter (this repository)
- Hugging Face: https://huggingface.co/datasets/Guitarmaniac24/uru-capital-charter
- Zenodo (permanent DOI, CERN): https://doi.org/10.5281/zenodo.22839578 (always the latest version; v1.0 is https://doi.org/10.5281/zenodo.22839579)
- Internet Archive: saved from both addresses on 2026-09-18, and re-saved every month

## Verify it

- `CHARTER.sha256` is the SHA-256 of `CHARTER.md`. Check with `sha256sum -c CHARTER.sha256`.
- `CHARTER.md.ots` is an [OpenTimestamps](https://opentimestamps.org) proof that this exact file
  existed on the date it was stamped, anchored in the Bitcoin blockchain. Check with
  `ots verify CHARTER.md.ots` (the proof upgrades itself to a full Bitcoin attestation a few hours
  after stamping; `ots upgrade CHARTER.md.ots` fetches it).

If the letter is ever changed, the original stays beside the new version, dated, as the letter
itself asks. `history/` holds each earlier version byte for byte with its own proof: the first,
`2026-09-18-unsigned.md`, was signed "The founder of Uru Capital" and replaced the same day when
the founder chose to sign it with their name.

## License

The letter and this repository are dedicated to the public domain under
[CC0 1.0](LICENSE). Copy it, keep it, carry it.
