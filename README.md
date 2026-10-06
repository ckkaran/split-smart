# 💸 SplitSmart – Group Expense Splitter

> Split trip, flat and party expenses fairly — and settle up in the **fewest possible payments**.

**🔗 Live demo:** https://ckkaran.github.io/split-smart/

## ✨ Features
- Add people and expenses (who paid, split between whom)
- Live balances: who gets back and who owes
- **Smart settle-up**: a greedy min-cash-flow algorithm reduces the number of transfers
- Amounts shown in ₹ with Indian number formatting
- Data saved in the browser, automatic dark mode, mobile friendly

## ⚙️ How the settle-up works
1. Compute each person's net balance (paid − share).
2. Repeatedly match the biggest debtor with the biggest creditor and transfer the smaller of the two amounts.
3. Stop when everyone is at zero — for *n* people this needs at most *n − 1* payments.

## 🛠️ Built with
HTML5 · CSS3 · Vanilla JavaScript

## 🚀 Run locally
```bash
git clone https://github.com/ckkaran/split-smart.git
cd split-smart
# open index.html in your browser
```

## 📄 License
MIT
