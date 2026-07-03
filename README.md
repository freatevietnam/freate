# Freate

> **Free** + **Create** — where freedom meets creativity.

The official landing page for the Freate open-source organization, hosted at **freate.io.vn**.

## About

Freate is a Vietnamese open-source organization founded by **Nguyễn Minh Khôi**, building high-quality, secure, and accessible technology products.

### Projects

| Project | Description | Tech Stack |
|---------|-------------|------------|
| [Freate Diary](https://github.com/freatevietnam/freatediary) | AES-256-GCM encrypted diary | Rust, Actix-web, SQLite |
| [Freate Drop](https://github.com/freatevietnam/freatedrop) | Anonymous Markdown sharing | Python/Django & Rust/Actix |
| [FreateOJ](https://github.com/freatevietnam/freateoj) | Online Judge — 56+ languages | Python/Django, Docker |

## Stack

- Pure HTML5 / CSS3 / JavaScript (no frameworks)
- Google Fonts (Inter)
- Gradient animations, scroll reveal, counter animation

## Structure

```
freate/
├── index.html
├── favicon.svg
├── logo.svg
├── css/
│   └── style.css
├── js/
│   └── script.js
├── README.md
├── LICENSE
├── CONTRIBUTING.md
├── SECURITY.md
└── .gitignore
```

## Development

```bash
git clone https://github.com/freatevietnam/freate.git
cd freate

python3 -m http.server 8000
# or
npx serve .
```

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

MIT © 2026 Freate
