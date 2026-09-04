# Mizan Web (`mizan-web`)

[![CI Workflow](https://github.com/Bedru-Mekiyu/mizan-web/actions/workflows/ci.yml/badge.svg)](https://github.com/Bedru-Mekiyu/mizan-web/actions/workflows/ci.yml)
[![Repository Status](https://img.shields.io/badge/status-active-success.svg)](#)

Welcome to the **Mizan Web** repository. This project is part of Bedru Mekiyu's web engineering portfolio hosted on GitHub.

---

## 📌 Project Overview

`mizan-web` is structured as a dedicated repository for web interface components, frontend modules, and services within the Mizan system ecosystem.

---

## 🛠️ Project Structure

```
mizan-web/
├── .github/
│   └── workflows/
│       └── ci.yml          # Continuous Integration workflow
├── term1                   # Submodule / subproject reference
├── .gitignore              # Git ignore configuration
└── README.md               # Repository documentation
```

---

## 🚀 Workflows & Verification

Automated workflow validation is powered by GitHub Actions (`.github/workflows/ci.yml`), performing continuous health checks:
- Verifying workflow configuration syntax.
- Validating repository integrity and required project assets.

### Local Verification
To execute workflow validation locally:
```bash
python3 -c "import glob, yaml; [yaml.safe_load(open(f)) for f in glob.glob('.github/workflows/*.yml')]"
```

---

## 📄 License & Author

Maintained by **[Bedru Mekiyu](https://github.com/Bedru-Mekiyu)**.
