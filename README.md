# EEGCCT - Compact Convolutional Transformer for MI EEG-based BCIs
PyTorch implementation of "Compact Convolutional Transformer for Subject-Independent Motor Imagery EEG-based BCIs"

## Abstract
![image](https://github.com/user-attachments/assets/6afeffc4-459b-4551-ad33-e868a453ab25)
![image](https://github.com/user-attachments/assets/591da44d-0ce5-455a-ab83-81424d51dc05)
This paper introduces two versions of EEGCCT, an adaptation of the Compact Convolutional Transformer (CCT) model for EEG analysis in motor imagery tasks. The EEGCCT model distinguishes itself in several key aspects:
1. Hybrid Model Structure: EEGCCT combines the global, long-range perspective provided by Transformers with the local feature extraction capabilities of CNNs.
2. Subject Independence: EEGCCT emphasizes its ability to generalize across several subjects. This makes EEGCCT especially well-suited for a variety of BCI applications in which subject-specific training data may be scarce, particularly when assessed through the application of the LOSO approach.
3. Handling Limited Data: Enhancement in performance with a smaller parameter size is a major advantage of EEGCCT over models such as Conformer, Hybrid s-CViT, and Hybrid t-CViT.

## Requirements:
* Python 3.10
* Pytorch 1.12

## Datasets:
The datasets used during the current study are available in the BCI Competition IV repository. The specific datasets used are 2a[1] and 2b[2], which can be accessed at \url{https://www.bbci.de/competition/iv/}.

[1] Tangermann, M. et al. Review of the BCI competition IV. Front. Neurosci. 6, DOI: 10.3389/fnins.2012.00055 (2012).
[2] Leeb, R. et al. Brain–computer communication: Motivation, aim, and impact of exploring a virtual apartment. IEEE
Transactions on Neural Syst. Rehabil. Eng. 15, 473–482, DOI: 10.1109/TNSRE.2007.906956 (2007).

## Citation
If our code was helpful to your research, we kindly ask that you cite our paper:
```
Not published yet. In Peer Review.
```
