# Privacy Policy for Personal AI Employee

Last Updated: 2026-05-14

This Privacy Policy explains how the "Personal AI Employee" handles data. This project is a personal automation tool designed to manage personal and business affairs autonomously.

## 1. Information Collected
To function effectively, this system interacts with several platforms:
*   **Authentication Data**: API tokens and keys (Meta, Twitter/X, LinkedIn, Google, Odoo) are stored locally in secure environment variables (`.env`).
*   **Social Media Content**: Drafts and content intended for Facebook, Instagram, and Twitter/X.
*   **Business Data**: Invoices, expenses, and contact information processed via Odoo ERP.
*   **Communication Data**: Incoming emails and WhatsApp messages processed to identify actionable tasks.

## 2. How Data is Used
*   **Automation**: Data is used solely to facilitate the automation of tasks, such as posting content to social media, managing invoices, and organizing business affairs.
*   **Reasoning Engine**: Data is processed by the AI reasoning engine to generate plans and execute actions.
*   **Logs**: Actions taken by the system are logged locally to `/Vault/Logs/` for auditing, debugging, and system transparency.

## 3. Data Disclosure
*   **No Sharing**: We do not sell, rent, or distribute your data to any third parties.
*   **Local Processing**: All processing occurs locally on your machine. Data stored within the `/Vault/` folder remains under your local control.

## 4. Security
*   **Local Control**: Your data is stored locally.
*   **Credential Protection**: API keys and tokens are stored in a local `.env` file, which is excluded from source control (Git).
*   **Audit Logging**: Every system action is logged locally to allow you to review exactly what the AI agent has done.

## 5. Contact
If you have any questions about this Privacy Policy, please contact:

[YOUR NAME/EMAIL HERE]
