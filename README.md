# Easy Boolean Builder for Naukri Recruiters

A simple tool to build clean Boolean search queries for Naukri.
https://vishal-dembla.github.io/Boolean-Builder-for-Naukri/

---

## What It Does
This tool helps recruiters generate perfectly formatted Boolean queries for Naukri Resdex. It eliminates the need to manually type operators, quotes, and parentheses — letting you:
- Focus on keywords, not syntax
- Avoid Boolean errors
- Speed up sourcing for complex roles

---

## Why This Exists
Naukri's Advanced Search supports Boolean logic, but its syntax rules can be tricky — especially when mixing OR, AND, and NOT. Many recruiters waste time debugging broken queries. This builder simplifies the process using a clean 3-box system.

---

## Features
- Separate input boxes for Any (OR), All (AND), and Exclude (NOT)
- Live Boolean query preview with auto-formatting
- Automatic quote and parenthesis handling
- Built-in syntax validation and error warnings
- Character count alert (500-char limit for Naukri)
- Copy to clipboard functionality
- Launch directly in Naukri (if logged in)
- Local save/export for reusable queries

---

## Example Output
Input:
- Any: Marketing Manager, Brand Manager
- All: Promotion, Pricing
- Exclude: FMCG, Consumer Durable

Output:
```
("Marketing Manager" OR "Brand Manager") AND ("Promotion" AND "Pricing") AND NOT ("FMCG" OR "Consumer Durable")
```

---

## Tech Stack
- HTML, Tailwind CSS (utility-first styling)
- Vanilla JavaScript (no frameworks)
- LocalStorage for saving queries
- No server or backend

---

## How to Use
1. Enter keywords in the relevant boxes:
   - Any: synonyms or alternate titles
   - All: must-have skills or experience
   - Exclude: roles or industries to avoid
2. Watch the live Boolean preview below update instantly.
3. Copy and paste the query into Naukri Resdex.
4. Use the Save or Export options to reuse later.

---

## License
MIT

## Author
Vishal Dembla – [LinkedIn](https://www.linkedin.com/in/vishaldembla1/)
