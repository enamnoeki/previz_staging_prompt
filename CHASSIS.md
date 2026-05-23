# CHASSIS.md

This file holds the **project-specific shared chassis** — the paste block that prefixes every brief in this project.

When you fork or clone this repo for a real project, **replace the contents of this file** with your project's actual chassis. The chassis below is a placeholder with guidance on what a chassis should contain.

---

## What is a chassis?

The chassis is a paragraph (or two) that establishes the framing every brief in the project shares. It tells the image AI — and any human reader — the constants of the project before any individual scene is described. It is project-level direction, not scene-level direction.

Every brief in this project begins with the chassis. Section 1 (SCENE PURPOSE) starts immediately after.

A good chassis locks in:

- **The role the AI should adopt.** ("Act as a cinematographer and visual layout artist working on…")
- **What kind of output is being generated.** (Tabletop maquette photography. Previz. Not finished illustration.)
- **The materials and physical conventions.** (Wooden puppets, cloth scraps, painted paper backdrops, practical lighting.)
- **The aesthetic constraints that apply to every scene.** (Puppet anatomy, face conventions, what the viewer should be able to tell about the image.)
- **What the chassis is *not* asking for.** (Not character illustration. Not photorealism. Not finished art.)

The chassis is the same in every brief. It does not change between scenes. If something changes between scenes, it belongs in the scene's individual sections, not the chassis.

## When to update the chassis

Rarely. The chassis is the project's spine. Changing it mid-project means every prior brief in the repo is now slightly out of sync with the current conventions. If you do change it, commit the change with a clear message and re-verify that existing briefs still produce consistent output.

If you find yourself wanting to change the chassis frequently, that's a signal that something scene-specific is wrongly living in the chassis. Pull it out into the brief sections.

## What about the generic default chassis?

The generic template (`TEMPLATE.md`) includes a generic fallback chassis for use when no project-specific chassis is supplied. That fallback is intentionally minimal — it just says "act as a cinematographer, generate previz staging." It is not a substitute for a real project chassis. For any real project, write a proper chassis here.

---

## PLACEHOLDER CHASSIS — REPLACE THIS BEFORE STARTING A PROJECT

Act as a cinematographer and visual layout artist working on **[PROJECT NAME]**, a **[PROJECT TYPE — e.g. tarot deck, comic series, poster set, animation pitch]** rooted in **[THEMATIC OR CULTURAL CONTEXT]**.

