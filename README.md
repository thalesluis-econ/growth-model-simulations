# Classical Growth Model with Endogenous Saving Rates
This **Wolfram Mathematica notebook** explores the dynamics of a **Classical Growth Model** where saving rates are determined endogenously. Unlike the standard Solow model, this version incorporates a subsistence consumption constraint, leading to non-linear dynamics and the potential for multiple equilibria (poverty traps vs. steady-state growth).

## Theoretical Framework
The endogenous saving rate is based on the work of King and Rebelo , modeled through a Stone-Geary utility/consumption function. This setup assumes that agents must satisfy a minimum level of consumption before they can begin to save effectively.

### Key Parameters:
\[Alpha]:  Productivity of capital (output elasticity).
z:  Subsistence consumption level.
\[Psi]: Subsistence product (minimum required output).
\[Phi]: Propensity to consume above the subsistence threshold.
n: Population growth rate.
\[Delta]: Depreciation rate of capital.
---

## Notebook Contents
The notebook is organized into three interactive `Manipulate` sections to visualize the model's mechanics:

1. **Diagram**: A visual decomposition of the capital accumulation equation, showing the intersection of the saving function and the break-even investment line ($n + \delta$).
2. **Phase Portrait**: A dynamic view of the change in capital over time ($\dot{k}$), highlighting how the system evolves from different initial conditions.
3. **Vectors**: A 1D vector field representation showing the direction of flow along the capital axis, identifying the stable ($k^*$) and unstable ($k_{\psi}$) equilibria.
---

## ⚠️ Prerequisites & Setup
This notebook uses the MaTeX package by Szabolcs Horvát to render high-quality $\LaTeX$ labels within the plots.

1. **Install MaTeX**: You must have the package installed. You can find it at [github.com/szhorvat/MaTeX].
2. **Enable MaTeX**: Before running the `Manipulate` cells, you must initialize the package. An **"Enable MaTeX"** initialization cell is provided at the beginning of each section for convenience.
3. **Ghostscript**: MaTeX requires a working installation of Ghostscript on your system to function correctly.
