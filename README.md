# Yoga Consultings

A modern, distinctive landing page for a yoga consultation business. The design is built around the idea at the center of the practice itself — breath — with a live breathing-pace animation as the page's signature element, framed by a warm stone-and-moss palette and editorial serif type.

## Features

- 🫁 **Signature breath widget** — a hero-level animation that visually paces box breathing (inhale 4s / hold 4s / exhale 4s / hold 4s), synced to a live label and countdown
- 🎨 Custom design system — warm stone background, deep moss and muted mauve accents, no stock template palette
- ✍️ Editorial type pairing — Fraunces (display serif) + Manrope (body) + IBM Plex Mono (labels/eyebrows)
- 📱 Fully responsive, down to small mobile screens, with a working mobile nav menu
- 🌀 Scroll-reveal animation, respecting `prefers-reduced-motion`
- 🧘 Service cards, about section, and contact section built around real service copy
- ♿ Visible keyboard focus and accessible landmarks

## Sections

| Section | Description |
|---------|-------------|
| Hero | Split layout — headline and CTA on one side, live breathing-pace animation on the other |
| Services | Private Sessions, Group Classes, and Wellness Consultation |
| About | Studio mission, told as a conversation, with a pull quote |
| Contact | Call-to-action to book a first consultation |

## Getting Started

Clone the repository:

```bash
git clone https://github.com/MoAbdi358/yoga-consultings.git
```

Open the project folder:

```bash
cd yoga-consultings
```

Launch the website by opening `index.html` in your browser, or use a local development server such as:

```bash
npx serve .
```

## Project Structure

```text
.
├── index.html
├── style.css
└── README.md
```

## Technologies Used

- HTML5
- CSS3 (custom properties / design tokens, CSS Grid, hairline-grid card layout)
- Vanilla JavaScript (breath-pacer animation, scroll-reveal via IntersectionObserver, sticky header, mobile nav)
- Google Fonts — Fraunces, Manrope, IBM Plex Mono

## Services

- 🧘 Private Yoga Sessions
- 👥 Group Yoga Classes
- 🌱 Wellness Consultation
- 💚 Mindfulness & Healthy Lifestyle Guidance

## Design Highlights

- **Signature element:** an animated breathing-pace circle in the hero, tying the page's one moment of visual boldness directly to the subject of the business
- Restrained, hairline-grid service cards instead of heavy drop-shadow cards
- Stone/moss/mauve palette chosen to avoid generic "wellness template" cream-and-terracotta defaults
- Editorial serif + grotesque sans type pairing for a distinctive, non-templated voice
- Sticky header that compresses on scroll
- Accessible mobile navigation

## Future Improvements

- Online appointment booking
- Contact form with email integration
- Testimonials section
- Pricing plans
- Dark mode
- Instructor profiles

## License

This project is intended for educational and portfolio purposes.

---

**Yoga Consultings** — Helping people achieve balance in mind, body, and life, one breath at a time.
