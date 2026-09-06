# Skylark Exim Cinematic Scroll Website PRD

Copy this entire file into Claude. This is the full product requirements document for a production-grade cinematic scroll website using Claude, Blender MCP, Higgsfield, Three.js/WebGL, and best-in-class frontend animation.

## 1. Product Definition

### Product Name

`Skylark Exim`

### Product Type

A cinematic, scroll-driven, 3D/WebGL website for an Indian seafood export business.

### One-Line Product Vision

Create the most premium cinematic seafood export website in India: a single scroll-controlled voyage from the Bay of Bengal to the world, proving that Skylark Exim protects every shrimp, every batch, and every shipment through disciplined processing, testing, freezing, packing, cold storage, and export documentation.

### Core Brand Idea

`Two Origins. One Standard.`

### Primary Experience Direction

The entire website must be a scroll animation.

This is not a normal corporate website with independent static sections. It is a continuous cinematic journey where scroll controls the camera, lighting, scene transitions, object movement, overlays, product reveals, and final export sequence.

The user should feel like they are watching and controlling a premium brand film inside the browser.

### Primary Route Choice

Use `Ocean` as the main canonical route.

The website begins with the Bay of Bengal, a large ship, a fishing vessel, and seafood export. The pond/aquaculture story must still be included because it is central to Skylark's two-origin promise, but the dominant cinematic journey should follow the ocean route first.

Implementation rule:

- Default scroll path: Ocean.
- Pond/aquaculture appears as a cinematic supporting chapter and optional origin branch.
- Both routes converge into the same processing, QC, freezing, packing, cold storage, and export proof.

## 2. Source Material

Use the following files from the project as mandatory references:

- `Skylark Exim Film Package v4.pdf`
- `Screen Recording 2026-09-06 at 10.23.50 AM.mov`
- `Screen Recording 2026-09-06 at 10.24.30 AM.mov`
- `Screen Recording 2026-09-06 at 10.25.18 AM.mov`

### PDF Facts To Use

Use these claims and details from the PDF:

- Skylark Exim is built around the message `Two Origins. One Standard.`
- Origins are the Bay of Bengal and Andhra aquaculture ponds.
- The seafood process includes nine major stages:
  1. Sourcing and receipt
  2. Deshelling and washing
  3. De-heading, peeling, and deveining
  4. Grading and sorting
  5. Quality control, residue testing, and inspection
  6. Freezing and glazing
  7. Packing
  8. Cold storage
  9. Export documentation and logistics
- Product forms include:
  - `HOSO` - Head On Shell On
  - `HLSO` - Headless Shell On
  - `PUD` - Peeled Undeveined
  - `PTO` - Peeled Tail On
- Size grades include:
  - `10/20`
  - `21/25`
  - `26/30`
  - `31/40`
  - `41/50`
- Use quality and residue-testing language:
  - Nitrofurans
  - Chloramphenicol
  - Tetracyclines
  - HACCP
  - EIC
  - EU and US residue limits
  - Every-batch testing
  - Certificate travels with the carton
- Use cold-chain language:
  - Minus 18 to minus 20 degrees Celsius
  - 700-pallet cold storage capacity
  - Reefer container
  - Cold chain
  - Batch documentation
- Use export language:
  - Visakhapatnam / Vizag
  - Bay of Bengal
  - Andhra coast
  - Health certificates
  - Packing lists
  - Certificates of origin
  - Residue certificates
  - Compliance records

### Reference Website Principles From Videos

The screen recordings show two useful reference directions:

1. Maritime cinematic reference:
   - Full-screen WebGL-style worlds.
   - Ships, ocean, geography, mist, cinematic parallax.
   - Minimal nav and sparse premium typography.
   - Scroll moves through scenes instead of jumping between pages.

2. Trading/finance cinematic reference:
   - Strong hero impact.
   - Bold text layered over animated 3D/AI visuals.
   - Product modules revealed through motion.
   - Glowing lines, route maps, network/data overlays.
   - High polish and strong conversion moments.

Skylark should use the cinematic depth of both references, but not copy their dark visual mood. Skylark must feel sunlit, coastal, Indian, precise, and export-ready.

## 3. Target Audience

### Primary Users

- International seafood buyers
- Importers
- Distributors
- Cold-chain procurement teams
- Restaurant and hospitality suppliers
- Export trade partners
- B2B buyers evaluating trust, consistency, and compliance

### User Mindset

These buyers do not want a pretty seafood brochure. They want proof:

- Can this exporter supply consistent product?
- Does the operation understand residue risk?
- Is the cold chain disciplined?
- Are documents reliable?
- Can they ship to strict markets?
- Does the product match the label?
- Will the carton arrive as promised?

### Emotional Goal

By the end of the scroll, the buyer should feel:

- Skylark is serious.
- The origin story is real.
- The process is controlled.
- The lab matters.
- The cold chain is credible.
- The export promise is backed by evidence.
- This is a company worth contacting for an RFQ.

## 4. Non-Negotiable Experience Requirements

### Entire Site Must Be Cinematic Scroll

Every major part of the website must be controlled by scroll.

Required:

- Scroll-linked camera movement.
- Scroll-linked 3D scene transitions.
- Scroll-linked text reveals.
- Scroll-linked object movement.
- Scroll-linked lighting changes.
- Scroll-linked route-map and documentation reveals.
- Scroll-linked product-form transitions.
- Scroll-linked export finale.

Avoid:

- Static section blocks.
- Generic landing-page hero.
- Card-heavy SaaS layout.
- Stock-image brochure pages.
- Separate pages that break the cinematic journey.
- Text-heavy walls.
- Random animations unrelated to the story.

### Cinematic First Screen

The first viewport must instantly communicate:

- Skylark Exim
- Seafood export
- India / Bay of Bengal
- Large ship / export scale
- Premium trust
- Morning/late-morning sunlight
- Motion and scroll-based cinematic experience

Do not begin with a static logo screen unless it lasts only as a short loading transition.

### Time Of Day

All scenes must feel like 10 AM to afternoon.

Required visual cues:

- Bright coastal sunlight.
- Blue-green water.
- Indian humidity haze.
- Sharp white specular glints on ocean and ice.
- Warm highlights on cranes, decks, and containers.
- Clean stainless-steel interiors.
- Cold-storage whites and blues.

