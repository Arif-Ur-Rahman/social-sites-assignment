# Social Sites Assignment

**Assigned to:** Mr. Jabir Chowdhury

Welcome! In this project you'll build a small website using only **HTML and CSS**. It's a chance to practise layout, styling, and linking pages together, and to show off how nicely you can design.

---

## The Project

You will build **5 pages**:

| File | What it is |
|------|------------|
| `index.html` | The home page. Shows 4 social icons: Facebook, Instagram, LinkedIn and Google. |
| `facebook.html` | Your own version of a Facebook page |
| `instagram.html` | Your own version of an Instagram page |
| `linkedin.html` | Your own version of a LinkedIn page |
| `google.html` | Your own version of the Google search page |

Clicking an icon on the home page must open **your** page, not the real website.
For example, clicking the Facebook icon opens `facebook.html`.

> **The main challenge:** the four social pages are built by you, from scratch.
> Look at the real sites for inspiration, then recreate the look in your own code.

---

## Folder Structure

Keep your files organised like this:

```
social-sites-assignment/
├── index.html
├── facebook.html
├── instagram.html
├── linkedin.html
├── google.html
├── css/
│   └── style.css      ← you may also create one CSS file per page
└── images/            ← put all your images here
```

---

## Page Requirements

### 1. `index.html` — Home Page
- [ ] A page title and a short heading (e.g. "My Social Sites")
- [ ] 4 icons: Facebook, Instagram, LinkedIn, Google
- [ ] Each icon is a link to the matching `.html` page
- [ ] The icons are centred on the page and nicely spaced
- [ ] A **hover effect** on each icon (e.g. grows bigger, changes colour, adds a shadow)
- [ ] Looks good on both a laptop and a phone screen

### 2. `google.html` — Google Search Page *(start here — easiest)*
- [ ] Top bar with links on the right (e.g. Gmail, Images, a profile circle)
- [ ] The word "Google" in the centre, in the right colours
- [ ] A rounded search box
- [ ] Two buttons under the search box ("Google Search" and "I'm Feeling Lucky")
- [ ] A footer at the bottom of the page

### 3. `instagram.html` — Instagram Profile Page
- [ ] Round profile picture
- [ ] Username, and a "Follow" button
- [ ] Stats row: posts, followers, following
- [ ] A short bio
- [ ] A photo grid with **3 columns** (at least 9 photos)

### 4. `linkedin.html` — LinkedIn Profile Page
- [ ] Top navigation bar
- [ ] Cover banner with a profile picture overlapping it
- [ ] Name, headline (job title) and location
- [ ] Sections shown as white cards: **About**, **Experience**, **Education**, **Skills**

### 5. `facebook.html` — Facebook Home Feed *(hardest — do this last)*
- [ ] Blue top navigation bar with logo text and a search box
- [ ] **3-column layout**: left menu, middle feed, right contacts list
- [ ] A "What's on your mind?" box at the top of the feed
- [ ] At least 3 posts, each with: profile picture, name, time, text, image, and Like / Comment / Share buttons

### Every social page must also have:
- [ ] A **"← Back to Home"** link that returns to `index.html`
- [ ] Its own `<title>` (shown in the browser tab)

---

## Rules

1. **HTML and CSS only.** JavaScript is not needed (see Bonus section).
2. **No CSS frameworks** — no Bootstrap, no Tailwind. Write your own CSS.
3. **Do not copy code** from the real websites (no "View Source" copying). Look at them, then build it yourself.
4. **Use relative links**, e.g. `href="facebook.html"`, not `C:\Users\...`.
5. **Use fake content.** Make up names, posts and bios. Don't use real people's photos or personal data.
6. **No working login or password forms.** These are design practice pages only.
7. **Icons:** you may use [Font Awesome](https://fontawesome.com/) (via CDN link) or download SVG icons into the `images/` folder.
8. **Images:** use your own images, or placeholder images such as `https://picsum.photos/300` (gives a random photo).

---

## Skills You'll Practise

| Page | Main skills |
|------|-------------|
| `index.html` | Links, centering, Flexbox, `:hover`, `transition` |
| `google.html` | Flexbox, centering, `border-radius`, buttons, positioning a footer |
| `instagram.html` | CSS Grid, circular images, `object-fit` |
| `linkedin.html` | Cards, `box-shadow`, `position: relative / absolute` |
| `facebook.html` | Multi-column layouts, `position: sticky`, reusable classes |

---

## Suggested Order & Timeline

| Step | Task |
|------|------|
| 1 | Create all 5 files and the folder structure. Make the icon links work. |
| 2 | Style `index.html` |
| 3 | Build `google.html` |
| 4 | Build `instagram.html` |
| 5 | Build `linkedin.html` |
| 6 | Build `facebook.html` |
| 7 | Make everything responsive and polish the details |

---

## How to Submit

- **Commit often** with clear messages, for example:
  - `Add home page with 4 icons`
  - `Style Instagram photo grid`
  - `Fix Facebook layout on mobile`
- Push your work to this repository after every work session.
- When a page is finished, tell your teacher so it can be reviewed.

---

## Grading (100 points)

| Area | Points |
|------|--------|
| All 5 pages exist and all links work (icons + back links) | 15 |
| Home page design and hover effects | 15 |
| Google page | 10 |
| Instagram page | 15 |
| LinkedIn page | 15 |
| Facebook page | 15 |
| Clean code: indentation, semantic tags (`header`, `nav`, `main`, `section`, `footer`), sensible class names | 10 |
| Responsive design (works on phone size) | 5 |
| **Total** | **100** |

---

## Bonus Challenges (optional)

- ⭐ Add a dark mode version of one page
- ⭐ Add CSS animations to the home page (e.g. icons fading in one by one)
- ⭐ Make the Instagram photos show a dark overlay with a ❤️ on hover
- ⭐ Use CSS variables (`--main-color`) for each site's colours
- ⭐ Make the Facebook "Like" button turn blue on click (this one needs a little JavaScript)

---

## Tips

- Use your browser's **DevTools** (right-click → Inspect) to test your layout and see real sites' spacing and colours.
- Use **Ctrl + Shift + M** in DevTools (Chrome) to preview phone screen sizes.
- Build the **structure (HTML) first**, then style it (CSS).
- Stuck? Break the page into boxes: draw it on paper first.

Good luck, and have fun! 🚀
