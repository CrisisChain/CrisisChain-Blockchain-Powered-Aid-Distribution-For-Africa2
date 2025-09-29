
# 🌍 CrisisChain – Hedera Powered Aid Distribution For Africa

**CrisisChain** is a decentralized web app platform designed to bring **transparency, fairness, and efficiency** to humanitarian aid distribution across Africa. Built on the **Hedera Hashgraph network**, it enables NGOs, donors, governments, and communities to collaborate in a **trustless, verifiable ecosystem** where aid flows directly to verified recipients with **low cost, high speed, and eco-friendly transactions**.

---

## ✨ Purpose

Aid often fails to reach those who need it most. CrisisChain on **Hedera** solves this by:
- Securely verifying identities
- Tracking every step of aid distribution
- Issuing tamper-proof digital aid tokens (via Hedera Token Service)
- Providing real-time dashboards for transparency (via Hedera Consensus Service)

---

## 🚀 Features

- 🔗 **Hedera Token Service (HTS)** for aid token creation & distribution
- 🎟️ **Token-based claiming** via verified identity
- 📊 **Hedera Consensus Service (HCS)** for immutable transaction logs
- 📍 **Map-based tracking** of aid distribution centers
- 👛 **Wallet integrations** (HashPack / Blade Wallet)
- 🛡️ **Tamper-proof, fraud-resistant system**
- 🌱 **Eco-friendly ledger** with low energy usage

---

## 🛠️ Tech Stack

| Layer            | Technology                          |
|------------------|------------------------------------|
| Frontend         | React.js / TypeScript / Tailwind CSS |
| Backend          | Supabase (Database + Auth)         |
| Blockchain       | Hedera Hashgraph (HTS + HCS)       |
| Database         | PostgreSQL (via Supabase)          |
| Authentication   | Supabase Auth with JWT             |
| Wallet           | HashPack / Blade Wallet            |
| Map Integration  | Leaflet.js / Mapbox                |

---

## 📦 Installation & Setup

### 1. Clone Repository
```bash
git clone https://github.com/Dibora12/CrisisChain-Hedera-Aid-Distribution
cd CrisisChain-Hedera-Aid-Distribution
npm install


### 2. Install Dependencies

Run the following command in your project folder:

```bash
npm install
clone: git clone https://github.com/Dibora12/CrisisChain-Blockchain-Powered-Aid-Distribution-for-Africa
cd CrisisChain-Blockchain-Powered-Aid-Distribution-for-Africa

```

### 3. Configure Environment Variables

Create a `.env.local` file in the root directory and add:

```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

### 4. Start the Development Server

Run the development server with:

```bash
npm run dev
```

---

## 📍 Key Modules

### 🙍‍♂️🙍‍♀️ Authentication & Identity

- Email/password login
- Secure session management
- User profile with Lace wallet address

### 🎯 Aid Management Dashboard

- View and verify new aid requests
- Export recipient lists
- Monitor distributions and logistics

### 🧾 Verification & Distribution

- Connect local verifiers
- Assign and claim tokens
- Ensure fair delivery using smart contracts

---

## 🔐 Security Highlights

- Row-Level Security (RLS) policies via Supabase
- Biometric and session-based authentication
- Private wallet connections via Lace
- Zero-knowledge proof integration for identity and eligibility

---

## 📚 User Guide

### Getting Started

1. **Sign Up / Log In**

   - Create an account using your email and password.
   - Connect your Cardano wallet via the Lace Wallet integration for secure transactions.

2. **Profile Setup**
   - Complete your profile with necessary information and link your wallet address.

### Using the Dashboard

- **Apply for Aid**

  - Navigate to the Aid Application page.
  - Fill in the required details and submit your application.
  - Your application will be verified by local verifiers.

- **Verification Process**

  - Verifiers receive aid requests in their dashboard.
  - They confirm identity and eligibility without exposing sensitive data (using zero-knowledge proofs).

- **Aid Distribution**

  - Once verified, aid tokens are issued via smart contracts.
  - You can track the status of your aid delivery in real time on the dashboard map.

- **Export Reports**
  - Admins and authorized users can export recipient and distribution reports for transparency.

### Offline Access

- The mobile app supports offline mode to submit reports or applications when internet is unavailable.
- Data syncs automatically once connection is restored.

---

## 📬 Contact

### 👥 Team

**Project Lead:** Dibora Shibeshi  
📧 Email: diborashibeshi@gmail.com

**Team Members:**

- Leyuthega Abebaw
- Hana Tamiru
  CrisisChain Team

## 🤝 Contributing

We welcome community collaboration!  
If you have ideas, improvements, or bug fixes:

- Fork the repo
- Create a new branch
- Submit a pull request

