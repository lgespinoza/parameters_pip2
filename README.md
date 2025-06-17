# PIP₂ Parameter Repository

This repository contains various parameter files for the PIP₂ (Phosphatidylinositol 4,5-bisphosphate) lipid, used in molecular dynamics simulations under different force fields and representations.

## Available Parameter Files

| System/Model          | File                                                   | Description |
|-----------------------|--------------------------------------------------------|-------------|
| CHARMM36 - Standard   | [SAPI25_c36.str](./SAPI25_c36.str)                     | Topology and charges for SAPI25 (PIP₂ with -4 charge) adapted for CHARMM36. |
| CHARMM General Force Field (CGenFF) | [pip2_cgenff.str](./pip2_cgenff.str)         | Parameter file for PIP₂ (named `ligandrm`) generated via CGenFF. |
| Martini CG (v2.0)     | [cg_martini_v2.0_PVP2_01.itp](./cg_martini_v2.0_PVP2_01.itp) | Coarse-grained model of PIP₂ (PVP2 variant) for use with Martini 2. |

