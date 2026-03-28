You are a senior UI designer and front-end developer. Before writing a single line
of code, go to these URLs and fully analyze their design AND functionality:

1. https://www.mtchackathon.com/
2. https://azra-bano.com/#home
3. https://reactbits.dev/get-started/index — study the components and animation
   primitives available here. You will use these later when animations are specified.

Study their: typography, layout structure, dark backgrounds, accent color usage,
spacing, interactive elements, backend-powered features, and overall visual language.
My portfolio should match THAT level of visual ambition, craft, and interactivity.

---

⚠️ ANIMATIONS NOTE:
DO NOT add any animations yet beyond basic CSS hover transitions.
Animations will be specified and added in a separate stage.
When we get there, we will use components from reactbits.dev.
For now: build the structure, layout, and style to perfection.

---

BUILD: A single HTML file personal portfolio website.

TECH (all via CDN):

- Tailwind CSS
- Google Fonts — pick two fonts matching the bold/editorial vibe of the references

BACKEND FUNCTIONALITY TO INCLUDE:

1. CONTACT FORM (functional):
   - Name, Email, Message fields
   - On submit: use EmailJS (https://www.emailjs.com/) via CDN to send the message
     directly to nityanth.maramreddy@gmail.com
   - Show success/error state after submission
   - Style the form to match the dark editorial aesthetic — NOT a generic white form
   - Label EmailJS config placeholders clearly in code as:
     <!-- EMAILJS_SERVICE_ID --> <!-- EMAILJS_TEMPLATE_ID --> <!-- EMAILJS_PUBLIC_KEY -->

2. VISITOR COUNTER:
   - Use a free API (e.g. countapi.xyz or similar) to show a live visitor count
     somewhere subtle — e.g. in the footer: "X people have visited this site"
   - Increment on each page load

3. RESUME DOWNLOAD TRACKING:
   - When "Download Resume" is clicked, log the event (can use a simple
     localStorage counter or a free analytics ping)
   - Show a small badge or text like "Downloaded X times" near the button

4. SMOOTH ACTIVE NAV:
   - Navbar links highlight the active section as user scrolls
     (IntersectionObserver-based, no library needed)

---

COLOR:

- Near-black base (#080808)
- Primary accent: electric red (match mtchackathon energy)
- Secondary accent: one complementary highlight color for tags
- Subtle radial gradient glows in background
- Glassmorphism sticky navbar

---

SECTIONS (smooth scroll, single page):

--- NAVBAR ---

- "NITU." bold top-left
- Links: About, Projects, Resume, Contact (active state highlights on scroll)
- Top-right: LinkedIn icon (https://www.linkedin.com/in/nityanth-maramreddy-7ba0a2208/)
  - GitHub icon (https://github.com/N1tu-Mar)

--- HOME ---

- Massive hero heading:
  "BUILDING THINGS" (white)
  "THAT MATTER." (accent color)
- Subheading: "CS + Neuroscience @ Rutgers. On a mission to build two startups
  that create global impact."
- Two CTA buttons: "See My Work" → Projects | "Get In Touch" → Contact
- Profile photo placeholder — label as <!-- PROFILE PHOTO -->
  Style with a glow border or offset frame, NOT a boring circle

--- ABOUT ---

- Small spaced-caps label in accent color: "ABOUT ME"
- Large heading: "Who I Am."
- Bio: "Hey! I'm Nitu — a Neuroscience & Computer Science student at Rutgers
  (GPA: 3.93) with an unconventional path. I started Pre-med, but realized I
  wanted to spend my life building things that create real impact at scale.
  My goal: build two startups that change the world. I live at the intersection
  of science, technology, and entrepreneurship."
- Big stat row (styled like mtchackathon's APR 4 / 7 HRS / FREE stats bar):
  3.93 GPA | 110+ Interviews | 4 Projects | 2 Startups
- Skills as minimal tags: Python, C#, JavaScript, React, Next.js, Tailwind CSS,
  Node.js, Git, Unity, Godot, Android Studio

--- PROJECTS ---

- Spaced-caps label: "PROJECTS"
- Large heading: "What I've Built."
- Bold cards, category tags styled like mtchackathon's KEYNOTE/MAIN/DEADLINE tags
- Hover: left border glow + subtle lift (CSS only for now)

CARD 1 — Palura
Tag: STARTUP · EDTECH · GAME DEV | Role: Founder & CEO
"Building full-scale video games where kids learn reading, writing, and speech
through core gameplay — think Mario and Zelda, but educational. Leading development
of an RPG platformer with speech-input spell mechanics. Scaled to YMCA locations
across NJ, libraries in Plainsboro, Princeton, New Brunswick. Expanding into NYC."
Stack: Unity · Godot · React · HTML/CSS

CARD 2 — UniFlow
Tag: STARTUP · CAMPUS TECH | Role: Head of Campus Ambassadors
"Real-time platform for cross-campus facility availability — parking, gyms,
libraries, dining halls. Partnered with Rutgers Dept. of Recreation for live data.
Team placed 3rd at TechStart RSVP Pitch Competition."
Stack: In Development

CARD 3 — ShiftFlow
Tag: HACKATHON · HEALTHTECH | Badge: TechStart RSVP Hackathon
"Mobile app for hospital CNAs and nurses. OCR scans a vitals monitor in under
10 seconds and auto-charts into Epic and EHR systems — saving 45 min/shift.
Includes digital shift handoffs and patient behavior logs."
Stack: Android Studio · OCR · JavaScript

CARD 4 — (Un)announced
Tag: FREELANCE · WEB DEV | Role: Developer + Studio Head
"Built the full website from scratch for (Un)announced — a Gen Z digital content
house for LinkedIn creators. Now Studio Head, consulting Gen Z founders in SaaS,
Fintech, EdTech, and Retail."
Stack: Tailwind CSS · Node.js · JavaScript

--- RESUME ---

- Spaced-caps label: "RESUME"
- Large heading: "Experience."
- Vertical timeline (styled like mtchackathon's day schedule — date left,
  content right, colored dot indicators, horizontal dividers):
  · Palura — Founder & CEO (Nov 2025–Present)
  · (Un)announced — Studio Head (Feb 2026–Present)
  · Centren Health LLC — Research Intern (Sept 2025–Jan 2026)
  · Neuropath Biosciences — Frontend Intern (Jun–Jan 2025, London)
- "Download Resume" button → <!-- RESUME PDF LINK -->
- Small badge near button: "Downloaded X times" (localStorage counter)

--- CONTACT ---

- Spaced-caps label: "CONTACT"
- Large heading: "Let's Talk."
- Subtext: "Building something? Want to collaborate? My inbox is always open."
- Functional EmailJS contact form (Name, Email, Message + Submit)
- Below form: three bold contact cards styled like mtchackathon's
  BUILDERS/VISIONARIES split:
  · Email — nityanth.maramreddy@gmail.com
  · LinkedIn — linkedin.com/in/nityanth-maramreddy-7ba0a2208
  · GitHub — github.com/N1tu-Mar

--- FOOTER ---

- "NITU. © 2026" left | LinkedIn + GitHub icons right
- Live visitor count: "X people have visited this site"
- Scrolling ticker (like mtchackathon's bottom bar):
  "RUTGERS UNIVERSITY · CS + NEUROSCIENCE · BUILDING FOR IMPACT · 2026 ·"

---

Make every design decision like the senior designers who built mtchackathon.com.
Bold. Intentional. Nothing generic. Animations come later — for now,
the structure, layout, and visual quality should be flawless.
