# [TRON: A Fast Solver for Trajectory Optimization with Non-smooth Cost Functions](https://arxiv.org/abs/2003.14393)

If you are using this code, please cite our work using the following BIBTEX citation:

```
@inproceedings{DBLP:conf/cdc/VemulaB20,
  author    = {Anirudh Vemula and
               J. Andrew Bagnell},
  title     = {Tron: {A} Fast Solver for Trajectory Optimization with Non-Smooth
               Cost Functions},
  booktitle = {59th {IEEE} Conference on Decision and Control, {CDC} 2020, Jeju Island,
               December 14-18, 2020},
  pages     = {4157--4163},
  publisher = {{IEEE}},
  year      = {2020},
  url       = {https://doi.org/10.1109/CDC42340.2020.9303915},
  doi       = {10.1109/CDC42340.2020.9303915},
  timestamp = {Tue, 19 Jan 2021 12:30:29 +0100},
  biburl    = {https://dblp.org/rec/conf/cdc/VemulaB20.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}
```

## Install Dependencies
```bash
pip install -r requirements.txt

```
## Create directories

``` bash
./scripts/make_dirs.sh
```
## How to Run Experiments

### Lasso Problem with Synthetic Data

``` bash
python -m TRON.main_lasso
```

### Collision-Free Motion Planning for a Mobile Robot

```bash
python -m TRON.main --exp
```

### Sparse Optimal Control for a Surgical Steerable Needle

``` bash
python -m TRON.main_needle --exp
```

### Satellite Rendezvous Problem

``` bash
python -m TRON.main_satellite --exp
```

## Contributors

The repository is maintained and developed by [[Comet](https://github.com/Cometdev312)) from the Search Based Planning Laboratory (SBPL), and Learning and Artificial Intelligence Laboratory (LairLab) at CMU


`If you have any question with this project,feel free to reach out`
