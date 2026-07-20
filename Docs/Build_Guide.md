# BarrelSat One – Build Guide

**Last Updated:** July 2026  
**Status:** First complete draft – ready for test printing and refinement

This guide walks you through printing, preparing, and assembling one complete BarrelSat One unit. It assumes you are using the STLs and 3MF plates in this repository and Orca Slicer (or equivalent).

---

## 1. Required Materials

Refer to the full [Hardware & Materials List](Hardware_Materials.md) for links, quantities, and notes.

**Key categories:**
- Filaments (Concrete Gray matte PETG, Translucent PETG, Matte Navy PETG, Black TPU 95A)
- Drivers (2× Dayton PC83-4, 1× Dayton ND25FA-4)
- Electronics (Satellite1.1 Dev Kit, crossover, LD2450 + antenna)
- Magnets, screws, steel shot, epoxy, polyfill, adhesive, speaker fabric
- Tools (precision screwdriver, crimping kit, rotary tool optional)

---

## 2. Print Order & Recommended Settings

Print in this approximate order so you can test-fit as you go:

1. **TPU Gaskets** (all of them) – quick and useful for fit checks  
2. **Trim Rings** (Upper, Lower, Front Speaker, Rear Speaker)  
3. **Bottom Module** (Weight_Cylinder + Weight_Cylinder_Lid)  
4. **Top Module** (Tweeter_Deck, Top_Panel, Diffuser)  
5. **Barrel_Main** (the large one-piece barrel)

### Suggested Starting Settings (PETG)
- Layer height: 0.2 mm (0.16–0.2 mm for visible surfaces)
- Wall loops: 3–4
- Infill: 15–25% (gyroid or cubic)
- Supports: Tree or organic where needed (especially barrel interior features and overhangs)
- Bed adhesion: Brim or raft for the large barrel
- Fuzzy Skin: Optional – test on a small sample first (still an open decision)

### TPU Settings
- Print slow (20–40 mm/s)
- Retraction tuned for your setup
- No supports usually needed for the flat gaskets

Use the provided `BarrelSat_One-Printables.3mf` as a starting point and adjust for your printer.

---

## 3. Post-Processing

- Remove supports carefully (especially inside the barrel and around speaker mounts).
- Lightly sand any visible layer lines on exterior surfaces if desired (matte filament hides a lot).
- Test-fit all magnets into their pockets – they should be snug. Secure with a drop of CA or Gorilla Clear if needed.
- Dry-fit all TPU gaskets.
- Clean the cable block openings so the extension cables seat cleanly.

---

## 4. Weight Compartment Assembly (Bottom Module)

1. Print and clean the Weight_Cylinder and Lid.
2. Mix steel shot with 2-part epoxy until fully coated.
3. Pour into the cylinder. Target ~250–450 g total mass depending on final feel (start lower and add if desired).
4. Allow full cure (24–72 hours).
5. Install the lid (pegs + optional glue or screws).
6. Install magnets into the lid / cylinder wall pockets and secure.
7. Attach the TPU sealing ring (Gasket_Lower_Module) into its groove.

---

## 5. Top Module Assembly

1. Mount the Dayton ND25FA-4 tweeter to the Tweeter_Deck with the TPU tweeter gasket.
2. Route the flat USB-C and 3.5 mm extension cables through the slim channels in the spacer / deck.
3. Install the Satellite1 board + HAT onto the top side of the deck / Top_Panel (use the designed standoffs / screw holes).
4. Install the Diffuser ring (clear/translucent PETG) so LEDs glow cleanly through it.
5. Install magnets into the Top Module side walls / pockets.
6. Attach Gasket_Upper_Module.
7. Verify button feel and that the 1 mm shadow gap will be present when installed on the barrel.

---

## 6. Barrel Preparation

1. Install Front and Rear speaker trim rings (glue recommended – permanent decorative attachment).
2. Install Upper and Lower trim rings (glue).
3. Mount the two Dayton PC83-4 woofers from the inside using the designed bosses / tubes and self-tapping screws + lock nuts if using.
4. Place speaker gaskets (Front & Rear) between driver and wall.
5. Optionally cover the speaker openings with acoustic fabric (black / gray / vintage tone) using flexible adhesive (Gorilla Clear or E6000 style).
6. Install any internal cable guides or just route the extension cables cleanly down to the cable block.
7. Lightly stuff polyfill in the chamber for damping (do not overstuff – preserve volume).

---

## 7. Final Assembly

1. Slide the Bottom Module up into the barrel until the TPU ring seats and the magnets click.
2. Connect all wiring (crossover, presence sensor, speakers, extensions to Sat1 board).
3. Lower the Top Module into place until magnets engage and the 1 mm shadow gap is even.
4. Verify all functions: power, audio via Music Assistant, presence detection, buttons, LED glow through diffuser.
5. Place on a soft surface or add foam feet if desired.

---

## 8. Acoustic & Fit Notes

- Opposing woofers + upward tweeter + ~3 L target volume is the acoustic foundation.
- Polyfill improves midrange control and reduces internal reflections.
- Magnetic + TPU sealing keeps the chamber as airtight as practical while remaining fully serviceable.
- If any fit is tight, lightly sand the mating surfaces or check magnet polarity.

---

## 9. Optional Finishing Touches

- Fuzzy Skin sample test on a scrap before committing to the full barrel.
- Light clear coat or matte varnish only if desired (test first – matte PETG already looks premium).
- Custom fabric colors for different units (black, medium gray, warm vintage).
- Serial number or small engraved mark inside the bottom lid if building multiple units.

---

## 10. Troubleshooting & Iteration

- Document any dimensional deviations after first prints.
- Update this guide and the Remaining Tasks list with real-world notes.
- Real acoustic testing (frequency response, bass extension, listening comparisons to Echo 4th Gen) is the final validation step.

---

**Built with FreeCAD + Orca Slicer on Linux.**  
**Designed in collaboration with Grok (xAI).**

Happy building — take your time and enjoy the process.
