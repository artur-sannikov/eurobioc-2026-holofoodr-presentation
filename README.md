# HoloFoodR: A Statistical Programming Framework For Holo-Omics Data Integration Workflows

This repository contains files to generate a presentation for the EuroBioC 2026
conference in Turku, Finland, which took place on June 3-5, 2026. The
presentation was created with the [slidev](https://sli.dev/) framework.

# How to Run?

The repository contains the flake.nix file, which can be used to install all
the required tools to build the presentation. If you have Nix and direnv
installed, just run `direnv allow` from the repository root, and it will
download the required tools.

Otherwise, install `pnpm` and `slidev-cli`.

After the tool installation, run `pnpm dev`, and the presentation should be
available at `http://localhost:3030`.

# Publication

The associated publication "HoloFoodR: a statistical programming framework for
holo-omics data integration workflows" is available in the [Bioinformatics
journal](https://doi.org/10.1093/bioinformatics/btaf605).

# Availability Online

The presentation is publicly available on [GitHub
pages](https://artur-sannikov.github.io/eurobioc-2026-holofoodr-presentation).
