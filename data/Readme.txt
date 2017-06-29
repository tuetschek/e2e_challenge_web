E2E NLG Dataset
===============

A new crowd-sourced data set of 50k instances in the restaurant domain. 
Each instance consist of a dialogue act-based meaning representation (MR) 
and several references in natural language. 

A detailed description is given on the challenge website:
    http://www.macs.hw.ac.uk/InteractionLab/E2E/

and in our SIGDIAL paper:
    https://arxiv.org/abs/1706.09254

1. File descriptions
--------------------

* trainset.csv - the training set (90%)
* devset.csv - the development set (10%)

MRs in the development set are distinct from the MRs in the training set.


2. Data fields
--------------

* `mr` - textual meaning representation
* `ref` - natural language utterance


3. Reference
------------

If you use this dataset in your work, please cite the corresponding paper:

@inproceedings{novikova2017e2e,
  title={The {E2E} Dataset: New Challenges for End-to-End Generation},
  author={Novikova, Jekaterina and Du{\v{s}}ek, Ondrej and Rieser, Verena},
  booktitle={Proceedings of the 18th Annual Meeting of the Special Interest Group on Discourse and Dialogue},
  address={Saarbr\"ucken, Germany},
  year={2017},
  note={arXiv:1706.09254},
  url={https://arxiv.org/abs/1706.09254},
}

