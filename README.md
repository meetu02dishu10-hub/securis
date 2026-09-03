# securis
SECURIS

Intelligent Protection Before the Payment

SECURIS is an intelligent banking safety system designed to protect vulnerable customers from digital financial fraud, scams, social engineering, and risky transactions.

Rather than reacting after fraud occurs, SECURIS introduces an intelligent safety layer before a transaction is completed. It evaluates transaction risk, identifies unusual behaviour, and adapts the level of security based on the situation.

---

The Problem

Digital banking has made financial transactions faster and more convenient. However, this convenience has also increased exposure to digital scams and social engineering.

Senior citizens, first-time digital banking users, and people with limited digital experience may be particularly vulnerable to situations where they are manipulated into authorising a transaction themselves.

A transaction can therefore appear completely legitimate to a banking system while still being fraudulent from the customer's perspective.

SECURIS addresses this gap by providing an additional layer of intelligent protection between the user's decision and the completion of a transaction.

---

Our Solution

SECURIS evaluates transactions using multiple risk signals and determines the appropriate level of protection.

Instead of treating every transaction in the same way, the system considers factors such as:

- Transaction amount
- Beneficiary history
- Transaction timing
- Transaction frequency
- Previous transaction patterns
- Deviation from normal user behaviour

Based on the calculated risk, SECURIS can allow the transaction normally, display a warning, request additional verification, or activate emergency protection.

The goal is simple: provide stronger security when it is needed without making everyday banking unnecessarily difficult.

---

Key Features

1. Risk-Scored Transaction Flow

Transactions are classified into three risk levels:

- Low Risk
- Medium Risk
- High Risk

The classification is based on simulated behavioural and transaction signals.

2. Guardian Verification

For high-risk transactions, the system can request confirmation from a trusted guardian before allowing the transaction to proceed.

This provides an additional layer of protection for vulnerable customers.

3. AI Safety Assistant

A simple, contextual AI assistant explains potential risks in understandable language.

Instead of displaying technical security information, it helps the user understand why a transaction may be considered risky and what they can do next.

4. Biometric Confirmation

Higher-risk transactions can trigger an additional biometric authentication step.

For the hackathon prototype, biometric verification is simulated to demonstrate the intended security workflow.

5. "Something Feels Wrong" Emergency Action

Users can quickly indicate that they suspect something is wrong.

This one-tap emergency mechanism can initiate protective actions within the banking interface, reducing the time between recognising a potential scam and taking action.

6. Post-Fraud Recovery Assistant

If a user believes they have already been affected by fraud, SECURIS provides a guided recovery process.

The assistant can help users understand immediate steps such as:

- Freezing or blocking a card
- Reporting a suspicious transaction
- Contacting the appropriate bank support
- Preparing information for a fraud complaint
- Reviewing recent transactions

---

How SECURIS Works

User
  ↓
Banking Interface
  ↓
Transaction Request
  ↓
Risk Analysis Engine
  ↓
Risk Classification
  ↓
Adaptive Security
  ↓
 ┌─────────────────────────────────────┐
 │ Safe Transaction                    │
 │ Warning                             │
 │ Guardian Verification               │
 │ Additional Authentication           │
 │ Emergency Protection                │
 └─────────────────────────────────────┘
  ↓
Transaction Outcome

The system adapts its response according to the level of risk instead of applying the same security process to every transaction.

---

Risk Analysis

SECURIS uses multiple signals to estimate transaction risk.

Examples include:

- New or unfamiliar beneficiary
- Unusually large transaction
- Unusual transaction time
- Sudden change in transaction behaviour
- Unusual transaction frequency
- Deviation from previous transaction patterns

For the hackathon demonstration, these signals are generated using simulated banking data.

The risk engine is intended to demonstrate the concept of adaptive fraud prevention rather than provide a production-ready banking fraud model.

---

Technology Stack

Component| Technology
Frontend| React / Next.js
Language| TypeScript
Styling| Tailwind CSS
Backend| Node.js
Database| Firebase / Supabase
AI Assistant| LLM-based contextual assistance
Risk Engine| Behavioural risk scoring
Version Control| Git & GitHub

---

Hackathon MVP

The SECURIS prototype demonstrates the complete safety journey through a simulated banking environment.

Included in the MVP

- Secure login
- Banking dashboard
- Transaction initiation
- Risk assessment
- Risk classification
- AI-powered safety guidance
- Guardian verification
- Biometric confirmation simulation
- Emergency fraud protection
- Post-fraud recovery guidance

No real bank accounts are connected and no real financial transactions are processed.

---

Future Scope

SECURIS can be further developed into a comprehensive banking safety platform with capabilities such as:

- Real banking and UPI integration
- Multilingual support
- Voice-based assistance
- Advanced behavioural biometrics
- Scam SMS and call detection
- Real-time fraud intelligence
- Integration with banking fraud-management systems
- Accessibility-focused banking interfaces
- Personalised protection based on customer behaviour
- Real-time transaction monitoring

---

Why SECURIS?

Traditional fraud detection often focuses on identifying suspicious transactions.

SECURIS focuses on something equally important:

What if the transaction is authorised by the customer, but the customer has been manipulated into making it?

By combining risk analysis, adaptive security, human assistance, and emergency protection, SECURIS aims to move banking security from reactive fraud detection to proactive customer protection.

---

Team

Built for the Hackathon by:

- ASIF
- TEJASWI
- HARISH
- SUSHMITA

---

Disclaimer

SECURIS is a hackathon prototype created for demonstration and educational purposes.

It does not connect to real bank accounts, access real financial information, or process real financial transactions.
