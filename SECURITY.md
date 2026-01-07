# Security Policy

## Supported Versions

We release patches for security vulnerabilities in the following versions:

| Version | Supported          |
| ------- | ------------------ |
| 1.0.x   | :white_check_mark: |

## Reporting a Vulnerability

We take the security of our indicators seriously. If you discover a security vulnerability, please follow these steps:

### 1. Do Not Publicly Disclose

Please do not open a public GitHub issue for security vulnerabilities.

### 2. Report Privately

Send an email to: **ganiepay@gmail.com**

Include:
- Description of the vulnerability
- Steps to reproduce
- Potential impact
- Suggested fix (if any)

### 3. Response Timeline

- **Initial Response:** Within 48 hours
- **Status Update:** Within 7 days
- **Fix Release:** Within 30 days (depending on severity)

### 4. Disclosure Policy

- We will acknowledge your report within 48 hours
- We will provide regular updates on our progress
- We will credit you in the security advisory (unless you prefer to remain anonymous)
- We will notify you when the vulnerability is fixed

## Security Best Practices

### For Users

1. **Always verify code source**
   - Only use indicators from official repository
   - Check commit history
   - Verify author

2. **Review code before use**
   - Pine Script is open source
   - Check for suspicious functions
   - Understand what the code does

3. **Use secure connections**
   - Always use HTTPS
   - Enable 2FA on TradingView
   - Use strong passwords

4. **Protect your API keys**
   - Never share API keys in indicators
   - Use read-only API keys when possible
   - Rotate keys regularly

5. **Be cautious with webhooks**
   - Verify webhook URLs
   - Use authentication
   - Monitor webhook activity

### For Contributors

1. **Code Review**
   - All code must be reviewed
   - Check for security issues
   - Test thoroughly

2. **No Sensitive Data**
   - Never commit API keys
   - Never commit passwords
   - Never commit personal information

3. **Dependencies**
   - Keep dependencies updated
   - Review third-party code
   - Use trusted sources

4. **Input Validation**
   - Validate all user inputs
   - Sanitize data
   - Handle errors gracefully

## Known Security Considerations

### Pine Script Limitations

1. **No Network Access**
   - Pine Script cannot make external API calls
   - Cannot access files
   - Cannot execute system commands

2. **Sandboxed Environment**
   - Runs in TradingView's sandbox
   - Limited to chart data
   - Cannot access other indicators

3. **No Sensitive Data Storage**
   - Cannot store passwords
   - Cannot access account information
   - Cannot execute trades directly

### Webhook Security

If using webhooks for automation:

1. **Use HTTPS only**
2. **Implement authentication**
3. **Validate incoming data**
4. **Rate limit requests**
5. **Log all activity**
6. **Monitor for suspicious patterns**

## Trading Security

### Risk Warnings

1. **No Financial Advice**
   - Indicators are tools, not advice
   - Do your own research
   - Understand the risks

2. **Test Before Live Trading**
   - Use demo accounts
   - Backtest strategies
   - Start with small positions

3. **Protect Your Capital**
   - Use stop losses
   - Manage position sizes
   - Never risk more than you can afford to lose

4. **Beware of Scams**
   - No guaranteed profits
   - No "holy grail" indicators
   - Be skeptical of unrealistic claims

## Incident Response

If a security incident occurs:

1. **Immediate Actions**
   - Assess the impact
   - Contain the issue
   - Notify affected users

2. **Investigation**
   - Determine root cause
   - Document findings
   - Implement fixes

3. **Communication**
   - Transparent updates
   - Clear timeline
   - Remediation steps

4. **Prevention**
   - Update security measures
   - Improve processes
   - Learn from incident

## Security Updates

We will announce security updates through:

- GitHub Security Advisories
- Repository README
- Email notifications (for critical issues)

## Contact

For security concerns:
- 📧 Email: ganiepay@gmail.com
- 🔒 PGP Key: Available upon request

For general questions:
- 💬 [GitHub Discussions](https://github.com/IamTamheedNazir/tradingview-indicators-pro/discussions)
- 🐛 [GitHub Issues](https://github.com/IamTamheedNazir/tradingview-indicators-pro/issues)

---

**Last Updated:** January 7, 2026

**Thank you for helping keep TradingView Indicators Pro secure!**