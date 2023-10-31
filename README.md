# Leveraging Synthetic Data to Learn Video Stabilization Under Adverse Conditions


<img src='https://github.com/A-Kerim/Leveraging-Synthetic-Data-to-Learn-Video-Stabilization-Under-Adverse-Conditions/blob/3b137bb787e74e5a81e377918b96559e4a3c1130/imgs/introduction.png'>
Our key idea is to use specially-designed synthetic data to train an affine transformation
matrix estimation CNN.

## Abstract
Stabilization plays a central role in improving the quality of videos. However, current methods perform poorly under adverse conditions. In this paper, we propose a synthetic-aware adverse weather video stabilization algorithm that dispenses real data for training, relying solely on synthetic data. Our approach leverages specially generated synthetic data to avoid the feature extraction issues faced by current methods. To achieve this, we present a novel data generator to produce the required training data with an automatic ground-truth extraction procedure. We also propose a new dataset, VSAC105Real, and compare our method to five recent video stabilization algorithms using two benchmarks. Our method generalizes well on real-world videos across all weather conditions and does not require large-scale synthetic training data. 


## Code, Datasets, and Simulator
* Our video stabilization code can be downloaded using this link: [Click](https://livelancsac-my.sharepoint.com/:u:/g/personal/kerim_lancaster_ac_uk/EZv0pwUMO0tMnrhSdei63E0BfxG3rApSkRxL29KGkkXxRA?e=7qCYqi)
* The VSNC35Synth and VSAC65Synth datasets can be downloaded using these links: [Part1](https://drive.google.com/file/d/15IX81jZuYrswblobBxx9EF378BESngWb/view?usp=sharing) and [Part2](https://drive.google.com/file/d/1FMpiJUABFNzMv_C3ef9pK31V-__OPlcx/view?usp=sharing)
* The Silver simulator can be downloaded using this link: [Click](https://livelancsac-my.sharepoint.com/:u:/g/personal/kerim_lancaster_ac_uk/EXmc7xfRKzVJj5Ix8P2AmZQB5KE4QcomfryRqGdlSfQxuw)

## Contact Authors
* Abdulrahman Kerim, PhD Student, at Lancaster University, a.kerim@lancaster.ac.uk
* Leandro Soriano Marcolino, Lecturer at Lancaster University, l.marcolino@lancaster.ac.uk

## Licence
* The dataset and the framework are made freely available to academic and non-commercial purposes. They are provided “AS IS” without any warranty.   
* If you use the dataset or the framework feel free to cite our work (paper link will be shared in the future).

## Acknowledgements
A. Kerim is supported by the Faculty of Science and Technology - Lancaster University.
