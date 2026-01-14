# VI-LINC
---
We provide our code to support the reproducibility of results
presented in the VI-Linc paper. However, we do not share models
or datasets. The sources of the datasets we used are referenced 
in the paper.

## Abstract / Overview
Imbalanced graph node classification is a highly relevant problem in various real-
world applications, including fraud detection in financial and trade networks
and spam filtering in product reviews. In these settings, detecting minority class
nodes is particularly challenging due to the inherent structural diversity of the
patterns and the limited availability of labeled training data. Conventional graph
learning methods are not explicitly designed for imbalanced settings and often
fail to generalize class-specific patterns from sparse and heterogeneous examples.
To address these challenges, we propose VI-LINC, a novel approach for visual
representation learning on graphs, tailored to imbalanced node classification. VI-
LINC introduces a structured visual representation of local graph neighborhoods
as a basis for forming class-specific pattern clusters in a visual embedding space,
improving class-discriminative pattern extraction and generalization. Extensive
experiments on three datasets, including real-world and synthetic data, demon-
strate that VI-LINC consistently outperforms state-of-the-art baselines, with
macro-average F1 gains of between 1.14% and 43.34%. VI-LINC is especially
effective in more complex neighborhoods, achieving macro-average F1 gains of
15.09%-184.69% for nodes with three or more 1-hop neighbors across real-world
datasets.


## Directory Structure
├── Vi_Linc_main.py
├── requirements.txt 
└── README.md
