
# KnackGit 🚀 *(WIP: Work in Progress)*  

KnackGit is a **Rust-powered CLI and macOS menu bar app** designed to make switching between multiple Git accounts seamless. Whether you're juggling **personal projects, open-source contributions, or enterprise repositories**, KnackGit simplifies **Git identity management** like never before.  

> 🚧 **This project is currently a Work in Progress (WIP).** Expect frequent updates as we build towards a stable release!  

## 🔥 Features *(Planned & In-Progress)*  

✅ **CLI & Menu Bar App** – Use it via the terminal or an intuitive macOS menu bar UI.  
✅ **Fast Git Profile Switching** – Swap between Git accounts in seconds.  
✅ **SSH & Credential Handling** – Automates `.gitconfig` and SSH key management.  
🔜 **Automatic Per-Repository Profiles** – Assign default Git accounts for specific repositories.  
🔜 **Interactive Profile Setup** – Easily configure accounts with guided prompts.  
🔜 **Cloud Sync (Future Scope)** – Sync Git profiles across machines.  

## 📦 Installation  

### 🚀 Using Cargo (CLI)  

```sh
cargo install knackgit
```

### 🖥 macOS App *(Coming Soon)*  

> A `.dmg` installer will be available in future releases. Stay tuned!  

## 🚀 Usage  

### 1️⃣ List available Git profiles  

```sh
knackgit list
```

### 2️⃣ Switch to a Git account  

```sh
knackgit use personal
```

### 3️⃣ Add a new Git profile  

```sh
knackgit add work --email dev@company.com --ssh-key ~/.ssh/id_rsa_work
```

### 4️⃣ Open the menu bar app *(macOS)*  

```sh
knackgit ui
```

## 🛠 Configuration  

KnackGit saves profiles in:  

📌 `~/.knackgit/config.json` *(modifiable manually if needed)*  

## 💡 Why KnackGit?  

Switching Git accounts manually is **tedious**—constantly editing `.gitconfig`, handling SSH keys, and juggling credentials. **KnackGit automates it all**, making it effortless to shift between work, personal, and other Git accounts in seconds.  

## 🤝 Contributing  

We're actively building **KnackGit**, and contributions are welcome! 🚀  

```sh
git clone https://github.com/knackline/KnackGit.git
cd KnackGit
cargo build
```

### 📢 Issues & Feature Requests  
Found a bug? Have an idea? Open an **[issue](https://github.com/knackline/KnackGit/issues)**!  

## 📜 License  

KnackGit is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.  

---

💙 Built with Rust & passion by [Knackline](https://github.com/knackline)  
```

Would you like to add **badges** (e.g., build status, Rust version) or a **roadmap** section? 🚀
