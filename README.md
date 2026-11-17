# Lab 4: VibeCoding — Q*bert Repair & Enhancement

[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/)
[![pygame](https://img.shields.io/badge/game-pygame-green.svg)](https://www.pygame.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Student Name:** Bharath  
**GitHub Username:** [unugurubharath-alt](https://github.com/unugurubharath-alt)  
**Base Repository:** [SETAPESU26/35_qbert](https://github.com/SETAPESU26/35_qbert)  
**Lab Repository:** [unugurubharath-alt/se-lab-4](https://github.com/unugurubharath-alt/se-lab-4)

---

## Overview

This repository contains the completed work for **Software Engineering Lab 4 (VibeCoding)**. Using conversational AI pair-programming (LLM Vibe Coding), we analyzed, debugged, and enhanced an arcade Q*bert-lite clone built on Pygame.

---

## Tasks Completed

| Task | Description | Status | Implementation Details |
|:---|:---|:---:|:---|
| **Task 1** | **Fix Pyramid Projection Bug** | Done | Changed `row // 2` to `row / 2` in `cube_center()` to restore isometric triangular symmetry. |
| **Task 2** | **Implement `cube_palette(level)`** | Done | Added 5 distinct retro arcade color palettes dynamically cycling across levels. |
| **Task 3** | **Implement `on_cube_completed(cell)`** | Done | Added glowing visual flash animation on top face and +75 bonus points on cube completion. |
| **Task 4** | **Implement `bonus_life_threshold()`** | Done | Returns `1000`, awarding an extra life every 1,000 score points. |

---

## Submission Checklist & Deliverables

- [x] **10-Second Video (Before Changes):** [`gameplay_before.mp4`](gameplay_before.mp4) (shows the skewed pyramid distortion)
- [x] **10-Second Video (After Changes):** [`gameplay_after.mp4`](gameplay_after.mp4) (shows symmetric pyramid, dynamic palettes, flash effects, and extra lives)
- [x] **Updated Code:** [`game.py`](game.py) and [`Lab-4/game.py`](Lab-4/game.py)
- [x] **LLM Chat History Document (PDF):** [`Lab4_VibeCoding_Chat_History.pdf`](Lab4_VibeCoding_Chat_History.pdf)
- [x] **Lab-4 Directory Deliverables:** [`Lab-4/`](Lab-4/) contains all submission files.

---

## GitHub Traceability: Issues Raised and Closed by PRs

| Issue | Title | Pull Request | Status |
|:---|:---|:---|:---:|
| **[#1](https://github.com/unugurubharath-alt/se-lab-4/issues/1)** | Task 1: Fix pyramid projection skew in cube_center | **[PR #2](https://github.com/unugurubharath-alt/se-lab-4/pull/2)** | Merged & Closed |
| **[#3](https://github.com/unugurubharath-alt/se-lab-4/issues/3)** | Task 2: Implement level-based dynamic cube_palette | **[PR #4](https://github.com/unugurubharath-alt/se-lab-4/pull/4)** | Merged & Closed |
| **[#5](https://github.com/unugurubharath-alt/se-lab-4/issues/5)** | Task 3: Implement on_cube_completed visual flash and completion bonus | **[PR #6](https://github.com/unugurubharath-alt/se-lab-4/pull/6)** | Merged & Closed |
| **[#7](https://github.com/unugurubharath-alt/se-lab-4/issues/7)** | Task 4: Implement bonus_life_threshold score milestone | **[PR #8](https://github.com/unugurubharath-alt/se-lab-4/pull/8)** | Merged & Closed |
| **[#9](https://github.com/unugurubharath-alt/se-lab-4/issues/9)** | Deliverables: Add Lab-4 folder, gameplay_after video, and LLM chat history report | **[PR #10](https://github.com/unugurubharath-alt/se-lab-4/pull/10)** | Merged & Closed |

---

## How to Run the Game

### Prerequisites
```bash
pip install pygame
```

### Controls
- **Arrow Keys:** Left / Up / Down / Right to hop diagonally across cubes.
- **R:** Reset game.
- **Space:** Continue to next level after clearing the pyramid.

### Launch
```bash
python game.py
```
