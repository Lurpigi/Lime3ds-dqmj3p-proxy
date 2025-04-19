# Lime3DS DQMJ3P Performance Fork (Proxy Repository)

> 🟢 **This is a proxy repository.** The actual project is maintained at:  
👉 **[github.com/Lurpigi/lime3ds-dqmj3p](https://github.com/Lurpigi/lime3ds-dqmj3p)**  
This proxy exists to make the project discoverable on GitHub and facilitate indexing and tracking.

[![](https://img.shields.io/github/v/release/Lurpigi/lime3ds-dqmj3p?include_prereleases&label=Release)](https://github.com/Lurpigi/lime3ds-dqmj3p/releases/latest)
[![](https://img.shields.io/github/downloads/Lurpigi/lime3ds-dqmj3p/total.svg)](https://github.com/Lurpigi/lime3ds-dqmj3p/releases)

---

## 🧩 Project Overview

This is a fork of the final archived version of **Lime3DS**, modified to use **core timing from Citra nightly-1543**, before the timing rewrite introduced in [PR #4913](https://web.archive.org/web/20230212174257/https://github.com/citra-emu/citra/pull/4913).

### 🎮 Why?
To **improve performance in _Dragon Quest Monsters: Joker 3 Professional_**, which runs significantly better on the old timing model.  
This fork is particularly useful if:
- You experience poor performance with post-1543 builds
- You are unable to run nightly-1543 due to driver limitations (e.g., some AMD GPUs)

> ⚠️ **Warning:** Performance may degrade in games other than DQMJ3P.

---

## 📦 Repository

To access the full source code and release builds, visit the main repository:

🔗 [https://github.com/Lurpigi/lime3ds-dqmj3p](https://github.com/Lurpigi/lime3ds-dqmj3p)

---

## 🔧 Building the Project

Clone the repository recursively to fetch all required submodules:

```sh
git clone --recursive https://github.com/Lurpigi/lime3ds-dqmj3p
