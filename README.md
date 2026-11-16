# Incredulous

[![Twine](https://img.shields.io/badge/Engine-Twine_2.10.0-blue.svg)](https://twinery.org/)
[![Harlowe](https://img.shields.io/badge/Format-Harlowe_3.3.9-brightgreen.svg)](https://twine2.neocities.org/)
[![Platform](https://img.shields.io/badge/Platform-Web_Browser-orange.svg)]()
[![Genre](https://img.shields.io/badge/Genre-Murder_Mystery_Interactive_Fiction-purple.svg)]()

> A text-driven detective whodunit where sharp forensic reasoning and suspect interrogation determine whether a murderer faces justice.

---

## Overview

**Incredulous** is an interactive narrative murder mystery built in Twine (Harlowe 3.3.9). Players take on the role of **Detective Harold** from the local sheriff's department, summoned to investigate the untimely murder of the prominent aristocrat **Lord Gabriel** at his private estate.

The investigation leads players through forensic evidence, contradictory alibis, and layered interrogations with household staff and town figures. Every choice tests your deductive acumen: piece together the physical clues, interrogate suspects, catch them in lies, and extract a confession before the guilty party escapes culpability.

---

## Narrative Premise & Suspects

Lord Gabriel was discovered dead on his estate under suspicious circumstances. Arriving at the crime scene, Detective Harold uncovers critical physical clues—including garden soil near the corpse, suspicious footprints, and crushed grass clutched tightly in the victim's hand indicating a violent struggle.

### Key Characters & Persons of Interest

- **Detective Harold**: The lead investigator tasked with uncovering the truth and notifying the victim's grieving family.
- **The Cook**: Provided dinner for Lord Gabriel on the fateful night. Overheard heated discussions regarding Lord Gabriel's uncle and crippling financial debts.
- **The Plumber**: Dispatched to the mansion to resolve a water leak; observed suspicious mud tracks across the floor trailing from the garden.
- **The Gardener**: Claims to have retired early, but the presence of specialized soil and defensive grass marks in the victim's grasp contradicts his narrative.
- **The Uncle**: In debt and desperate for inheritance; has an undeniable financial motive.
- **The Mayor**: Local civic leader holding town authority, whose recent communications with the victim warrant close scrutiny.
- **Lady Gabriel & Family**: The victim's family, arriving at the airport to receive the shocking news.

---

## Gameplay Mechanics

- **Interactive Investigation**: Navigate rooms, crime scenes, the mayor's office, and police holding facilities.
- **Clue Cross-Examination**: Discover forensic evidence (soil types, debt records, witness timelines) and confront suspects when their testimonies clash with physical findings.
- **Intuition / Point Scoring (`$points`)**: Tracks the accuracy and rigor of your investigative decisions. Making correct deductions earns points, while reckless accusations diminish your case.
- **Branching Interrogations**: Choose your line of questioning carefully. Pushing too hard too early or failing to substantiate claims can cause suspects to stonewall.
- **Multiple Endings**: Secure a full confession with rock-solid evidence or risk letting the real culprit walk free.

---

## Controls & How to Play

- **Input**: Mouse click / touch on any highlighted interactive story link (`(link-goto:)`).
- **Restarting**: Refresh the browser page at any time to restart the investigation.

---

## Running the Game

No installations or local servers are required!

1. Clone or download this repository:
   ```bash
   git clone https://github.com/knandakumar25/Incredulous.git
   ```
2. Navigate into the directory and open `index.html` in any modern web browser (Google Chrome, Firefox, Microsoft Edge, Safari):
   ```bash
   # On Windows (PowerShell)
   Start-Process .\index.html
   ```

---

## Project Structure

```
Incredulous/
├── index.html           # Full compiled Twine Harlowe story, styles, and logic
├── congratulations.png  # Victory / resolution screen graphic
└── README.md            # Project documentation
```

---

## Technologies Used

- **Engine**: [Twine 2.10.0](https://twinery.org/)
- **Story Format**: Harlowe 3.3.9
- **Languages**: HTML5, CSS3, JavaScript, Harlowe Story Script
