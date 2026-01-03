## 1. Core Philosophy (Rules of the Game)

Print these mentally and don’t break them:

1. **One project = one day, max 3–5 hours**
2. **No backend. No auth. No DB. No APIs.**
3. **Local-only. No deployment.**
4. **Static data only (hardcoded JSON or JS objects)**
5. **Done > perfect**
6. **Reuse your own components aggressively**

If something doesn’t serve *speed + clarity*, it’s out.

---

## 2. Baseline Tech Stack (Stick to This for 30 Days)

### Framework

**→ React + Vite**

**Why:**

* Fast dev server
* Minimal boilerplate
* Forces component thinking
* Industry-relevant but not overengineered

**Template:**

```bash
npm create vite@latest daily-site -- --template react
```

No Next.js. No SSR. No routing libraries.

---

### Styling

Pick **ONE** and do not change it mid-challenge.

#### Recommended: **Tailwind CSS**

Best for speed + consistency.

**Rules if using Tailwind:**

* No custom CSS files unless absolutely necessary
* Use utility classes only
* Create reusable components instead of repeating class soup

Alternative if you hate Tailwind:

* Vanilla CSS + CSS Modules
* But Tailwind is faster for this challenge

---

### State Management

**→ React `useState` and `useEffect` only**

Rules:

* No Redux
* No Zustand
* No Context unless unavoidable

This is a UI challenge, not state architecture practice.

---

### Data

**Static JS object or JSON file**

Example:

```js
const business = {
  name: "Green Leaf Café",
  tagline: "Fresh. Local. Simple.",
  services: ["Coffee", "Brunch", "Pastries"],
  hours: "Mon–Sat 8am–4pm",
}
```

No fetching. No async unless faking loading states.

---

## 3. Folder Structure (Keep It Identical Every Day)

This prevents decision fatigue.

```txt
src/
  components/
    Header.jsx
    Hero.jsx
    Services.jsx
    About.jsx
    Contact.jsx
    Footer.jsx

  data/
    business.js

  App.jsx
  main.jsx
```

Rules:

* Same structure every day
* Same section names
* Only content and layout change

This is deliberate muscle memory training.

---

## 4. Website Scope (What Each Site Must Include)

Every website should include **exactly this**:

1. **Hero section**

   * Business name
   * Tagline
   * Call to action

2. **Services / Offerings**

   * 3–6 items

3. **About section**

   * Short paragraph

4. **Contact / CTA**

   * Fake phone/email
   * Fake location

5. **Footer**

   * Business name + year

No blogs. No galleries. No booking systems.

---

## 5. Daily Timebox (Very Important)

### Suggested Schedule (3–4 hours total)

**Day X**

1. **15 min** – Pick random business & rough vibe
2. **30 min** – Layout + structure
3. **90 min** – Styling & components
4. **30 min** – Polish (spacing, typography)
5. **15 min** – Review & stop

When time’s up, you STOP—even if it’s ugly.

---

## 6. Business Randomization Rules

To avoid analysis paralysis:

* Pick businesses from:

  * Google Maps random city
  * Yelp categories
  * Walk around your city mentally

Examples:

* Local plumber
* Nail salon
* Dentist
* Yoga studio
* Auto repair shop
* Landscaping company
* Pet grooming
* Small bakery
* Cleaning service

No startups. No SaaS. No personal portfolios.

---

## 7. Design Constraints (This Makes You Faster)

Each day:

* **One font family**
* **One primary color**
* **One accent color**
* **Light mode only**

Use:

* Google Fonts (Inter, Poppins, Montserrat, Playfair)
* No font pairing experiments unless you reuse a previous combo

---

## 8. Tooling (Minimal, Non-Negotiable)

* **VS Code**
* **ESLint (default)**
* **Prettier**
* **Browser DevTools**

No design tools. No Figma. No Notion.

---

## 9. What You’re Actually Training

This challenge trains:

* Visual hierarchy
* Spacing intuition
* Component abstraction
* Speed under constraints
* Knowing when something is “good enough”

Not:

* Architecture
* Scalability
* Backend thinking
