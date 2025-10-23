# edb-rs 🪄🐛

We make **Ethereum debugging less painful** (and a little magical).

**EDB** is a Rust-powered debugger that lets you step through Solidity contracts like they’re *real programs*, not cryptic bytecode soup.

---

## 🛠 What we build
- **Source-level debugging**: see your Solidity code, not just 0x hieroglyphics.  
- **Time travel**: scrub forward and backward until you catch the bug *red-handed*.  
- **Variable & state inspection**: locals, storage, calldata — if the EVM has it, you can interrogate it.  
- **Transaction replay**: drag mainnet/testnet txs under the microscope and watch them spill their secrets.

---

## 🚀 Quick start
```bash
git clone https://github.com/edb-rs/edb
cd edb
cargo build --release
cargo install --path crates/edb
cargo install --path crates/rpc-proxy
cargo install --path crates/tui
```

Then replay any transaction:

```bash
edb --rpc-urls <RPC_ENDPOINTS> replay 0xdeadbeef...c0ffee
```

---

## 📚 Links

* Repo: [edb](https://github.com/edb-rs/edb)
* Q&A TG Group: https://t.me/edb_feedback
* License: AGPL-3.0
* Sponsors: ESP (Ethereum Foundation) ❤️

> Debugging Solidity without EDB is like being Sherlock without Watson.
> 
> EDB won't fix your bugs, but it will level up our morale bar.
