# learningsprint3

An educational, browser-based visualization that teaches the main ways web sessions get hijacked, and which security settings stop each one.

## Purpose

Session hijacking is the exploitation of a valid session to gain unauthorized access. This lab lets students change security settings and immediately see whether an attack succeeds, with a step-by-step explanation of why.

## Features

- **Scenario dropdown** covering seven attack methods: packet sniffing, predictable tokens, DNS cache poisoning, mixed HTTPS/HTTP content, XSS, side channels and memory leakage, and CSRF.
- **Toggles** for HTTPS, the Secure and HttpOnly cookie flags, token rotation, and a SameSite dropdown.
- **Entropy slider** (8 to 128 bits) with a calculator showing the expected number of guesses needed to brute-force a token.
- **Step log** that shows what the victim, server, and attacker do in each scenario.

## How to Run

No installation is needed.

1. Download or clone this repository.
2. Open `index.html` in any modern browser.

Or use GitHub Pages: go to **Settings > Pages**, choose the `main` branch, and open the published link.

## Safety Note

This is a simulation for teaching. It does not send network traffic, contact any server, or contain working exploit code. Token values are random samples generated in the browser
