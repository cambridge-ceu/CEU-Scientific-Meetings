# Chapter 6. Sharing with the internet

## Setup

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
mkdir c6
cd c6
wget https://raw.githubusercontent.com/writeson/the-well-grounded-python-developer/integration/examples/CH_06/requirements.txt
pip install -r requirements.txt
```

## Files

```
c6
├── app.py
├── app.sav
├── requirements.txt
├── static
│   ├── css
│   │   ├── index.css
│   │   └── myblog.css
│   └── js
│       └── index.js
└── templates
    ├── base.html
    ├── index.html
    └── index.sav
```

where .sav is the simple version described under <https://cambridge-ceu.github.io/CEU-scientific-meetings/Flask/>.

## Run

This is as before.