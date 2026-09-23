# Structural Biology Programme · CNIO

Software from the **Structural Biology Programme** at the Spanish National Cancer
Research Centre ([CNIO](https://www.cnio.es/en/research-innovation/scientific-programmes/structural-biology-programme/)),
Madrid.

We build and maintain the tools we use every day: cryo-EM data collection and
processing, protein design, biochemistry data analysis, and web apps that help
us run things in the labs. Everything public here is released for the community
to use and adapt.

---

## Protein design

**[BinderFlow](https://github.com/cryoEM-CNIO/BinderFlow)** — an automated,
modular pipeline for de novo protein binder design on SLURM clusters. Runs
backbone generation, filtering, sequence design and scoring in batches, with
**BFmonitor**, a web dashboard for live campaign monitoring and hit selection.
Built on RFdiffusion, dl_binder_design and PyRosetta.

## Cryo-EM processing

**[CNIO_Relion_Tools](https://github.com/cryoEM-CNIO/CNIO_Relion_Tools)** —
web-based dashboards for RELION 5: `relion_live.py` for real-time feedback
during data collection, `relion_analyse.py` for interactive analysis of project
metadata (2D/3D classification, refinement convergence, particle statistics),
plus ice-thickness estimation and parallelised PNG export.

**[RELION_ShiftParticles2D](https://github.com/cryoEM-CNIO/RELION_ShiftParticles2D)** —
RELION external job that re-centres particles after 2D classification using the
centre of mass of each class average or a user-provided shift.

## Biochemistry

**[CE_tools](https://github.com/cryoEM-CNIO/CE_tools)** — processing pipeline
for capillary electrophoresis data from primer-extension DNA assays: `.fsa`
extraction, normalisation, peak quantification, statistical reporting and an
interactive Dash dashboard.

## Programme infrastructure

**[SBP-APPS](https://github.com/cryoEM-CNIO/SBP-APPS)** — some of the
programme's web apps and dashboards people are developing to carry out their
everyday work, served at
[cryoem-cnio.github.io/SBP-APPS](https://cryoem-cnio.github.io/SBP-APPS/).

---

## How to cite

If our tools are useful in your work, please cite them:

**BinderFlow**
> González-Rodríguez N, Chacón-Sánchez C, Llorca O, Fernández-Leiro R.
> *Automated and modular protein binder design with BinderFlow.*
> PLOS Comput. Biol. **21**(11), e1013747 (2025).
> https://doi.org/10.1371/journal.pcbi.1013747

**relion_live.py / relion_analyse.py (CNIO_Relion_Tools)**
> González-Rodríguez N, Areán-Ulloa E, Fernández-Leiro R.
> *A web-based dashboard for RELION metadata visualization.*
> Acta Cryst. D **80**, 93–100 (2024). https://doi.org/10.1107/S2059798323010902

---

## Contributing

Issues and pull requests are welcome on any of the public repositories. If you
hit a problem or want a feature, open an issue, we read them 🙂

## Contact

Rafael Fernández-Leiro
[rfleiro@cnio.es](mailto:rfleiro@cnio.es) ·
[Genome Integrity and Structural Biology Group](https://www.cnio.es/en/research-innovation/scientific-programmes/structural-biology-programme/genome-integrity-and-structural-biology-group/) · CNIO
