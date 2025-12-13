# FinFET_7nm-Circuit-Design-Characterization
This workshop builds professional FinFET skills on **ASAP7 (7 nm)** using **Xschem/Ngspice** and open repositories. You’ll characterise **NFET/PFET** (Id–Vd, gm, ro), size an inverter, extract **VTC/noise margins**, and automate measure scripts. Next, simulate a **Self-Cascode MOS bandgap**, reproducing **Vref, line/load regulation**, and **temperature drift** with instructor decks. Run deterministic PVT sweeps and produce benchmarked, publication-ready plots. Graduated with a **validated 7 nm workflow** and a portfolio ready for advanced-node.

# Workshop Overview
- FinFET Circuit Design and Characterisation is a hands-on workshop for advanced-node skills. Built directly on open repositories with the ASAP7 (7 nm) predictive platform, you will work in Xschem and Ngspice using BSIM-CMG device models. The curriculum follows an industry-aligned loop: design, simulate, verify, document — emphasising credible methods, reproducible datasets, and trusted figures that meet international expectations for research and product teams.

- You will begin at the device level with NFET and PFET characterisation, extracting complete I-V families, transconductance (gm), output resistance (ro), and practical bias points. You will then construct an inverter, generate and interpret its voltage transfer characteristic (VTC), and quantify switching points, noise margins, and static current. Each lab includes sensible sweep ranges, pre-checked netlists, and measurement recipes so you can focus on learning rather than tool friction. Results are archived for traceability. 

- The program then extends to a precision bandgap reference at 7 nm, guided by instructor-supplied schematics and netlists aligned with the repository’s figures. You will reproduce and analyze reference plots — temperature stability, line and load regulation, output resistance, and startup behaviour — while learning repeatable techniques for biasing and compensation. Automated supply and temperature sweeps, optional PVT corners, and Monte Carlo mismatch runs help you benchmark outcomes against published literature and communicate confidence in your results.

- Graduates leave with a coherent portfolio: annotated netlists, verified waveforms, tables, and engineering narratives that demonstrate readiness for advanced-node roles. We include templates, checklists, and scripts to accelerate future projects, plus guidance on documenting methods for submission or engineering reviews. Whether you are targeting graduate research, analog or ASIC design, or high-impact internships, this workshop equips you with practical 7 nm experience and evidence of competence that travels globally.

# Pre-requisites
- Basic Electronics & Logic – Ohm’s Law, RC time constants, transistor basics; Boolean algebra and simple gates.
- Math Readiness on Comfort with algebra, exponents, and plotting (no calculus required).
- Basic Linux shell, Git, and plain-text editing (VS Code/Vim).
- SPICE Exposure (Optional) Prior NGSpice/LTspice experience helps but is not required.

# List of All Open-Source Tools Used

| Name of Tool    | Application / Usage       |
| :------------------ | :-------------------------------- |
| Xschem + Ngspice + ASAP7 (7 nm) PDK   | Open-source schematic + SPICE flow with BSIM-CMG FinFET models for accurate device/circuit sims. |
| ASAP7 Model Decks (TT/FF/SS)           | Corner libraries, VDD/temperature parameters, and include files for deterministic sign-off.|
| Ngspice Built-in Plotter & CSV Export  | Instant waveform viewing plus data dumps for tables/plots without extra packages|
| VS Code / Vim Netlist Editing           | Syntax-highlighted templates and snippets to speed deck creation and revisions.|
| Bash/Make Automation                   | One-command runs for sweeps, reproducible logs, and clean artifact directories|
| Git + GitHub                          | Version control, issues, and a polished portfolio repo for career visibility.|


# Author:
Shyam Razesh

Acknowledgments
-----
 [Mr. Kunal Ghosh](https://www.linkedin.com/in/kunal-ghosh-vlsisystemdesign-com-28084836/ ) 

Reference
----
[FinFET Circuit Design & Characterization Program](https://www.vlsisystemdesign.com/7nm/)

https://github.com/kunalg123/vsdflow










































