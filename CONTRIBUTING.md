# 🤝 Contributing to TradingView Indicators Pro

Thank you for your interest in contributing! We welcome contributions from the community.

---

## 📋 Ways to Contribute

### 1. **Submit New Indicators**
- Create professional Pine Script indicators
- Include complete documentation
- Add usage examples
- Provide backtesting results

### 2. **Improve Existing Indicators**
- Fix bugs
- Optimize performance
- Add new features
- Improve code quality

### 3. **Documentation**
- Write tutorials
- Create video guides
- Translate documentation
- Add trading strategies

### 4. **Report Issues**
- Bug reports
- Feature requests
- Performance issues
- Documentation errors

---

## 🚀 How to Contribute

### Step 1: Fork the Repository

Click the "Fork" button at the top right of this repository.

### Step 2: Clone Your Fork

```bash
git clone https://github.com/YOUR_USERNAME/tradingview-indicators-pro.git
cd tradingview-indicators-pro
```

### Step 3: Create a Branch

```bash
git checkout -b feature/your-indicator-name
```

### Step 4: Make Your Changes

#### For New Indicators:

1. **Create indicator file:**
   ```
   indicators/your-indicator-name.pine
   ```

2. **Create documentation:**
   ```
   docs/your-indicator-name.md
   ```

3. **Update README.md:**
   - Add your indicator to the list
   - Include description and features
   - Add link to documentation

#### For Bug Fixes:

1. Fix the issue
2. Test thoroughly
3. Update documentation if needed

### Step 5: Test Your Changes

- Test indicator on TradingView
- Verify all features work
- Check for errors
- Test on multiple timeframes
- Test on different assets

### Step 6: Commit Your Changes

```bash
git add .
git commit -m "Add: Your Indicator Name - Brief description"
```

**Commit Message Format:**
- `Add: New indicator name` - For new indicators
- `Fix: Bug description` - For bug fixes
- `Update: What was updated` - For updates
- `Docs: Documentation changes` - For docs

### Step 7: Push to Your Fork

```bash
git push origin feature/your-indicator-name
```

### Step 8: Create Pull Request

1. Go to your fork on GitHub
2. Click "New Pull Request"
3. Select your branch
4. Fill in the PR template
5. Submit!

---

## 📝 Indicator Guidelines

### Code Quality

✅ **Required:**
- Pine Script v5
- Clear variable names
- Comments explaining logic
- Proper indentation
- No hardcoded values (use inputs)

✅ **Best Practices:**
- Efficient calculations
- Minimal repainting
- Clear visual design
- Customizable settings
- Alert conditions

### Documentation Required

Each indicator must include:

1. **Overview** - What it does
2. **Features** - Key capabilities
3. **Installation** - How to install
4. **Settings** - All input parameters
5. **How It Works** - Logic explanation
6. **Trading Strategy** - How to use it
7. **Examples** - Screenshots/charts
8. **Backtesting** - Performance data
9. **FAQ** - Common questions

### File Structure

```
indicators/
  your-indicator.pine          # Indicator code

docs/
  your-indicator.md            # Full documentation
  images/
    your-indicator-example.png # Screenshots
```

---

## 🎯 Indicator Checklist

Before submitting, ensure:

- [ ] Code is Pine Script v5
- [ ] No compilation errors
- [ ] Works on multiple timeframes
- [ ] Works on multiple assets
- [ ] Has customizable settings
- [ ] Includes alert conditions
- [ ] Has clear visual design
- [ ] Documentation is complete
- [ ] Includes usage examples
- [ ] Has backtesting results
- [ ] README.md is updated
- [ ] No plagiarized code

---

## 📊 Backtesting Requirements

Include backtesting data:

```markdown
### Backtesting Results

**Asset:** BTC/USDT
**Timeframe:** 15m
**Period:** Last 6 months
**Settings:** [Your settings]

| Metric | Value |
|--------|-------|
| Total Trades | 250 |
| Win Rate | 65% |
| Profit Factor | 2.1 |
| Max Drawdown | 15% |
```

---

## 🐛 Bug Report Template

```markdown
**Indicator:** [Name]
**Version:** [Version]
**TradingView:** [Browser/Desktop]

**Description:**
Clear description of the bug

**Steps to Reproduce:**
1. Step 1
2. Step 2
3. Step 3

**Expected Behavior:**
What should happen

**Actual Behavior:**
What actually happens

**Screenshots:**
If applicable

**Additional Context:**
Any other information
```

---

## 💡 Feature Request Template

```markdown
**Feature Title:** [Clear title]

**Problem:**
What problem does this solve?

**Proposed Solution:**
How should it work?

**Alternatives:**
Other solutions considered

**Additional Context:**
Any other information
```

---

## 🎨 Code Style

### Pine Script Style

```pinescript
//@version=5
indicator("Indicator Name", overlay=true)

// ============================================
// SETTINGS
// ============================================
length = input.int(14, "Length", minval=1)
showSignals = input.bool(true, "Show Signals")

// ============================================
// CALCULATIONS
// ============================================
value = ta.sma(close, length)

// ============================================
// VISUAL
// ============================================
plot(value, "SMA", color=color.blue)

// ============================================
// ALERTS
// ============================================
alertcondition(condition, "Alert Name", "Alert Message")
```

### Documentation Style

- Use clear headings (##, ###)
- Include code blocks with syntax highlighting
- Add tables for comparisons
- Use emojis for visual appeal
- Include screenshots
- Write in clear, simple English

---

## ⚖️ License

By contributing, you agree that your contributions will be licensed under the MIT License.

---

## 🙏 Recognition

Contributors will be:
- Listed in README.md
- Credited in indicator comments
- Mentioned in release notes
- Given contributor badge

---

## 📞 Questions?

- 💬 Open a [Discussion](https://github.com/IamTamheedNazir/tradingview-indicators-pro/discussions)
- 📧 Email: ganiepay@gmail.com
- 🐛 Report issues: [GitHub Issues](https://github.com/IamTamheedNazir/tradingview-indicators-pro/issues)

---

## 🌟 Thank You!

Every contribution, no matter how small, helps make this project better for everyone!

**Happy Contributing! 🚀**