# Leveraging Synthetic Data to Learn Video Stabilization Under Adverse Conditions


<img src='https://github.com/A-Kerim/Leveraging-Synthetic-Data-to-Learn-Video-Stabilization-Under-Adverse-Conditions/blob/3b137bb787e74e5a81e377918b96559e4a3c1130/imgs/introduction.png'>
Our key idea is to use specially-designed synthetic data to train an affine transformation
matrix estimation CNN.

## Abstract
Video stabilization plays a central role to improve videos quality. However, despite
the substantial progress made by these methods, they were, mainly, tested under
standard weather and lighting conditions, and may perform poorly under adverse
conditions. In this paper, we propose a synthetic-aware adverse weather robust
algorithm for video stabilization that does not require real data and can be
trained only on synthetic data. We also present Silver, a novel rendering engine
to generate the required training data with an automatic ground-truth extraction
procedure. Our approach uses the specially generated synthetic data for training an
affine transformation matrix estimator avoiding the feature extraction issues faced by
current methods. Additionally, since no video stabilization datasets under adverse
conditions are available, we propose the novel VSAC105Real dataset for evaluation.
We compare our method to five state-of-the-art video stabilization algorithms using
two benchmarks. Our results show that current approaches perform poorly in at least
one weather condition, and, even training in a small dataset with synthetic data only,
we achieve the best performance in terms of stability average score, distortion score,
success rate, and average cropping ratio when considering all weather conditions.
Hence, our video stabilization model generalizes well on real-world videos and does
not require large-scale synthetic training data to converge.


## Code, Datasets, and Simulator
* Our video stabilization code can be downloaded using this link: [Click](https://livelancsac-my.sharepoint.com/:u:/g/personal/kerim_lancaster_ac_uk/EX7jGWteToRJu2GP21bx3g8Bv-4fUp54VBv3HAm4Tyi_Xg?e=wvSxsh)
* The VSNC35Synth and VSAC65Synth datasets can be downloaded using these links: [Part1](https://drive.google.com/file/d/15IX81jZuYrswblobBxx9EF378BESngWb/view?usp=sharing) and [Part2] (https://drive.google.com/file/d/1FMpiJUABFNzMv_C3ef9pK31V-__OPlcx/view?usp=sharing)
* The Silver simulator can be downloaded using this link: [Click](https://livelancsac-my.sharepoint.com/:u:/g/personal/kerim_lancaster_ac_uk/ERMsh_Ba7TFPhCTXNejU4DABx0nXx4emT4fs_gKHl7zhkg?e=nNennA)

## Contact Authors
* Abdulrahman Kerim, PhD Student, at Lancaster University, a.kerim@lancaster.ac.uk
* Leandro Soriano Marcolino, Lecturer at Lancaster University, l.marcolino@lancaster.ac.uk

## Licence
* The dataset and the framework are made freely available to academic and non-commercial purposes. They are provided “AS IS” without any warranty.   
* If you use the dataset or the framework feel free to cite our work (paper link will be shared in the future).

## Acknowledgements
A. Kerim is supported by the Faculty of Science and Technology - Lancaster University.
