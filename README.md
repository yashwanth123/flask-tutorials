# 🌐 Flask Tutorials Collection

This repository contains a set of mini-projects and tutorials using the **Flask web framework** in Python. Each subdirectory explores a different concept — from Jinja templating to blog creation and API rendering.

---

## 🧩 Projects Included

### 🔷 1. `Jinjia/`
- Renders a CSV (`London.csv`) to a table using **Jinja2 templating**
- Basic Flask + HTML data integration
- Routes: `/`, `/data`

### 🔷 2. `analytics/`
- Loads an external `api.json` file and renders statistics using Flask
- Template: `stats.html`
- Good example for working with APIs or JSON files

### 🔷 3. `bf_encrypt/`
- Reads a `.csv` and includes basic encryption logic (possibly brute-force related)
- Uses jQuery (`jquery-3.4.0.js`) for frontend interaction

### 🔷 4. `blog/`
- Full-featured blog system split into:
  - `back-end`: SQLite database + core logic
  - `front-end`: Post creation, editing, deletion
- Templates: `create.html`, `edit.html`, `layout.html`
- Uses Flask routing and SQL integration

---

## 🛠 Tech Stack

- Python 3.x
- Flask (lightweight web framework)
- Jinja2 (templating)
- SQLite (blog module)
- HTML/CSS/JS for frontend
- jQuery (used in `bf_encrypt`)

---

## ▶️ How to Run (General)

Each folder contains its own `app.py`. Navigate into any folder and run:

```bash
cd folder_name
python app.py
