# Enact Web Draft

Static HTML prototype for the **Enact** project website — a national repository for practice-based research, funded by the Arts and Humanities Research Council (AHRC).

## About Enact

Enact is a partnership between the University of Westminster, Queen Mary University of London, and the University of Leeds. It aims to build open infrastructure that treats practice research as first-class scholarly output: citable, discoverable, and preserved for the long term.

**Strapline:** *A repository built for practice research*

## Site Structure

| File | Section |
|------|---------|
| `index.html` | Homepage — hero, benefits, timeline, news, get involved, FAQs, contact |
| `about.html` | About — logo/fonts, funders, key messages, institutional logos, project board, contact |
| `team.html` | Team — executive group, delivery team, technology partner |
| `community-engagement.html` | Community — advisory group, pathfinders, audience pages |
| `project-deliverables.html` | Project deliverables overview |
| `wp1.html` | WP1: Project Set-up & Management |
| `wp2.html` | WP2: Community Leadership & Engagement |
| `wp3.html` | WP3: Repository Build |
| `wp4.html` | WP4: Metadata & Open Standards |
| `wp5.html` | WP5: Skills & Training |
| `news.html` | News |
| `events.html` | Events — monthly drop-ins, Enact on the road |

## Technical Notes

- Pure HTML/CSS — no build tools or JavaScript frameworks
- Designed for eventual migration to a WordPress theme at the University of Westminster
- Navigation uses WordPress-compatible `ul.nav-menu > li.menu-item` markup, matching `wp_nav_menu()` output
- CSS-only dropdown menus (hover-activated, no JS required)
- Design system: Playfair Display + Source Serif Pro + Inter · green `#1a5c3a` + amber `#d97706`

## Status

This is a **draft prototype** for review and content development. Not a production site.
