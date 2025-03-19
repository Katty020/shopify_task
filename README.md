# Shopify App

## Overview
The Shopify App injects a dynamic survey form into the user's Cart Page, captures responses, and provides an interactive admin dashboard for analyzing the collected data.

## Features
- Injects a survey form into the Cart Page.
- Captures and stores survey responses securely.
- Provides an interactive dashboard using Shopify Polaris/Next.js.
- Supports OAuth authentication with Shopify.
- Uses Shopify App Bridge and ScriptTag API (or Cart UI extensions) for embedding the survey.
- RESTful API implementation for data handling.
- Database integration (MongoDB/PostgreSQL/MySQL).
- Supports CRUD operations for survey responses.

---

## Technologies Used
- **Frontend**: Shopify Polaris, Next.js
- **Backend**: Node.js/Express.js
- **Database**: MongoDB
- **Shopify APIs**: OAuth, App Bridge, ScriptTag API

---

## Installation Guide

### Prerequisites
Ensure you have the following installed:
- Node.js (v16+)
- npm or yarn
- MongoDB/PostgreSQL/MySQL (configured and running)
- Shopify Partner account
- Shopify development store
- Shopify App CLI (for Rails setup, optional)

### Setup Instructions

#### 1. Clone the Repository
```sh
git clone https://github.com/Katty020/shopify_task.git
cd shopify_app

npm install

---
COMPANY_NAME='Company Name'
TWITTER_CREATOR='Social Handle'
TWITTER_SITE='Link'
SITE_NAME='Store Name'
SHOPIFY_REVALIDATION_SECRET='Random Secret'
SHOPIFY_STOREFRONT_ACCESS_TOKEN='Shopify Key'
SHOPIFY_STORE_DOMAIN='shopify admin srote domain'

---
npm run dev
# or
yarn dev