Avoid:

- Early dawn.
- 4 AM darkness.
- Night harbour.
- Storm scenes.
- Heavy noir.
- Gloomy drama.

## 5. Recommended Technical Stack

Use the best production stack for a cinematic WebGL scroll website.

### Frontend

- `Vite`
- `React`
- `TypeScript`
- `React Three Fiber`
- `Three.js`
- `Drei`
- `GSAP`
- `ScrollTrigger`
- `Lenis`
- `Zustand`
- `React Hook Form`
- `Zod`
- `Lucide React`

### Animation

- Use `GSAP ScrollTrigger` for the main cinematic scroll timeline.
- Use `Lenis` for smooth scroll.
- Use `React Three Fiber` for WebGL scene rendering.
- Use `Drei` for environment, loaders, camera helpers, Html overlays, Float, Text, shader utilities, and performance helpers.
- Use `Anime.js` only for small UI micro-interactions if it improves polish without fighting GSAP.
- Use CSS transitions for basic hover states.

### 3D And Media Pipeline

- Blender MCP for custom GLB assets.
- Higgsfield, using the latest Blender collector workflow, for cinematic video loops, concept shots, textures, scene references, and asset enhancement.
- GLB/GLTF for 3D assets.
- KTX2, WebP, or AVIF for optimized textures.
- Draco or Meshopt compression for models.
- Optional `postprocessing` package for bloom, depth of field, vignette, and color grading.

### Automation Principle

The build must be treated as an automated production pipeline, not a manual design exercise.

Claude should orchestrate the entire process end to end:

1. Create the production website scaffold.
2. Create the Blender asset plan.
3. Use Blender MCP to generate the required 3D models and animatable scene assets.
4. Run and verify the Blender outputs.
5. Use the latest Higgsfield Blender collector workflow to collect Blender outputs and generate cinematic loops, image references, motion references, textures, or enhancement passes.
6. Integrate Blender and Higgsfield outputs into the Three.js/WebGL website.
7. Build the scroll animation system.
8. Run the website locally.
9. Run automated visual QA.
10. Iterate until the website is complete.

The only acceptable reasons to pause are missing authentication, missing credits, unavailable Blender MCP access, unavailable Higgsfield access, or a hard local machine failure.

### Forms And Buyer Flow

- React Hook Form for RFQ.
- Zod validation.
- Optional email/API integration later.
- For now, store form state cleanly and make the CTA production-ready.

### QA

- Playwright for visual checks.
- Lighthouse for performance and accessibility.
- Manual mobile viewport checks.
- Canvas nonblank checks.

## 5A. Automated Agentic Production Pipeline

This project must be executed as one automated creative-technical pipeline.

Do not treat Blender, Higgsfield, and the website as separate manual phases. Claude should coordinate them like a senior developer running a production build.

### Pipeline Objective

Generate the website, generate the 3D assets, generate/enhance cinematic media, integrate everything, run it, QA it, and improve it without waiting for manual handoff after every step.

### Required Automation Flow

1. Project Inspection
   - Inspect the local folder.
   - Detect whether an app already exists.
   - Detect source references, PDF, videos, and any existing assets.
   - Create an asset inventory file if helpful.

2. Website Scaffold
   - If no app exists, create a Vite React TypeScript production app.
   - Install Three.js, React Three Fiber, Drei, GSAP, ScrollTrigger, Lenis, Zustand, React Hook Form, Zod, and Lucide React.
   - Create the cinematic scroll shell immediately.

3. Blender MCP Asset Generation
   - Use Blender MCP to create every required 3D model.
   - Create all models as web-ready modular GLB assets.
   - Create correct pivots and separated moving parts for animation.
   - Export each model to a predictable asset folder.
   - Generate preview renders or turntables for verification.

4. Blender Run And Verification
   - Open/run the generated Blender scene or asset generation script.
   - Verify that every model exists.
   - Verify exported GLB files load.
   - Verify animations/pivots where required.
   - Check scale consistency between assets.
   - Fix broken models before moving to website integration.

5. Higgsfield Blender Collector Step
   - Use the latest Higgsfield Blender collector workflow after Blender models are created and verified.
   - Collect Blender renders, turntables, model previews, camera paths, scene references, and visual passes.
   - Use collected Blender outputs as Higgsfield inputs or references.
   - Generate cinematic video loops, hero shots, texture references, and enhancement imagery that match the actual Blender/WebGL direction.
   - Do not generate disconnected random visuals that cannot be used in the website.

6. Asset Processing
   - Convert Higgsfield outputs to web formats.
   - Compress video loops.
   - Convert images to WebP or AVIF.
   - Compress GLB assets with Draco or Meshopt where possible.
   - Create responsive versions for desktop and mobile.

7. WebGL Integration
   - Load Blender GLBs into React Three Fiber scenes.
   - Use Higgsfield outputs as backgrounds, texture references, fallback media, hero loops, or scene-enhancement layers.
   - Connect all 3D objects to the master GSAP ScrollTrigger timeline.
   - Replace placeholders with final generated assets.

8. Cinematic Scroll Build
   - Build one master scroll timeline from opening ship to export finale.
   - Connect scroll progress to camera, object animation, shader uniforms, text reveals, product transitions, document reveals, and route-map arcs.
   - Ensure Ocean is the primary default route.
   - Keep Ponds as a second-origin chapter and optional route toggle.

9. Runtime Verification
   - Start the dev server.
   - Open the site locally.
   - Verify WebGL canvas renders.
   - Verify scroll animation works from first frame to final frame.
   - Verify product explorer and RFQ form.

10. Automated QA And Iteration
   - Run Playwright screenshots across desktop, wide desktop, tablet, and mobile.
   - Check canvas pixels so the WebGL scene is not blank.
   - Check text overlap and readability.
   - Check performance.
   - Fix issues and rerun QA until the cinematic experience is stable.

### Automation Deliverables

Claude should produce these project outputs:

- Production React/TypeScript website.
- Blender-generated GLB assets.
- Higgsfield-generated cinematic media or references.
- Integrated WebGL scene system.
- Scroll animation timeline.
- Product explorer.
- RFQ form.
- Asset manifest.
- QA screenshots.
- Local dev URL.
- Clear final build notes.

### Automation Guardrails

