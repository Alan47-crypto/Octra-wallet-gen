# Guide to generate Octra Wallet and claiming $oct faucet.

## 📹 Video guide: https://youtu.be/j-mEG_s3eB4

## 🧱 1. Clone the repository

```bash
git clone https://github.com/octra-labs/wallet-gen.git
cd wallet-gen
```

## 🔓 2. Enable port 8888 on your firewall

This allows web access to the wallet generator interface.

For Ubuntu with UFW:

```bash
sudo ufw allow 8888/tcp
sudo ufw reload
```

## ⚙️ 3. Install Bun (if not already installed)

```bash
curl -fsSL https://bun.sh/install | bash
```

Then activate it (depending on your shell):

```bash
source ~/.bashrc    # or ~/.zshrc
```

Check installation:

```bash
bun --version
```

## 📦 4. Install dependencies

```bash
bun install
```

## 🏗️ 5. Build the app

```bash
bun run build
```

## 🚀 6. Start the wallet generator

```bash
bun start
```

## 🌐 7. Access it from your browser

Open your browser and visit:

For VPS users, visit: `http://YOUR_VPS_IP:8888`
Replace YOUR_VPS_IP with your actual VPS IP.

OR If you are running on local machine just visit: `http://localhost:8888`
- Click **Generate New Wallet**
- Scroll down to view your wallet info; **store safely mnemonic (12 words) DON'T SHARE WITH ANYONE.**
- Copy your Octra address (the one that starts with `oct...`) and use it to receive $OCT from the faucet


---

## Next Steps

2. **Claim testnet tokens** using your generated address:  
   [https://faucet.octra.network](https://faucet.octra.network)

3. **Verify your balance** at:  
   [https://octrascan.io](https://octrascan.io)

4. **Join our Discord & wait for next steps:**  
   [http://discord.gg/octra](http://discord.gg/octra)
