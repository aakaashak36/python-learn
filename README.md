# 🐍 Python Learning Roadmap

> **Who this is for:** A JavaScript developer who wants to expand their toolkit into data, automation, and beyond. Python will feel familiar fast — the concepts transfer, the syntax is just different.

---

## Phase 1 — Get Oriented (Week 1–2)

**Goal:** Understand how Python differs from JavaScript and get comfortable with the basics.

Since you already know JS, you're not starting from zero. You're translating.

| JavaScript | Python |
|---|---|
| `let x = 5` | `x = 5` |
| `console.log(x)` | `print(x)` |
| `function greet() {}` | `def greet():` |
| `array.map(fn)` | `[fn(x) for x in array]` |
| `===` | `==` |

### 📖 Official Docs
- [Python Official Tutorial](https://docs.python.org/3/tutorial/) — Chapters 1–5 (skip Chapter 1, start at 2)
- [Python Built-in Types](https://docs.python.org/3/library/stdtypes.html) — bookmark this, you'll return to it

### 🎥 YouTube
- **Programming with Mosh** — [Python for Beginners (6 hours)](https://www.youtube.com/watch?v=_uQrJ0TkZlc) — Start here. Mosh is clear, structured, and skips the fluff.
- **freeCodeCamp** — [Python Full Course (12 hours)](https://www.youtube.com/watch?v=rfscVS0vtbw) — Use this as a reference when Mosh moves too fast.

### Topics to Cover
- Variables, data types (int, float, str, bool, None)
- Lists, tuples, dictionaries, sets
- Conditionals and loops
- Functions and scope
- String formatting (f-strings especially)
- Reading/writing files

---

## Phase 2 — Think Pythonically (Week 3–4)

**Goal:** Write Python the way Python developers actually write it, not "JavaScript in Python syntax."

### 📖 Official Docs
- [List Comprehensions](https://docs.python.org/3/tutorial/datastructures.html#list-comprehensions)
- [Itertools](https://docs.python.org/3/library/itertools.html)
- [Python Standard Library Overview](https://docs.python.org/3/library/)

### 🎥 YouTube
- **Corey Schafer** — [Python OOP Tutorials (playlist)](https://www.youtube.com/playlist?list=PL-osiE80TeTsqhIuOqKhwlXsIBIdSeYtc) — The best OOP explainer on YouTube, bar none.
- **Corey Schafer** — [Python Comprehensions](https://www.youtube.com/watch?v=3dt4OGnU5sM) — Essential Pythonic syntax.

### Topics to Cover
- Classes and OOP (compare to JS classes — very similar!)
- List/dict/set comprehensions
- Lambda functions
- `*args` and `**kwargs`
- Modules and `import` system
- Error handling with `try/except`
- Virtual environments (`venv`)

---

## Phase 3 — The Ecosystem (Week 5–7)

**Goal:** Learn the libraries that make Python genuinely powerful.

### 📖 Official Docs
- [pip documentation](https://pip.pypa.io/en/stable/)
- [requests library](https://docs.python-requests.org/en/latest/)
- [pandas documentation](https://pandas.pydata.org/docs/)

### 🎥 YouTube
- **Tech With Tim** — [Python Automation Tutorials](https://www.youtube.com/@TechWithTim) — Practical, project-based automation.
- **Corey Schafer** — [Python pandas Tutorials (playlist)](https://www.youtube.com/playlist?list=PL-osiE80TeTsWmV9i9c58mdDCSskIFdDS) — The definitive pandas intro.
- **Sentdex** — [Python for Data Analysis](https://www.youtube.com/@sentdex) — Great for when you want to go deeper into data.

### Topics to Cover
- `requests` — fetch data from APIs (you'll find this familiar from `fetch()`)
- `pandas` — data manipulation (think spreadsheets in code)
- `matplotlib` — basic data visualization
- `os` and `pathlib` — working with files and directories
- `json` — you already know this concept from JS

---

## Phase 4 — Solidify with a Project (Week 8+)

**Goal:** Build something real that you're proud to put on GitHub.

### 📖 Official Docs
- [argparse — CLI argument parsing](https://docs.python.org/3/library/argparse.html)

### 🎥 YouTube
- **freeCodeCamp** — [Python Projects for Beginners](https://www.youtube.com/watch?v=8ext9G7xspg)

---

## 🏗️ Capstone Project: Medical Data Explorer CLI

**What you'll build:** A command-line tool that fetches real public health data and lets you explore it interactively.

**Description:** Using the [CDC Open Data API](https://dev.socrata.com/foundry/data.cdc.gov) or a downloaded CSV (e.g. from [Kaggle](https://www.kaggle.com/datasets)), build a CLI tool that:

1. Loads a health/disease dataset (e.g. COVID stats, flu rates, or hospital data)
2. Lets the user filter by state, year, or category via command-line flags
3. Displays a summary table in the terminal
4. Optionally saves a filtered CSV

**Skills practiced:** pandas, argparse, file I/O, string formatting, OOP (wrap your logic in a class), error handling

**Stretch goals:**
- Add a simple `matplotlib` bar chart output
- Scrape data live from a public health website using `requests` + `BeautifulSoup`
- Add a `--help` menu with usage examples

**Repo structure suggestion:**
```
python-health-explorer/
├── README.md
├── requirements.txt
├── data/
│   └── sample_data.csv
└── src/
    ├── main.py
    ├── loader.py
    └── explorer.py
```

---

## Ongoing References

| Resource | Use It For |
|---|---|
| [docs.python.org](https://docs.python.org/3/) | Official reference — always up to date |
| [Real Python](https://realpython.com/) | Deep-dive articles on specific topics |
| [PyPI](https://pypi.org/) | Finding packages |
| [Corey Schafer YouTube](https://www.youtube.com/@coreyms) | Going deeper on any topic |

---

*Next step after this roadmap: Pick a domain — web (FastAPI/Flask), data science (NumPy/scikit-learn), or automation — and go deep in that direction.*
