# CNC Plasma Cutting — Student Curriculum

> CTE Metals & Fabrication | Mr. McAteer | Crescent Valley High School

A complete instructional curriculum for teaching the CNC plasma cutting workflow on an **Arclight Arc Pro** table with **Hypertherm Powermax 45**, **SheetCam**, and **CommandCNC**.

## Live Site

**[View the curriculum &rarr;](https://mr-mcateer.github.io/plasma-cnc-curriculum/)**

## Learning Path

The curriculum follows a 4-phase instructional design:

| Phase | Topic | Guide |
|-------|-------|-------|
| **1. Understand** | How CNC plasma cutting works | `guides/how-cnc-plasma-works.html` |
| **2. Design** | File workflow & export settings | `guides/plasma-workflow.html` |
| **2b. Design** | AI image to plasma cut pipeline | `guides/ai-to-plasma-guide.html` |
| **3. Prepare** | SheetCam CAM & CommandCNC operation | `guides/sheetcam-commandcnc-guide.html` |
| **4. Cut** | Safety, live cut, troubleshooting | Pages 3-4 of station guide |


## Equipment

- **CNC Table:** Arclight Arc Pro
- **Plasma Source:** Hypertherm Powermax 45 @ 45A
- **Consumables:** 45A Shielded (Duramax)
- **CAM Software:** SheetCam 6.1.38
- **Controller:** CommandCNC 2.7.8
- **Materials:** 12, 14, 16 GA mild steel

## Quick Reference — Kerf Values (45A Shielded, Mild Steel)

| Gauge | Thickness | Kerf Width | Feed Rate | Pierce Delay |
|-------|-----------|------------|-----------|--------------|
| 16 GA | 0.060" | 0.039" | 200 IPM | 0.4 sec |
| 14 GA | 0.075" | 0.043" | 160 IPM | 0.5 sec |
| 12 GA | 0.105" | 0.049" | 110 IPM | 0.8 sec |

*Source: Hypertherm Powermax45 Duramax cut charts (810050)*

## Repository Structure

```
plasma-cnc-curriculum/
  index.html                              # Landing page (learning hub)
  guides/
    how-cnc-plasma-works.html             # Phase 1: Science & machine anatomy
    plasma-workflow.html                  # Phase 2: Design-to-cut file pipeline
    ai-to-plasma-guide.html              # Phase 2b: AI image workflow
    sheetcam-commandcnc-guide.html       # Phase 3-4: CAM + machine operation
  tools/
    kerf-checker.html                     # DXF validation tool
    student-store.html                    # Pricing & project tracker
  assets/
    photos/                               # Equipment & process reference photos
```

## Deploying with GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings > Pages**
3. Set source to **Deploy from a branch**
4. Select **main** branch, **/ (root)** folder
5. Save — site will be live at `https://mr-mcateer.github.io/plasma-cnc-curriculum/`

## Printing

All guide pages are designed for **US Letter (8.5 x 11")** and include print CSS. Use your browser's Print function (Ctrl+P / Cmd+P) to generate clean PDFs or hard copies for the shop.

## License

Educational materials for Crescent Valley High School CTE program. Created by Mr. McAteer.
