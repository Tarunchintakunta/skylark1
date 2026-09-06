# Skylark Cinematic Scroll Website - Start Here

Use this folder as the ordered master brief for Claude.

The website must be a production-grade cinematic scroll animation, not a normal static website.

## Read Order

1. `00_START_HERE.md`
2. `01_MASTER_PRD.md`
3. `02_SCROLL_STORYBOARD.md`
4. `03_AUTOMATED_PIPELINE.md`
5. `04_ASSETS_AND_PROMPTS.md`
6. `05_QA_AND_DEFINITION_OF_DONE.md`

## Core Direction

Build a cinematic WebGL website for Skylark Exim, an Indian seafood export business.

The main story is an ocean adventure:

- Fishermen board a large fishing vessel.
- The vessel travels into the Bay of Bengal.
- A cinematic compass/data interface shows time, temperature, route, and sea conditions.
- Nets are cast into the ocean.
- Swordfish and tuna are caught as the hero seafood.
- Other fish and seafood appear as supporting products.
- The catch is stored in onboard chilled storage.
- The vessel returns to Visakhapatnam/Vizag port.
- Fish are transferred into cold-chain containers.
- The product enters processing: inspection, cutting, washing, grading, QC, residue testing, freezing, glazing, packing, and cold storage.
- Packed cartons are loaded into reefer export containers.
- Containers move to a large container vessel.
- A sky view transitions into a globe view.
- Route lines travel from India to global markets.

## Seafood Focus

Hero ocean seafood:

1. Swordfish
2. Tuna

Supporting seafood:

- Other ocean fish
- Shrimp
- HOSO shrimp
- HLSO shrimp
- PUD shrimp
- PTO shrimp

Shrimp and ponds remain part of the second-origin story, but the cinematic hero route is ocean-first.

## Technical North Star

Use the best production stack for this type of experience:

- Vite
- React
- TypeScript
- Three.js
- React Three Fiber
- Drei
- GSAP ScrollTrigger
- Lenis
- Zustand
- React Hook Form
- Zod
- Lucide React
- Blender MCP
- Higgsfield using the latest Blender collector workflow

## Automation Requirement

Claude must act as an autonomous production agent:

- Create the website.
- Create all required Blender models.
- Run and verify Blender outputs.
- Export optimized GLB assets.
- Use Higgsfield with the latest Blender collector workflow.
- Generate cinematic scene media.
- Integrate all assets into the WebGL site.
- Run the site locally.
- Run QA.
- Fix issues.

Do not stop at writing prompts or giving advice.

