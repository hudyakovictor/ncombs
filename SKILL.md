Award-winning automotive experience site using Next.js + GSAP + Three.js

Purpose
Use this skill when creating or planning a cinematic, high-end website for an automotive workshop, detailing studio, tuning garage, restoration shop, or performance brand. The focus is immersive storytelling, premium interaction design, strong visual identity, and carefully controlled 3D scenes.

When to use this skill
Use this skill when the project needs one or more of the following:

cinematic scroll storytelling

premium animation language

immersive brand presentation

3D product or vehicle visualization

visually distinctive service pages

award-oriented digital craft

strong emotional first impression with real conversion goals

What this skill is optimized for
This skill is optimized for websites that need to look like a top-tier brand experience while still functioning as a service business website. It is especially good for automotive businesses that rely on perceived expertise, premium quality, visual trust, and memorable presentation.

Stack responsibilities
Next.js
Next.js is the application foundation.

Responsibilities

routing and page structure

rendering strategy

asset organization

server/client separation

SEO foundations

performance-oriented delivery

Best use
Use Next.js to structure the site into maintainable sections and page templates while keeping the final experience fast and scalable.

GSAP
GSAP is the motion and choreography layer.

Responsibilities

scroll-triggered storytelling

reveal timing

section transitions

pinned sequences

text and media choreography

premium micro-interactions

Best use
Use GSAP to direct the user's eye through the story of the workshop, its process, and its proof of quality. Motion should clarify, dramatize, and pace the experience.

Three.js
Three.js is the immersive visual layer.

Responsibilities

hero 3D scenes

mechanical storytelling

lighting and atmosphere

camera motion

spatial transitions

premium technical visualization

Best use
Use Three.js for selective high-value moments such as a hero car silhouette, rotating detail parts, paint reflections, wheel assemblies, brake systems, or exploded technical views.

Core design philosophy
This stack should not produce a generic “cool website.” It should produce a believable, crafted, cinematic digital identity for a real automotive business.

The visual system should feel intentional, physical, and tactile. Strong websites in this category often borrow from film titles, luxury automotive campaigns, motorsport pacing, industrial photography, and editorial fashion layouts rather than from startup templates.

Recommended user experience goals
The visitor understands the brand in the first screen.

The visitor feels quality, precision, and confidence.

The visitor can easily discover services and proof of expertise.

The visitor can reach booking or quote actions without friction.

The site remains enjoyable on mobile, not just on a large desktop monitor.

Ideal content structure
Homepage
cinematic hero

service specialties

proof of quality

case studies or transformations

process or capabilities

trust indicators

booking CTA

Service page
service promise

who it is for

technical breakdown

visual proof

pricing or estimate direction

FAQs

action section

Portfolio page
before/after cases

vehicle categories

workmanship details

materials and methods

CTA to request similar work

Motion guidance
Motion must support narrative hierarchy.

The most important headline should settle first.

Supporting text should follow.

Images and 3D should reinforce the message, not compete with it.

Use pinned sections rarely, only for meaningful story chapters.

Micro-interactions should feel crisp, not playful unless the brand specifically calls for it.

3D guidance
Start with one flagship 3D scene.

Keep mobile fallback simple.

Use lighting as part of the brand language.

Use realistic materials carefully; poor realism is worse than no realism.

Reduce complexity if 3D does not clearly improve the story.

Performance guidance
Lazy-load Three.js scenes below the fold.

Compress textures aggressively.

Keep font usage tight.

Avoid heavy animation on low-end mobile devices.

Measure Core Web Vitals early.

Prefer fewer stronger moments over constant motion everywhere.

Accessibility guidance
All core content must remain understandable without animation.

Text contrast must remain strong over image and video backgrounds.

Keyboard users must be able to navigate forms and menus comfortably.

Reduced-motion mode must disable non-essential movement.

Do not hide critical content inside 3D-only interactions.

Visual style directions this skill supports well
premium industrial

cinematic luxury garage

futuristic performance lab

motorsport-inspired minimalism

brutalist mechanical workshop

dark editorial automotive brand

Visual anti-patterns
Avoid the following:

startup SaaS aesthetics

generic purple/blue AI gradients

empty motion without narrative purpose

overstuffed 3D on every screen

unreadable text over glossy imagery

template feature grids with no brand character

exaggerated effects that reduce trust

Suggested folder architecture
text
app/
  page.tsx
  services/
  portfolio/
  contact/
components/
  layout/
  sections/
  motion/
  three/
lib/
  animation/
  cms/
  utils/
public/
  images/
  models/
  video/
Suggested component split
HeroScene

ServiceHighlights

ProofBar

BeforeAfterGallery

ProcessTimeline

WorkshopStats

BookingCTA

ThreeCanvasIntro

CaseStudyRail

Execution checklist
Define brand mood before implementation.

Write the homepage story before building sections.

Choose where motion matters most.

Choose only one or two places where 3D is essential.

Verify mobile behavior early.

Check readability over every visual background.

Keep the booking path obvious.

Audit performance before adding extra visual layers.

Success criteria
This skill is successful when the final site feels immersive, premium, and memorable without sacrificing clarity, speed, trust, or maintainability. The result should be strong enough for award consideration and grounded enough to generate real business outcomes.