# 🎮 GTA Requirements

**Will your PC run Grand Theft Auto VI?**

GTA Requirements is an unofficial fan-made website that helps users estimate whether their PC may be capable of running *Grand Theft Auto VI* based on predicted system requirements.

The project combines a PC specification checker, estimated hardware requirements, a release countdown, and an email notification form into a single, easy-to-use website.

> ⚠️ **Important:** The system requirements presented on this website are community-based predictions, not official specifications published by Rockstar Games.

## ✨ Features

- 🖥️ **PC Compatibility Checker** — Select your CPU, GPU, and RAM to receive an estimated compatibility verdict.
- ⚙️ **Predicted System Requirements** — Compare your hardware against estimated minimum, recommended, high-end, and 4K hardware tiers.
- ⏳ **Release Countdown** — A live countdown to the announced console release date.
- 📧 **Email Notifications** — Subscribe to receive updates when official PC system requirements become available.
- ❓ **FAQ Section** — Find answers about the predicted specifications, PC release status, and the project's unofficial nature.
- 📱 **Responsive Design** — A gaming-inspired interface designed for a range of screen sizes.
- 🌆 **Vice City-Inspired Aesthetic** — Dark colors, bold typography, and a visual style inspired by the atmosphere of GTA VI.

## 🛠️ Built With

- **HTML5** — Website structure and content.
- **CSS3** — Layout, styling, animations, and responsive design.
- **Vanilla JavaScript** — Hardware compatibility logic and countdown timer.
- **Google Fonts** — Bebas Neue, Manrope, and IBM Plex Mono.
- **Brevo** — Email subscription form integration.
- **Cloudflare Turnstile** — CAPTCHA protection for the subscription form.

The website uses vanilla HTML, CSS, and JavaScript without a frontend framework.

## 🚀 Getting Started

### Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/Dejv1d0/GTA_Requirements.git
   ```

2. Navigate to the project directory:

   ```bash
   cd GTA_Requirements
   ```

3. Open `index.html` in your browser.

For a better development experience, you can use the **Live Server** extension in Visual Studio Code.

### Project Structure

```text
GTA-Requirements/
├── index.html
├── style.css
├── brevo.css
└── README.md
```

- `index.html` — Main page structure, compatibility checker, countdown, predicted specifications, subscription form, and FAQ.
- `style.css` — Main website styling.
- `brevo.css` — Styling for the email subscription form.

## ⚙️ How the Compatibility Checker Works

The checker evaluates three hardware categories:

| Component | Evaluation |
|---|---|
| CPU | Processor performance tier |
| GPU | Graphics card performance tier |
| RAM | Available system memory capacity |

Each selected component receives an individual assessment. The combined result provides one of three estimated verdicts:

- **Covered** — Hardware meets the project's predicted recommended tiers.
- **Playable with compromises** — Some components may fall below the predicted recommended level.
- **Below predicted minimum** — At least one key component falls below the estimated minimum tier.

The checker uses predefined hardware categories and simplified rules. It does not automatically detect hardware, benchmark a computer, or run GTA VI.

## 📊 Predicted System Requirements

The website currently includes four estimated hardware tiers:

- **Minimum** — Entry-level predicted hardware.
- **Recommended** — Targeted at 1080p gaming.
- **High-end** — Targeted at 1440p with high or ultra settings.
- **4K / Ray Tracing** — High-performance hardware for demanding graphics settings.

These estimates are speculative and may differ significantly from the actual requirements if a PC version is released.

## 📬 Email Notifications

The notification form uses Brevo to process email subscriptions and Cloudflare Turnstile for CAPTCHA protection.

The intended purpose is to notify subscribers when Rockstar Games officially publishes GTA VI PC system requirements.

Subscription delivery depends on the external services and their configuration.

## 🔮 Future Improvements

Potential areas for further development include:

- More detailed CPU and GPU selection.
- A larger hardware database.
- More granular performance estimates for different resolutions.
- Improved accessibility and mobile responsiveness.
- Automatic updates when official system requirements are published.
- Additional performance and hardware comparison tools.

## ⚠️ Disclaimer

GTA Requirements is an independent, unofficial fan-made project. It is not affiliated with, endorsed by, or connected to Rockstar Games or Take-Two Interactive.

Grand Theft Auto, GTA VI, and related trademarks belong to their respective owners.

All system requirements displayed on this website are estimates created for informational purposes only. They should not be treated as official hardware recommendations or guarantees of game performance.

**Always refer to official Rockstar Games announcements for confirmed information.**

## 📄 License

No license has been specified yet. Unless a license is added to this repository, all rights to the project's original code remain with their respective copyright holder.

---

*Built for the GTA community. Updated when confirmed information becomes available.*