- Do not stop after writing prompts.
- Do not stop after creating Blender assets.
- Do not stop after generating Higgsfield media.
- Do not leave the website with placeholders if final assets can be generated.
- Do not require manual copying between Blender, Higgsfield, and the website unless a connector limitation makes it unavoidable.
- If a tool requires login, credits, or approval, pause only for that specific blocker and continue immediately after it is resolved.
- Keep every asset named predictably and referenced by the website.
- Maintain an asset manifest so nothing gets lost.

## 6. Core Narrative

### Story Title

`The Voyage Under Seal`

### Story Premise

A reefer container waits at Visakhapatnam under late-morning sunlight. Inside it is not just seafood. It contains an entire chain of decisions: the boat, the ocean, the first ice, the inspection table, the washing water, the peeling hands, the grading number, the residue lab, the freezing tunnel, the carton label, the cold store, the export documents, and the seal.

The site scrolls backward and forward through that chain. The ocean is the primary origin. The ponds appear as the controlled second origin that proves Skylark can handle both wild catch and aquaculture product with the same standard.

### Main Narrative Line

`A shipment is never just a shipment. It is a history under seal.`

### Final Narrative Line

`Two origins. One standard. From this shore to yours.`

## 7. Scroll Architecture

The site should be one continuous scroll timeline.

Use scroll progress to control a master timeline from `0.00` to `1.00`.

### Scene Timeline

| Scroll Progress | Scene | Main Visual | Story Beat |
|---|---|---|---|
| 0.00 - 0.08 | Opening Ship | Large vessel, reefer container, port, sunlight | A shipment is waiting |
| 0.08 - 0.16 | Ocean Origin | Camera flies from ship to fishing vessel | The Bay gives once |
| 0.16 - 0.24 | Catch And Ice | Crew, crates, shrimp, ice, water | Freshness begins at first touch |
| 0.24 - 0.32 | Harbour Intake | Vizag harbour, inspection, accepted/rejected sorting | Not everything earns the name |
| 0.32 - 0.40 | Pond Origin Insert | Aerial ponds, water sampling, batch log | Second origin, same standard |
| 0.40 - 0.50 | Washing And Handling | Stainless line, chilled water, workers | Respect before processing |
| 0.50 - 0.60 | Product Forms | HOSO, HLSO, PUD, PTO animated reveal | Buyer specs become physical |
| 0.60 - 0.70 | Grading | Conveyor, grades, size overlays | The number means something |
| 0.70 - 0.80 | QC And Residue Lab | Instruments, inspector, certificates | Trust is a result |
| 0.80 - 0.88 | Freezing And Glazing | IQF tunnel, frost, glaze mist | Time stops |
| 0.88 - 0.94 | Packing And Cold Storage | Cartons, labels, pallets, 700-pallet store | Cold chain holds |
| 0.94 - 1.00 | Export Finale | Documents, reefer seal, vessel departs | From this shore to yours |

### Scroll Rule

No scene should feel like a separate web page. Each scene must visually transition into the next using one of:

- Camera movement.
- Object match cut.
- Shader transition.
- Fog/haze wipe.
- Water surface dissolve.
- Container-door wipe.
- Document overlay transforming into route map.
- Shrimp/product close-up becoming next processing scene.

## 8. Scene-By-Scene Requirements

### Scene 1: Opening Ship

#### Purpose

Establish scale, premium export credibility, India, seafood logistics, and cinematic scroll control.

#### Visual

- Large export vessel at or near Visakhapatnam port.
- Reefer container in foreground.
- Blue-green Bay of Bengal.
- Sunlight around 10 AM.
- Cranes, quay, containers, mild haze.
- Subtle workers/forklift movement.
- Camera starts close to container seal and pulls out to reveal vessel scale.

#### Copy

`SKYLARK EXIM`

`A shipment is never just a shipment.`

`It is a history under seal.`

`Two origins. One standard.`

#### Interaction

- Scroll prompt should be visual, not instructional-heavy.
- A small progress rail appears.
- Nav is transparent and minimal.

#### Animation

- Container seal glints.
- Ship engine vibration subtle.
- Water shader moves.
- Heat haze/light haze in distance.
- Camera dolly reveals port scale.

### Scene 2: Ocean Origin

#### Purpose

Make Ocean the primary route.

#### Visual

- Camera leaves the port and sweeps over the Bay of Bengal.
- Fishing vessel appears in late-morning sunlight.
- Nets, crates, ice, wet deck.
- The water feels alive but not stormy.

#### Copy

`The Bay gives once.`

`We protect what arrives at its peak.`

#### Animation

- Ocean shader with gentle waves.
- Boat has slow roll/pitch.
- Ice sparkles.
- A close-up shrimp/crate reveal leads into intake.

### Scene 3: Catch, Ice, And First Touch

#### Purpose

Show freshness discipline before the product reaches the plant.

#### Visual

- Shrimp moved into ice.
- Crew hands, crates, deck water.
- No unsafe or dirty handling.
- Product feels fresh, cold, export-worthy.

#### Copy

`Freshness is protected before processing begins.`

`The first standard is the first touch.`

#### Details

- Show immediate chilling.
- Show batch awareness beginning.
- Do not show chaos or excessive fishing violence.

### Scene 4: Harbour Intake

#### Purpose

Show that Skylark does not accept everything automatically.

#### Visual

- Vizag harbour/intake bay.
- Inspector handling shrimp under light.
- Two visual flows: accepted and rejected.
- Camera crosses from coastal light into clean facility light.

#### Copy

`The ocean decides what it gives.`

`Skylark decides what earns its name.`

#### Animation

- Camera tracks alongside crates.
- Product passes inspection light.
- Accepted/rejected paths separate as animated lines.

### Scene 5: Pond Origin Insert

#### Purpose

Include the second origin without making it the dominant route.

#### Visual

- Aerial view of Andhra aquaculture ponds.
- Geometric pond grid.
- Technician takes water sample.
- Batch tag appears.
- Logbook or digital ledger animates.

#### Copy

`The pond is a controlled history.`

`Water. Inputs. Harvest. Batch identity.`

`Known before the carton exists.`

#### Interaction

- Include a small route toggle:
  - `Ocean`
  - `Ponds`
