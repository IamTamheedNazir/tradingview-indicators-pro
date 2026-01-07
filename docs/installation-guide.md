# 📖 Installation Guide

Complete guide to installing and using TradingView Indicators Pro.

---

## 🚀 Quick Start (3 Minutes)

### Step 1: Open TradingView

1. Go to [TradingView.com](https://www.tradingview.com/)
2. Sign in to your account (or create free account)
3. Open any chart (e.g., BTC/USDT)

### Step 2: Access Pine Editor

1. Click **"Indicators"** button at top of chart
2. Click **"Pine Editor"** tab at bottom of screen
3. You'll see a code editor panel

### Step 3: Copy Indicator Code

1. Go to this repository: [TradingView Indicators Pro](https://github.com/IamTamheedNazir/tradingview-indicators-pro)
2. Navigate to `indicators/` folder
3. Click on the indicator you want (e.g., `live-market-scanner-v7.pine`)
4. Click **"Raw"** button
5. Copy all the code (Ctrl+A, Ctrl+C)

### Step 4: Paste and Add to Chart

1. Go back to TradingView Pine Editor
2. Delete any existing code
3. Paste the copied code (Ctrl+V)
4. Click **"Add to Chart"** button (top right of editor)
5. Done! ✅

---

## 📺 Video Tutorial

[Watch Installation Video](https://www.youtube.com/watch?v=example) *(Coming Soon)*

---

## 🎯 Detailed Installation

### For Beginners

#### What is Pine Script?

Pine Script is TradingView's programming language for creating custom indicators and strategies. Don't worry - you don't need to know programming! Just copy and paste.

#### What You Need

- ✅ TradingView account (free or paid)
- ✅ Internet browser
- ✅ 3 minutes of time

#### Step-by-Step with Screenshots

**1. Open TradingView Chart**

![Open Chart](./images/step1-open-chart.png)

- Go to TradingView.com
- Click "Chart" in top menu
- Select any trading pair (BTC/USDT recommended for testing)

**2. Open Indicators Menu**

![Indicators Button](./images/step2-indicators.png)

- Look for "Indicators" button at top of chart
- Click it to open indicators menu

**3. Open Pine Editor**

![Pine Editor](./images/step3-pine-editor.png)

- At bottom of screen, click "Pine Editor" tab
- You'll see a code editor with some default code

**4. Get Indicator Code**

![Get Code](./images/step4-get-code.png)

- Open this GitHub repository in new tab
- Go to `indicators/` folder
- Click on indicator file (e.g., `live-market-scanner-v7.pine`)
- Click "Raw" button to see plain code
- Select all (Ctrl+A) and copy (Ctrl+C)

**5. Paste Code**

![Paste Code](./images/step5-paste-code.png)

- Go back to TradingView Pine Editor
- Delete existing code (Ctrl+A, Delete)
- Paste copied code (Ctrl+V)

**6. Add to Chart**

![Add to Chart](./images/step6-add-to-chart.png)

- Click "Add to Chart" button (top right of Pine Editor)
- Indicator will appear on your chart!

**7. Configure Settings**

![Settings](./images/step7-settings.png)

- Click indicator name on chart
- Click gear icon ⚙️ to open settings
- Adjust settings as needed
- Click "OK"

---

## ⚙️ Configuration

### Accessing Settings

1. Click on indicator name on chart
2. Click gear icon ⚙️
3. Settings panel will open

### Common Settings

#### Live Market Scanner V7

| Setting | Options | Recommended |
|---------|---------|-------------|
| Signal Sensitivity | Low/Medium/High | Medium |
| Show Future Candles | On/Off | On |
| Show TP/SL Levels | On/Off | On |
| Show Live Dashboard | On/Off | On |

#### Smart Money Concepts

| Setting | Options | Recommended |
|---------|---------|-------------|
| Show Order Blocks | On/Off | On |
| Show Fair Value Gaps | On/Off | On |
| Show Break of Structure | On/Off | On |
| Show Liquidity Zones | On/Off | On |
| Order Block Lookback | 5-100 | 20 |

#### Multi-Timeframe Trend

| Setting | Options | Recommended |
|---------|---------|-------------|
| Timeframe 1 | Any | 5m |
| Timeframe 2 | Any | 15m |
| Timeframe 3 | Any | 1H |
| Timeframe 4 | Any | 4H |
| Timeframe 5 | Any | 1D |
| EMA Length | 1-200 | 50 |

---

## 🔔 Setting Up Alerts

### Create Alert

1. **Right-click on chart**
2. **Select "Add Alert"** (or press Alt+A)
3. **Configure alert:**
   - Condition: Select your indicator
   - Choose specific condition (e.g., "Long Entry")
   - Alert name: Give it a descriptive name
   - Message: Customize alert message
4. **Choose notification method:**
   - ✅ Popup
   - ✅ Email
   - ✅ SMS (paid plans)
   - ✅ Webhook (for automation)
5. **Click "Create"**

### Alert Examples

**Long Entry Alert:**
```
Condition: Live Market Scanner V7 - Long Entry
Message: 🚀 LONG Signal on {{ticker}} at {{close}}
Notifications: Email + Popup
```

**Short Entry Alert:**
```
Condition: Live Market Scanner V7 - Short Entry
Message: 🔻 SHORT Signal on {{ticker}} at {{close}}
Notifications: Email + Popup
```

**Breakout Alert:**
```
Condition: Support & Resistance - Resistance Breakout
Message: ⚡ Breakout on {{ticker}} - Price: {{close}}
Notifications: Email + SMS
```

---

## 🔧 Troubleshooting

### Common Issues

#### "Script could not be translated from: null"

**Solution:**
- Make sure you copied ALL the code
- Check that first line is `//@version=5`
- Try copying code again from "Raw" view

#### "Compilation error"

**Solution:**
- Delete all code in Pine Editor
- Copy fresh code from repository
- Make sure you're using latest version

#### "Indicator not showing on chart"

**Solution:**
- Check if indicator is in indicator list (left side)
- Click eye icon 👁️ to show/hide
- Try removing and re-adding indicator

#### "Dashboard not visible"

**Solution:**
- Check indicator settings
- Enable "Show Live Dashboard"
- Zoom out on chart if dashboard is off-screen

#### "Too many signals" or "No signals"

**Solution:**
- Adjust sensitivity settings
- Try different timeframe
- Check if market is too choppy

---

## 📱 Mobile Installation

### TradingView Mobile App

**Note:** Pine Editor is not available on mobile app. You must add indicators from desktop first.

**Steps:**
1. Install indicators on desktop (follow guide above)
2. Save chart layout
3. Open TradingView mobile app
4. Load saved chart layout
5. Indicators will appear!

---

## 💻 Desktop App vs Browser

### Browser (Recommended for Installation)
✅ Full Pine Editor access
✅ Easy copy/paste
✅ Works on any OS

### Desktop App
✅ Better performance
✅ More stable
✅ Offline charts
❌ Pine Editor same as browser

**Recommendation:** Use browser for installation, then switch to desktop app for trading.

---

## 🔄 Updating Indicators

### When Updates Are Released

1. Go to repository
2. Check if new version available
3. Copy new code
4. Paste in Pine Editor (replace old code)
5. Click "Add to Chart"
6. Old version will be replaced

### Auto-Update (Future Feature)

We're working on auto-update functionality. For now, check repository regularly for updates.

---

## 📊 Multiple Indicators

### Adding Multiple Indicators

You can add multiple indicators to same chart:

1. Add first indicator (follow installation guide)
2. Open Pine Editor again
3. Click "+" button to create new indicator
4. Paste second indicator code
5. Click "Add to Chart"
6. Repeat for more indicators

### Recommended Combinations

**Combo 1: Complete Analysis**
- Live Market Scanner V7
- Smart Money Concepts
- Multi-Timeframe Trend Detector

**Combo 2: Breakout Trading**
- Support & Resistance Finder
- Volume Profile Analyzer
- Breakout Scanner

**Combo 3: Trend Following**
- Multi-Timeframe Trend Detector
- Market Structure Analyzer
- Momentum Oscillator Pro

---

## 🎓 Next Steps

After installation:

1. ✅ Read indicator documentation
2. ✅ Test on demo account
3. ✅ Learn trading strategies
4. ✅ Set up alerts
5. ✅ Practice risk management

---

## 📞 Need Help?

- 💬 [GitHub Discussions](https://github.com/IamTamheedNazir/tradingview-indicators-pro/discussions)
- 🐛 [Report Issue](https://github.com/IamTamheedNazir/tradingview-indicators-pro/issues)
- 📧 Email: ganiepay@gmail.com

---

## ✅ Installation Checklist

- [ ] TradingView account created
- [ ] Chart opened
- [ ] Pine Editor accessed
- [ ] Indicator code copied
- [ ] Code pasted in editor
- [ ] Indicator added to chart
- [ ] Settings configured
- [ ] Alerts set up
- [ ] Documentation read
- [ ] Ready to trade!

---

**🎉 Congratulations! You're ready to start using professional indicators!**

[← Back to README](../README.md) | [Next: Configuration Guide →](./configuration-guide.md)