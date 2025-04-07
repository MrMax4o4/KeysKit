# 🔐 Keyskit — API Keys Validation

[![Website](https://img.shields.io/badge/Visit-kkit.io-blue)](https://kkit.io)

**Keyskit** is a lightweight tool built for bug bounty hunters and developers to quickly test if an API key is valid — no need to dig through docs or write a script.

Just select a provider, copy the command, and test it locally on your own terminal.

---

## ✨ Features

- 🧪 Ready-to-use `curl` commands copy & test
- 🔍 Supports many common providers
- ⚡ Lightweight and easy to use

---

## 🌐 Try it online

👉 Visit [**kkit.io**](https://kkit.io) and test your API keys in seconds.

---

## 📸 Preview

![SiteScreenshot](Assets/SiteScreenshot.png "SiteScreenshot")

---

## 🧩 Contribution Guidelines

We welcome your contributions! If you'd like to add a new API key template, please follow these simple rules:

### 📁 File Naming
- Use clear and consistent naming:  
  e.g., `Stripe.json`, `Slack_API.json`, `AWS_Token.json`
- File must be saved in the **Templates directory** of the repo.

### 🔧 Template Structure
Each file should follow this JSON structure:

```json
{
  "name": "Provider Name - Auth Type",
  "method": "GET or POST",
  "header": "'Header-Key':'Value','Another-Header':'AnotherValue'",
  "url": "https://api.provider.com/endpoint",
  "body": "param1=$API_KEY&param2=value",
  "note": "Optional notes or tips for users",
  "description": "Brief explanation of the provider or endpoint purpose"
}
```

### 🧠 Tips
- Use \$Variable format for any dynamic user input.
- Add a helpful description so users understand what the API does.
- If the body is empty, just use an empty string ("").
- Only include public information — never add real API keys
---

## 💖 Support the Project

If you found this tool useful, consider buying me a coffee to support its development:

[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-support-orange?logo=buy-me-a-coffee&style=flat-square)](https://www.buymeacoffee.com/kkit)

---
## ⚠️ Legal

Keyskit is meant for **educational and legitimate testing purposes only**. Always make sure you’re testing keys you own or have permission to test.

---

## 📄 License

Licensed under the [MIT License](LICENSE).
