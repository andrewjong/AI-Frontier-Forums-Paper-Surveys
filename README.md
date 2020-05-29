# Deep Learning Papers Survey
Personal repository to track my paper surveys.

Each paper summary is under Issues. Progress is managed on the Projects page.

## ■ Deep Learning Papers
### ◎ General Deep Learning
- Activation Functions
  - Swish [TO READ]

- Batch Size

- Learning Rate

### ◎ Vision
- Hand-Designed Architectures
  - Accuracy
    - ?
  - Mobile Efficiency
    - MobileNetV1: Depthwise Separable Convolutions
    - MobileNetV2: Inverted and Linear Residual Bottlenecks
    - Fully Learnable Group Convolution for Acceleration of Deep Neural Networks
    - GhostNet
    
  - Squeeze-and-Excitation Networks (seems to be commonly used in a lot of top architectures)

- Neural Architecture Search
  - MNasNet [TO WRITE]
  - Searching for MobileNetV3 [TO READ]
  - EfficientNets [TO WRITE] 
  - Designing Network Design Spaces [TO WRITE]
  - FBNet [TO WRITE]
  
- Data Augmentation
  - AutoAugment [TO READ]
  - Fast AutoAugment [TO READ]
  - AdvProp [TO READ]
  
- Camera Pipeline
  - Deep Demosaicing for Edge Implementation

### ◎ Generative Graphics
- Networks
  - DCGAN [TO WRITE]
  - StyleGAN [TO WRITE]
  - MSG-GAN [TO READ]
  - StyleGAN2 [TO READ]
- Layers
  - Spectral Normalization GAN (SN-GAN) [TO READ]
- Loss Functions
  - WGAN [TO WRITE]
  - WGAN-GP [TO WRITE]
  - Mescheder R1/R2 [TO WRITE]
  - Implicit Competitive Regularization [TO READ]
  
- Systems (fundamental systems that generalize widely)
  - Pix2Pix [TO WRITE]
  - CycleGAN [TO WRITE]
  - Guided Image-to-Image Translation with Bi-Directional Feature Transformation [TO READ]

- Applications
  - Virtual Try-on
    - FW-GAN [TO WRITE]

### ◎ Reinforcement Learning
- Algorithms
  - Q-Learning [TO FIND]
  - PPO [TO FIND]
  
  - World Models [TO READ]
  
- Navigation
  - https://paperswithcode.com/paper/vision-based-navigation-with-language-based [TO READ]

- Model Based

- Model Free
  
### ◎ Natural Language Processing
- Architectures
  - Attention is All You Need (Transformers) [TO READ]
  - BERT [TO READ]

## ■ Other Papers
Maybe I'll survey papers from other fields.

## ■ How to read and research papers on machine learning
 - Paper survey
     - The easiest way to find an advanced version of the paper is to find the cited paper on Google Scholer.
     -Basically, the ones with the highest number of citations are the ones of interest. However, the latest papers will of course have fewer citations.
     - Basically, the latest papers give better experimental results, so look for the latest published date on Google Scholar as much as possible.
     - If there is no official implementation of the paper, the cost of reproducing the original implementation is high, so we preferentially search for one with an official implementation.
     - Check PapersWithCode to see if the paper is officially implemented.

- How to read a dissertation
    - Basically, it is efficient to read "Abstract"-> "Introduction"-> "Conclusion"-> "Details of what you did"-> "Experiments"-> "Related Work". Related Work can be skipped at worst.
    - Notice the words "In this paper ..." and "In this work ..." in the Abstract and Introduction, and the words "the contributions of this paper ... as follows." At the end of the Introduction.
    - Unresolved issues and problems in the paper are often described in Future work and Conculution in the paper. Or, it is often mentioned in the Related Work of the paper citing the paper.

## ■ Template for Paper Survey
```
## 0. Article Information and Links

- Paper link: 
- Release date: YYYY/MM/DD
- Number of citations (as of 2020/MM/DD): 
- Implementation code: 
- Supplemental links (e.g. results): 
- Publication: Conference YYYY


## 1. What do the authors try to accomplish?

## 2. What's great compared to previous research?

## 3. Where are the key elements of the technology and method?

## 4. How did you verify that it works?

## 5. Things to discuss? (e.g. weaknesses, potential for future work, relation to other work)

## 6. Are there any papers to read next?

## 7. References

```

## ■ Reference site
### ◎ Paper site
arXiv
Google Scholer
### ◎ Convenient site
- papers with code
    - You can check if the paper is implemented.
- Hyper Collocation
- arXiv Vanity
### ◎ Other reference sites
- arXivTimes
- ymym3412/acl-papers
- shunk031/paper-survey
