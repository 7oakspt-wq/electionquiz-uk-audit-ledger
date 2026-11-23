# Election Quiz UK — Cryptographic Polling Audit Ledger

This public repository stores automated 6-hourly cryptographic verification proofs (**Bitcoin OpenTimestamps `.ots`** and **DigiCert RFC 3161 `.tsr`**) for cumulative aggregated live polling totals published by **Election Quiz UK**.

* **Live Human-Readable Polling Tracker (Canonical Source):** https://electionquiz.co.uk/voter-sentiment-index/live-polling-data/
* **Take the 30-Question UK Policy Trade-Off Quiz:** https://electionquiz.co.uk/
* **Privacy & UK GDPR Notice:** Only aggregated statistical totals are recorded here. Zero personal data, zero emails, zero IP addresses, and zero individual respondent rows are ever published.

## How to Independently Verify Any Snapshot
1. Open the `/snapshots/` folder and download any matching `.json` and `.ots` pair.
2. Drop both files into the verifier at https://opentimestamps.org/ to confirm the exact Bitcoin block height and UTC timestamp proving the data existed untouched at that moment.
