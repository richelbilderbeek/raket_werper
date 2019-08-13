# raket_werper

Branch|[![Travis CI logo](pics/TravisCI.png)](https://travis-ci.org)
---|---
`master`|[![Build Status](https://travis-ci.org/richelbilderbeek/raket_werper.svg?branch=master)](https://travis-ci.org/richelbilderbeek/raket_werper)
`develop`|[![Build Status](https://travis-ci.org/richelbilderbeek/raket_werper.svg?branch=develop)](https://travis-ci.org/richelbilderbeek/raket_werper)

`raket_werper` (EN: 'rocket launcher') contains 
the `raket` (EN: 'rocket') experiment scripts 
and stores the results.

Has the following folder structure:

 * `scripts`: contains the scripts
 * `data`: contains the simulation data (to be created)
 * `results`: contains the simulation results (to be created)

## Data

 * [20190811](http://richelbilderbeek.nl/raket_werper_20190811.zip)
   minimal runs, most fail
 * [20190812](http://richelbilderbeek.nl/raket_werper_20190812.zip)
   minimal runs, most fail

## Cluster usage

 * `sbatch ./scripts/1_install_raket`
 * `sbatch ./scripts/2_create_input_files_general`
 * `sbatch ./scripts/3_create_posterior_files`
 * `sbatch ./scripts/4_create_nltt_files`
 * `sbatch ./scripts/5_nltt_files_to_csv`
 * `sbatch ./scripts/6_to_long`
 * `sbatch ./scripts/7_create_fig_1`

## Local usage

 * `./scripts/1_install_raket`
 * `./scripts/2_create_input_files_general`
 * `./scripts/3_create_posterior_files`
 * `./scripts/4_create_nltt_files`
 * `./scripts/5_nltt_files_to_csv`
 * `./scripts/6_to_long`
 * `./scripts/7_create_fig_1`

See [.travis.yml](.travis.yml) for the complete usage.