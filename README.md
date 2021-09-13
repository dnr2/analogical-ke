# Analogical Knowledge Extraction Data
This repository contains the subset of relations taken from [NextKB](https://www.qrg.northwestern.edu/nextkb/index.html) used in the evaluation of the paper "Combining Analogy with Language Models for Knowledge Extraction"

# Data Format (CycL)

The data is represented in CycL format. The  key  differences  between  CycL  representation  and  other  commonly  used  representations  are  (1)  CycL  represents  concepts  as  disambiguated  constants. For  example,  the concept "Mouse" can be  represented by either Mouse-RodentorComputerMouse,  depending on the word sense.  Concepts are represented by collections, e.g. ComputerMouse is a collection, while Mouse32 might denote an instance of that collection, a specific computer mouse; (2) relations can be of arbitrary arity, instead of only using binary relations, which allows relationships like between to be represented; (3) relations can be higher-order, e.g. (relationAllExists eatsWillingly Omnivore Meat) takes predicates and concepts (a.k.a. Collections in OpenCyc) as arguments; (4) logical functions can be used to produce new terms, e.g. (FruitFn AppleTree) represents the collection of the fruits of apple trees.

# How to Cite

```
@inproceedings{
    ribeiro2021combining,
    title={Combining Analogy with Language Models for Knowledge Extraction},
    author={Danilo Neves Ribeiro and Kenneth Forbus},
    booktitle={3rd Conference on Automated Knowledge Base Construction},
    year={2021},
    url={https://openreview.net/forum?id=4TpJpZ-_gyl}
}
```

# NextKB Attribution
This work includes data from NextKB, which was compiled by the Qualitative Reasoning Group at Northwestern University. NextKB is freely available under the Creative Commons Attribution 4.0 license from http://qrg.northwestern.edu/nextkb/index.html. The included data was created by contributors to the Qualitative Reasoning Group, contributors to Cycorp's OpenCyc, University of California at Berkeley's FrameNet project, the VerbNet project, and Princeton University's WordNet project. For details of attributions, please see http://www.qrg.northwestern.edu/nextkb/license.html

TODO: add section on how to cite AKBC 2021 paper