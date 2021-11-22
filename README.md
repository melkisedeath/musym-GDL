# musym-GDL
Geometric Deep Learning Applied on Symbolic Music Scores

Overview
--------

Cadence and Voice Leading Detection in Symbolic Classical Music is a challenging task. This Repository provides method for Geometrical Deep Learning models and score graph modelling paradigms for applying Node Classification on Musical Score graphs for Cadence Detection.



#### A typical Heterogenous graph modelling of the musical score

<img src="static/graph_representation.png" alt="score2graph_representation" style="zoom:50%;" />

<img src="static\node_attributes.png" alt="node_attributes" style="zoom:50%;" />



## Dependencies

- pytorch  1+

- dgl v0.6

- pandas

  

### Quickstart

Install requirements with pip: 

```shell
pip install -r requirements.txt
```

#### Quickstart with Conda

```shell
conda env create -f environment.yml
```
Followed by
```shell
conda activate musym
```

### Run a experiment

```shell
cd musym/models/rgcn_homo
python entity_classify.py -d cora --gpu 0
```

