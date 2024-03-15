# Yagijiru

## Description

Cook them like locals [do](https://kyoudo-ryouri.com/en/food/2907.html)!

Using open LLMs to summarize metadata description to select a dataset to analyze. This app is currently dedicated to the ChIP-Atlas database.

## Installation

1. Clone the repository: `git clone https://github.com/inutano/yagijiru.git`
2. Install [Ollama](https://github.com/ollama/ollama) and run
3. Install [yllm](https://github.com/ekg/yllm)

## Usage

```
Usage:
    ./yj genome-assembly                                                 # Show available genome-assembly
    ./yj <genome-assembly> experiment-type                               # Show available experiment-type
    ./yj <genome-assembly> <experiment-type> cell-type                   # Show available cell-type
    ./yj <genome assembly> <experiment-type> <cell-type>                 # Show list of attribute names aggregated by LLM
    ./yj <genome assembly> <experiment-type> <cell-type> experiments     # Show the list of experiments for the given attribute set
    ./yj <genome assembly> <experiment-type> <cell-type> <experiment_id> # Perform curation of the given experiment

```
