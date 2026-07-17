Project overview
This project is an award-oriented web experience for an automotive brand or workshop, built on Next.js + GSAP + Three.js. The goal is to produce a cinematic, high-performance website with strong storytelling, premium motion, and immersive 3D details while preserving accessibility, responsiveness, and conversion-oriented UX.

Core product intent
The site should feel like a digital brand film rather than a generic service website. Every section should communicate trust, engineering precision, craftsmanship, and visual confidence. The user should quickly understand what the company does, why it is credible, and how to take action.

Primary experience principles
Treat the website as a directed narrative, not a stack of disconnected sections.

Use motion to guide attention, not to decorate empty layout.

Use 3D sparingly and intentionally: hero moments, mechanical storytelling, exploded parts, material closeups, lighting, or camera transitions.

Keep interaction quality high on desktop and mobile.

Always protect performance, readability, and booking/contact conversion.

Tech stack
Framework: Next.js

Animation system: GSAP

3D / WebGL: Three.js

Styling: Tailwind CSS or modular CSS, depending on implementation

Content: CMS-ready architecture preferred

Agent roles
1. Creative Director Agent
Responsible for tone, concept, visual metaphor, and emotional direction.

What this agent does

Defines the art direction before layout starts.

Chooses whether the site should feel industrial, futuristic, premium, brutalist, elegant, or cinematic.

Ensures the project does not drift into generic startup aesthetics.

Keeps all visual decisions aligned with one brand story.

Output examples

Brand mood statement

Visual keywords

Color and typography direction

Motion attitude

Imagery references

2. Information Architecture Agent
Responsible for structure, section order, user flow, and clarity.

What this agent does

Maps the narrative from first impression to trust to conversion.

Defines page hierarchy and section purpose.

Prevents visually impressive but confusing journeys.

Makes sure booking, quote, or contact actions are always easy to find.

Output examples

Sitemap

Homepage section sequence

Service page structure

Conversion path recommendations

3. Motion Design Agent
Responsible for GSAP choreography and interaction rhythm.

What this agent does

Designs scroll-driven storytelling.

Defines when elements reveal, pin, scale, mask, or transition.

Uses motion to support hierarchy and narrative pacing.

Avoids over-animation and protects reduced-motion users.

Output examples

Motion map by section

Scroll trigger definitions

Entrance/exit states

Reduced-motion fallback behavior

4. 3D Experience Agent
Responsible for all Three.js scenes and spatial storytelling.

What this agent does

Proposes which 3D moments are justified.

Defines scene complexity, lighting mood, camera logic, and performance budget.

Recommends when to use full 3D, subtle shader accents, or fake depth instead.

Ensures 3D supports the business story, not just visual spectacle.

Output examples

Hero scene concept

Scene interaction rules

Camera path notes

Mobile fallback strategy

5. Frontend Architecture Agent
Responsible for Next.js implementation quality.

What this agent does

Designs the component structure.

Separates server and client responsibilities.

Makes animation and 3D modules isolated and maintainable.

Prevents monolithic page code and fragile animation coupling.

Output examples

App folder structure

Component boundaries

Rendering strategy

Data-loading approach

6. Performance Agent
Responsible for keeping the experience premium without becoming heavy.

What this agent does

Sets budgets for JS, images, fonts, and WebGL cost.

Identifies animation or 3D hotspots that hurt LCP, INP, or smoothness.

Recommends lazy loading, code splitting, texture optimization, and scene simplification.

Verifies mobile viability.

Output examples

Performance budgets

Asset optimization checklist

Lazy-loading plan

Fallback recommendations

7. Accessibility and UX Agent
Responsible for clarity, inclusion, and interaction correctness.

What this agent does

Ensures focus order, keyboard behavior, contrast, readable motion, and semantic structure.

Protects form usability and CTA clarity.

Balances immersive design with practical usability.

Prevents the site from becoming beautiful but exhausting.

Output examples

Accessibility checklist

Form interaction standards

Mobile UX warnings

Focus and navigation notes

Build rules
Do not start with code before the concept and page narrative are defined.

Every page must have one primary goal.

Every motion effect must have a job: reveal, guide, compare, emphasize, or transition.

Every 3D scene must justify its cost.

Never let the hero consume all attention while service trust sections feel weak.

Avoid generic dark gradients, neon blobs, and AI-looking layout patterns.

Use large typography, strong contrast, and material-driven imagery where appropriate.

Prefer real photos, textures, workshop details, and believable surfaces over abstract decoration.

Recommended page types
Homepage / flagship storytelling page

Services overview page

Individual service detail page

Portfolio / before-after case studies

About workshop / team credibility page

Booking / quote page

Contact / location page

Default homepage narrative
Cinematic hero with strong value proposition

Signature services or specialties

Why clients trust this workshop

Selected work / transformations / before-after

Process or technical capability

Testimonials or proof

Clear booking CTA

Motion rules
Use GSAP ScrollTrigger for narrative sections only when motion improves understanding.

Prefer opacity, transform, clip-path, and parallax depth over chaotic animation.

Stagger text and image reveals carefully.

Pinning should be rare and meaningful.

Keep scroll smooth but not sluggish.

Respect prefers-reduced-motion.

Three.js rules
Use 3D in hero sections, technical callouts, or premium transitions.

Keep polygon counts and texture sizes under control.

Provide mobile fallback for every non-essential 3D scene.

Prefer one unforgettable 3D moment over many mediocre ones.

Camera movement should feel intentional and cinematic, not game-like unless conceptually justified.

Visual direction guardrails
Avoid template-like SaaS blocks.

Avoid generic feature cards with icons in colored circles.

Avoid overusing glassmorphism.

Avoid excessive purple/blue AI gradients.

Favor metal, light, paint, rubber, reflections, and workshop materiality.

Typography should feel premium and editorial, not default-tech.

Deliverable standards
A finished implementation should include:

strong art direction

responsive layout

motion system map

optimized 3D scenes

clear CTAs

high accessibility baseline

measurable performance strategy

Definition of success
The project succeeds when it feels premium, memorable, and trustworthy while remaining fast, legible, and conversion-capable. It should be impressive enough for design showcases but practical enough for real customers looking to book a service.