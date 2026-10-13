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

======================================================================================================================================================================================================================================================================================================================================
# Social Sites Assignment

**Assigned to:** Mr. Jabir Chowdhury

## Project Overview

This project is a collection of five interconnected web pages built using HTML5 and CSS3. It includes a home page that links to four individually designed social media pages: Facebook, Instagram, LinkedIn, and Google.

The project focuses on recreating familiar social media interfaces while practising page layout, CSS styling, responsive design, navigation, and clean code organization.

## Pages Overview

| File | Description |
|---|---|
| `index.html` | Home page featuring links to four social media pages |
| `facebook.html` | Facebook-inspired page with a login interface and supporting sections |
| `instagram.html` | Instagram-inspired profile page with profile information, statistics, and a photo grid |
| `linkedin.html` | LinkedIn-inspired profile page with navigation, a cover banner, profile information, and content cards |
| `google.html` | Google-inspired search page with a search interface and supporting elements |

## Completed Work

### 1. Home Page and Navigation

- Created a home page featuring four social media icons.
- Linked each icon to its corresponding local HTML page.
- Added navigation links to move between the home page and individual social media pages.
- Implemented a "← Back to Home" link on the social media pages.

### 2. Facebook Page

- Built a Facebook-inspired interface with a logo, introductory text, and illustration.
- Designed a login form layout with input fields, buttons, and a password recovery link.
- Added supporting elements, including Meta branding and footer links.
- Refined the layout and adjusted CSS for different viewport sizes.

### 3. Instagram Page

- Created an Instagram-inspired profile layout.
- Added a circular profile picture, username, Follow button, and profile statistics.
- Built a three-column photo grid using HTML and CSS.
- Organized the profile content and image elements for a consistent layout.

### 4. LinkedIn Page

- Built a LinkedIn-inspired profile interface with a navigation bar.
- Designed a cover banner with an overlapping profile picture.
- Added profile information, including a name, headline, and location.
- Created content cards for About, Experience, Education, and Skills.
- Used CSS Grid, Flexbox, positioning, spacing, and box shadows to structure the layout.
- Refined responsive behavior for laptop, tablet, and mobile viewports.

### 5. Google Search Page

- Created a Google-inspired search page.
- Designed the central Google logo and search interface.
- Styled the search field, buttons, navigation elements, and supporting sections.
- Organized the page layout using HTML and CSS.

### 6. Responsive Design and Code Refinement

- Worked on responsive layout adjustments across the social media pages.
- Used CSS media queries to adapt layouts to different viewport sizes.
- Adjusted widths, spacing, typography, and element positioning for smaller screens.
- Refined the CSS structure and styling to improve readability, consistency, and maintainability.
- Practised organizing layouts into sections, containers, and individual components.

### 7. Git and GitHub Workflow

- Practised creating and working with Git branches.
- Used Git commands to inspect repository status, branches, and commit history.
- Worked with remote branches and pushed changes to GitHub.
- Practised the branch-based workflow for submitting changes through Pull Requests.

## Technologies and Tools

- **HTML5** — Page structure and semantic elements
- **CSS3** — Styling, layouts, transitions, and responsive design
- **Flexbox** — Alignment and one-dimensional layouts
- **CSS Grid** — Structured multi-column layouts
- **Media Queries** — Responsive viewport adjustments
- **Git** — Version control and branch management
- **GitHub** — Repository hosting and Pull Request workflow

## Key Learning Outcomes

Through this project, I practised building multi-page websites, organizing HTML and CSS, recreating familiar user interfaces, implementing page navigation, creating responsive layouts, and managing project changes with Git and GitHub.

The project also helped me strengthen my understanding of Flexbox, CSS Grid, positioning, spacing, reusable styling patterns, and responsive design.

## Project Status

The project has progressed through the development of the four social media pages and the home page, along with responsive layout refinements and code polishing.

**More to learn, more to build.**