- Ocean remains selected by default.
- Selecting `Ponds` shifts the scene camera to the pond path, then rejoins the same processing timeline.

### Scene 6: Washing And Handling

#### Purpose

Turn a basic process step into a premium trust moment.

#### Visual

- Clean water running before product enters.
- Shrimp enters washing drum or chilled wash channel.
- Stainless steel.
- PPE workers.
- Water clarity emphasized.

#### Copy

`Before anything else, respect.`

`Clean water. Controlled temperature. Trained hands.`

#### Animation

- Water particles and refraction.
- Slow motion wash moment.
- Camera tracks over stainless surface into worker hands.

### Scene 7: De-Heading, Peeling, Deveining

#### Purpose

Show Indian seafood-processing craft and precision.

#### Visual

- Close-up hands working.
- Worker silhouettes or detailed models if available.
- Clean motion, precision, repetition.
- No gore, no discomfort.

#### Copy

`Ten thousand hours in every pair of hands.`

`Each cut protects consistency.`

#### Overlay Labels

- `HOSO`
- `HLSO`
- `PUD`
- `PTO`

### Scene 8: Product Forms Explorer

#### Purpose

Make the product offering clear for buyers.

#### Visual

Four product states appear in a cinematic carousel controlled by scroll:

- HOSO
- HLSO
- PUD
- PTO

#### Required Content

For each product form:

- Full name.
- 3D or generated product visual.
- Common buyer use.
- Size grades.
- Packing/export status.

#### Copy

`A buyer who names a form is not naming a shape.`

`They are naming a promise of consistency.`

#### Interaction

- Scroll cycles through forms.
- Click/tap lets user pin a form.
- Product spec panel appears as a buyer-facing overlay.

### Scene 9: Grading And Sorting

#### Purpose

Show that the grade number matters commercially.

#### Visual

- Grading conveyor.
- Product sizes separate into clean channels.
- Overlay grade numbers.
- Restaurant/importer use case implied, not overdone.

#### Grade Overlays

- `10/20`
- `21/25`
- `26/30`
- `31/40`
- `41/50`

#### Copy

`The number on the label is an agreement.`

`Size, weight, type, and consistency travel together.`

### Scene 10: QC And Residue Testing

#### Purpose

This is the commercial trust centre of the website.

#### Visual

- QC inspector is the hero character of this section.
- Bright residue lab.
- Sample vials.
- Instruments.
- Inspection lamp.
- Certificate and batch file.
- HACCP/EIC visual documentation.

#### Copy

`Trust is not a claim.`

`It is a result.`

`Every batch is tested before shipment.`

`Nitrofurans. Chloramphenicol. Tetracyclines.`

`EU and US limits, whichever is stricter.`

`The certificate travels with the carton.`

#### Tone

Serious. Quiet. Evidence-led.

Do not make this section flashy or comedic. Use controlled camera movement, precise close-ups, and minimal sound/motion.

### Scene 11: Freezing And Glazing

#### Purpose

Make the cold-chain process visually beautiful and premium.

#### Visual

- IQF tunnel.
- Frost crystals.
- Cold vapour.
- Thin water glaze forming on frozen shrimp.
- Block freezing and blast freezing references.

#### Copy

`Where time stops.`

`Individually Quick Frozen.`

`A clean glaze protects the journey.`

#### Animation

- Shrimp passes into cold tunnel.
- Particles crystallize.
- Glaze mist catches sunlight/cold light.
- Camera macro close-up.

### Scene 12: Packing

#### Purpose

Show that the carton is the buyer's first physical proof.

#### Visual

- Vacuum pack sealing.
- Cartons filled and weighed.
- Labels applied.
- Scale confirmation.
- Pallet wrapping.

#### Copy

`A carton is not packaging.`

`It is proof.`

#### Label Fields

Show these as animated UI overlays:

- Product name
- Species
- Size grade
- Product form
- Batch number
- Net weight
- Origin
- Country of origin
- Residue certificate
- HACCP / EIC
- Buyer allocation

### Scene 13: Cold Storage

#### Purpose

Show scale and cold-chain discipline.

#### Visual

- Cold storage doors open.
- Racking scale.
- Pallets and cartons.
- Forklift.
- Temperature display.
- Frost/cold vapour controlled tastefully.

#### Copy

`Minus 18 to minus 20 degrees Celsius.`

`700 pallets of cold-chain readiness.`

`Not one degree of compromise.`

#### Animation

- Doors open as scroll progresses.
- Camera moves down aisle.
- Temperature display sharpens.
- Pallet labels light up.

### Scene 14: Export Documentation

#### Purpose

Show export trust beyond product quality.

#### Visual

- Export officer prepares documents.
- Health certificate.
- Packing list.
- Certificate of origin.
- Residue certificate.
- Compliance record.
- Documents animate into a clean route map.

#### Copy

`A container does not move on heritage.`

`It moves on paperwork that is correct.`

#### Required Documents

- Health certificate
- Packing list
- Certificate of origin
- Residue certificate
- Compliance records
- HACCP / EIC documentation

### Scene 15: Reefer Loading And Seal

#### Purpose

Bring all proof into one final action.

#### Visual

- Pallets loaded into reefer container.
- Temperature set.
- Container door closes.
- Seal bar drops.
- Lock/seal close-up.
- Vessel departs into the Bay of Bengal.

#### Copy

`From this shore to yours, every step protects a promise.`

`Two origins. One standard.`

#### Animation

- Documents, batch labels, QC proof, cold-chain temp, and origin route lines converge into the seal.
- Seal click is the final emotional beat.
- Camera pulls out to ship leaving in afternoon light.

### Scene 16: RFQ Finale

#### Purpose

Convert the buyer after the cinematic proof.

#### Visual

- RFQ form appears as a precise buyer console over the final ship/ocean scene.
- Not a generic contact form.
- Keep it minimal, premium, and functional.

#### Fields

- Product form
- Size grade
- Origin preference
- Destination market
- Estimated quantity
- Packaging preference
- Required certifications/documents
- Buyer name
- Company
- Email
- WhatsApp
- Message

#### CTA

`Request Export Quote`

Secondary CTA:

`Download Process Profile`

## 9. UI Requirements

### Navigation

Use a minimal transparent nav:

- Skylark Exim wordmark
- Origins
- Process
- Products
- Quality
- Export
- RFQ

