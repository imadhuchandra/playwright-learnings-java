# 📘 Playwright CLI Commands (Java-Focused)

Here’s a complete and updated list of common `npx playwright` commands you can use with the Playwright CLI.

---

## 🧪 Basic Commands

| Command | Description |
|--------|-------------|
| `npx playwright install` | Install all supported browsers (Chromium, Firefox, WebKit) |
| `npx playwright install <browser>` | Install only a specific browser (e.g., chromium, firefox, webkit) |
| `npx playwright uninstall` | Remove installed browsers |
| `npx playwright test` | Run all tests in the `tests` directory (default) |
| `npx playwright test <filename>` | Run a specific test file |
| `npx playwright test --project=<project-name>` | Run tests using a specific project config |
| `npx playwright test --grep <regex>` | Run only tests matching the name regex |
| `npx playwright show-report` | Open the Playwright HTML test report |

---

## 🎥 Code Generation & Debug

| Command | Description |
|--------|-------------|
| `npx playwright codegen <url>` | Launch the browser and generate code by recording interactions |
| `npx playwright codegen` | Launch blank browser to record |
| `npx playwright codegen --target=java` | Generate Playwright Java code |
| `npx playwright codegen --target=java --output=myTest.java <url>` | Record and save Java test code |
| `npx playwright codegen --save-storage=state.json` | Save local/session storage during recording |

---

## 🌍 Browsers & Devices

| Command | Description |
|--------|-------------|
| `npx playwright install-deps` | Install OS dependencies required for browsers (Linux) |
| `npx playwright open <url>` | Open a browser in headed mode (great for debugging) |
| `npx playwright devices` | List available emulated devices |
| `npx playwright install chromium` | Install only Chromium browser |
| `npx playwright install firefox` | Install only Firefox browser |
| `npx playwright install webkit` | Install only WebKit browser |

---

## 🧰 Utilities

| Command | Description |
|--------|-------------|
| `npx playwright update` | Update Playwright to the latest version |
| `npx playwright debug` | Launch the Playwright inspector debugger |
| `npx playwright cr <url>` | Record a HAR file (network trace) for Chrome |
| `npx playwright screenshot <url>` | Capture screenshot of a page |
| `npx playwright pdf <url>` | Generate PDF (only works in Chromium) |
| `npx playwright video` | Record video of a session (requires script setup) |

---

## 📦 Project Setup

| Command | Description |
|--------|-------------|
| `npx playwright init` | Scaffold a new Playwright project |
| `npx playwright install` | Install Playwright browsers (part of init flow) |
