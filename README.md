# KhaledOS

### My personal portfolio, with a desktop of its own.

KhaledOS starts with a simple introduction: my name, a quiet screen, and an invitation to scroll. From there, it opens into a MacBook-inspired workspace where you can explore my background, experience, photos, and life outside software engineering.

A little professional. A little less serious once you get inside.

This repository documents the project. The application source and original assets are maintained in a separate private repository.

[GitHub](https://github.com/jeffyoh312) · [LinkedIn](https://www.linkedin.com/in/khaledmorshedac/)

Visit the official portfolio website here: [KhaledOS] https://khaledos-40ikdvxpv-jeffyoh312s-projects.vercel.app/

## The idea

I wanted a portfolio that felt like meeting a person, rather than reading a list of qualifications. It still needed to be useful, especially for someone looking at my experience or considering me for a serious position.

The result has two sides. The hero is minimal and restrained. The workspace is more playful, using familiar desktop interactions to organise the content without putting everything on the screen at once.

Visitors choose where to go. Recruiters have a dedicated résumé view; everyone else can explore at their own pace.

## Inside the workspace

| App | What you’ll find |
| --- | --- |
| **About me** | My background, interests, technical skills, and social links. |
| **Khaled AI** | A coming-soon planned bot that will answer questions about me. Despite the name, no AI model or working chatbot is connected yet. |
| **Contact me** | Email, LinkedIn, GitHub, and my general location. |
| **For recruiters** | A résumé covering Education, experience, community involvement, skills, certifications, and honors. Verification links and award PDFs are included. |
| **Projects** | A space for future work. |
| **Off hours** | Sports, good company, and giving back, with photo slideshows alongside the stories. |
| **Photos** | A personal photo collection. Select an image to see it in full. |
| **Settings** | Appearance controls, design credits, and a few completely necessary system specifications. |

Yes, the processor is a **KM-5 Ultra Chip**. Battery health is **101%**. Neither claim should influence a hardware purchase.

## How it was built

The website uses **HTML, CSS, and vanilla JavaScript**. There is no frontend framework, database, or application server.

That was enough for what the site needs to do. Its content lives in local files, and the interactions happen in the browser. Keeping the implementation small also makes it straightforward to edit and host as a static website.

### From the hero to the desktop

On larger screens, scrolling gradually expands a laptop-shaped frame until the workspace fills the viewport. JavaScript tracks the scroll position and passes a progress value to CSS, which adjusts the frame’s size and position.

The laptop itself is drawn in CSS. It is not a video or a downloaded 3D model.

### One window, several apps

The apps share a reusable window. Selecting an icon changes the content inside it and updates the active navigation state, without reloading the page.

A single app list controls the desktop icons, dock, and Favourites menu which keeps their order consistent. The Desktop controls lets visitors close, minimise, or enlarge the window, while the phone layout provides an “All apps” button to return to the home screen.

### Photos and slideshows

All photographs are registered in one shared collection. The Photos app displays the full collection; the Sports and Good Company slideshows select specific entries from it.

This avoids maintaining separate copies of the same image. Captions also provide accessible descriptions, and the full-image viewer preserves the photograph’s proportions rather than cropping it to fit a card.

### Light, dark, and automatic appearance

Settings and Control Center share the same appearance preference. A choice made in one is reflected in the other and saved in the visitor’s browser.

Auto follows the device’s light or dark preference. The menu-bar clock uses Kuala Lumpur time, regardless of where the visitor is browsing from.

## Technology stack

| Technology | How it is used |
| --- | --- |
| **HTML5** | Page structure, navigation, app-window shell, and native image dialogs. |
| **CSS** | Responsive layouts, themes, typography, the laptop frame, and visual transitions. |
| **JavaScript** | App switching, scroll behaviour, photo viewing, slideshows, settings, and clipboard actions. |
| **Browser APIs** | `localStorage` remembers appearance, `matchMedia` reads device preferences, and `Intl.DateTimeFormat` supplies the Kuala Lumpur clock. Scroll updates use `requestAnimationFrame`. |
| **Node.js** | A small build script prepares page metadata for the hosting domain. A separate check script validates app content and local asset references. |
| **Vercel configuration** | Defines how to build the metadata and serve the static website. The project is prepared for Vercel deployment. |
| **Google Fonts and system fonts** | Montserrat for the hero, with native system font stacks for the desktop interface. |

There are no npm package dependencies. Node.js is used during preparation, not as a server running behind the website.

The technologies listed in my personal skills section are broader than the tools used to build KhaledOS. This project does not use React, Next.js, or an AI service.

## Adapting the experience for smaller screens

Shrinking a desktop interface onto a phone made it crowded. The mobile layout therefore changes how the workspace behaves.

On phones, the laptop animation and bottom dock are removed. Visitors open apps from the home grid, read content in a single column, and return through “All apps.” Off Hours images sit above their accompanying text.

Tablet-sized layouts keep the dock but skip the laptop zoom. Larger screens retain the full desktop experience. These changes follow viewport width, so the interface responds to the space available rather than trying to identify a particular device.

The site also includes labelled buttons, visible keyboard focus, Escape-to-close controls, keyboard photo navigation, and reduced-motion styling.

## Preparing it for the web

A small Node.js build script updates the page title, description, canonical URL, social-sharing metadata, and structured profile information using the deployment domain. It also generates `robots.txt` and a sitemap.

Preview deployments are marked not to be indexed. The public production domain can be set through configuration without editing every link by hand.

There is no contact form backend or visitor account system. Contact links and email copying keep that part simple, and no analytics have been added.

## Current status

The portfolio interface, résumé view, photo collection, appearance controls, and responsive layouts are implemented. Projects and Khaled AI remain clearly labelled placeholders.

Source checks cover app registration, image paths, slideshow selections, credential files, and JavaScript parsing. They do not replace testing the experience in a browser. A full mobile and cross-browser visual review is still outstanding; no accessibility certification, performance score, or benchmark is claimed here.

The next additions are completed project write-ups, more photographs, and the planned informational bot.

## About this repository

This is a public showcase, not an installable copy of the application. It explains the design and implementation while keeping the source repository, original photographs, and documents out of this repository.

Assets displayed on the public website are still accessible to its visitors. Keeping the source repository private does not make those published files private.

## Inspiration and credits

The workspace is an independent, playful parody of Apple’s design language. KhaledOS is not affiliated with, endorsed by, or sponsored by Apple Inc.

| Asset | Source |
| --- | --- |
| Application icons | [macOSicons](https://macosicons.com/) |
| Wallpaper | [WallpaperCave](https://wallpapercave.com/funny-macbook-wallpapers) |
| iPear parody logo | [Pinterest reference](https://www.pinterest.com/pin/807973990184796171/) |
| Technology icons | [Skill Icons](https://github.com/tandpfun/skill-icons) |
| Web fonts | [Google Fonts](https://fonts.google.com/) |

Third-party artwork and trademarks belong to their respective owners. I do not claim ownership of them. The MacBook-inspired frame is implemented in CSS.

---

**Khaled Morshed**  
Personal Portfolio / KhaledOS 2026