Navigation should not feel like a normal website menu. It should feel like a cinematic chapter selector.

### Progress Rail

Add a vertical or horizontal chapter progress rail:

- Ship
- Ocean
- Intake
- Ponds
- Processing
- Products
- QC
- Freezing
- Packing
- Cold Storage
- Export
- RFQ

Each marker updates based on scroll position.

### Route Toggle

Include an origin toggle:

- Ocean
- Ponds

Default: `Ocean`.

Rules:

- The toggle should not break the scroll experience.
- It should shift camera and content context while preserving the overall journey.
- If too complex for v1, implement Ocean as default and include Ponds as a scroll chapter.

### Product Controls

Use a cinematic product selector:

- Four product states.
- Scroll-scrubbed transitions.
- Click/tap support.
- Stable spec panel.
- Clear buyer information.

### Buttons

Use icon-supported buttons where appropriate:

- Anchor/ship icon for origin.
- Snowflake icon for freezing/cold chain.
- File/check icon for documentation.
- Send icon for RFQ.

Use Lucide React if icons are needed.

## 10. Visual Design Requirements

### Overall Look

Premium cinematic B2B maritime export.

It should feel like:

- Maritime film.
- Indian seafood export.
- Scientific quality proof.
- Cold-chain logistics.
- High-end interactive WebGL.

It should not feel like:

- Restaurant website.
- Local fish market.
- Generic seafood brochure.
- Crypto/trading clone.
- Dark tech template.
- Tourism site.

### Color Palette

Use a varied coastal-industrial palette:

- Deep water: `#063544`
- Bay blue: `#0E6F8E`
- Sea green: `#2FA889`
- Sunlit brass: `#D7A84F`
- Ice white: `#F4FAFA`
- Stainless grey: `#AAB8BC`
- Coral shrimp accent: `#E36F52`
- Ink: `#102024`
- Lab white: `#F7FBFC`
- Cold-chain blue: `#BFE8F4`

Important:

- Do not make the site all blue.
- Use sunlight, brass, stainless, white, and coral accents.
- Keep QC/lab sections brighter and cleaner.
- Keep freezing sections crisp and cold.

### Typography

Recommended:

- Headings: `Sora` or `Space Grotesk`
- Body: `Inter` or `Manrope`
- Technical labels: tabular numerals

Rules:

- No negative letter spacing.
- No tiny unreadable text.
- No giant text inside small cards.
- Use large type only for cinematic hero statements.
- Technical labels should feel precise and export-grade.

### Composition

- Full-bleed canvas.
- Text overlays placed with strong margins.
- Use dark translucent gradients only when needed for readability.
- Keep panels minimal.
- Do not use nested cards.
- Do not use generic floating blobs, random gradients, or decorative orbs.

## 11. 3D Asset Requirements

Use Blender MCP to create or refine these assets.

### Required GLB Assets

1. `skylark_export_vessel.glb`
   - Large vessel.
   - Cargo/export scale.
   - Clean silhouette.
   - Suitable for late-morning ocean scene.

2. `reefer_container.glb`
   - Reefer unit.
   - Door animation.
   - Lock bar and seal.
   - No baked fake brand text unless brand assets are available.

3. `bay_fishing_vessel.glb`
   - Indian fishing vessel.
   - Deck crates.
   - Nets/gears.
   - Gentle animation-ready pivots.

4. `ice_crates_and_shrimp.glb`
   - Crates with ice and shrimp/product forms.
   - Clean export-grade handling.

5. `vizag_harbour_intake.glb`
   - Dock/intake transition environment.
   - Accepted/rejected flow areas.

6. `andhra_pond_grid.glb`
   - Aquaculture ponds.
   - Bund roads.
   - Water-sampling point.
   - Harvest crates.

7. `processing_line.glb`
   - Washing drum/channel.
   - Stainless tables.
   - Grading conveyor.
   - Trays.

8. `worker_character_set.glb`
   - Fishing crew.
   - Farm technician.
   - Processing worker.
   - QC inspector.
   - Export officer.
   - Cold-store operator.

9. `shrimp_product_forms.glb`
   - HOSO.
   - HLSO.
   - PUD.
   - PTO.
   - Use morph targets or separate meshes.

10. `qc_lab_station.glb`
   - Lab bench.
   - Sample vials.
   - Testing instrument.
   - Certificate folder.
   - Inspection lamp.

11. `iqf_freezing_tunnel.glb`
   - Tunnel.
   - Conveyor.
   - Frost particle anchor points.

12. `cold_storage_racks.glb`
   - Pallet racks.
   - Cartons.
   - Forklift path.
   - Temperature display.

13. `export_document_set.glb`
   - Health certificate.
   - Packing list.
   - Certificate of origin.
   - Residue certificate.
   - Compliance records.

14. `world_route_map.glb`
   - Abstract globe/map or route-line system.
   - India as starting point.
   - Global arcs to buyer markets.

### Asset Optimization Rules

- Use GLB.
- Optimize for web.
- Use texture atlases where possible.
- Prefer baked normals over heavy geometry.
- Use mesh compression.
- Keep pivots correct for animated doors, conveyor, ship, crates, labels, and seal bar.
- Avoid huge single-scene files.
- Use modular assets.

## 12. Higgsfield Generation Plan

Use Higgsfield credits intentionally and as part of the automated pipeline. Higgsfield should be used after the Blender MCP asset generation and verification pass, using the latest Blender collector workflow to collect Blender outputs.

Generate only visuals that will become hero loops, fallback videos, reference images, texture references, scene enhancement passes, or motion references used by the website.

Do not use Higgsfield as a disconnected brainstorming tool. It must receive the Blender/WebGL direction and reinforce the actual cinematic scroll build.

### Higgsfield Automation Requirements

- Use Blender-generated renders, turntables, asset previews, or camera-path exports as source/reference material where possible.
- Preserve the 10 AM to afternoon lighting direction.
- Preserve Indian seafood export context.
- Preserve the Ocean-primary route.
- Generate each clip or image for a defined website scene.
- Save outputs into a structured media folder.
- Convert outputs into web-ready formats before integration.
- Integrate each accepted output into the site as a texture, background loop, fallback, transition layer, or scene reference.
- Reject or regenerate outputs that show unsafe handling, dirty facilities, incorrect time of day, distorted product, fake unreadable labels, or generic seafood imagery.

