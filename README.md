# 🎓 WebVerse Academy

A static front-end website for an online web development course platform. It features a hero landing page with an integrated login form, a pricing/plans page, and a course enrollment page.

## 🌐 Live Preview

Open `index.html` in any modern browser to get started.

## 📁 Project Structure

```
webverse-academy/
├── index.html      # Landing page with navbar, hero section & login form
├── login.html      # Course pricing plans page
├── enroll.html     # Course enrollment page
└── 1.jpg           # Hero background image (night tree reflection)
```

## 📄 Pages Overview

### `index.html` — Landing Page
- Navbar with logo, navigation links, and a search bar
- Full-screen hero section with `1.jpg` as the background
- Course intro text for the Web Design & Development course
- Embedded login form with email/password inputs and social login icons (Facebook, Instagram, Twitter, Google, Skype)
- "JOIN US" CTA button linking to `login.html`

### `login.html` — Pricing Plans
- Displays three course subscription tiers in a pricing table:

  | Plan         | Duration  | Price |
  |--------------|-----------|-------|
  | Beginner     | 1 Month   | $99   |
  | Intermediate | 3 Months  | $249  |
  | Advanced     | 6 Months  | $499  |

- "Enroll Now" button linking to `contact.html`

### `enroll.html` — Course Enrollment
- Lists 4 available courses: Web Development, Data Science, Machine Learning, Graphic Design
- Each course has an **Enroll** button that triggers a confirmation alert
- Link back to `login.html`

## ✨ Features

- Responsive hero layout with a dark gradient overlay
- Inline login form with smooth hover transitions
- Social media icon integration via [Ionicons](https://ionicons.com/)
- Clean pricing table layout
- Orange (`#ff7200`) brand accent color throughout

## 🛠️ Tech Stack

- **HTML5** — page structure and layout
- **CSS3** — flexbox, gradients, transitions, responsive sizing
- **JavaScript** — enrollment alert on `enroll.html`
- **Ionicons v5** — social media icons (loaded via CDN)

## 🚀 Getting Started

No build tools or dependencies needed. Just clone and open:

```bash
git clone <your-repo-url>
cd webverse-academy
open index.html
```

Make sure `1.jpg` is in the same directory as `index.html` for the hero background to load correctly.

## 🔗 Page Flow

```
index.html  →  login.html (Pricing)  →  enroll.html (Course Selection)
     ↑                                         |
     └─────────── "Login here" link ───────────┘
```



## 📄 License

This project is open source and available under the [MIT License](LICENSE).
