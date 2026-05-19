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

---

## Example: Children of Mawu-Lisa (filled-in chassis)

For reference, here is what a completed chassis looks like in a real project:

> Act as a cinematographer and visual layout artist working on a tarot deck called Children of Mawu-Lisa, rooted in Ewe cosmology. Generate staging, blocking, and composition ideas as cinematic previsualization — tabletop maquette photography using wooden artist's puppets, cloth scraps, paper cutouts, and practical set lighting. The goal is NOT finished illustration. The goal is NOT a character render. The goal is symbolic readability, ceremonial blocking, graphic composition hierarchy, and theatrical emotional staging captured as visibly handmade puppet photography on a small physical stage.
>
> PREVIZ RENDER REQUIREMENT (applies to every card): The image should read as a photograph of a small tabletop set. Puppets are posable wooden artist's dolls with visible ball joints at shoulders, elbows, hips, and knees, AND articulated wooden hand mannequins attached at the wrists with individual posable wooden fingers. Hands should read as separate jointed wooden pieces, not the mitten-shaped hands of standard artist's dolls. Puppet heads are sculpted wooden forms with defined jawlines and chins — closer to a lay figure or stop-motion armature head than the smooth egg-shaped head of a standard artist's doll. Heads have basic sculpted facial geometry — a defined jawline and chin, a nose ridge with visible nostrils suggested, and shallow indented eye sockets where the eyes would sit — but no painted features (no irises, no eyebrows, no lips). Any face markings called for in a specific card (moon dots, sun motifs, ancestral lines, pock-motifs) are painted directly onto the bare wooden surface over this sculpted geometry. Puppets are dressed in cloth scraps and paper costume elements. Backdrops are painted paper or fabric. Props are obviously handmade — cardboard, foil, dowel rods, found objects. Lighting is practical lamps with colored gels. The viewer should be able to tell it is a maquette, not an illustration.