### Prompt Rules

Every Higgsfield prompt must include:

- Indian seafood export context.
- Bay of Bengal or Andhra coast.
- 10 AM or afternoon sunlight.
- Premium cinematic commercial style.
- Clean handling.
- Trust and export quality.
- No darkness, storm, or unsafe handling.

### Prompt 1: Opening Ship

Prompt:

`Premium cinematic 3D-realistic shot of a large refrigerated cargo vessel and reefer containers at Visakhapatnam port on the Indian east coast, bright 10 AM sunlight, blue-green Bay of Bengal water, humid coastal haze, cranes in the background, wet metal deck glints, slow dolly camera movement, high-end seafood export logistics commercial, clean composition, global trade scale, ultra realistic, 16:9`

Negative:

`night, dawn, storm, rain, dirty port, tourist beach, fantasy, messy text, distorted logo, cartoon, low quality, unsafe loading`

### Prompt 2: Ocean Fishing Route

Prompt:

`Indian fishing vessel on the Bay of Bengal at late morning, crew handling iced seafood crates with clean export-grade discipline, blue-green ocean, sunlight sparkling on water, cinematic tracking shot from sea level, fresh ice, wet deck, Andhra coast maritime atmosphere, premium seafood export documentary, realistic motion, 16:9`

Negative:

`night, early dawn, storm, unsafe handling, dirty deck, dead fish pile, chaos, overdramatic waves, distorted hands, low hygiene`

### Prompt 3: First Ice Close-Up

Prompt:

`Macro cinematic close-up of fresh shrimp being placed into clean crushed ice on a stainless seafood export crate, bright coastal daylight reflections, cold vapor, water droplets, premium Indian seafood export film, high trust food handling, realistic texture, shallow depth of field, 16:9`

Negative:

`dirty ice, grey product, spoiled seafood, blood, clutter, unsafe gloves, low quality, cartoon`

### Prompt 4: Andhra Aquaculture Ponds

Prompt:

`Aerial cinematic shot over geometric shrimp aquaculture ponds in coastal Andhra Pradesh at 10 AM, farm technician taking a water sample on the pond bund, organized ponds, clean water, batch traceability tags, harvest crates, warm sunlight, calm ripples, premium food export documentary tone, realistic India coastal aquaculture, 16:9`

Negative:

`night, sunset, polluted water, muddy chaos, fantasy, rice farm, tourist resort, low quality`

### Prompt 5: Processing Facility

Prompt:

`Premium cinematic seafood processing facility in India, stainless steel tables, trained workers in hygienic PPE carefully handling shrimp, chilled washing water, inspection lights, grading conveyor, clean white and blue environment, slow smooth camera dolly, global export quality tone, realistic documentary commercial, 16:9`

Negative:

`dirty factory, unsafe food handling, clutter, exposed hair, horror lighting, dark shadows, low quality`

### Prompt 6: Product Forms

Prompt:

`Four premium seafood product-form renders of export shrimp, HOSO head on shell on, HLSO headless shell on, PUD peeled undeveined, PTO peeled tail on, clean ice-white background, subtle stainless surface, realistic texture, buyer specification style, high-end B2B seafood catalogue, 16:9`

Negative:

`cartoon, cooked shrimp, restaurant garnish, plate dish, messy label, low quality, distorted anatomy`

### Prompt 7: QC Lab

Prompt:

`Sterile seafood residue testing lab in India, serious QC inspector preparing shrimp sample, lab instrument, sample vial, certificate folder, bright fluorescent clean environment, evidence-led commercial film, slow close-up camera movement, HACCP and EIC compliance mood, premium export trust, 16:9`

Negative:

`messy lab, science fiction, party lighting, cartoon, fake readable text, low detail, dirty surfaces`

### Prompt 8: IQF Freezing And Glazing

Prompt:

`Beautiful cinematic macro shot of individual shrimp exiting an IQF freezing tunnel, fine frost crystals, clean glazing mist forming a thin protective ice layer, stainless steel, cold vapour, crisp highlights, premium seafood export commercial, bright clean cold-chain look, 16:9`

Negative:

`dirty ice, freezer burn, grey product, gloomy lighting, fantasy ice cave, low quality`

### Prompt 9: Cold Storage

Prompt:

`Large seafood export cold storage facility, rows of pallet racking with sealed cartons, temperature display showing minus 18 to minus 20 degrees Celsius, forklift moving carefully, bright cold white-blue lighting, 700-pallet capacity impression, premium Indian export logistics commercial, 16:9`

Negative:

`dark warehouse, clutter, unsafe forklift, broken cartons, unreadable fake text, low quality`

### Prompt 10: Export Seal

Prompt:

`Reefer container being sealed at Visakhapatnam port, pallets of frozen seafood cartons inside, temperature unit visible, export documents in hand, container lock bar closing, large vessel departing into Bay of Bengal in afternoon sun, premium global seafood logistics commercial, cinematic wide shot, 16:9`

Negative:

`night, storm, unsafe loading, generic fake logos, dirty container, distorted hands, low quality`

## 13. Blender MCP Prompt Plan

Use Blender MCP before Higgsfield. Blender is the source-of-truth 3D production step.

Claude must create the models, run/verify the Blender outputs, export web-ready GLBs, and only then pass collected Blender outputs into the latest Higgsfield Blender collector workflow.

### Blender Automation Requirements

- Generate every required model in Blender MCP.
- Run Blender or the MCP generation process, not just describe the model.
- Export every accepted asset as GLB.
- Create preview renders or turntables for inspection.
- Validate that each exported GLB loads in the web project.
- Keep animation pivots correct.
- Keep asset scale consistent.
- Name assets predictably.
- Maintain an asset manifest.
- Fix broken geometry, missing materials, scale issues, or unusable exports before integrating them.

### Blender Prompt Style

Use prompts like:

`Create a low-to-mid poly optimized GLB asset for a premium WebGL cinematic website. The asset is [object]. It should match Indian seafood export, Bay of Bengal, late-morning sunlight, clean industrial realism. Use separated moving parts with correct pivots, optimized materials, and no baked unverified text. Export as GLB with web-friendly textures.`

### Blender Build Order

