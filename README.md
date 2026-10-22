# KhaledOS

### A personal portfolio with a desktop of its own.

Most portfolios start with a list of projects and a résumé. Mine starts with a quiet introduction and an invitation to scroll.

Keep going, and the page opens into a MacBook-inspired desktop. There are apps to explore, photos to flick through, a dedicated space for recruiters, and a few things in Settings that probably wouldn't pass an actual hardware inspection.

It's still a portfolio. I just wanted it to feel a little more like me.

**[Explore KhaledOS](https://khaledos.vercel.app/)** · [LinkedIn](https://www.linkedin.com/in/khaledmorshedac/) · [GitHub](https://github.com/jeffyoh312)

## Take a look around

Rather than putting everything on one long page, KhaledOS lets visitors decide what they want to open.

| App | What's inside |
| --- | --- |
| **For Recruiters** | My résumé, experience, education, achievements, and certificate verification links |
| **About Me** | Background, interests, skills, and a little more about who I am |
| **Off Hours** | Football, people, community, and life away from the screen |
| **Photos** | A personal gallery with full-screen viewing |
| **Contact Me** | The easiest ways to reach or find me |
| **Settings** | Appearance controls, credits, and some questionable system specifications |

**Projects** and **Khaled AI** are still works in progress. Khaled AI is a planned informational chatbot, not a live AI feature yet.

## A few details behind the desktop

The laptop animation is made with **CSS**, not a video or 3D model. As you scroll, JavaScript updates its progress until the desktop fills the screen.

Inside, the apps share one reusable window. An app list keeps the desktop icons, dock, and menus in sync, while opening an app swaps its content without refreshing the page.

Other small touches make it feel more like a real desktop:

- **Light, dark, and auto themes** that stay in sync between Settings and Control Center. Your choice is remembered in the browser.
- **A Kuala Lumpur clock** that shows local time, wherever you're visiting from.
- **A shared photo collection** powering the gallery and the Off Hours slideshows.
- **Responsive layouts** that trade the laptop animation and dock for a simpler app grid on phones.
- **Keyboard and motion preferences**, including focus states, Escape-to-close behaviour, and reduced-motion styling.

## Built with

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS-1572B6?logo=css&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-111827?logo=vercel&logoColor=white)

The website is built with **HTML, CSS, and vanilla JavaScript**. No React, Next.js, database, or application backend. The interface runs in the browser, and a small Node.js build script prepares deployment metadata such as page descriptions, sharing previews, and the sitemap. **Vercel** hosts the static site.

Keeping it lightweight was a deliberate choice. The interesting part of this project is the interaction design, not the number of libraries behind it.

## About this repository

This is a **public showcase** of KhaledOS. The application source, original photos, and personal documents are kept in a separate private repository, so this repository isn't an installable copy of the website.

The portfolio is an ongoing personal project. The desktop, résumé, gallery, themes, and responsive layouts are implemented; the project gallery and Khaled AI are planned additions.

## Inspiration and credits

KhaledOS is an independent, playful parody of Apple's design language. It is **not affiliated with or endorsed by Apple Inc.**

Some artwork and design references come from third parties:

- App icons: [macOSicons](https://macosicons.com/)
- Wallpaper: [WallpaperCave](https://wallpapercave.com/funny-macbook-wallpapers)
- iPear logo reference: [Pinterest](https://www.pinterest.com/pin/807973990184796171/)
- Technology icons: [Skill Icons](https://github.com/tandpfun/skill-icons)
- Fonts: [Google Fonts](https://fonts.google.com/)

Third-party artwork and trademarks remain the property of their respective owners. The MacBook-inspired frame itself is drawn with CSS.

---

**Khaled Morshed** · Personal Portfolio · 2026