# Malli Website

The website for **Malli**, an Indian restaurant opening in Fall 2026 at 131 Oakview Commons Drive, Suite 109, Holly Springs, NC 27540.

> *Indian Dining, Reimagined.* Malli is the word for jasmine in several Indian languages, and in another southern language it also means "come back."

## What's in this repo

| File | What it is |
| --- | --- |
| `index.html` | The whole site in one self-contained file (about 2.3 MB). All photos, logo artwork, fonts links, styles and scripts are embedded, so it opens directly in a browser and can be hosted anywhere as-is, including GitHub Pages. |
| `README.md` | This file. |

## How the site works

The site is a **paged, full-screen layout** rather than one long scrolling page. Each section fills the screen, and visitors move between them with the top navigation, the footer arrows, the keyboard (← → / Page Up, Page Down) or by swiping on a phone.

### Pages

1. **Home** – the Malli mark, wordmark and "Wine, dine, gather" tagline over a photo of the Tulip dining room, with animated silk waves and a drifting colour mesh that respond to the pointer.
2. **The Malli promise** – a short statement: every dish has a story, every cocktail a personality, every visit a memory.
3. **Our story** – why the restaurant is called Malli, its three pillars (Authentic Flavors, Elevated Experience, People at the Heart) and a photo of Tulip.
4. **Spaces** – an auto-rotating showcase of the five rooms, each with a photo cut to the petal shape of the ceiling. The room names run in a row just under the heading (click one to jump to it), with the selected room's details below:
   - **Tulip** – the dining room
   - **Jasmine** – the bar
   - **Magnolia** – the private room
   - **Gardenia** – events and wine tasting
   - **Dahlia** – the bistro
5. **Menu** – tabs for Small plates, Mains, Dessert and Cocktails, each with a short chapter intro. This is a sample menu; final dishes and prices are confirmed before opening.
6. **Events** – heading across the top, then *You host* / *We host* stacked on the left and centered against the panel (You host shows first; they alternate every 7 seconds while the page is open; click either to choose), with a wide photo and details on the right that match the highlighted one. *We host*: An Evening of Wine & Spice in Gardenia (coming soon) over a black-and-white lamb karahi photo, with Reserve a spot and See past events buttons. *You host*: private events with 3, 5 or 7 course menus in the private dining room (PDR, up to 12) or Gardenia on the mezzanine (up to 36), buffets in Gardenia or booking the whole restaurant, with a one-week notice and Email operations / Call buttons.
7. **Gallery** – five tiles shaped like the wall relief, cycling through room and dish photos (dahi vada, stuffed kebabs, lamb karahi, seekh kebabs, pani puri, grilled fish). Click any tile to open a full-screen lightbox.
8. **Contact** – opening details, address, a **Join the waitlist** button, and a live Google map with no frame: its edges fade softly into the page and gold double corner brackets mark the corners, plus a floating card with Directions and Open in Maps buttons. In the dark palettes the map is tinted dark to match.

### Other features

- **Four colour palettes**, switchable from the footer: Claret and gold, Emerald and champagne, Charcoal blue and champagne (the default), and White and burgundy. The visitor's choice is remembered in their browser.
- **Responsive** layouts for desktop, tablet and phone.
- **Reduced motion**: animations switch off for visitors who have that setting turned on in their device.
- Footer links to Instagram ([@malli.indian](https://www.instagram.com/malli.indian/)), phone and [mallinc.us](https://mallinc.us/).

## Change history

- **Initial design** – built as a Claude artifact under a separate account.
- **Moved to this account** – the self-contained `index.html` was republished as a new Claude artifact.
- **New homepage background** – the hero photo was replaced with a full-resolution photo of Malli's Tulip dining room (chandeliers, wall relief and the Malli sign).
- **Moodier homepage** – the Tulip photo was darkened and warmed (lower brightness, more contrast, a touch of sepia) for a low-lit, candlelit feel.
- **Photo in the white palette** – the white palette used to hide the homepage photo; it now shows it faintly, like a faded print behind the logo.
- **New Events page** – redesigned as two equal-height panels (events we host / host your own) that follow all four palettes.
- **Events switcher** – the two Events panels became a *We host | You host* switch with one panel at a time, alternating automatically.
- **Contact map** – the drawn map was replaced with a live, interactive Google map with soft fading edges and gold corner brackets; the waitlist button became a rounded gold button.
- **Spaces room names moved up** – the row of room names now sits just under the *Five rooms* heading, with the selected room's details below it.
- **New Events layout** – heading on top, stacked *We host / You host* tabs on the left, and a photo-and-details panel on the right (matches the latest mockup).
- **Spaces layout fix** – on shorter laptop screens the room description overlapped the list of room names. The text now always sits between the heading and the list; on screens under about 820px tall the room names run in a row and the arrow buttons are hidden (names stay clickable and rooms still rotate automatically).

## Known to-dos

- **Waitlist link**: the "Join the waitlist" button still points to a Claude artifact on the old account (`claude.ai/artifact/Ko6oTuadjJ7hvtXgKTYKzS`). It needs to be moved over, rebuilt, or pointed at another sign-up form.
- **Order Online** and **Reserve a Table** buttons currently jump to the Contact page; they will need real links once online ordering and reservations open.
- Menu items and prices are placeholders until opening.

## Viewing or hosting the site

- **Locally**: download `index.html` and open it in any modern browser.
- **GitHub Pages**: in the repo's *Settings → Pages*, choose *Deploy from a branch*, select `main` and `/ (root)`, and save. The site will be live at `https://<username>.github.io/<repo-name>/`.
