# 🛠️ Renovate Config

This repository contains the centralized configuration for [Renovate](https://github.com/renovatebot/renovate), used to manage dependency updates across multiple repositories.

---

## 📦 What is Renovate?

[Renovate](https://renovatebot.com/) is a tool that automatically creates Pull Requests to keep your dependencies up-to-date.
This repo holds shared configuration files that can be extended from any other repo.

---

## 🔧 Usage

To use this config in a project, add a `renovate.json` or `.github/renovate.json` file in the root of your target repository:

```json
{
  "extends": [
    "github>your-username/renovate-config"
  ]
}
