

<div align="center" style="background: linear-gradient(135deg, #0a192f 0%, #1e3a8a 100%); padding: 2rem; border-radius: 12px; box-shadow: 0 4px 8px rgba(0,0,0,0.15);">
  
# 🔐 KeysKit — API Keys Validation
 <img src="https://raw.githubusercontent.com/MrMax4o4/testrepo/main/Assets/shield-lock.svg" width="28" style="filter: drop-shadow(0 0 2px #64ffda)">

[![Website](https://img.shields.io/badge/Visit-kkit.io-blue)](https://kkit.io)

[![Counter](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/MrMax4o4/KeysKit/contents/templates&label=ACTIVE%20TEMPLATES%20COUNT&query=%24.length&color=e6f1ff&style=for-the-badge&logo=github&logoColor=e6f1ff&labelColor=1a365d)](https://github.com/MrMax4o4/KeysKit/tree/main/templates)

[![KeySkit Demo](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=16&duration=3000&pause=1000&color=1a365d&background=0a192f00&width=600&lines=curl-ready+API+checks+for+750%2B+providers;1-liner+verification+for+every+bounty+submission;Stop+wasting+time+on+dead+keys+-+validate+first;No+docs+digging+or+custom+scripts+needed&center=true&vCenter=true)](https://github.com/MrMax4o4/KeySkit)

</div>

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
- Use "\$Variable" format for any dynamic user input.
- Add a helpful description so users understand what the API does.
- If the body is empty, just use an empty string ("").
- Only include public information — never add real API keys
---

## 💖 Support the Project

If you found this tool useful, consider buying me a coffee to support its development:

[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-support-orange?logo=buy-me-a-coffee&style=flat-square)](https://www.buymeacoffee.com/kkit)

---

## ✨ Contributors

Thanks goes to these wonderful people 🖋 🔣:

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/a7med-tal3at"><img src="https://avatars.githubusercontent.com/u/63285291?v=4?s=100" width="100px;" alt="a7med-tal3at"/><br /><sub><b>a7med-tal3at</b></sub></a><br /><a href="#content-a7med-tal3at" title="Content">🖋</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

Contributions of any kind are welcome!

---
## ⚠️ Legal

Keyskit is meant for **educational and legitimate testing purposes only**. Always make sure you’re testing keys you own or have permission to test.

---

## 📄 License

Licensed under the [MIT License](LICENSE).
