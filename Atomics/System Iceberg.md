2026-07-31 12:25

Tags:

# System Iceberg

The **Systems Iceberg Model** (also termed the _Systems Pyramid_) is a foundational conceptual framework in system dynamics, conceived at MIT’s Sloan School of Management and popularized by Michael Goodman, Daniel Kim, and Peter Senge.

It uses a visual metaphor to demonstrate that the vast majority of systemic complexity and root causes (~90%) lie invisible beneath the surface level of daily events.

```mermaid

graph TD
    subgraph Visible ["SURFACE WATERLINE (Visible ~10%)"]
        L1["<b>LEVEL 1: EVENTS</b><br><i>'What just happened?'</i><br>Discrete incidents, outcomes, &amp; snapshots (Firefighting / Reactive posture)"]
    end

    subgraph Invisible ["SUB-SURFACE MASS (Invisible ~90%)"]
        L2["<b>LEVEL 2: PATTERNS OF BEHAVIOR</b><br><i>'What has been happening over time?'</i><br>Longitudinal trends, trajectories, velocity, &amp; recurring cycles (Responsive posture)"]
        L3["<b>LEVEL 3: SYSTEMIC STRUCTURES</b><br><i>'What forces/loops create these patterns?'</i><br>Rules, incentives, feedback loops, stocks/flows, &amp; info architectures (Redesign posture)"]
        L4["<b>LEVEL 4: MENTAL MODELS</b><br><i>'What worldviews/beliefs sustain these structures?'</i><br>Deeply held assumptions, tacit frames, &amp; organizational paradigms (Transformative posture)"]
    end

    L1 --> L2
    L2 --> L3
    L3 --> L4
    
    

```
