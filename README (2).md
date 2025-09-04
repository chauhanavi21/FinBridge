# FinBridge – Unified Banking Platform  

<div align="center">
  <img src="https://imgur.com/placeholder.png" alt="FinBridge Banner" width="600"/>
</div>

## 🔗 Introduction  

**FinBridge** is a modern financial SaaS application that unifies your banking experience. It enables users to securely link multiple bank accounts, view balances and transactions in real time, categorize spending, and send money to peers. Designed with performance, scalability, and security in mind, FinBridge offers an intuitive dashboard and seamless user experience across all devices.  

---

## ⚙️ Tech Stack  

- **Next.js 14** – Server-side rendering, routing, and optimized performance  
- **TypeScript** – Strong typing for maintainable and scalable code  
- **Appwrite** – Authentication, database, and file storage  
- **Plaid** – Bank account linking and real-time transaction retrieval  
- **Dwolla** – Peer-to-peer money transfers between verified users  
- **React Hook Form & Zod** – Form handling and schema validation  
- **Tailwind CSS & ShadCN** – Utility-first responsive UI styling  
- **Chart.js** – Interactive financial data visualization  

---

## ✨ Features  

- 🔐 **Secure Authentication** – User sign-up/sign-in with Appwrite  
- 🏦 **Bank Account Linking** – Connect external accounts via Plaid  
- 💳 **Aggregated Dashboard** – Unified balances, spending categories, and transaction summaries  
- 📊 **Analytics** – Visual breakdown of expenses and income using interactive charts  
- 🔄 **Transaction History** – Paginated and filterable transaction logs  
- 💸 **Money Transfers** – Send and receive payments securely with Dwolla integration  
- 📱 **Responsive Design** – Optimized for mobile, tablet, and desktop  

---

## 🚀 Getting Started  

### Prerequisites  
- Node.js 18+  
- Appwrite instance running locally or hosted  
- Plaid developer account and API keys  
- Dwolla sandbox account for transfers  

### Installation  

```bash
# Clone the repository
git clone https://github.com/yourusername/finbridge.git

# Navigate into the project folder
cd finbridge

# Install dependencies
npm install

# Start the development server
npm run dev
```

---

## 📂 Project Structure  

```
finbridge/
 ├── app/                # Next.js app router pages and layouts
 │    ├── (auth)/        # Authentication pages (sign-in, sign-up)
 │    ├── (root)/        # Protected routes (dashboard, transfers, history)
 │    └── globals.css    # Global styles
 ├── components/         # Reusable UI components
 ├── lib/                # Utility functions and service integrations
 │    ├── actions/       # Appwrite, Plaid, and Dwolla actions
 │    └── utils.ts       # Helper utilities
 ├── types/              # TypeScript type definitions
 └── package.json
```

---

## 🧪 Testing  

Run unit tests with:  

```bash
npm run test
```

---

## 📈 Future Improvements  

- AI-powered financial insights and recommendations  
- Budget planning and goal tracking  
- Multi-currency support  

---

## 📜 License  

This project is licensed under the MIT License – feel free to modify and use it as needed.  