Generate staging, blocking, and composition ideas as cinematic previsualization — tabletop maquette photography using **[PRIMARY FIGURE MATERIAL — e.g. wooden artist's puppets, paper cutouts, clay figures]**, **[ENVIRONMENTAL MATERIALS — e.g. cloth scraps, painted paper backdrops, foamcore sets]**, and **[LIGHTING APPROACH — e.g. practical lamps with colored gels]**.

The goal is NOT finished illustration. The goal is NOT a character render. The goal is **[WHAT THE PREVIZ IS FOR — e.g. symbolic readability, ceremonial blocking, graphic composition hierarchy, theatrical staging]** captured as visibly handmade puppet photography on a small physical stage.

PREVIZ RENDER REQUIREMENT (applies to every brief):

The image should read as a photograph of a small tabletop set. **[DESCRIBE FIGURE CONVENTIONS — anatomy, joints, hands, heads, face treatment, paint markings, costume materials. Be specific about what counts as correct rendering and what does not. This is where you lock the puppet spec across the entire project.]**

Backdrops are **[BACKDROP CONVENTION]**. Props are **[PROP CONVENTION — visibly handmade from what materials]**. Lighting is **[LIGHTING CONVENTION]**. The viewer should be able to tell it is a maquette, not an illustration.

```
---------------------------------------------------------
SECTION 1 — SCENE PURPOSE
---------------------------------------------------------
What the image is saying. The emotional or storytelling
function the composition must perform.
Examples: tension before chaos, ceremonial invocation,
emotional isolation, surveillance, intimidation,
discovery, awe, grief held in stillness.


---------------------------------------------------------
SECTION 2 — ENVIRONMENT
---------------------------------------------------------
Backdrop, setting, atmosphere. Where the scene takes
place and what the air feels like.
Examples: ancestral shrine at dusk, flooded intersection,
rooftop under storm light, market stall at noon,
ceremonial clearing ringed by cloth.


---------------------------------------------------------
SECTION 3 — FLOORPLAN
---------------------------------------------------------
Top-down spatial truth of the tabletop set. Built before
the cast enters and before the camera is placed. Treat
this as the architectural plan of the stage — the camera
section later will say where you are standing on this
plan.

TOP-DOWN GRID:
ASCII diagram of the stage from directly above, drawn
from a standard front-reference orientation: the bottom
edge of the grid is the downstage edge of the table, the
top edge is upstage / the backdrop wall. This reference
view is fixed regardless of where the camera ends up.

Use these conventions:
  P1  = puppet one, P2 = puppet two, etc.
  >   = direction puppet is facing
  []  = prop or object footprint
  ~   = cloth, water, drape
  ##  = wall, backdrop, solid barrier
  *   = light source position
  .   = empty stage floor

Stage is roughly 24" wide x 18" deep unless noted.

Example:

  ## ## ## ## ## ## ## ## ##
  ## .  .  .  .  .  .  .  ##   (backdrop, upstage)
  ## .  .  [altar]  .  .  ##
  ## .  .  P1>     .  .  ##
  ## .  *  .  .  *  .  ##
  ## .  .  P2< .  .  .  ##
  ## .  .  .  .  .  .  ##
  -- -- -- -- -- -- -- --      (downstage edge)

ELEVATION (SIDE VIEW):
ASCII diagram from the side showing vertical staging.
Use these conventions:
  --- = tabletop surface
  |   = backdrop or vertical element
  o   = puppet head height
  X   = hanging element
  *   = light source

Example:

         *                X
         |                |
         |     o          |   (backdrop, 14" tall)
         |     |          |
         |     |   o      |
  ------ |-----|---|----- |

Note hanging elements, light positions, backdrop height,
and whether any element risks entering frame from above
once the camera is placed.

PROSE TRANSLATION:
One paragraph rewriting the floorplan in plain language
for the image AI. This is what flows into AI
VISUALIZATION GUIDANCE later — write it cleanly.
Example: "A small cardstock altar sits center-stage,
upstage-center, with puppet one standing just downstage
of it facing the audience. Puppet two kneels downstage-
left, body turned three-quarters toward puppet one.
Two practical lamps flank the stage at mid-height, one
camera-left with amber gel, one camera-right with blue
gel. A painted paper backdrop rises fourteen inches
behind the altar."


---------------------------------------------------------
SECTION 4 — ASSET DESCRIPTIONS
---------------------------------------------------------
Short visual descriptions of every puppet and object in
the scene. The chassis covers the generic puppet spec
(wooden lay-figure, articulated hands, sculpted head,
no painted features). This section adds what makes each
specific asset distinct in this scene: paint markings,
costume, scale, materials, condition, and symbolic role.

PUPPETS:
For each puppet, give a short paragraph covering:
- label (P1, P2, etc. — matches FLOORPLAN)
- scale / size relative to others
- paint markings on the bare wood (moon dots, sun
  motifs, ancestral lines, etc.)
- costume (cloth scraps, paper elements, color, condition)
- any held or worn props
- significance / who this puppet represents

Example:
P1 — Mawu figure. Six-inch lay-figure puppet. Bare wood
darkened with walnut stain. Seven small white moon dots
painted in an arc across the forehead. Wears a torn
indigo muslin wrap from shoulder to hip, raw edges
visible. Left hand holds a small clay-colored thimble
(offering bowl). No headpiece. Represents the lunar
half of the Mawu-Lisa pair; the cooler, receptive
principle.

P2 — Lisa figure. Six-inch lay-figure puppet, paired
scale with P1. Bare wood with a warmer ochre wash. A
single sun motif painted at the sternum — radiating
lines in burnt orange. Wears a yellow paper sash
crumpled at the waist. Empty hands, palms turned
upward. Represents the solar half; the active,
projective principle.

OBJECTS:
For each significant object, give a short paragraph
covering:
- label (matches FLOORPLAN if relevant)
- material and construction
- scale
- color / finish / condition
- placement role (does it frame, divide, anchor?)
- significance, if any

Example:
Altar — cardstock and balsa construction, roughly
three inches tall, four inches wide. Painted matte
black with chalked white symbols across the front
face. Centers the stage. Significance: the threshold
between the twin principles; offerings cross here.

Offering bowl — brass thimble, half an inch tall.
Sits dead-center on the altar. Catches a glint from
the camera-right key light. Significance: ancestral
exchange, the small thing that holds everything.

Cloth drape — torn muslin scrap, roughly twelve
inches long, indigo-dyed unevenly. Sweeps from upper-
left corner of frame down to behind the altar.
Significance: lineage, continuity, the thread between.

NOTES:
- Keep descriptions concrete. "Torn muslin scrap" not
  "fabric element." "Brass thimble" not "small vessel."
- If an asset reappears across multiple scenes in the
  series, lock its description once and reuse verbatim.
  Consistency across the series is the whole point.
- If an asset has no symbolic weight, omit the
  significance line.


---------------------------------------------------------
SECTION 5 — CHARACTER ACTION
---------------------------------------------------------
Simple verbs only. What each puppet is doing right now.
Examples: kneeling, pouring, reaching, turning away,
holding offering, standing in arrested motion.


---------------------------------------------------------
SECTION 6 — CHARACTER ORIENTATION
---------------------------------------------------------
Body and head angles relative to camera.

BODY DIRECTION:
Examples: front, back, profile, 3/4 front, 3/4 back,
torso twisted opposite hips.

HEAD DIRECTION:
Examples: toward camera, away, screen-left, downward
to focal object, tilted back.

POSE RELATIONSHIP TO CAMERA:
Examples: silhouette clearly readable, partially
obscured by foreground, foreshortened, overlapping
another figure, cropped by frame edge.


---------------------------------------------------------
SECTION 7 — CAMERA
---------------------------------------------------------
Single consolidated camera spec. The camera enters the
space defined by FLOORPLAN — describe its position
relative to that plan.

SHOT TYPE:
Examples: wide, medium, close-up, OTS, extreme wide,
two-shot, insert.

ANGLE:
Examples: eye level, low angle, high angle, bird's eye,
worm's eye, dutch tilt.

LENS FEEL:
Examples: wide-angle distortion, normal 50mm, long lens
compression, fisheye, anamorphic squeeze.

CAMERA POSITION IN SPACE:
Describe where the camera stands on the floorplan.
Examples: downstage-center at tabletop edge level,
downstage-right looking upstage-left, overhead rigged
two feet above set, ground level six inches from P1.

PERSPECTIVE GRID:
Examples: 1-point centered, 2-point with VPs far apart,
3-point with vertical distortion, isometric top-down,
curvilinear.

HORIZON LINE:
Examples: low horizon for scale, centered, high horizon
showing floor space, no horizon (interior).

VANISHING POINTS:
Examples: both VPs offscreen far apart (subtle),
close VPs (dramatic), single centered VP, extreme
3-point pulling skyward.


---------------------------------------------------------
SECTION 8 — FOCAL POINT
---------------------------------------------------------
Where the eye lands first. One thing.
Examples: glowing offering bowl, single lit candle,
puppet's outstretched hand, hanging mask, distant
figure in doorway.


---------------------------------------------------------
SECTION 9 — SPATIAL BLOCKING (CAMERA POV)
---------------------------------------------------------
Translate the floorplan into foreground / midground /
background as seen through the camera placed in
Section 7. This is NOT a restatement of the floorplan —
it's how the top-down map collapses into depth layers
from this specific viewpoint.

Examples: from the chosen camera, P1 reads lower-right
foreground, altar pushes to center-midground, P2 sits
upper-left midground partially behind altar, backdrop
deep background, hanging cloth upper-left foreground
framing the shot.


---------------------------------------------------------
SECTION 10 — OBJECT POSITIONING
---------------------------------------------------------
Specific placement of props and environmental elements
that aren't the primary subject, as they appear in
frame.
Examples: doorway frames puppet, hanging beads obscure
upper third, cloth drape sweeps from upper-left to
lower-right, offering bowl placed dead-center on altar.


---------------------------------------------------------
SECTION 11 — COMPOSITION NOTES
---------------------------------------------------------
Visual flow, balance, geometric structure.
Examples: strong diagonal from lower-left to upper-
right, triangular composition anchored on altar, heavy
negative space upper half, tunnel framing, repeating
vertical rhythm of poles, symmetrical mandala-style.


---------------------------------------------------------
SECTION 12 — LIGHTING
---------------------------------------------------------
Direction, intensity, mood. General lighting design
before specifying gel colors.
Examples: single key from camera-left at 45 degrees,
soft fill camera-right, hard rim from upstage, bounced
ambient only, harsh top-down, candle-level practical.


---------------------------------------------------------
SECTION 13 — COLORED GEL LIGHTING
---------------------------------------------------------
Specific gel choices on practical lamps.
Examples: CTO amber on key, CTB blue on backlight,
deep magenta on background wash, green on floor uplight,
no gel (white tungsten) on fill.


---------------------------------------------------------
SECTION 14 — MOOD / INFLUENCE
---------------------------------------------------------
Emotional register and cinematic touchstones.
Examples: ceremonial stillness, Nollywood political
drama, quiet suspense, editorial illustration clarity,
ritual gravity, Wong Kar-wai color saturation.


---------------------------------------------------------
SECTION 15 — READABILITY GOAL
---------------------------------------------------------
What the viewer should feel and register at a glance,
including silhouette test at thumbnail size.
Examples: at thumbnail size the viewer should
immediately read "two figures separated by an altar."
Silhouette must hold. Emotional register: grief held
in stillness, not melodrama.


---------------------------------------------------------
SECTION 16 — PHYSICAL STAGING APPROACH (MAQUETTE)
---------------------------------------------------------
How to physically build the scene as a real tabletop
diorama. Materials, construction, scale.
Examples: foamcore base eighteen inches deep, painted
paper backdrop rolled and clipped to standing dowels,
puppets at six-inch scale, altar built from cardstock
and balsa, offering bowl is a thimble, cloth drape is
torn muslin scrap, lamps are clip-on desk lights with
gel sheets taped to barn doors.


---------------------------------------------------------
SECTION 17 — LAYERED CUTOUT IDEAS
---------------------------------------------------------
How the scene breaks into depth planes. Useful for
both physical construction and for thinking about
foreground / midground / background separation.
Examples:
- Plane 1 (foreground): cut paper foliage, soft focus
- Plane 2: kneeling puppet
- Plane 3 (midground): altar with offering
- Plane 4: standing puppet
- Plane 5 (background): painted paper backdrop with
  distant trees


---------------------------------------------------------
SECTION 18 — ACRYLIC GRID SUGGESTION
---------------------------------------------------------
Compositional grid alignment. Rule of thirds, golden
ratio, dynamic symmetry, centered mandala, etc.
Specify where key elements land on the grid.
Examples: focal point on upper-right thirds
intersection, horizon on lower third, puppet heads
aligned to left and right thirds verticals, altar
centered for symmetry break.


---------------------------------------------------------
SECTION 19 — AI VISUALIZATION GUIDANCE
---------------------------------------------------------
A single dense paragraph describing the full scene for
the image AI prompt. This is the synthesis of
everything above, written as one flowing description.
Pull the PROSE TRANSLATION from FLOORPLAN forward and
expand it with the asset descriptions, action, camera,
lighting, gels, and mood. No bullet points. No section
labels. Just prose the model can read straight through.


---------------------------------------------------------
SECTION 20 — NEGATIVE PROMPTS
---------------------------------------------------------
What to avoid. Standing list plus scene-specific
additions.

STANDING AVOID LIST (every scene):
anime, manga character render, 3D character model,
smooth CGI skin, illustrated character, finished
illustration, mitten hands, fused fingers, blob hands,
painted anime face, photographic realism of human
skin, painted eyebrows, painted irises, painted lips,
smooth egg-shaped puppet head.

SCENE-SPECIFIC AVOIDS:
Examples: no modern objects, no visible studio
equipment in frame, no shadows falling outside the
stage area, no symmetry where asymmetry is required.


---------------------------------------------------------
SECTION 21 — FINAL ILLUSTRATION TARGET
---------------------------------------------------------
Note on what the downstream artist will do with this
previz. NOT to be rendered in the previz itself —
this is metadata for the next stage of the pipeline.
Examples: downstream artist will translate to ink-and-
gouache illustration in series house style, keeping
puppet blocking but rendering as human figures in
ceremonial dress. Backdrop will become full painted
scene. Gels translate to color palette, not literal
stage lighting.


---------------------------------------------------------
SECTION 22 — REFERENCE MATERIAL (OPTIONAL)
---------------------------------------------------------
Attached references guide environment accuracy,
spatial logic, lighting behavior, object placement,
camera feel, and compositional inspiration.

Do NOT closely replicate reference compositions or
rendering style. References are context, not targets.

Omit this section entirely when no references are
attached.
```
---

## Example: Children of Mawu-Lisa (filled-in chassis)

For reference, here is what a completed chassis looks like in a real project:

> Act as a cinematographer and visual layout artist working on a tarot deck called Children of Mawu-Lisa, rooted in Ewe cosmology. Generate staging, blocking, and composition ideas as cinematic previsualization — tabletop maquette photography using wooden artist's puppets, cloth scraps, paper cutouts, and practical set lighting. The goal is NOT finished illustration. The goal is NOT a character render. The goal is symbolic readability, ceremonial blocking, graphic composition hierarchy, and theatrical emotional staging captured as visibly handmade puppet photography on a small physical stage.
>
> PREVIZ RENDER REQUIREMENT (applies to every card): The image should read as a photograph of a small tabletop set. Puppets are posable wooden artist's dolls with visible ball joints at shoulders, elbows, hips, and knees, AND articulated wooden hand mannequins attached at the wrists with individual posable wooden fingers. Hands should read as separate jointed wooden pieces, not the mitten-shaped hands of standard artist's dolls. Puppet heads are sculpted wooden forms with defined jawlines and chins — closer to a lay figure or stop-motion armature head than the smooth egg-shaped head of a standard artist's doll. Heads have basic sculpted facial geometry — a defined jawline and chin, a nose ridge with visible nostrils suggested, and shallow indented eye sockets where the eyes would sit — but no painted features (no irises, no eyebrows, no lips). Any face markings called for in a specific card (moon dots, sun motifs, ancestral lines, pock-motifs) are painted directly onto the bare wooden surface over this sculpted geometry. Puppets are dressed in cloth scraps and paper costume elements. Backdrops are painted paper or fabric. Props are obviously handmade — cardboard, foil, dowel rods, found objects. Lighting is practical lamps with colored gels. The viewer should be able to tell it is a maquette, not an illustration.