1. Reefer container with door and seal animation.
2. Large export vessel.
3. Fishing vessel and deck crates.
4. Ocean/port modular set.
5. Shrimp product-form models.
6. Processing line.
7. QC lab station.
8. IQF tunnel and cold-storage racks.
9. Pond grid.
10. Documentation and route-map assets.

### Blender Output Folder Structure

Use a clean structure similar to:

- `public/assets/models/vessels/`
- `public/assets/models/containers/`
- `public/assets/models/ocean/`
- `public/assets/models/ponds/`
- `public/assets/models/processing/`
- `public/assets/models/products/`
- `public/assets/models/qc/`
- `public/assets/models/cold-chain/`
- `public/assets/models/export/`
- `public/assets/renders/blender-previews/`
- `public/assets/media/higgsfield/`
- `src/data/assetManifest.ts`

### Asset Manifest Requirements

Create and maintain an asset manifest with:

- Asset ID.
- File path.
- Scene usage.
- Source tool: Blender MCP, Higgsfield, manual, generated placeholder.
- Status: planned, generated, verified, integrated, needs-regeneration.
- Notes about pivots, animation, scale, and optimization.

### Must-Have Animatable Parts

- Ship movement path.
- Ocean waves via shader, not heavy mesh.
- Reefer container doors.
- Seal bar.
- Conveyor.
- Washing drum.
- Product-form morph/transition.
- QC document/card reveal.
- Cold-storage door.
- Forklift path.
- Route-line map arcs.

## 14. Motion Design

### Scroll Motion Personality

Motion should be:

- Slow enough to feel premium.
- Direct enough to feel confident.
- Precise in QC sections.
- Beautiful in freezing/glazing.
- Expansive in ocean/export scenes.

Avoid:

- Overly bouncy UI.
- Random floating elements.
- Too much parallax.
- Camera spins.
- Motion sickness.
- Repeating the same reveal pattern in every section.

### Camera Rules

- One strong camera move per scene.
- Keep horizon stable in ocean scenes.
- Use close-ups for proof.
- Use wide shots for scale.
- Use shallow depth of field sparingly.
- Camera should never obscure critical text.

### Transition Ideas

- Container seal close-up becomes product batch tag.
- Ocean water surface becomes washing water.
- Ice sparkle becomes IQF frost.
- Certificate document becomes export route map.
- Cold-storage aisle becomes reefer container interior.
- Container door closing becomes final ship wide shot.

## 15. Content Requirements

### Mandatory On-Screen Copy

Use these lines exactly or very close:

- `SKYLARK EXIM`
- `Two Origins. One Standard.`
- `A shipment is never just a shipment.`
- `It is a history under seal.`
- `The Bay gives once.`
- `The first standard is the first touch.`
- `The pond is a controlled history.`
- `Water. Inputs. Harvest. Batch identity.`
- `Before anything else, respect.`
- `Ten thousand hours in every pair of hands.`
- `The number on the label is an agreement.`
- `Trust is not a claim. It is a result.`
- `Every batch is tested before shipment.`
- `Nitrofurans. Chloramphenicol. Tetracyclines.`
- `EU and US limits, whichever is stricter.`
- `The certificate travels with the carton.`
- `Where time stops.`
- `A carton is not packaging. It is proof.`
- `Minus 18 to minus 20 degrees Celsius.`
- `700 pallets of cold-chain readiness.`
- `Not one degree of compromise.`
- `From this shore to yours, every step protects a promise.`

### Product Copy

#### HOSO

`Head On Shell On`

`Whole shrimp presentation with head and shell retained for buyers who require full-form product integrity.`

#### HLSO

`Headless Shell On`

`Head removed, shell retained, prepared for buyers who need protection, yield control, and visual consistency.`

#### PUD

`Peeled Undeveined`

`Peeled product prepared for buyers who specify faster kitchen or processing use while retaining buyer-defined vein preference.`

#### PTO

`Peeled Tail On`

`Peeled with tail retained for presentation-led applications where consistency and appearance matter.`

### Process Copy

Keep copy minimal in the scroll. Use expanded copy only in hover/accordion/spec areas.

## 16. RFQ Form Requirements

### Form Goal

Turn cinematic trust into buyer action.

### Fields

- Product form: HOSO, HLSO, PUD, PTO, Other
- Size grade: 10/20, 21/25, 26/30, 31/40, 41/50, Other
- Origin preference: Ocean, Ponds, Either
- Destination market
- Estimated quantity
- Packaging preference
- Required documents
- Buyer name
- Company
- Email
- WhatsApp
- Message

### Validation

- Product form required.
- Destination market required.
- Buyer name required.
- Company required.
- Email or WhatsApp required.

### Success State

Show:

`Your RFQ has been prepared for Skylark Exim.`

If no backend exists:

`Connect this form to email, CRM, or WhatsApp before launch.`

## 17. Accessibility And Fallbacks

### Required

- HTML content must exist outside canvas.
- All route/product controls must be keyboard accessible.
- RFQ must be a real form.
- Canvas must have meaningful aria labels or be marked decorative where appropriate.
- Text contrast must be strong.
- Motion-reduced mode must exist.

### Reduced Motion

When `prefers-reduced-motion` is enabled:

- Disable smooth scroll inertia.
- Reduce camera movement.
- Use static scene snapshots.
- Keep chapter progression but remove heavy transitions.

### Low-Power Fallback

If WebGL fails:

- Use Higgsfield-generated stills or videos as backgrounds.
- Preserve the same scroll narrative.
- Keep RFQ functional.

## 18. Performance Requirements

### Targets

- Fast first meaningful paint.
- Lazy-load heavy 3D scenes.
- Keep hero interactive quickly.
- Avoid blocking the page on every GLB.

### Technical Rules

- Split each scene into separate lazy-loaded modules.
- Preload next scene assets based on scroll progress.
- Use compressed GLB.
- Use optimized textures.
- Use instancing for repeated cartons, crates, route markers, and particles.
- Use shader-based ocean rather than dense geometry.
- Use adaptive DPR.
- Pause offscreen animations.
- Avoid massive video backgrounds on mobile.

### Performance Budget

Initial load should include only:

- Core shell.
- Hero vessel/container low-detail asset or placeholder.
- Critical CSS.
- First text overlay.

Everything else loads progressively.

