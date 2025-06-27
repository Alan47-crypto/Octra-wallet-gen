Guide to generate Octra Wallet and claiming $oct faucet.
# Octra Wallet Generator

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

If you’re using a cloud VPS provider like AWS, DigitalOcean, or GCP, also make sure their security group or firewall rules allow inbound traffic on port 8888.

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

By default, the app runs on:  
[http://<YOUR_VPS_IP>:8888](http://<YOUR_VPS_IP>:8888)

## 🌐 7. Access it from your browser

Open your browser and visit:

```
http://<YOUR_VPS_IP>:8888

OR

http://localhost:8888
```
If you are running on local machine.

---

## Next Steps

2. **Claim testnet tokens** using your generated address:  
   [https://faucet.octra.network](https://faucet.octra.network)

3. **Verify your balance** at:  
   [https://octrascan.io](https://octrascan.io)

4. **Join our Discord & wait for next steps:**  
   [http://discord.gg/octra](http://discord.gg/octra)
