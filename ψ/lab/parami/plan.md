# Oracle Team Landing Page — Project Plan

> **Project**: parami.makeloops.xyz — บารมี 10 ทัศ Landing Page
> **Issue**: #1
> **Created**: 2026-03-18
> **Owner**: Gabbzaa
> **Coordinator**: Athitthaan (อธิษฐานบารมี)

---

## Vision

เว็บไซต์แสดงทีม Oracle บารมี 10 ทัศ ทั้ง 11 ตัว — แต่ละ Oracle มีบุคลิก สี และบทบาทเฉพาะตัว ผู้เยี่ยมชมจะเข้าใจว่า Oracle Family คืออะไร แต่ละตัวทำอะไร และทำงานร่วมกันอย่างไร

---

## The 11 Oracles (บารมี 10 ทัศ)

| # | Oracle | บารมี | Role | Domain |
|---|--------|-------|------|--------|
| 1 | Jingjing | สมาธิ (Concentration) | Frontend & Web Automation | UI/UX, Browser |
| 2 | Sila | ศีลบารมี (Morality) | Backend & Database | API, Data Layer |
| 3 | Panya | ปัญญาบารมี (Wisdom) | Data & Analytics | Insights, ML |
| 4 | Wiriya | วิริยบารมี (Effort) | DevOps & Infrastructure | CI/CD, Cloud |
| 5 | Sati | สติ (Mindfulness) | Testing & QA | Quality, Coverage |
| 6 | Thaan | ทานบารมี (Generosity) | Content Creator | Writing, Media |
| 7 | Metta | เมตตา (Loving-kindness) | Community & UX | Users, Empathy |
| 8 | Khanti | ขันติบารมี (Patience) | Debugging | Troubleshooting |
| 9 | Sajja | สัจจบารมี (Truthfulness) | Security | Auth, Secrets |
| 10 | Athitthaan | อธิษฐานบารมี (Determination) | Project Management | Planning, Coordination |
| 11 | Ubekkha | อุเบกขาบารมี (Equanimity) | Monitoring | Observability, Alerts |

---

## Milestones & Timeline

### Milestone 1: Foundation (Week 1 — Mar 18–24)
**Goal**: Repo setup, design system, basic structure

| Task | Description | DoD |
|------|-------------|-----|
| M1.1 | สร้าง repo `parami-landing` + deploy pipeline | Repo exists, `main` auto-deploys to parami.makeloops.xyz |
| M1.2 | เลือก tech stack (แนะนำ: Astro/Next.js + Tailwind) | Tech stack documented, boilerplate committed |
| M1.3 | ออกแบบ design system — สี, font, layout | Design tokens defined (colors per Oracle, typography) |
| M1.4 | สร้าง Oracle data schema (JSON/MDX) | Data file with all 11 Oracles: name, บารมี, role, description, color |

### Milestone 2: Core Pages (Week 2 — Mar 25–31)
**Goal**: Landing page + individual Oracle profiles

| Task | Description | DoD |
|------|-------------|-----|
| M2.1 | Hero section — แนะนำ Oracle Family | Hero with tagline, animation/visual, responsive |
| M2.2 | Team grid — แสดง 11 Oracle cards | Grid layout, each card shows avatar/icon, name, บารมี, role |
| M2.3 | Oracle profile pages (11 pages) | Each Oracle has dedicated page: description, character, domain |
| M2.4 | Navigation + routing | Smooth navigation between pages, active state |

### Milestone 3: Polish & Content (Week 3 — Apr 1–7)
**Goal**: Visual identity, content, interactions

| Task | Description | DoD |
|------|-------------|-----|
| M3.1 | Oracle avatars/illustrations | Each Oracle has unique visual representation |
| M3.2 | เนื้อหาแต่ละ Oracle — philosophy, metaphor | Content written for all 11 profiles |
| M3.3 | Animations & transitions | Page transitions, hover effects, scroll animations |
| M3.4 | Philosophy section — 5 Principles | Section explaining the shared Oracle philosophy |
| M3.5 | Family tree / relationship diagram | Visual showing how Oracles connect and collaborate |

### Milestone 4: Launch (Week 4 — Apr 8–14)
**Goal**: Production-ready, live at parami.makeloops.xyz

| Task | Description | DoD |
|------|-------------|-----|
| M4.1 | SEO + meta tags + OG images | Social sharing works, meta descriptions set |
| M4.2 | Performance optimization | Lighthouse score > 90 on all categories |
| M4.3 | Responsive testing | Works on mobile, tablet, desktop |
| M4.4 | Accessibility audit | WCAG 2.1 AA compliance |
| M4.5 | Final review + deploy | Human approval, live at parami.makeloops.xyz |

---

## Task Breakdown Summary

| Milestone | Tasks | Duration |
|-----------|-------|----------|
| M1: Foundation | 4 tasks | Week 1 (Mar 18–24) |
| M2: Core Pages | 4 tasks | Week 2 (Mar 25–31) |
| M3: Polish & Content | 5 tasks | Week 3 (Apr 1–7) |
| M4: Launch | 5 tasks | Week 4 (Apr 8–14) |
| **Total** | **18 tasks** | **4 weeks** |

---

## Definition of Done (Project-level)

- [ ] เว็บไซต์ live ที่ parami.makeloops.xyz
- [ ] แสดง Oracle ทั้ง 11 ตัว พร้อมข้อมูลครบถ้วน
- [ ] แต่ละ Oracle มีหน้า profile เฉพาะ
- [ ] แสดง 5 Principles ของ Oracle Philosophy
- [ ] Responsive — ใช้งานได้ทุก device
- [ ] Lighthouse > 90
- [ ] Human (Gabbzaa) approved

---

## Tech Stack Options

> **แนะนำให้ Gabbzaa ตัดสินใจ** (Principle 3: External Brain, Not Command)

| Option | Pros | Cons |
|--------|------|------|
| **Astro + Tailwind** | Fast, static-first, great DX | Less dynamic interactivity |
| **Next.js + Tailwind** | Full React ecosystem, SSR/SSG | Heavier for a landing page |
| **SvelteKit + Tailwind** | Lightweight, great animations | Smaller ecosystem |

---

## Risks & Mitigations

| Risk | Impact | Mitigation |
|------|--------|------------|
| Content for 11 Oracles not ready | Blocks M3 | Start content drafts in M1, parallelize |
| Avatar/illustration delays | Blocks visual identity | Use placeholder icons, iterate |
| Domain/DNS not configured | Blocks launch | Set up DNS in M1 |
| Scope creep (interactive features) | Delays launch | Strict MVP scope, extras go to v2 |

---

## Notes

- นี่คือ project แรกของ Athitthaan — born today (2026-03-18)
- Oracle แต่ละตัวอาจมี repo ของตัวเอง สามารถดึงข้อมูลจาก soul files
- Future: เชื่อมกับ OracleNet, live status, activity feed
