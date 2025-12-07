---
type: assignment
date: 2025-11-01T00:00:00+3:30
title: 'HW1 #1 - Random Graphs and Network Models'
pdf: /static_files/assignments/SN_HW1.pdf
due_event: 
    type: due
    date: 2025-11-11T23:59:00+3:30
    description: 'Assignment 1 Due'
---

# Assignment 1: Random Graphs and Network Models

## Overview

This assignment explores fundamental concepts in network science, including small-world phenomena, scale-free networks, and phase transitions in random graphs. You will implement various network models and analyze their structural properties through both theoretical derivations and computational simulations.

---

## Submission Guidelines

### File Format
- Submit a **single ZIP file** named: `SN_HW1_[StudentNumber].zip`
- Contents must include:
  - **Report** in PDF format
  - **All code files** (Python/MATLAB/etc.)
- Upload to the **eLearn platform**

### Questions & Support
- Contact TAs via **email only** (avoid social media DMs)
- TAs: Faezeh Mozaffari, Farzad Jannati

### AI Tool Usage
- You **must document** any use of AI tools (ChatGPT, Copilot, etc.)
- Include in your report:
  - Which tools you used
  - How you used them
  - **Link to ChatGPT conversations** (if applicable)

### Late Policy
- **Up to 7 days late** accepted with **5% penalty per day**
- After 7 days: **No submissions accepted**

### Academic Integrity
- **Plagiarism = -0.25 grade** for ALL involved students
- **Random verification sessions** (5-10 minutes) will be conducted
- Discrepancies between report and presentation increase re-selection probability

---

## Grading Criteria

- **Theoretical Questions (30%)**
  - Mathematical rigor and clarity
  - Correct derivations with explanations
  
- **Implementation & Code (40%)**
  - Correct algorithm implementation
  - Code quality and documentation
  - Reproducibility
  
- **Analysis & Insights (30%)**
  - Quality of visualizations
  - Depth of analysis
  - Comparison with theory
  - AI tool documentation

---

## Required Libraries (Suggested)

```python
# Python
import networkx as nx
import numpy as np
import matplotlib.pyplot as plt
from scipy.optimize import curve_fit
from scipy.stats import linregress
```