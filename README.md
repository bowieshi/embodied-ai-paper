# Embodied AI Paper Reading

My research interests lie in Embodied AI and Robotics. Currently I focus on Human motion generation, especially on Human scene interaction. This list will mostly contain papers related to these fields.

## (1) Pre-reading

Wonderful articles for understanding the basics of generative models (especially for green hand):

1. [Understanding Variational Autoencoders (VAEs)](https://towardsdatascience.com/understanding-variational-autoencoders-vaes-f70510919f73)

2. [Bayesian inference problem, MCMC and variational inference](https://towardsdatascience.com/bayesian-inference-problem-mcmc-and-variational-inference-25a8aa9bce29)

3. [An In-Depth Guide to Denoising Diffusion Probabilistic Models DDPM – Theory to Implementation](https://learnopencv.com/denoising-diffusion-probabilistic-models/)

4. [Understanding the Variational Lower Bound](https://xyang35.github.io/2017/04/14/variational-lower-bound/)

## (2) Fundamental Models

### Generative Models

1. [Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2006.11239)

2. [Hierarchical Text-Conditional Image Generation with CLIP Latents](https://arxiv.org/abs/2204.06125)

3. [GLIDE: Towards Photorealistic Image Generation and Editing with Text-Guided Diffusion Models](https://arxiv.org/abs/2112.10741)

4. [Diffusion Models Beat GANs on Image Synthesis](https://arxiv.org/abs/2105.05233)

5. [Learning Structured Output Representation using Deep Conditional Generative Models](https://papers.nips.cc/paper_files/paper/2015/file/8d55a249e6baa5c06772297520da2051-Paper.pdf)

## (3) Survey

1. [Human Motion Generation: A Survey](https://arxiv.org/abs/2307.10894)

## (4) Human Model

### SMPL

1. [[SIGGRAPH Aisa 2015] SMPL: A Skinned Multi-Person Linear Model](https://smpl.is.tue.mpg.de)
2. [[CVPR 2019] SMPLX: Expressive Body Capture: 3D Hands, Face, and Body from a Single Image](https://smpl-x.is.tue.mpg.de)
3. [[ECCV 2016] Smplify: Keep it SMPL: Automatic Estimation of 3D Human Pose and Shape from a Single Image](https://smplify.is.tue.mpg.de)

## (5) Human Motion Generation

### Human Motion Dataset

1. [HumanML3D: A large and diverse 3d human motion-language dataset](https://github.com/EricGuo5513/HumanML3D)
2. [AMASS: Archive of Motion Capture As Surface Shapes](https://amass.is.tue.mpg.de)
4. [Motion-X: A Large-scale 3D Expressive  Whole-body Human Motion Dataset](https://motion-x-dataset.github.io)

### Condition on Text/Action/Trajectory

1. [[ICLR 2023] Human Motion Diffusion Model](https://arxiv.org/abs/2209.14916)
2. [Generating Diverse and Natural 3D Human Motions from Text](https://ericguo5513.github.io/text-to-motion/)
3. [[ICLR 2024] OmniControl: Control Any Joint at Any Time for Human Motion Generation](https://arxiv.org/abs/2310.08580)
4. [[ECCV 2024] TLcontrol: Trajectory and Language Control for Human Motion Synthesis](https://tlcontrol.weilinwl.com)
5. [[CVPR 2022] The Wanderings of Odysseus in 3D Scenes](https://yz-cnsdqz.github.io/eigenmotion/GAMMA/)

## (6) Interaction

### Physical-based Interaction

1. [UniHSI: Unified Human-Scene Interaction via Prompted Chain-of-Contacts](https://xizaoqu.github.io/unihsi/)
2. [PhysHOI: Physics-Based Imitation of Dynamic Human-Object Interaction](https://wyhuai.github.io/physhoi-page/)

### Human Object Interaction

1. [[CVPR 2022] BEHAVE: Dataset and Method for Tracking Human Object Interactions](https://virtualhumans.mpi-inf.mpg.de/behave/)
2. [Full-Body Articulated Human-Object Interaction](https://github.com/jnnan/chairs)
3. [CG-HOI: Contact-Guided 3D Human-Object Interaction Generation](https://www.christian-diller.de/projects/cg-hoi/)
4. [HOI-Diff: Text-Driven Synthesis of 3D Human-Object Interactions using Diffusion Models](https://neu-vi.github.io/HOI-Diff/)
5. [Controllable Human-Object  Interaction Synthesis](https://lijiaman.github.io/projects/chois/)
6. [Object Motion Guided Human Motion Synthesis](https://lijiaman.github.io/projects/omomo/)

### Human Scene Interaction

1. [[ICCV 2021] SAMP: Stochastic Scene-Aware Motion Prediction](https://samp.is.tue.mpg.de)

2. [[ECCV 2022] COINS: Compositional Human-Scene Interaction Synthesis with Semantic Control](https://zkf1997.github.io/COINS/index.html)

3. [[ICCV 2023] DIMOS: Synthesizing Diverse Human Motions in 3D Indoor Scenes](https://zkf1997.github.io/DIMOS/)

4. [[CVPR 2024 spotlight] Scaling Up Dynamic Human-Scene Interaction Modeling](https://jnnan.github.io/trumans/)
5. [[CVPR 2023] CIRCLE: Capture In Rich Contextual Environments](https://stanford-tml.github.io/circle_dataset/)

## (7) Embodied Environment

### Environment Generation

1. [Matterport3D: Learning from RGB-D Data in Indoor Environments](https://niessner.github.io/Matterport/)
2. [Structured3D: A Large Photo-realistic Dataset for Structured 3D Modeling](https://structured3d-dataset.org)
3. [LayoutGPT: Compositional Visual Planning and Generation with Large Language Models](https://layoutgpt.github.io)
4. [Holodeck: Language Guided Generation of  3D Embodied AI Environments](https://yueyang1996.github.io/holodeck/)
5. [ProcTHOR: Large-Scale Embodied AI Using Procedural Generation](https://procthor.allenai.org)

### Object Generation (Reconstruction from Image)

1. [[CVPR 2023] PC2: Projection-Conditioned Point Cloud Diffusion for Single-Image 3D Reconstruction](https://lukemelas.github.io/projection-conditioned-point-cloud-diffusion/)
2. [[ECCV 2022] CHORE: Contact, Human and Object REconstruction from a single RGB image](https://virtualhumans.mpi-inf.mpg.de/chore/)
3. [[CVPR 2024 Highlight] Template Free Reconstruction of Human-object Interaction with Procedural Interaction Generation](https://virtualhumans.mpi-inf.mpg.de/procigen-hdm/)
4. [[CVPR 2024] One-2-3-45++: Fast Single Image to 3D Objects with Consistent Multi-View Generation and 3D Diffusion](https://sudo-ai-3d.github.io/One2345plus_page/)
5. [[SIGGRAPH 2024] CLAY: A Controllable Large-scale Generative Model for Creating High-quality 3D Assets](https://sites.google.com/view/clay-3dlm)

## (8) 3D Vision

### Point Cloud Processing

1. [[CVPR 2017] PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation](https://stanford.edu/~rqi/pointnet/)
2. [[NIPS 2017] PointNet++: Deep Hierarchical Feature Learning on Point Sets in a Metric Space](https://stanford.edu/~rqi/pointnet2/)

### Human Pose Estimation

1. [[CVPR 2024] WHAM: Reconstructing World-grounded Humans with Accurate 3D Motion](https://wham.is.tue.mpg.de)

### Contact Estimation

1. [[ICCV 2023 Oral] DECO: Dense Estimation of 3D Human-Scene COntact in the Wild](https://deco.is.tue.mpg.de)
2. [[CVPR 2024] LEMON: Learning 3D Human-Object Interaction Relation from 2D Images](https://yyvhang.github.io/LEMON/)
3. [EgoChoir: Capturing 3D Human-Object Interaction Regions from Egocentric Views](https://yyvhang.github.io/EgoChoir/)

## (9) Video Understanding

### Egocentic Video Understanding

1. [[CVPR 2023] Ego-Body Pose Estimation via Ego-Head Pose Estimation](https://lijiaman.github.io/projects/egoego/)
2. [[SIGGRAPH 2023] EgoLocate: Real-time Motion Capture, Localization, and Mapping with Sparse Body-mounted Sensors](https://xinyu-yi.github.io/EgoLocate/)
3. [[CVPR 2024 Oral] EgoGen: An Egocentric Synthetic Data Generator](https://ego-gen.github.io)
4. [[CVPR 2024] Ego-Exo4D: Understanding Skilled Human Activity from First- and Third-Person Perspectives](https://ego-exo4d-data.org)

### LLM-Based

1. [MotionGPT: Human Motion  as Foreign Language](https://motion-gpt.github.io)

## (10) Computer Graphics

### Character Animation

1. [[SIGGRAPH Asia 2019] Neural State Machine for Character-Scene Interactions](https://www.ipab.inf.ed.ac.uk/cgvu/nsm.pdf)
2. [[SIGGRAPH 2021] AMP: Adversarial Motion Priors for Stylized Physics-Based Character Control](https://xbpeng.github.io/projects/AMP/index.html)
3. [[SIGGRAPH 2022] ASE: Large-Scale Reusable Adversarial Skill Embeddings for Physically Simulated Characters](https://xbpeng.github.io/projects/ASE/index.html)
4. [[SIGGRAPH 2023] Learning Physically Simulated Tennis Skills from Broadcast Videos](https://research.nvidia.com/labs/toronto-ai/vid2player3d/)

## (11) Robotics

### Humanoid

1. [HumanPlus: Humanoid Shadowing and Imitation from Humans](https://humanoid-ai.github.io)
