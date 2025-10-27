# Resume Dashboard — Streamlit

A modern, interactive resume dashboard for **Teja Naidu Chintha**, showcasing data-science impact, skills, experience timeline, and projects. Built with **Streamlit** + **Plotly** to demonstrate dashboard craftsmanship.

## Quickstart

```bash
# 1) Create a virtualenv (optional but recommended)
python -m venv .venv && source .venv/bin/activate  # Windows: .venv\Scripts\activate

# 2) Install deps
pip install -r requirements.txt

# 3) Run
streamlit run app.py
```

The app reads from `resume_data.json`. Edit this file to update content (skills, KPIs, projects).

## Deploy (Streamlit Community Cloud)

1. Push this folder to a GitHub repo.
2. On **share.streamlit.io**, create a new app → pick your repo → set **Main file path** to `app.py`.
3. Add the file **requirements.txt** in the repo root.
4. Deploy — you’ll get a public URL you can share.

## Customize

- Add a profile photo: in `app.py`, create an `st.sidebar.image("photo.png")` and include the file.
- Add more sections: follow the `Projects`/`Experience` card pattern.
- Plug in live metrics: replace the demo ROC chart with real model-monitoring metrics.

---

**Tip:** Use this dashboard in job applications to highlight both your **ML impact** and **dashboard design skill**.