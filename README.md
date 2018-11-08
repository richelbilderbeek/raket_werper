# raket_werper

Branch|[![Travis CI logo](pics/TravisCI.png)](https://travis-ci.org)
---|---
`master`|[![Build Status](https://travis-ci.org/richelbilderbeek/raket_werper.svg?branch=master)](https://travis-ci.org/richelbilderbeek/raket_werper)
`develop`|[![Build Status](https://travis-ci.org/richelbilderbeek/raket_werper.svg?branch=develop)](https://travis-ci.org/richelbilderbeek/raket_werper)

`raket` experiment scripts and storage.

Has the following folder structure:

 * `scripts`: contains the scripts

Should create the following folder structure:

 * `scripts`: contains the scripts
 * `data`: contains the simulation data
 * `results`: contains the simulation results

## Cluster usage

 * `sbatch ./scripts/install_raket`
 * `sbatch ./scripts/create_input_files_general`
 * `sbatch ./scripts/create_output_files`
 * `sbatch ./scripts/create_nltt_files`
 * `sbatch ./scripts/nltt_files_to_csv`
 * `sbatch ./scripts/to_long`
 * `sbatch ./scripts/rkt_plot`

## Local usage

 * `./scripts/install_raket`
 * `./scripts/create_input_files_general`
 * `./scripts/create_output_files`
 * `./scripts/create_nltt_files`
 * `./scripts/nltt_files_to_csv`
 * `./scripts/to_long`
 * `./scripts/rkt_plot`

See [.travis.yml](.travis.yml) for the complete usage.