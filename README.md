# Frontend Developer Challenge: Pixel-Perfect Replication – Railway Pricing Page

## Overview
This is a 90-minute timed coding exercise designed to evaluate your attention to detail, proficiency with Tailwind CSS, and ability to translate a real-world design into clean, precise code.

Your task is to replicate the **desktop version only** of the Railway pricing page as pixel-perfect as possible using the provided Next.js + Tailwind boilerplate.

**Target Page:** https://railway.app/pricing

## Time Limit
**Strictly 90 minutes**.  
Prioritize visual accuracy and clean code. A highly precise implementation of the required sections is more important than rushing to include everything.

## Boilerplate Setup
- Next.js 14+ (App Router)
- Tailwind CSS pre-configured
- No additional libraries installed (keep it vanilla)
- Run locally with:
  ```bash
  npm install
  npm run dev


### Section 3: Required Scope
```markdown
## Required Scope (Build exactly these sections – stop after the footer)
1. **Header/Navbar** (logo, Sign in, Book a demo buttons)
2. **Banner/Hero section** (headline "Pay only for what your app uses, by the second", subheadline, visual icons/elements)
3. **Pricing cards** (all plan tiers: Hobby, Pro, Enterprise – with their details and highlights)
4. **Resource details section** (usage pricing grid: Memory, CPU, Volumes, Egress, Object Storage)
5. **Feature comparison table** (only the first 10 feature rows – e.g., Projects, Services per project, CPU per service, RAM per service, Ephemeral disk, Volume storage, Volumes per project, Buckets per project, Build image size, Collaboration – Team members)
6. **Footer** (links to product sections, legal links, cookie preferences, etc.)

**Do NOT build:**
- Mobile/responsive breakpoints below desktop
- Any sections beyond the footer
- Animations, videos, carousels, scroll effects, or complex interactions
- Functional elements (static styling only)

**Images & Media:**
- Use placeholder images (e.g., Unsplash, solid colors, or simple SVGs) for icons, backgrounds, or illustrations
- Replace any animated content with static images
- Focus on layout and spacing – exact images not required

## Requirements
- **Pixel-perfect desktop match** (1440px+ viewport)
- Use Tailwind classes extensively (arbitrary values allowed: e.g., `[#1A1A1A]`, `[27px]`)
- Clean, semantic HTML
- Proper use of flex/grid for layouts (especially cards and table)
- Exact typography, spacing, colors, shadows, borders, rounding, and hover states
- Minimal or no custom CSS

## Submission Instructions
1. **Fork this repository** to your personal GitHub account.
2. **Make your forked repository public** — private repositories will not be considered or reviewed.
3. Complete the challenge in your forked repository (commit regularly with clear messages).
4. Deploy a live preview if possible (Vercel strongly recommended).
5. Raise a Merge Request (MR) internally as instructed by the interview coordinator (no need to submit a PR back to the original organization repository).
6. In your internal MR or submission:
   - Include a link to your deployed live preview
   - Confirm that `docker compose up --build` works correctly in your fork
7. Do not share zip files or private links — only public repositories and internal MRs will be evaluated.

## Evaluation Criteria (Scored out of 100)

| Category                  | Weight | Details                                                                 |
|---------------------------|--------|-------------------------------------------------------------------------|
| **Visual Accuracy**       | 50%    | Pixel-perfect match: colors (exact hex), typography (sizes, weights, line-height, letter-spacing), spacing/padding/margins, shadows, borders, rounding, hover states |
| **Layout & Structure**    | 20%    | Correct use of flex/grid (especially cards and table), proper nesting, semantic HTML |
| **Tailwind Proficiency**  | 15%    | Extensive use of utility classes, minimal custom CSS, clean class organization |
| **Code Quality**          | 10%    | Readable component structure, logical file organization, no unused code |
| **Attention to Detail**   | 5%     | Subtle elements (e.g., checkmarks, badges, pricing highlights, icon alignment) |

We value precision and craftsmanship. Good luck!
