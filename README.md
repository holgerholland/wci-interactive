# World Cleanup Institute — Interactive Structure

An interactive, single-page web application visualising the organisational and programmatic structure of the **World Cleanup Institute (WCI)**. Built as a standalone HTML file with no external dependencies beyond Google Fonts.

## 📁 Repository Structure

```
wci-interactive/
├── index.html          # Main application (self-contained SPA)
├── README.md           # This file
├── CHANGELOG.md        # Version history
├── LICENSE             # Licence terms
└── docs/
    └── structure.md    # Content outline & navigation map
```

## 🚀 Quick Start

No build step required. Simply open `index.html` in any modern browser:

```bash
# Option 1 — direct file
open index.html

# Option 2 — local dev server (recommended)
npx serve .
# or
python3 -m http.server 8080
```

Then navigate to `http://localhost:8080`.

## 🧭 Navigation Sections

| Section | Description |
|---|---|
| **Overview** | Institute mission, structure, and strategic pillars |
| **Research** | Research clusters: Environmental Action, Circular Economy, Social Innovation, Impact Measurement |
| **ISO 26000 Framework** | Alignment with the ISO 26000 social responsibility standard |
| **Innovation Hub** | Community Projects, Conference/Summit, We Create Future initiative |
| **Impact Entrepreneurship Lab** | Startup Programme, Innovation Workshops, Guest Lectures, Incubation, CE Labs |
| **Partnerships** | Academic partners, NGO collaboration, City partnerships |
| **Certification Network** | World Cleanup Certified Network — onboarding, community, annual review |
| **Learning** | Project-Based Learning, Student Impact Projects, ACASOL, Research Assistants |
| **Governance** | Board structure, committees, legal framework |
| **Funding** | Revenue streams and impact investment |
| **Roadmap** | Strategic milestones and timeline |

## 🛠 Technical Details

- **Type:** Single-page application (SPA), self-contained HTML
- **Styling:** Inline CSS with CSS custom properties (design tokens)
- **Fonts:** Barlow, Barlow Condensed, Barlow Semi Condensed (Google Fonts)
- **Colour Palette:**
  - Navy `#2B3990` / Amber `#D4883A` / Mint `#1fb87a`
- **JavaScript:** Vanilla JS — sidebar navigation, section toggling, page routing
- **No frameworks, no build pipeline, no dependencies**

## 📋 Browser Support

| Browser | Support |
|---|---|
| Chrome / Edge | ✅ Full |
| Firefox | ✅ Full |
| Safari | ✅ Full |
| Mobile (iOS/Android) | ✅ Responsive |

## 📄 Versioning

Current version: **v3** (`WCI_Interactive_v3.html`)

See [`CHANGELOG.md`](./CHANGELOG.md) for full version history.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m 'Add: description of change'`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a Pull Request

## 📬 Contact

World Cleanup Institute — [worldcleanup.org](https://worldcleanup.org)
