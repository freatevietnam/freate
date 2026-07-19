# Freate Vietnam Landing Page

> **Free** + **Create** — Where freedom meets creativity.

The official landing page repository for **Freate Vietnam** open-source organization, hosted live at **[freate.io.vn](https://freate.io.vn)**.

## About Freate

Freate is a Vietnamese open-source technology organization founded by **Nguyễn Minh Khôi**, dedicated to developing high-performance, secure, and accessible software tools for everyone.

### Member Projects

| Project | Description | Tech Stack | Repository |
|---|---|---|---|
| **Freate Diary** | End-to-end encrypted digital diary | Rust, Actix-web, SQLite, Hardware AES-256-GCM | [freatediary](https://github.com/freatevietnam/freatediary) |
| **Freate Drop** | Instant anonymous Markdown sharing | Python/Django & Rust/Actix-Web, Fernet/AES-256-GCM | [freatedrop](https://github.com/freatevietnam/freatedrop) / [freatedrop-rust](https://github.com/freatevietnam/freatedrop-rust) |
| **FreateOJ** | Online Judge platform supporting 56+ languages | Python/Django, Docker Sandbox, Socket.IO | [freateoj](https://github.com/freatevietnam/freateoj) |
| **FreateOJ Wiki Builder** | Cross-platform Desktop GUI Wiki bundler | Rust, egui, SQLite, htmx | [freateoj-buildwiki](https://github.com/freatevietnam/freateoj-buildwiki) |
| **FreateOJ Docs** | Official Online Judge documentation | Static HTML, CSS | [freateoj-docs](https://freatevietnam.github.io/freateoj-docs/) |

## Tech Stack

- Native HTML5 / CSS3 (Custom Properties & Glassmorphism) / Vanilla ES6 JS
- Google Fonts (Inter & JetBrains Mono)
- URL Query Parameter Toast Alert System (`?message=...&messagetype=...`)
- Dark & Light theme switcher

## Local Development

```bash
git clone https://github.com/freatevietnam/freate.git
cd freate

# Run a local web server
python3 -m http.server 8000
# or
npx serve .
```

Then visit `http://localhost:8000`.

To test the URL notification alert feature:
`http://localhost:8000/?message=Test+Notice&messagetype=error`

## License

MIT © 2026 Freate Vietnam
