---
title: Setup
layout: default
nav_exclude: true
---

# Setup

This guide walks you through the essential setup process for your project, including installing tools, creating accounts, and configuring tokens.

---

## Downloading VSCode

**Visual Studio Code** (VSCode) is a powerful and lightweight code editor that supports various programming languages and extensions.

### Steps to Download and Install:
1. Visit the official VSCode download page: [Download VSCode](https://code.visualstudio.com/download).
2. Choose the appropriate version for your operating system (Windows, macOS, or Linux).
3. Download the installer and run it.
4. Follow the installation prompts.
5. Once installed, open VSCode and explore its extensions to enhance your development environment:
   - Install extensions like **Python**, **Markdown Preview**, and **GitLens**.

---

## Downloading Python

Python is a versatile programming language widely used for scripting and building applications.

### Steps to Download and Install:
1. Visit the official Python website: [Download Python](https://www.python.org/downloads/).
2. Choose the latest stable version for your operating system.
3. Download the installer and run it.
4. During installation, ensure you check the box for **"Add Python to PATH"**.
5. Verify the installation:
   - Open a terminal or command prompt.
   - Run the command:
     ```bash
     python --version
     ```
   - You should see the installed version of Python displayed.

---

## Creating an OpenAI Account

To use OpenAI's APIs, you'll need an account on their platform.

### Steps to Create an Account:
1. Visit the OpenAI website: [OpenAI Sign-Up](https://platform.openai.com/signup/).
2. Click **Sign Up** and enter your email address or log in with a Google/Microsoft account.
3. Verify your email and complete the onboarding steps.
4. Once signed in, you’ll land on the OpenAI dashboard, where you can manage your API keys and usage.

---

## Creating Tokens

API tokens are required to authenticate and interact with OpenAI's services.

### Steps to Create a Token:
1. Go to the **API Keys** section in your OpenAI dashboard: [API Keys](https://platform.openai.com/account/api-keys).
2. Click **Create new secret key**.
3. Copy the generated token and store it securely:
   - Paste it into a secure notes app or a `.env` file in your project directory.
   - Example `.env` file content:
     ```env
     OPENAI_API_KEY=your_api_key_here
     ```
4. Be cautious:
   - Never share your token publicly.
   - Avoid committing it to version control (e.g., GitHub).

---

With these steps complete, you’re ready to start using the tools and services necessary for your project. Proceed to the next section to begin coding and integrating APIs!
