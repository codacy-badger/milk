[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](http://www.gnu.org/licenses/gpl-3.0) [![Codacy Badge](https://api.codacy.com/project/badge/Grade/9a353bc4127449018e663280295d4016)](https://www.codacy.com/gh/milk-org/CommandLineInterface?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=milk-org/CommandLineInterface&amp;utm_campaign=Badge_Grade)

# Module milk-core  {#page_module_milk-core}

milk-core for **milk** package.


Module inclues key frameworks :

- **image streams** : low-latency shared memory streams
- **processinfo** : process management and control
- **function parameter structure (FPS)** : reading/writing function parameters

## Compilation

    ./compile.sh $PWD/local

## Adding plugins

Compile with cacao plugins:

    ./fetch_cacao_dev.sh
    ./compile.sh $PWD/local

Compile with coffee plugins:

    ./fetch_coffee_dev.sh
    ./compile.sh $PWD/local


