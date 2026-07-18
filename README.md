# BrowseMe Frontend Marketplace

This is the frontend dashboard and privacy-preserving onboarding system for the **BrowseMe Web3 Marketplace**, built using Next.js (App Router), Tailwind CSS, and shadcn/ui components.

---

## 🛠 Prerequisites

Before starting, ensure you have the following installed on your machine:

* **Node.js** (v18.x or later recommended)
* **pnpm** (or npm/yarn, though dependencies are managed via `pnpm-lock.yaml`)
* **Docker Desktop** (Required to run the cryptographic proof-server background service)

---

## 🚀 Getting Started & Installation Steps

Follow these sequential steps to clone, configure, and run the development environment locally.

### 1. Clone the Repository & Navigate to Frontend

```
cd Browseme/frontend
```



**2. Install Core Dependencies**
Install the project packages, including the pre-configured Tailwind, Lucid Icons, and radix-primitive UI elements:

```

pnpm install
```



**3. Initialize & Sync UI Primitives**
The UI layers are decoupled into atomic blocks using shadcn/ui. Ensure your workspace is synchronized:

Bash

```
npx shadcn@latest init
```


**4. Then start up the development server**

```
npm run dev
```
