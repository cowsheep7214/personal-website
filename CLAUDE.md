# personal website - claude context

## about the person
Justin is non-technical. He wants short, simple responses. Walk him through everything. No jargon unless necessary.

## the site
A minimal personal website. Design goal: very simple, high visual appeal, low spatial clutter. Content is about letting the viewer clearly get to know Justin.

Vibe references Justin likes: minimal.gallery, recent.design, godly.website.

## tech
Plain HTML/CSS/JS in a single `index.html`. No framework, no build step. Deployed on Vercel; every push to the working branch auto-deploys. Live URL: https://personal-website-psi-flax-52.vercel.app

## current structure
- Left side: fixed vertical tabs (me / projects / videos) that switch which section is shown
- Top right: fixed icon dock (text, email, LinkedIn) with an "origin fill" hover effect (dark circle expands from the pointer, icon flips light)
- Center content:
  - "me" tab: `hi, i'm justin :)` heading, small muted intro paragraph, "read more" button that expands more text
  - "projects" tab: placeholder
  - "videos" tab: placeholder

## style
- Background: `#fafaf7` (soft cream)
- Text: `#1a1a1a` (near-black)
- Muted: `#6b6b6b`
- Font: Inter from Google Fonts
- Max content width: 620px, generous vertical padding

## working conventions
- Keep responses short and simple - Justin is non-technical
- Use plain HTML/CSS/JS, avoid frameworks
- Commit each meaningful change with a clear message
- Push after every change (Vercel redeploys automatically)
- Working branch: `claude/practical-bohr-m70tdp`

## known constraints
- Fetching some sites (e.g. 21st.dev, playground.nothing.tech) is blocked in some environments - if Justin references a component from these, ask him to paste code or screenshot

## todo / open questions
- Real content for "read more", "projects", "videos" tabs
- Real LinkedIn URL (currently placeholder)
- Phone number for the sms: link (currently opens blank)
- Possibly a small 3D city/scene as a hero visual (Justin was interested; see Spline / three.js)
