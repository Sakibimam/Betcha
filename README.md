# Betcha 🧠🎉 — Meme Betting Game Powered by \$GUI

Betcha is a decentralized prediction game where users bet \$GUI tokens on meme templates they believe will go viral. It blends meme culture, on-chain utility, and social media hype into a fun, community-driven experience built on Aptos.

---

## 🌟 Key Features

* **Meme Battles**: Create or join meme competitions using viral templates
* **Bet with \$GUI**: Stake \$GUI tokens to back the meme you think will go viral
* **Social Sharing**: Each meme gets a unique hashtag. Players spread the memes on X (Twitter), IG, etc.
* **Virality Oracle**: Custom API checks which meme got the most traction
* **Reward Distribution**: Winning backers get rewarded in \$GUI
* **Leaderboards**: Track top meme pickers and win badges

---

## 🔧 Tech Stack

* **Frontend**: Next.js + TailwindCSS
* **Wallet**: Aptos Wallet Adapter (Martian, Pontem)
* **Backend**: Firebase (Realtime DB, Auth, Functions)
* **Smart Contracts**: Move (Aptos Layer 1)
* **Oracles**: RapidAPI + custom scripts to fetch social data

---

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://gitlab.com/your-org/betcha.git
cd betcha

# Install dependencies
yarn install

# Create your env file
cp .env.example .env.local

# Start dev server
yarn dev
```

Open your browser at `http://localhost:3000`

---

## 🧪 Smart Contract Functions

```move
public fun create_battle(...)
public fun place_bet(template_id: u64, amount: u64)
public fun end_battle(...)
public fun distribute_rewards(...)
```

---

## 📄 Environment Variables (`.env.local`)

```env
NEXT_PUBLIC_FIREBASE_API_KEY=xxx
NEXT_PUBLIC_WALLET_NETWORK=devnet
NEXT_PUBLIC_CONTRACT_ADDRESS=xxx
```

---

## 🧭 Project Vision

Betcha brings memes and DeFi together by letting users bet on what will go viral. We're making \$GUI a part of online culture through community-driven prediction games that are fun, competitive, and reward early trendspotters.

---

## 📜 License

MIT License

---

## 🙌 Contributions

Pull requests and issues are welcome! Let’s shape the future of meme prediction together.

---

> "Don’t just scroll memes. Bet on them. That’s Betcha."