## 19. QA Requirements

### Visual QA

Use Playwright screenshots for:

- Desktop 1440x900
- Desktop wide 1920x1080
- Tablet 834x1194
- Mobile 390x844

Check:

- Canvas is not blank.
- Hero immediately communicates the business.
- Text does not overlap.
- Buttons are visible.
- Product forms are legible.
- RFQ works.
- Mobile scroll is smooth.
- Route toggle is usable.

### Cinematic QA

The site fails QA if:

- It looks like static sections stacked on a page.
- The camera movement feels random.
- The site is too dark.
- The ocean route does not feel primary.
- The QC section feels decorative instead of serious.
- Product details are hard to understand.
- The final export seal does not feel like a climax.

### Business QA

Check:

- HOSO/HLSO/PUD/PTO are present.
- Grades are present.
- HACCP/EIC are present.
- 700-pallet cold storage is present.
- EU/US limits are present.
- Every-batch testing is present.
- Certificate travels with carton is present.
- Vizag/Visakhapatnam, Andhra, and Bay of Bengal are present.
- Ocean and pond origins are both present.

## 20. Implementation Milestones

### Milestone 1: Foundation

- Create Vite React TypeScript app.
- Install dependencies.
- Build global layout.
- Add full-screen canvas.
- Add scroll manager.
- Add placeholder scene objects.
- Add minimal nav and progress rail.

### Milestone 2: Cinematic Timeline

- Build GSAP ScrollTrigger master timeline.
- Add camera path for all chapters.
- Add basic scene transitions.
- Add scroll-synced copy overlays.
- Add reduced-motion fallback.

### Milestone 3: Ocean Primary Route

- Add ship/port hero.
- Add ocean shader.
- Add fishing vessel sequence.
- Add ice/crate close-up.
- Add harbour intake.

### Milestone 4: Pond Insert

- Add Andhra pond grid.
- Add water sampling.
- Add batch traceability overlay.
- Add route toggle.
- Rejoin main processing timeline.

### Milestone 5: Processing And Products

- Add washing scene.
- Add worker/hand silhouettes or models.
- Add product-form explorer.
- Add grading and sorting sequence.
- Add buyer-friendly product panels.

### Milestone 6: Trust Core

- Add QC lab.
- Add residue-testing copy.
- Add HACCP/EIC overlays.
- Add certificate-travels-with-carton visual.
- Keep tone serious and precise.

### Milestone 7: Cold Chain And Export

- Add IQF/freezing/glazing scene.
- Add packing scene.
- Add 700-pallet cold storage.
- Add export documentation.
- Add reefer loading and seal.
- Add ship departure finale.

### Milestone 8: RFQ And Polish

- Add RFQ form.
- Add responsive polish.
- Add performance optimization.
- Add fallback imagery/video.
- Run QA.
- Fix all overlaps and blank states.

## 21. Claude Execution Instructions

When Claude receives this PRD:

1. Read this file fully.
2. Inspect the local project.
3. Use the existing codebase if present.
4. If no codebase exists, create a production-ready Vite React TypeScript project.
5. Build the cinematic scroll shell and master timeline with temporary primitives only long enough to prove the motion system.
6. Create the complete Blender MCP asset-generation plan.
7. Use Blender MCP to generate all required 3D models and animatable scene assets.
8. Run and verify the Blender outputs.
9. Export optimized GLB assets into the website asset folders.
10. Create the asset manifest.
11. Use the latest Higgsfield Blender collector workflow to collect verified Blender outputs.
12. Generate Higgsfield cinematic loops, images, textures, and enhancement passes for the exact website scenes.
13. Convert and optimize Higgsfield outputs for web.
14. Integrate Blender GLBs and Higgsfield media into the React Three Fiber site.
15. Connect all assets to the GSAP ScrollTrigger cinematic timeline.
16. Keep Ocean as the primary default route and include Ponds as the second-origin chapter/optional route.
17. Keep all major business details from this PRD.
18. Do not simplify the site into a generic landing page.
19. Do not stop after a design description; implement the website.
20. Do not leave manually replaceable placeholders if Blender or Higgsfield can generate the needed asset.
21. Start the dev server and provide the local URL.
22. Run Playwright visual QA before final response.
23. Fix QA issues and rerun checks until the cinematic scroll experience is presentable.

### Claude Automation Instruction

Claude should behave like an autonomous senior production agent.

The correct behavior is:

- Create models.
- Run Blender.
- Export assets.
- Use Higgsfield collector.
- Generate cinematic media.
- Integrate media.
- Run the website.
- QA the website.
- Fix the website.
- Report final URL and files.

The incorrect behavior is:

- Only writing prompts.
- Only giving advice.
- Only creating a PRD.
- Only creating static sections.
- Asking the user to manually do every Blender/Higgsfield step when the tools are available.
- Treating Higgsfield outputs as optional decoration.
- Treating Blender assets as optional placeholders.

## 22. Definition Of Done

The website is complete only when:

- It is a full cinematic scroll animation.
- Ocean is the primary route.
- Ponds are still represented as the second origin.
- The story flows from ship to ocean to process to proof to export.
- The first viewport feels premium and cinematic.
- All PDF-derived business details are included.
- Blender MCP has generated the required 3D assets, or any unavailable tool blocker is explicitly documented.
- Blender outputs have been run, exported, verified, and integrated.
- The latest Higgsfield Blender collector workflow has been used where available.
- Higgsfield outputs are scene-specific and integrated into the website where useful.
- The asset manifest exists and is up to date.
- Product forms are visible and useful.
- QC/residue testing is a central trust moment.
- Cold storage and 700-pallet capacity are visible.
- Export documentation is visible.
- RFQ flow is present.
- Mobile layout is polished.
- Motion-reduced fallback exists.
- WebGL fallback exists.
- No text overlaps.
- No blank canvas.
- The final seal/export scene feels like a strong ending.

## 23. Final Creative North Star

This website should feel like a buyer is moving through a living export film:

The ship waits.

The Bay gives.

The product is protected.

The pond proves traceability.

The plant applies discipline.

The lab earns trust.

The freezer stops time.

The carton carries proof.

The cold store holds the promise.

The documents clear the world.

The seal closes.

The vessel leaves.

`Two origins. One standard. From this shore to yours.`
