
Slurm Meadow for eHive
======================

> [!IMPORTANT]  
> As per eHive version 2.7.0, all the meadows other than `SLURM` and `Local` are deprecated and not supported anymore.
> `SLURM` is natively supported by eHive, and this fork is not needed or supported any longer.
> 
> This repository is going to be archived soon ~1Q2025.
>
> Please, do not hesitate to contact us, should this be a problem.

[eHive](https://github.com/Ensembl/ensembl-hive) is a system for running computation pipelines on distributed computing resources - clusters, farms or grids.

This repository is the implementation of eHive's _Meadow_ interface for the SLURM job scheduler.

:warning: This repository is a fork of [tweep/ensembl-hive-slurm](https://github.com/tweep/ensembl-hive-slurm), and host changes required for a test.
Commits will eventually be fed back to the original repository.

Version numbering and compatibility
-----------------------------------

All tags and branches (except _main_) have been stripped off, to
emphasize that this is a development project.
