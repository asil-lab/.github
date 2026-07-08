<div align="center">

# Autonomous Swarm Intelligence Lab

### Making swarms intelligent, autonomous, and safe.

We build open-source research software for autonomous multi-agent systems, swarm intelligence, distributed navigation, cooperative control, learning-based robotics, and safe multi-robot autonomy.

[![Research](https://img.shields.io/badge/research-swarm%20intelligence-1f6feb?style=for-the-badge)](#research-themes)
[![Robotics](https://img.shields.io/badge/robotics-multi--agent%20autonomy-238636?style=for-the-badge)](#featured-repositories)
[![Open Source](https://img.shields.io/badge/code-open%20source-f85149?style=for-the-badge)](#for-new-users)

</div>

---

## What We Study

The **Autonomous Swarm Intelligence Lab (ASIL)** develops algorithms, software, and experimental systems that help distributed sensing and robotic networks perceive, localize, decide, coordinate, and act in complex environments.

Our work sits at the intersection of signal processing, statistical machine learning, optimization, robotics, and distributed intelligence. We are especially interested in systems where autonomy emerges from many agents working together under uncertainty, limited communication, and real-world dynamics.

## Research Themes

| Theme | Focus |
| --- | --- |
| **Distributed autonomous sensing** | Building sensor and robot networks that infer, localize, and act without centralized supervision. |
| **Position, navigation, and timing** | Estimating position, time, and orientation for mobile multi-agent systems, including anchorless and GPS-denied settings. |
| **Probabilistic sensor fusion** | Combining heterogeneous, noisy, and partial measurements using Bayesian inference, Gaussian processes, and state-space models. |
| **Cooperative relative navigation** | Developing scalable algorithms for agents that localize themselves and one another through neighborhood information. |
| **Formation control and stability** | Designing resilient coordination laws for drone, rover, and robotic formations under uncertain conditions. |
| **Robust decision-making** | Turning uncertain sensor data into trustworthy perception, planning, and control for safety-critical autonomy. |
| **Space and field robotics** | Applying swarm autonomy to drones, rovers, satellites, lunar missions, and other inaccessible environments. |

## Featured Repositories

| Repository | Description |
| --- | --- |
| [`go2-autonomous-navigation`](https://github.com/asil-lab/go2-autonomous-navigation) | Autonomous navigation project using a Unitree Go2 robot for mapping lava tubes in the TU Delft Moonshot Rhizome 2.0 project. |
| [`EHJR_CPCCA`](https://github.com/asil-lab/EHJR_CPCCA) | Code for distributed navigation with dynamic obstacles. |
| [`EHJR-GPMPC-chance`](https://github.com/asil-lab/EHJR-GPMPC-chance) | Cooperative Gaussian process-based model predictive control for safe multi-agent navigation. |
| [`aeb_mm_rgp`](https://github.com/asil-lab/aeb_mm_rgp) | Code related to the MM-RGP paper. |
| [`zli-large-afc`](https://github.com/asil-lab/zli-large-afc) | Multicluster design and control of large-scale affine formations. |
| [`zli-sparse-urf`](https://github.com/asil-lab/zli-sparse-urf) | Simulation code for sparse universally rigid frameworks for multi-agent formation stabilization. |
| [`zli-garkf-afc`](https://github.com/asil-lab/zli-garkf-afc) | Adaptive edge tracking for resilient affine formation maneuver of multi-agent systems. |

## For New Users

Each repository contains project-specific installation, usage, and citation instructions. A typical workflow is:

```bash
git clone https://github.com/asil-lab/<repository-name>.git
cd <repository-name>
```

Then follow the instructions in that repository's `README.md`. Many projects include scripts, examples, or simulation setups that reproduce the corresponding research results.

## For Lab Members

When publishing a new public repository, please include:

- A clear `README.md` explaining the project goal, installation steps, and usage examples
- A license file when the code is intended to be publicly reusable
- A `CITATION.cff` file or citation section when the repository supports a publication
- Minimal reproducible examples, scripts, or simulation entry points when possible
- Notes about required datasets, trained models, hardware, simulators, and external dependencies

Please avoid committing large generated files, private datasets, credentials, API keys, tokens, or machine-specific configuration files.

## Citation

If you use code from one of our repositories, please cite the corresponding paper listed in that repository.

A typical citation section may look like:

```bibtex
@article{example2026,
  title   = {Paper Title},
  author  = {Author List},
  journal = {Journal or Conference Name},
  year    = {2026}
}
```

## Contact

For questions about a specific project, please open an issue in the relevant repository.

For general information about the lab, please refer to the organization profile and linked project repositories.

---

<div align="center">

Maintained by the **Autonomous Swarm Intelligence Lab**.

</div>
