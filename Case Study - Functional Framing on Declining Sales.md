2026-07-23 15:06

Tags:

# Case Study: Functional Framing on Declining Sales

The single data point—**"Sales are declining by 15%"**—triggers completely different interpretations and interventions based on functional frames:

```mermaid
graph TD
    Root["Sales are down by 15%"] --> Finance
    Root --> Marketing
    Root --> Operations
    Root --> Strategy

    subgraph Finance ["Finance"]
        F_Diag["<b>Diagnosis:</b><br>Margin pressure"]
        F_Rem["<b>Remedy:</b><br>Cost-cutting"]
        F_Diag --- F_Rem
    end

    subgraph Marketing ["Marketing"]
        M_Diag["<b>Diagnosis:</b><br>Brand erosion"]
        M_Rem["<b>Remedy:</b><br>New ad campaign"]
        M_Diag --- M_Rem
    end

    subgraph Operations ["Operations"]
        O_Diag["<b>Diagnosis:</b><br>Poor product availability"]
        O_Rem["<b>Remedy:</b><br>Supply chain integration"]
        O_Diag --- O_Rem
    end

    subgraph Strategy ["Strategy"]
        S_Diag["<b>Diagnosis:</b><br>Changing industry structure"]
        S_Rem["<b>Remedy:</b><br>Business model transformation"]
        S_Diag --- S_Rem
    end
```
