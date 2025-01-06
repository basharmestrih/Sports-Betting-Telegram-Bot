![Screenshot 2025-01-06 164026](https://github.com/user-attachments/assets/70f6450c-a374-498c-8ec2-cf10e329bc9e)



# Telegram Bot for Sports Betting Site Management

This repository contains a **Telegram bot** designed to manage a sports betting site. The bot allows users to perform various actions, such as creating an account, depositing funds, withdrawing funds, placing bets, and chatting with support. The bot is built using **Python** and leverages the following libraries:

- **`python-telegram-bot`**: For interacting with the Telegram API.
- **`pandas`**: For managing user data and transactions.
- **`selenium`**: For automating interactions with the sports betting site.

---

## 1. Features

- **User Account Management**:
  - Create a new account.
  - Log in to an existing account.
- **Financial Transactions**:
  - Deposit funds into the account.
  - Withdraw funds from the account.
- **Betting**:
  - Place bets on available sports events.
  - View bet history and results.
- **Support**:
  - Chat with customer support directly through the bot.
  - Get answers to frequently asked questions (FAQs).
- **Admin Panel**:
  - Manage users, transactions, and bets (for admins only).

---

## 2. How It Works

1. **User Interaction**:
   - Users interact with the bot through Telegram commands and menus.
   - The bot processes user inputs and performs the requested actions.

2. **Account Management**:
   - New users can create an account by providing necessary details.
   - Existing users can log in to access their accounts.

3. **Financial Transactions**:
   - Users can deposit funds using supported payment methods.
   - Withdrawal requests are processed and sent to the user's account.

4. **Betting**:
   - Users can view available sports events and place bets.
   - Bet results are updated automatically, and users are notified.

5. **Support**:
   - Users can chat with support agents or use the bot's FAQ section for quick help.

6. **Data Management**:
   - User data, transactions, and bets are stored and managed using `pandas`.

7. **Automation**:
   - `Selenium` is used to automate interactions with the sports betting site (e.g., placing bets, checking results).

---

## 3. How to Use

### Step 1: Clone the Repository
```bash
git clone https://github.com/your-username/sports-betting-bot.git
cd sports-betting-bot
python bot.py
