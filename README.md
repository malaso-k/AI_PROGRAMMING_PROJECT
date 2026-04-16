# AI_PROGRAMMING_PROJECT
# 💰 Finance Helper Bot

A friendly, console-based FAQ bot designed to answer common financial questions about accounts, loans, savings, budgeting, and more. Built with simple pattern matching for clear, calm responses.

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=yellow)
![License](https://img.shields.io/badge/License-MIT-green)

## ✨ Features

- **Interactive Chat**: Conversational interface for finance queries
- **20+ Topics Covered**: Accounts, loans, interest rates, budgeting, security, and more
- **Multi-language Keywords**: Handles variations like "current/checking account"
- **Smart Normalization**: Ignores case, extra spaces, and punctuation
- **Graceful Exit**: Multiple exit commands (exit, quit, bye, goodbye)
- **Help System**: Built-in help command shows all topics

## 📋 Topics Covered
Accounts: open account, savings account, current/checking account, minimum balance
Loans: apply for loan, eligibility, repayment terms
Rates & Fees: interest rates, service charges, hidden fees
Cards: debit card, credit card, lost/stolen card
Security: fraud, scams, account safety
Personal Finance: budgeting, saving money, credit score, retirement
Support: contact info, customer care

text

## 🚀 Quick Start

1. **Clone the repo**
   ```bash
   git clone https://github.com/malaso-k/finance-helper-bot.git
   cd finance-helper-bot
   ```

2. **Run the bot**
   ```bash
   python finance_faq_bot.py
   ```

3. **Start chatting!**
You: how do i open an account
Bot: To open an account, you usually fill in an online form...

text

## 💬 Example Conversation
==============================================================
💰 Finance Helper Bot
==============================================================
Hello 😊 I'm your calm assistant for general finance questions.

You: what is a savings account
Bot: A savings account is a safe place to keep your money while earning a small amount of interest...

You: how to save more money
Bot: To save more money, try tracking your spending, cutting small unnecessary costs...

You: help
Bot: You can ask me about: opening accounts, savings vs current accounts...

You: bye
Bot: Thank you for chatting with me. I wish you a calm and successful financial journey. 🌱

text

## 🛠️ How It Works

1. **Input Normalization**: Converts input to lowercase, removes extra spaces
2. **Pattern Matching**: Checks for 30+ keyword combinations
3. **Contextual Responses**: Returns pre-written, friendly answers
4. **Fallback Handling**: Suggests rephrasing if no match found

## 🔧 Customization

Want to add new topics? Edit the `get_response()` function:

```python
if "your new topic" in text:
    return "Your custom response here..."
```

## 👨‍💻 Author

**Malaso Natipa Koina**  
**Admission No:** 252297DAI  
[GitHub Profile](https://github.com/malaso-k)

## 📄 License

This project is open source and available under the MIT License.

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🙏 Acknowledgments

- Built for educational purposes
- Inspired by real banking FAQ systems
- Uses simple regex for robust text matching

# AI_PROGRAMMING_PROJECT
malaso natipa koina 252297DAI
simple chart bot that can only answer a few frequently asked question on common finanical website 
since its simple just run it on vs code terminl
