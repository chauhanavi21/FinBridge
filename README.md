# FinBridge
<div align="center"> <br /> <!-- You can replace the image below with your own project banner. For the README in a real repository, ensure the image is stored in the repo and referenced with a relative path or a stable URL. --> <img src="https://imgur.com/placeholder.png" alt="Project Banner" width="600"/> <br /> <div> <img src="https://img.shields.io/badge/-Next.js-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=000000" alt="Next.js" /> <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="TypeScript" /> <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="Tailwind CSS" /> <img src="https://img.shields.io/badge/-Appwrite-black?style=for-the-badge&logoColor=white&logo=appwrite&color=FD366E" alt="Appwrite" /> </div> <h3 align="center">FinBridge: A Unified Banking Platform</h3> <div align="center"> This repository contains the full source code for FinBridge, a unified banking platform built with Next.js and TypeScript. </div> </div>
🔗 Introduction

FinBridge is a modern financial SaaS application designed to unify your banking experience. Built with the latest features of Next.js, TypeScript and TailwindCSS, FinBridge allows you to securely link multiple bank accounts through Plaid, aggregate balances and transactions in real‑time, and send money to other users via Dwolla. The intuitive dashboard displays your spending by category, recent transactions and total balances so you can manage your finances efficiently on any device.

⚙️ Tech Stack

Next.js – powering the server‑side rendering and API routes.

TypeScript – ensuring type safety across the codebase.

Appwrite – providing authentication, database and file storage services.

Plaid – linking external bank accounts and retrieving account and transaction data.

Dwolla – enabling peer‑to‑peer money transfers between verified users.

React Hook Form & Zod – building robust forms with client‑side and server‑side validation.

TailwindCSS & ShadCN – rapidly styling UI components with a utility‑first approach.

Chart.js – visualizing spending patterns and balances with interactive charts.

✨ Features

Secure Authentication – leverages Appwrite to provide token‑based registration and login with server‑side session management.

Link Multiple Banks – integrates with Plaid to securely connect one or more bank accounts and retrieve balances and transaction histories.

Unified Dashboard – aggregates balances across all connected accounts, highlights recent transactions, and displays spending by category with charts.

My Banks – lists all linked institutions, their account numbers (masked) and current balances at a glance.

Transaction History – offers a paginated and filterable history of transactions, including category, date, and merchant information.

Funds Transfer – uses Dwolla’s sandbox API to send money to other users by shareable account ID, with proper confirmation and error handling.

Real‑time Updates – updates account data and UI automatically after linking a bank or completing a transfer.

Responsive Design – optimized for desktops, tablets and mobile devices for a seamless user experience everywhere.

🚀 Quick Start

Follow these steps to set up the project locally:

Prerequisites

Git

Node.js

npm

Clone the Repository

git clone https://github.com/your-username/finbridge.git
cd finbridge


Install Dependencies

npm install


Configure Environment Variables

Create a .env file in the root of the project and populate it with your credentials:

#NEXT
NEXT_PUBLIC_SITE_URL=

#APPWRITE
NEXT_PUBLIC_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
NEXT_PUBLIC_APPWRITE_PROJECT=
APPWRITE_DATABASE_ID=
APPWRITE_USER_COLLECTION_ID=
APPWRITE_BANK_COLLECTION_ID=
APPWRITE_TRANSACTION_COLLECTION_ID=
APPWRITE_SECRET=

#PLAID
PLAID_CLIENT_ID=
PLAID_SECRET=
PLAID_ENV=
PLAID_PRODUCTS=
PLAID_COUNTRY_CODES=

#DWOLLA
DWOLLA_KEY=
DWOLLA_SECRET=
DWOLLA_BASE_URL=https://api-sandbox.dwolla.com
DWOLLA_ENV=sandbox


Run the Development Server

npm run dev


Open http://localhost:3000
 in your browser to view the application.
