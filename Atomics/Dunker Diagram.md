2026-07-28 14:01

Tags:

# Dunker Diagram

- **Origin & Concept:** Proposed by cognitive psychologist Karl Dunker. Uses **functional analysis** to map a problem as a hierarchical tree, moving from a general functional goal down through distinct solution directions to concrete leaf nodes.
    
- **Core Function:** Directly combats **functional fixedness** (the tendency to view objects, departments, or processes as having only one fixed function) and prevents premature convergence on a single remedy.

```mermaid
graph TD
    Root["<b>Root Goal:</b><br>Reduce Patient Waiting Times"] --> B1["<b>Branch 1:</b><br>Increase Capacity"]
    Root --> B2["<b>Branch 2:</b><br>Improve Scheduling"]
    Root --> B3["<b>Branch 3:</b><br>Reduce Unnecessary Visits<br><i>(Counter-intuitive)</i>"]

    B1 --> L1["• Hire more doctors/nurses<br>• Extend operating hours<br>• Add consultation rooms"]
    B2 --> L2["• AI appointment allocation<br>• Pre-consultation triage<br>• Staggered intake"]
    B3 --> L3["• Tele-health / Digital consults<br>• Self-assessment apps<br>• Trained pharmacy clinics"]
```