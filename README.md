# JDRC17 – The 17th Japan Drosophila Research Conference

Website for JDRC17, jointly held with Japan-Taiwan Fly Symposium 2026.

- **Dates:** November 4–6, 2026
- **Venue:** Multi-purpose Digital Hall, West Building 9, Ookayama Campus, Institute of Science Tokyo
- **Organizer:** JDRC17 Office, Institute of Science Tokyo

## Pages

| File | Description |
|---|---|
| `index.html` | Top page |
| `about.html` | About the conference and organizing committee |
| `registration.html` | Registration fees and how to register |
| `abstract.html` | Abstract submission guidelines |
| `participants.html` | Presentation guidelines and social events |
| `venue.html` | Venue information and access |
| `program.html` | Tentative conference program |
| `contact.html` | Contact information (JDRC17 Office) |

## Local preview

```bash
./serve.sh
```

Open http://localhost:8080 in your browser. Press Ctrl+C to stop.

## Sponsor logos

Logos are shown on `index.html` (strip above "Welcome") and `about.html` ("Sponsors & Supporters").
Each logo belongs to its respective company and is used only to credit JDRC17 sponsorship.

| File | Sponsor | Source (official site) |
|---|---|---|
| `images/nikon_logo.svg` | Nikon | https://www.jp.nikon.com/ |
| `images/oxford_instruments_logo.png` | Oxford Instruments | https://www.oxinst.com/ |
| `images/zeiss_logo.svg` | Carl Zeiss Co., Ltd. | https://www.zeiss.co.jp/ |
| `images/drobot_logo.png` | DroBot Biotechnology | https://www.drobot.com.tw/ |

To add a sponsor, put the logo in `images/`, add an `<a class="sponsor-item">` to the `.sponsor-grid` in both pages, and add a row above. Card and logo-box sizes are set in `style.css` (`.sponsor-item img`), so no per-logo sizing is needed.

## TODO

- [ ] Update contact email address in `contact.html`
- [ ] Add plenary speaker name and affiliation in `index.html` and `program.html`
- [ ] Fill in organizing committee members in `about.html`
- [ ] Remove demo banner (`demo-banner`) when the site goes live
- [ ] Update `robots.txt` to allow indexing when the site goes live
