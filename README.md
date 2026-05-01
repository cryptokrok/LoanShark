# LoanShark
A Python + HTML simulation of a multi-tier credit ecosystem. Play as Money Borrower, Rep, Apprentice, Loan Shark, or Financier. Manage advances, credit chains, bucket deposits, and compound interest. Built for educational game theory + finance modeling.
# Loan Shark Game 🦈

Interactive simulation of a 5-tier credit and reputation system. Players progress from Money Borrower → Rep → Apprentice Loan Shark → Loan Shark → Financier.

### **Core Mechanics**
- **Credit Chains**: Default penalties hit Rep + Borrower + referee
- **Bucket System**: Security R2/R100, Salary R12 fixed, Skills variable % 
- **Financing**: R50 fee per R100 advanced. Financiers deploy R5,000 at 5% default compound interest
- **Level Progression**: Credit score + voucher system for promotion

### **Includes**
1. `loan_shark_game.py` - Complete Python implementation with all 5 classes
2. `loan_shark_formulas.md` - All game formulas and rules 
3. `index.html` - Playable browser sim with arcade mini-game + mobile UI

### **Run It**
**Python**: `python loan_shark_game.py` or import classes in Colab  
**Browser**: Open `index.html` - no install needed

Built to model risk, reputation, and cash flow in informal lending networks.
