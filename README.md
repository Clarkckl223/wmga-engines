# wmga-engines

Open-source Go (围棋) engine and model files, served via jsDelivr for wmga.com.my.
No application code of 黑白思弈馆 is stored here.

| Folder | Contents | License |
|---|---|---|
| `gnugo/` | `gnugo.wasm` — GNU Go compiled to WebAssembly (engine unmodified). Build notes `BUILD.md`, link helper `rt.c`, `wasm.patch`. | GPL v3 — see `gnugo/COPYING.txt`. Source: https://github.com/runningskull/gnugo (mirror of official GNU Go), commit 84a32e9cee2a70c0ec6ef58c1be279fed84a9a53 |
| `katago/` | KataGo b10 network converted to TensorFlow.js (`model.json` + shards) | see `katago/LICENSE.txt` (KataGo) |
