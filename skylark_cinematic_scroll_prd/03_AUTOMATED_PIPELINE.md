# Automated Production Pipeline

This project must be automated end to end.

Claude should not only write instructions. Claude should create, run, verify, integrate, QA, and iterate.

## Pipeline Summary

1. Inspect project.
2. Create website scaffold.
3. Build cinematic scroll shell.
4. Create Blender MCP model plan.
5. Generate all Blender models.
6. Run Blender outputs.
7. Export optimized GLB assets.
8. Verify models and animations.
9. Use latest Higgsfield Blender collector workflow.
10. Generate cinematic Higgsfield media.
11. Process and compress media.
12. Integrate assets into Three.js/React website.
13. Connect everything to GSAP scroll timeline.
14. Run dev server.
15. Run Playwright visual QA.
16. Fix issues.
17. Deliver final URL and files.

## Folder Structure

Use or create:

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
- `public/assets/media/fallbacks/`
- `src/data/assetManifest.ts`
- `src/scenes/`
- `src/components/`
- `src/timeline/`
- `src/styles/`

## Asset Manifest

Create an asset manifest with these fields:

- `id`
- `name`
- `type`
- `sourceTool`
- `filePath`
- `scene`
- `status`
- `animationNotes`
- `scaleNotes`
- `optimizationNotes`
- `fallbackPath`

Statuses:

- `planned`
- `generated`
- `verified`
- `integrated`
- `needs-regeneration`
- `blocked`

## Blender MCP Automation

Claude must use Blender MCP to generate web-ready GLB assets.

Required actions:

- Generate models.
- Run Blender/MCP generation.
- Export GLB.
- Generate preview renders or turntables.
- Verify each asset exists.
- Verify scale and pivots.
- Verify moving parts.
- Fix broken exports.

Do not only write Blender prompts. Run the generation when Blender MCP is available.

## Higgsfield Automation

Use Higgsfield after Blender outputs are verified.

Use the latest Blender collector workflow.

Required actions:

- Collect Blender outputs.
- Use previews, renders, turntables, and camera paths as references.
- Generate cinematic loops and images for exact website scenes.
- Save media to the project.
- Convert to web-ready formats.
- Integrate into the website.

Do not generate random disconnected media.

## WebGL Integration

Integrate Blender and Higgsfield outputs into:

- Hero vessel scene.
- Ocean journey.
- Nets and catch scene.
- Onboard chilled storage.
- Port transfer.
- Processing facility.
- Pond/shrimp chapter.
- Product explorer.
- QC lab.
- Freezing/glazing.
- Cold storage.
- Reefer loading.
- Container vessel departure.
- Globe route map.

## Scroll Timeline Implementation

Use GSAP ScrollTrigger as the master timeline.

Connect scroll to:

- Camera path.
- Scene visibility.
- Vessel movement.
- Ocean shader uniforms.
- Compass HUD data.
- Net casting.
- Product/catch reveal.
- Container movement.
- Facility camera movement.
- QC document reveals.
- Frost/glaze particles.
- Cold storage door.
- Reefer seal.
- Globe route arcs.
- Text overlays.

## Automated QA

Run:

- TypeScript build.
- Lint if configured.
- Playwright screenshots.
- Canvas nonblank checks.
- Mobile viewport checks.
- RFQ form validation checks.

Required viewports:

- 1440x900.
- 1920x1080.
- 834x1194.
- 390x844.

Fix:

- Blank canvas.
- Broken GLB paths.
- Broken media paths.
- Unreadable text.
- Text overlap.
- Bad mobile layout.
- Stuttering scroll.
- Missing product details.
- Missing QC details.

