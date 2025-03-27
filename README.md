# FinTech Banking Capstone Project

This is a FinTech banking application built using modern technologies. The application allows users to connect to different banking accounts, view transaction history, and transfer funds from one bank to another. The project utilizes a combination of powerful technologies like Next.js, Appwrite, Plaid, Dwolla, Sentry, Shadcn, Tailwind CSS, and TypeScript.

## Technologies Used

- **Next.js**: A React framework for building static and dynamic web applications.
- **Appwrite**: A backend-as-a-service platform for building secure APIs.
- **Plaid**: A financial services API that connects to users' bank accounts.
- **Dwolla**: A payment API to facilitate ACH transfers.
- **Sentry**: An error tracking tool to monitor and fix application crashes in real-time.
- **Shadcn**: A UI component library for building modern, accessible components.
- **Tailwind CSS**: A utility-first CSS framework for creating custom designs quickly.
- **TypeScript**: A typed superset of JavaScript that compiles to plain JavaScript.

## Features

- **Bank Account Connection**: Users can securely link their bank accounts through Plaid integration.
- **Transaction History**: View a list of transactions from connected bank accounts.
- **Fund Transfers**: Easily transfer funds between different bank accounts using Dwolla's ACH transfer API.
- **Real-time Error Tracking**: Integrated Sentry for monitoring and fixing any potential issues or crashes.
  
## Installation

To get started with this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/fintech-banking.git
   cd fintech-banking
2. Install the required dependencies:
   ```bash
   npm i --force
3. Environment Variables Configuratio

     Edit file named `.env` in the root of your project and add the following content:
    
    ```env
    # NEXT
    NEXT_PUBLIC_SITE_URL=
    
    # APPWRITE
    NEXT_PUBLIC_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
    NEXT_PUBLIC_APPWRITE_PROJECT=
    APPWRITE_DATABASE_ID=
    APPWRITE_USER_COLLECTION_ID=
    APPWRITE_BANK_COLLECTION_ID=
    APPWRITE_TRANSACTION_COLLECTION_ID=
    APPWRITE_SECRET=
    
    # PLAID
    PLAID_CLIENT_ID=
    PLAID_SECRET=
    PLAID_ENV=
    PLAID_PRODUCTS=
    PLAID_COUNTRY_CODES=
    
    # DWOLLA
    DWOLLA_KEY=
    DWOLLA_SECRET=
    DWOLLA_BASE_URL=https://api-sandbox.dwolla.com
    DWOLLA_ENV=sandbox
4. Start the development server and run the project in the Web Browser
   ```bash
   npm run dev
   http://localhost:3000

