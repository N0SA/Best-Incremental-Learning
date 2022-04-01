# Best Incremental Learning

Documments, papers, codes, and talks for incremental learning 

**Keywords:** Incremental Learning, Continual Learning, Continuous Learning, Lifelong Learning 

## 1 Quick Start

[Continual Learning | Papers With Code](https://paperswithcode.com/task/continual-learning)

[Incremental Learning | Papers With Code](https://paperswithcode.com/task/incremental-learning)

[知乎-思悥](https://www.zhihu.com/question/271184649/answer/2415451526)

**Origin of the Study**

+ Catastrophic Forgetting, Rehearsal and Pseudorehearsal(2001)[[paper]](https://www.tandfonline.com/doi/abs/10.1080/09540099550039318)
+ Catastrophic forgetting in connectionist networks(1999)[[paper]](https://www.sciencedirect.com/science/article/pii/S1364661399012942)
+ Catastrophic Interference in Connectionist Networks: The Sequential Learning Problem(1989)[[paper]](https://www.sciencedirect.com/science/article/abs/pii/S0079742108605368)

## 2  Survey

### 2.1 Surveys

- Online Continual Learning in Image Classification: An Empirical Survey (Neurocomputing 2021)[[paper]](https://arxiv.org/abs/2101.10423)
- A continual learning survey: Defying forgetting in classification tasks (TPAMI 2021) [[paper]](https://ieeexplore.ieee.org/abstract/document/9349197)
- Rehearsal revealed: The limits and merits of revisiting samples in continual learning (ICCV 2021)[[paper]](https://arxiv.org/abs/2104.07446)
- Continual Lifelong Learning in Natural Language Processing: A Survey (COLING 2020) [[paper]](https://www.aclweb.org/anthology/2020.coling-main.574/)
- A Comprehensive Study of Class Incremental Learning Algorithms for Visual Tasks (Neural Networks 2020) [[paper]](https://arxiv.org/abs/2011.01844)
- Embracing Change: Continual Learning in Deep Neural Networks(Trends in Cognitive Sciences 2020)[[paper]](https://www.sciencedirect.com/science/article/pii/S1364661320302199)
- Towards Continual Reinforcement Learning: A Review and Perspectives(Arxiv 2020)[[paper]](https://arxiv.org/abs/2012.13490)
- Class-incremental learning: survey and performance evaluation(arXiv 2020) [[paper]](https://arxiv.org/abs/2010.15277) 
- A comprehensive, application-oriented study of catastrophic forgetting in DNNs (ICLR 2019) [[paper]](https://openreview.net/forum?id=BkloRs0qK7)
- Three scenarios for continual learning (arXiv 2019) [[paper]](https://arxiv.org/abs/1904.07734v1)
- Continual lifelong learning with neural networks: A review(Arxiv 2019)[[paper]](https://arxiv.org/abs/1802.07569)

### 2.2 Analysis & Study

+ Probing Representation Forgetting in Supervised and Unsupervised Continual Learning (CVPR 2022) [[paper]](https://arxiv.org/abs/2203.13381)
+ Learngene: From Open-World to Your Learning Task (AAAI 2022) [[paper]](https://arxiv.org/pdf/2106.06788.pdf)
+ Continual Normalization: Rethinking Batch Normalization for Online Continual Learning (ICLR 2022) [[paper]](https://openreview.net/forum?id=vwLLQ-HwqhZ)
+ **[CLEVA-Compass]** CLEVA-Compass: A Continual Learning Evaluation Assessment Compass to Promote Research Transparency and Comparability (ICLR 2022) [[paper]](https://openreview.net/pdf?id=rHMaBYbkkRJ)[[code]](https://github.com/ml-research/CLEVA-Compass)
+ Learning curves for continual learning in neural networks: Self-knowledge transfer and forgetting (ICLR 2022) [[paper]](https://openreview.net/pdf?id=tFgdrQbbaa)
+ **[CKL]** Towards Continual Knowledge Learning of Language Models (ICLR 2022) [[paper]](https://openreview.net/pdf?id=vfsRB5MImo9)
+ Pretrained Language Model in Continual Learning: A Comparative Study (ICLR 2022) [[paper]](https://openreview.net/pdf?id=figzpGMrdD)
+ Effect of scale on catastrophic forgetting in neural networks (ICLR 2022) [[paper]](https://openreview.net/pdf?id=GhVS8_yPeEa)
+ Learning where to learn: Gradient sparsity in meta and continual learning(NeurIPS 2021) [[paper]](https://proceedings.neurips.cc/paper/2021/hash/2a10665525774fa2501c2c8c4985ce61-Abstract.html)
+ Continuous Coordination As a Realistic Scenario for Lifelong Learning(ICML 2021)[[paper]](https://proceedings.mlr.press/v139/nekoei21a.html)
+ Understanding the Role of Training Regimes in Continual Learning (NeurIPS 2020)[[paper]](https://proceedings.neurips.cc/paper/2020/hash/518a38cc9a0173d0b2dc088166981cf8-Abstract.html)
+ Optimal Continual Learning has Perfect Memory and is NP-HARD (ICML 2020)[[paper]](https://proceedings.mlr.press/v119/knoblauch20a.html)



## 3 Paper

### 3.1 From an Algorithm Perspective

|      |                 Network Structure Expansion                  |                          Rehearsal                           |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| 2022 | **L2P**(CVPR 2022) [[paper]](https://arxiv.org/abs/2112.08654)[[code]](https://github.com/google-research/l2p)<br />**MEAT**(CVPR 2022) [[paper]](https://arxiv.org/abs/2203.11684) [[code]](https://github.com/zju-vipa/MEAT-TIL)<br />**STCISS**(TNNLS 2022) [[paper]](https://arxiv.org/abs/2012.03362)<br />**MBP**(TNNLS 2022)[[code]](https://ieeexplore.ieee.org/document/9705128)<br />**SSR**(ICLR 2022) [[paper]](https://openreview.net/pdf?id=boJy41J-tnQ)[[code]](https://github.com/feyzaakyurek/subspace-reg)<br />**RGO**(ICLR 2022) [[paper]](https://openreview.net/pdf?id=7YDLgf9_zgm)<br />**TRGP**(ICLR 2022) [[paper]](https://openreview.net/pdf?id=iEvAf8i6JjO)<br />**TransIL**(WACV 2022) [[paper]](https://arxiv.org/pdf/2110.08421.pdf) | **NECIL**(CVPR 2022) [[paper]](https://arxiv.org/abs/2203.06359)<br />**CwD**(CVPR 2022) [[paper]](https://arxiv.org/abs/2112.04731)[[code]](https://github.com/Yujun-Shi/CwD)<br />**MSL**(CVPR 2022) [[paper]](https://arxiv.org/abs/2203.03970)<br />**i-fuzzy**(ICLR 2022)[[paper]](https://openreview.net/pdf?id=nrGGfMbY_qK)[[code]](https://github.com/naver-ai/i-Blurry)<br />**CLS-ER**(ICLR 2022) [[paper]](https://openreview.net/pdf?id=uxxFrDwrE7Y)[[code]](https://github.com/NeurAI-Lab/CLS-ER) <br />**DPPs**(ICLR 2022) [[paper]](https://openreview.net/pdf?id=a7H7OucbWaU)[[code]](https://github.com/andrearosasco/DistilledReplay) <br />**OCS**(ICLR 2022) [[paper]](https://openreview.net/pdf?id=f9D-5WNG4Nv) <br />**InfoRS**(ICLR 2022) [[paper]](https://openreview.net/pdf?id=IpctgL7khPp) <br />**ER-AML**(ICLR 2022) [[paper]](https://openreview.net/pdf?id=N8MaByOzUfb)[[code]](https://github.com/pclucas14/aml) <br />**FAS**(ICLR 2022) [[paper]](https://openreview.net/pdf?id=metRpM4Zrcb) <br />**LUMP** (ICLR 2022) [[paper]](https://openreview.net/pdf?id=9Hrka5PA7LW)<br />**CF-IL**(ICLR 2022) [[paper]](https://openreview.net/pdf?id=RxplU3vmBx)[[code]](https://github.com/MozhganPourKeshavarz/Cost-Free-Incremental-Learning)<br />**LFPT5**(ICLR 2022) [[paper]](https://openreview.net/pdf?id=HCRVf71PMF)[[code]](https://github.com/qcwthu/Lifelong-Fewshot-Language-Learning)<br />**CandVot**(WACV 2022) [[paper]](https://openaccess.thecvf.com/content/WACV2022/papers/He_Online_Continual_Learning_via_Candidates_Voting_WACV_2022_paper.pdf)<br />**FlashCards**(WACV 2022) [[paper]](https://openaccess.thecvf.com/content/WACV2022/papers/Gopalakrishnan_Knowledge_Capture_and_Replay_for_Continual_Learning_WACV_2022_paper.pdf)<br /> |
| 2021 | <br />**DER**(CVPR 2021)[[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Yan_DER_Dynamically_Expandable_Representation_for_Class_Incremental_Learning_CVPR_2021_paper.pdf)[[code]](https://github.com/Rhyssiyan/DER-ClassIL.pytorch) <br />**EFT**(CVPR 2021)[[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Verma_Efficient_Feature_Transformations_for_Discriminative_and_Generative_Continual_Learning_CVPR_2021_paper.pdf)[[code]](https://github.com/vkverma01/EFT) <br />**PASS**(CVPR 2021) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhu_Prototype_Augmentation_and_Self-Supervision_for_Incremental_Learning_CVPR_2021_paper.pdf)[[code]](https://github.com/Impression2805/CVPR21_PASS) <br />**GeoDL**(CVPR 2021) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Simon_On_Learning_the_Geodesic_Path_for_Incremental_Learning_CVPR_2021_paper.pdf)[[code]](https://github.com/chrysts/geodesic_continual_learning) <br />**IL-ReduNet**(CVPR 2021) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Wu_Incremental_Learning_via_Rate_Reduction_CVPR_2021_paper.pdf) <br />**PIGWM**(CVPR 2021) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhou_Image_De-Raining_via_Continual_Learning_CVPR_2021_paper.pdf) <br />**BLIP**(CVPR 2021) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Shi_Continual_Learning_via_Bit-Level_Information_Preserving_CVPR_2021_paper.pdf)[[code]](https://github.com/Yujun-Shi/BLIP)<br />**Adam-NSCL**(CVPR 2021) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Wang_Training_Networks_in_Null_Space_of_Feature_Covariance_for_Continual_CVPR_2021_paper.pdf)[[code]](https://github.com/ShipengWang/Adam-NSCL)<br />**PLOP**(CVPR 2021) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Douillard_PLOP_Learning_Without_Forgetting_for_Continual_Semantic_Segmentation_CVPR_2021_paper.pdf)[[code]](https://github.com/arthurdouillard/CVPR2021_PLOP) <br />**SDR**(CVPR 2021) [[paper]](https://lttm.dei.unipd.it/paper_data/SDR/)[[code]](https://github.com/LTTM/SDR) <br />**SPB**(ICCV 2021)[[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Wu_Striking_a_Balance_Between_Stability_and_Plasticity_for_Class-Incremental_Learning_ICCV_2021_paper.pdf) <br />**Else-Net**(ICCV 2021) [[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Li_Else-Net_Elastic_Semantic_Network_for_Continual_Action_Recognition_From_Skeleton_ICCV_2021_paper.pdf) <br />**LCwoF-Framework**(ICCV 2021)[[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Kukleva_Generalized_and_Incremental_Few-Shot_Learning_by_Explicit_Learning_and_Calibration_ICCV_2021_paper.pdf) <br />**AFEC**(NeurIPS 2021)[[paper]](https://openreview.net/pdf/72a18fad6fce88ef0286e9c7582229cf1c8d9f93.pdf)[[code]](https://github.com/lywang3081/AFEC) <br />**F2M**(NeurIPS 2021) [[paper]](https://openreview.net/forum?id=ALvt7nXa2q)[[code]](https://github.com/moukamisama/f2m)<br /> **NCL**(NeurIPS 2021) [[paper]](https://openreview.net/forum?id=W9250bXDgpK)[[code]](https://github.com/tachukao/ncl) <br />**BCL**(NeurIPS 2021) [[paper]](https://openreview.net/forum?id=u1XV9BPAB9) <br />**Posterior Meta-Replay**(NeurIPS 2021)[[paper]](https://proceedings.neurips.cc/paper/2021/hash/761b42cfff120aac30045f7a110d0256-Abstract.html) <br />**Bridging-Non-Co-occurrence**(NeurIPS 2021) [[paper]](https://proceedings.neurips.cc/paper/2021/hash/ffc58105bf6f8a91aba0fa2d99e6f106-Abstract.html)<br />**MARK**(NeurIPS 2021) [[paper]](https://openreview.net/forum?id=hHTctAv9Lvh) <br />**BNS** (NeurIPS 2021) [[paper]](https://papers.nips.cc/paper/2021/hash/ac64504cc249b070772848642cffe6ff-Abstract.html) <br />**Co-occur**(NeurIPS 2021) [[paper]](https://proceedings.neurips.cc/paper/2021/hash/ffc58105bf6f8a91aba0fa2d99e6f106-Abstract.html)<br />**CLNER**(AAAI 2021)[[paper]](https://www.aaai.org/AAAI21Papers/AAAI-7791.MonaikulN.pdf) <br />**CLIS**(AAAI 2021) [[paper]](https://www.aaai.org/AAAI21Papers/AAAI-2989.ZhengE.pdf) <br />**PCL**(AAAI 2021) [[paper]](https://www.cs.uic.edu/~liub/publications/AAAI2021_PCL.pdf)<br /> **MAS3**(AAAI 2021) [[paper]](https://arxiv.org/abs/2009.12518) <br />**FSLL**(AAAI 2021) [[paper]](https://arxiv.org/pdf/2103.00991.pdf)<br />**VAR-GPs**(ICML 2021) [[paper]](https://proceedings.mlr.press/v139/kapoor21b.html) <br />**BSA**(ICML 2021) [[paper]](https://proceedings.mlr.press/v139/kumar21a.html) <br />**GPM**(ICLR 2021)[[paper]](https://arxiv.org/abs/2103.09762)[[code]](https://github.com/sahagobinda/GPM) <br /> | **ORDisCo**(CVPR 2021) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Wang_ORDisCo_Effective_and_Efficient_Usage_of_Incremental_Unlabeled_Data_for_CVPR_2021_paper.pdf)<br />**AANets**(CVPR 2021)[[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Liu_Adaptive_Aggregation_Networks_for_Class-Incremental_Learning_CVPR_2021_paper.pdf)[[code]](https://github.com/yaoyao-liu/class-incremental-learning)<br />**ORDisCo**(CVPR 2021) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Wang_ORDisCo_Effective_and_Efficient_Usage_of_Incremental_Unlabeled_Data_for_CVPR_2021_paper.pdf) <br />**DDE**(CVPR 2021)[[paper]](https://openaccess.thecvf.com/content/CVPR2021/html/Hu_Distilling_Causal_Effect_of_Data_in_Class-Incremental_Learning_CVPR_2021_paper.html)[[code]](https://github.com/JoyHuYY1412/DDE_CIL) <br />**IIRC**(CVPR 2021) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Abdelsalam_IIRC_Incremental_Implicitly-Refined_Classification_CVPR_2021_paper.pdf)<br />**Hyper-LifelongGAN**(CVPR 2021)[[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhai_Hyper-LifelongGAN_Scalable_Lifelong_Learning_for_Image_Conditioned_Generation_CVPR_2021_paper.pdf) <br />**CEC**(CVPR 2021)[[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_Few-Shot_Incremental_Learning_With_Continually_Evolved_Classifiers_CVPR_2021_paper.pdf)  <br />**iMTFA**(CVPR 2021)[[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Ganea_Incremental_Few-Shot_Instance_Segmentation_CVPR_2021_paper.pdf)[[code]](https://github.com/danganea/iMTFA) <br />**RM**(CVPR 2021)[[paper]](https://ieeexplore.ieee.org/document/9577808)[[code]](https://github.com/clovaai/rainbow-memory) <br />**LOGD**(CVPR 2021)[[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Tang_Layerwise_Optimization_by_Gradient_Decomposition_for_Continual_Learning_CVPR_2021_paper.pdf) <br />**SPPR**(CVPR 2021) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/html/Zhu_Self-Promoted_Prototype_Refinement_for_Few-Shot_Class-Incremental_Learning_CVPR_2021_paper.html)<br />**SS-IL**(ICCV 2021)[[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Ahn_SS-IL_Separated_Softmax_for_Incremental_Learning_ICCV_2021_paper.pdf) <br />**TCD**(ICCV 2021) [[Paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Park_Class-Incremental_Learning_for_Action_Recognition_in_Videos_ICCV_2021_paper.pdf) <br />**OCL**(ICCV 2021) [[paper]](https://openaccess.thecvf.com/content/ICCV2021/html/Cai_Online_Continual_Learning_With_Natural_Distribution_Shifts_An_Empirical_Study_ICCV_2021_paper.html)[[code]](https://github.com/IntelLabs/continuallearning)<br />**CoPE**(ICCV 2021) [[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/De_Lange_Continual_Prototype_Evolution_Learning_Online_From_Non-Stationary_Data_Streams_ICCV_2021_paper.pdf)[[code]](https://github.com/Mattdl/ContinualPrototypeEvolution) <br />**Co2L**(ICCV 2021) [[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Cha_Co2L_Contrastive_Continual_Learning_ICCV_2021_paper.pdf)[[code]](https://github.com/chaht01/co2l) <br />**SPR**(ICCV 2021) [[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Kim_Continual_Learning_on_Noisy_Data_Streams_via_Self-Purified_Replay_ICCV_2021_paper.pdf) <br />**NACL**(ICCV 2021) [[paper]](https://openaccess.thecvf.com/content/ICCV2021/html/Rostami_Detection_and_Continual_Learning_of_Novel_Face_Presentation_Attacks_ICCV_2021_paper.html) <br />**ABD**(ICCV 2021) [[paper]](https://openaccess.thecvf.com/content/ICCV2021/html/Smith_Always_Be_Dreaming_A_New_Approach_for_Data-Free_Class-Incremental_Learning_ICCV_2021_paper.html)[[code]](https://github.com/GT-RIPL/AlwaysBeDreaming-DFCIL)<br />**HSCNet**(ICCV 2021) [[paper]](https://openaccess.thecvf.com/content/ICCV2021/html/Wang_Continual_Learning_for_Image-Based_Camera_Localization_ICCV_2021_paper.html)[[code]](https://github.com/AaltoVision/CL_HSCNet)<br />**RECALL**(ICCV 2021) [[paper]](https://openaccess.thecvf.com/content/ICCV2021/html/Maracani_RECALL_Replay-Based_Continual_Learning_in_Semantic_Segmentation_ICCV_2021_paper.html)[[code]](https://github.com/lttm/recall) <br />**VAE**(ICCV 2021) [[Paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Cheraghian_Synthesized_Feature_Based_Few-Shot_Class-Incremental_Learning_on_a_Mixture_of_ICCV_2021_paper.pdf) <br />**ER+T**(ICPR 2021)[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9412614)[[code]](https://github.com/hastings24/rethinking_er)<br />**KCL** (ICML 2021) [[paper]](https://proceedings.mlr.press/v139/derakhshani21a.html)[[code]](https://github.com/mmderakhshani/KCL) <br />**MLIOD**(TPAMI 2021)[[paper]](https://arxiv.org/abs/2003.08798)[[code]](https://github.com/JosephKJ/iOD) <br />**BNS**(NeurIPS 2021) [[paper]](https://papers.nips.cc/paper/2021/hash/ac64504cc249b070772848642cffe6ff-Abstract.html)<br />**FS-DGPM**(NeurIPS 2021) [[paper]](https://openreview.net/forum?id=q1eCa1kMfDd)[[code]](https://github.com/danruod/fs-dgpm) <br />**SSUL**(NeurIPS  2021) [[paper]](https://proceedings.neurips.cc/paper/2021/file/5a9542c773018268fc6271f7afeea969-Paper.pdf)[[code]](https://github.com/clovaai/SSUL) <br />**DualNet**(NeurIPS 2021) [[paper]](https://openreview.net/pdf?id=eQ7Kh-QeWnO)[[code]](https://github.com/phquang/DualNet) <br />**classAug**(NeurIPS 2021) [[paper]](https://papers.nips.cc/paper/2021/file/77ee3bc58ce560b86c2b59363281e914-Paper.pdf) <br />**GMED**(NeurIPS 2021) [[paper]](https://papers.nips.cc/paper/2021/hash/f45a1078feb35de77d26b3f7a52ef502-Abstract.html) <br />**BooVAE**(NeurIPS 2021) [[paper]](https://papers.nips.cc/paper/2021/hash/952285b9b7e7a1be5aa7849f32ffff05-Abstract.html)[[code]](https://github.com/AKuzina/BooVAE) <br />**GeMCL**(NeurIPS 2021) [[paper]](https://papers.nips.cc/paper/2021/hash/b4e267d84075f66ebd967d95331fcc03-Abstract.html)<br /> **RMM**(NeurIPS 2021) [[paper]](https://proceedings.neurips.cc/paper/2021/file/1cbcaa5abbb6b70f378a3a03d0c26386-Paper.pdf)[[code]](https://github.com/aminbana/gemcl) <br />**LSF**(IJCAI 2021) [[paper]](https://www.ijcai.org/proceedings/2021/0137.pdf) <br />**ASER**(AAAI 2021)[[paper]](https://www.aaai.org/AAAI21Papers/AAAI-9988.ShimD.pdf)[[code]](https://github.com/RaptorMai/online-continual-learning) <br />**CML**(AAAI 2021)[[paper]](https://www.aaai.org/AAAI21Papers/AAAI-4847.WuT.pdf)<br /> **HAL**(AAAI 2021)[[paper]](https://www.aaai.org/AAAI21Papers/AAAI-9700.ChaudhryA.pdf) <br />**AU**(WACV 2021) [[paper]](https://openaccess.thecvf.com/content/WACV2021/html/Kurmi_Do_Not_Forget_to_Attend_to_Uncertainty_While_Mitigating_Catastrophic_WACV_2021_paper.html)<br />**IDBR**(NAACL 2021) [[paper]](https://www.aclweb.org/anthology/2021.naacl-main.218.pdf)[[code]](https://github.com/GT-SALT/IDBR) |
| 2020 | **MiB**(CVPR 2020) [[paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Cermelli_Modeling_the_Background_for_Incremental_Learning_in_Semantic_Segmentation_CVPR_2020_paper.pdf)[[code]](https://github.com/fcdl94/MiB) <br />**K-FAC** (CVPR 2020) [[paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Lee_Continual_Learning_With_Extended_Kronecker-Factored_Approximate_Curvature_CVPR_2020_paper.html) <br />**SDC**(CVPR 2020)[[paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Yu_Semantic_Drift_Compensation_for_Class-Incremental_Learning_CVPR_2020_paper.html)[[code]](https://github.com/yulu0724/SDC-IL) <br />**CLCL**(ICLR 2020)[[paper]](https://openreview.net/forum?id=rklnDgHtDS)[[code]](https://github.com/yli1/CLCL)<br />**APD**(ICLR 2020)[[paper]](https://arxiv.org/abs/1902.09432) <br />**HYPERCL**(ICLR 2020)[[paper]](https://openreview.net/forum?id=SJgwNerKvB)[[code]](https://github.com/chrhenning/hypercl)<br />**CN-DPM**(ICLR 2020)[[paper]](https://arxiv.org/pdf/2001.00689.pdf) <br />**UCB**(ICLR 2020)[[paper]](https://arxiv.org/abs/1906.02425) <br />**CLAW**(ICLR 2020)[[paper]](https://arxiv.org/pdf/1911.09514.pdf) <br />**APD**(ICLR 2020)[[paper]](https://arxiv.org/pdf/1902.09432.pdf) <br />**CAT**(NeurIPS 2020) [[paper]](https://proceedings.neurips.cc/paper/2020/file/d7488039246a405baf6a7cbc3613a56f-Paper.pdf)[[code]](https://github.com/ZixuanKe/CAT) <br />**AGS-CL**(NeurIPS 2020)[[paper]](https://proceedings.neurips.cc/paper/2020/hash/258be18e31c8188555c2ff05b4d542c3-Abstract.html) <br />**MERLIN**(NeurIPS 2020)[[paper]](https://proceedings.neurips.cc/paper/2020/file/a5585a4d4b12277fee5cad0880611bc6-Paper.pdf)[[code]](https://github.com/mattriemer/mer) <br />**OSAKA**(NeurIPS 2020) [[paper]](https://proceedings.neurips.cc/paper/2020/file/c0a271bc0ecb776a094786474322cb82-Paper.pdf)[[code]](https://github.com/ElementAI/osaka) <br />**RATT**(NeurIPS 2020)[[paper]](https://proceedings.neurips.cc/paper/2020/file/c2964caac096f26db222cb325aa267cb-Paper.pdf) <br />**CCLL**(NeurIPS 2020)[[paper]](https://proceedings.neurips.cc/paper/2020/hash/b3b43aeeacb258365cc69cdaf42a68af-Abstract.html) <br />**CIDA**(ECCV 2020) [[paper]](https://link.springer.com/chapter/10.1007/978-3-030-58601-0_4)<br />**GraphSAIL**(CIKM 2020) [[paper]](https://dl.acm.org/doi/abs/10.1145/3340531.3412754) <br />**ANML**(ECAI 2020) [[paper]](https://arxiv.org/abs/2002.09571) [[code]](https://github.com/uvm-neurobotics-lab/ANML)<br />**NICW**(BMVC 2020) [[paper]](https://arxiv.org/pdf/2008.13710.pdf) <br />**DAM**(TPAMI 2020)[[paper]](https://openreview.net/pdf?id=7YDLgf9_zgm) <br />**OGD**(PMLR 2020)[[paper]](http://proceedings.mlr.press/v108/farajtabar20a.html) <br />**BLD**(ECCV2020) [[paper]](https://arxiv.org/abs/2008.01510)[[code]](https://github.com/DonkeyShot21/batch-level-distillation) <br />**OvA-INN**(IJCNN 2020) [[paper]](https://ieeexplore.ieee.org/abstract/document/9206766) <br />**XtarNet**(ICML 2020)[[paper]](http://proceedings.mlr.press/v119/yoon20b/yoon20b.pdf)[[code]](https://github.com/EdwinKim3069/XtarNet)<br />**DMC**(WACV 2020)[[paper]](https://openaccess.thecvf.com/content_WACV_2020/html/Zhang_Class-incremental_Learning_via_Deep_Model_Consolidation_WACV_2020_paper.html) | **TOPIC**(CVPR 2020)[[paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Tao_Few-Shot_Class-Incremental_Learning_CVPR_2020_paper.html)<br />**iTAML**(CVPR2020) [[paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Rajasegaran_iTAML_An_Incremental_Task-Agnostic_Meta-learning_Approach_CVPR_2020_paper.html)[[code]](https://github.com/brjathu/iTAML)<br />**FSCIL**(CVPR 2020)[[paper]](https://arxiv.org/pdf/2004.10956.pdf)[[code]](https://github.com/xyutao/fscil)<br />**GFR**(CVPR 2020)[[paper]](https://ieeexplore.ieee.org/document/9150851/#:~:text=Generative%20Feature%20Replay%20For%20Class-Incremental%20Learning%20Abstract%3A%20Humans,that%20the%20task-ID%20is%20unknown%20at%20inference%20time.) <br />**OSIL**(CVPR 2020)[[paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/He_Incremental_Learning_in_Online_Scenario_CVPR_2020_paper.html)  <br />**ONCE**(CVPR 2020) [[paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Perez-Rua_Incremental_Few-Shot_Object_Detection_CVPR_2020_paper.html)<br />**WA**(CVPR 2020)[[paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Zhao_Maintaining_Discrimination_and_Fairness_in_Class_Incremental_Learning_CVPR_2020_paper.pdf)[[code]](https://github.com/hugoycj/Incremental-Learning-with-Weight-Aligning) <br />**CGATE**(CVPR 2020)[[paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Abati_Conditional_Channel_Gated_Networks_for_Task-Aware_Continual_Learning_CVPR_2020_paper.html)[[code]](https://github.com/lit-leo/cgate)<br />**Mnemonics**(CVPR 2020) [[paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Liu_Mnemonics_Training_Multi-Class_Incremental_Learning_Without_Forgetting_CVPR_2020_paper.html)[[code]](https://github.com/yaoyao-liu/mnemonics) <br />**MEGA**(NeurIPS 2020)[[paper]](https://par.nsf.gov/servlets/purl/10233158) <br />**GAN Memory**(NeurIPS 2020)[[paper]](https://proceedings.neurips.cc/paper/2020/hash/bf201d5407a6509fa536afc4b380577e-Abstract.html)[[code]](https://github.com/MiaoyunZhao/GANmemory_LifelongLearning) <br />**Coreset**(NeurIPS 2020)[[paper]](https://proceedings.neurips.cc/paper/2020/file/aa2a77371374094fe9e0bc1de3f94ed9-Paper.pdf) <br />**FROMP**(NeurIPS 2020)[[paper]](https://proceedings.neurips.cc/paper/2020/file/2f3bbb9730639e9ea48f309d9a79ff01-Paper.pdf)[[code]](https://github.com/team-approx-bayes/fromp) <br />**DER**(NeurIPS 2020)[[paper]](https://proceedings.neurips.cc/paper/2020/file/b704ea2c39778f07c617f6b7ce480e9e-Paper.pdf) <br />**InstAParam**(NeurIPS 2020)[[paper]](https://proceedings.neurips.cc/paper/2020/file/ca4b5656b7e193e6bb9064c672ac8dce-Paper.pdf) <br />**BOCIL**(AAAI 2020)[[code]](https://ojs.aaai.org/index.php/AAAI/article/view/6060)<br />**REMIND**(ECCV 2020)[[paper]](https://link.springer.com/chapter/10.1007/978-3-030-58598-3_28)[[code]](https://github.com/tyler-hayes/REMIND) <br />**ACL**(ECCV 2020)[[paper]](https://link.springer.com/chapter/10.1007/978-3-030-58621-8_23)[[code]](https://github.com/ZixuanKe/CAT)<br />**TPCIL**(ECCV 2020)[[paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123640256.pdf)  <br />**GDumb**(ECCV 2020)[[paper]](https://www.robots.ox.ac.uk/~tvg/publications/2020/gdumb.pdf)[[code]](https://github.com/drimpossible/GDumb) <br />**PRS**(ECCV 2020)[[paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123580409.pdf) <br />**PODNet**(ECCV 2020)[[paper]](https://arxiv.org/abs/2004.13513)[[code]](https://github.com/arthurdouillard/incremental_learning.pytorch)<br />**FA**(ECCV 2020) [[paper]](https://link.springer.com/chapter/10.1007/978-3-030-58517-4_41) <br />**L-VAEGAN**(ECCV 2020) [[paper]](https://link.springer.com/chapter/10.1007/978-3-030-58565-5_46) <br />**Piggyback GAN**(ECCV 2020) [[paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123660392.pdf)[[code]](https://github.com/arunmallya/piggyback) <br />**LAMOL**(ICLR 2020)[[paper]](https://openreview.net/forum?id=Skgxcn4YDS)[[code]](https://github.com/chho33/LAMOL) <br />**FRCL**(ICLR 2020)[[paper]](https://arxiv.org/abs/1901.11356)[[code]](https://github.com/AndreevP/FRCL)<br />**GRS**(ICLR 2020)[[paper]](https://openreview.net/forum?id=SJlsFpVtDB) <br />**Brain-inspired replay**(Natrue Communications 2020)[[paper]](https://www.nature.com/articles/s41467-020-17866-2)[[code]](https://github.com/GMvandeVen/brain-inspired-replay)<br />**ScaIL**(WACV 2020) [[paper]](https://openaccess.thecvf.com/content_WACV_2020/html/Belouadah_ScaIL_Classifier_Weights_Scaling_for_Class_Incremental_Learning_WACV_2020_paper.html)[[code]](https://github.com/EdenBelouadah/class-incremental-learning/tree/master/scail/) <br />**ARPER**(EMNLP 2020)[[paper]](https://arxiv.org/abs/2010.00910) <br />**DnR**(COLING 2020) [[paper]](https://www.aclweb.org/anthology/2020.coling-main.318.pdf) <br />**ADER**(RecSys 2020)[[paper]](https://arxiv.org/abs/2007.12000)[[code]](https://github.com/DoubleMuL/ADER)<br />**MUC**(ECCV 2020) [[paper]](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123710698.pdf)[[code]](https://github.com/srebuffi/iCaRL)<br /> |
| 2019 | **LwM**(CVPR 2019)[[paper]](https://ieeexplore.ieee.org/document/8953962) <br />**CPG**(NeurIPS 2019)[[paper]](https://arxiv.org/pdf/1910.06562v1.pdf)[[code]](https://github.com/ivclab/CPG) <br />**UCL**(NeurIPS 2019)[[paper]](https://proceedings.neurips.cc/paper/2019/file/2c3ddf4bf13852db711dd1901fb517fa-Paper.pdf) <br />**OML**(NeurIPS 2019)[[paper]](https://proceedings.neurips.cc/paper/2019/hash/f4dd765c12f2ef67f98f3558c282a9cd-Abstract.html)[[code]](https://github.com/Khurramjaved96/mrcl) <br />**ALASSO**(ICCV 2019)[[paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Park_Continual_Learning_by_Asymmetric_Loss_Approximation_With_Single-Side_Overestimation_ICCV_2019_paper.pdf) <br />**Learn-to-Grow**(PMLR 2019)[[paper]](http://proceedings.mlr.press/v97/li19m/li19m.pdf) <br />**OWM**(Nature Machine Intelligence 2019)[[paper]](https://arxiv.org/abs/1810.01256)[[code]](https://github.com/beijixiong3510/OWM) | **LUCIR**(CVPR 2019)[[paper]](https://openaccess.thecvf.com/content_CVPR_2019/html/Hou_Learning_a_Unified_Classifier_Incrementally_via_Rebalancing_CVPR_2019_paper.html)[[code]](https://github.com/hshustc/CVPR19_Incremental_Learning) <br />**TFCL**(CVPR 2019) [[paper]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Aljundi_Task-Free_Continual_Learning_CVPR_2019_paper.pdf) <br />**GD**(CVPR 2019)[[paper]](https://ieeexplore.ieee.org/document/9010368) <br />**DGM**(CVPR 2019)[[paper]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Ostapenko_Learning_to_Remember_A_Synaptic_Plasticity_Driven_Framework_for_Continual_CVPR_2019_paper.pdf) <br />**BiC**(CVPR 2019)[[paper]](https://arxiv.org/abs/1905.13260)[[code]](https://github.com/wuyuebupt/LargeScaleIncrementalLearning) <br />**MER**(ICLR 2019)[[paper]](https://openreview.net/pdf?id=B1gTShAct7)[[code]](https://github.com/mattriemer/mer) <br />**PGMA**(ICLR 2019) [[paper]](https://openreview.net/forum?id=ryGvcoA5YX) <br />**A-GEM**(ICLR 2019) [[paper]](https://arxiv.org/pdf/1812.00420.pdf)[[code]](https://github.com/facebookresearch/agem) <br />**IL2M**(ICCV 2019)[[paper]](https://ieeexplore.ieee.org/document/9009019) <br />**ILCAN**(ICCV 2019)[[paper]](https://ieeexplore.ieee.org/document/9009031) <br />**Lifelong GAN**(ICCV 2019)[[paper]](https://openaccess.thecvf.com/content_ICCV_2019/html/Zhai_Lifelong_GAN_Continual_Learning_for_Conditional_Image_Generation_ICCV_2019_paper.html) <br />**GSS**(NIPS 2019)[[paper]](https://proceedings.neurips.cc/paper/2019/file/e562cd9c0768d5464b64cf61da7fc6bb-Paper.pdf) <br />**ER**(NIPS 2019)[[paper]](https://arxiv.org/abs/1811.11682) <br />**MIR**(NIPS 2019)[[paper]<br />](https://proceedings.neurips.cc/paper/2019/hash/15825aee15eb335cc13f9b559f166ee8-Abstract.html) **RPS-Net**(NIPS 2019)[[paper]](https://www.researchgate.net/profile/Salman-Khan-62/publication/333617650_Random_Path_Selection_for_Incremental_Learning/links/5d04905ea6fdcc39f11b7355/Random-Path-Selection-for-Incremental-Learning.pdf) <br />**CLEER**(IJCAI 2019) [[paper]](https://arxiv.org/abs/1903.04566)<br />**PAE**(ICMR 2019) [[paper]](https://dl.acm.org/doi/10.1145/3323873.3325053)[[code]](https://github.com/ivclab/PAE) |
| 2018 | **PackNet**(CVPR 2018) [[paper]](https://arxiv.org/abs/1711.05769)[[code]](https://github.com/arunmallya/packnet) <br />**OLA**(NIPS 2018) [[paper]](http://papers.nips.cc/paper/7631-online-structured-laplace-approximations-for-overcoming-catastrophic-forgetting.pdf) <br />**RCL**(NIPS 2018) [[paper]](http://papers.nips.cc/paper/7369-reinforced-continual-learning.pdf)[[code]](https://github.com/xujinfan/Reinforced-Continual-Learning) <br />**MARL**(ICLR 2018)[[paper]](https://arxiv.org/abs/1711.01239)<br />**DEN**(ICLR 2018)[[paper]](https://openreview.net/forum?id=Sk7KsfW0-)[[code]](https://github.com/jaehong31/DEN) <br />**Piggyback**(ECCV 2018) [[paper]](https://arxiv.org/abs/1801.06519) <br />**RWalk**(ECCV 2018)[[paper]](https://arxiv.org/abs/1801.10112) <br />**MAS**(ECCV 2018)[[paper]](https://arxiv.org/pdf/1711.09601.pdf)[[code]](https://github.com/rahafaljundi/MAS-Memory-Aware-Synapses) <br />**R-EWC**(ICPR 2018)[[paper]](https://arxiv.org/abs/1802.02950)[[code]](https://github.com/xialeiliu/RotateNetworks) <br />**HAT**(PMLR 2018)[[paper]](http://proceedings.mlr.press/v80/serra18a.html)[[code]](https://github.com/joansj/hat) | **MeRGANs**(NIPS 2018) [[paper]](https://arxiv.org/abs/1809.02058)[[code]](https://github.com/WuChenshen/MeRGAN) <br />**EEIL**(ECCV 2018)[[paper]](https://arxiv.org/abs/1807.09536)[[code]](https://github.com/fmcp/EndToEndIncrementalLearning) <br />**Adaptation by Distillation**(ECCV 2018) [[paper]](http://openaccess.thecvf.com/content_ECCV_2018/papers/Saihui_Hou_Progressive_Lifelong_Learning_ECCV_2018_paper.pdf) <br />**ESGR**(BMVC 2018) [[paper]](http://bmvc2018.org/contents/papers/0325.pdf)[[code]](https://github.com/TonyPod/ESGR) <br />**VCL**(ICLR 2018)[[paper]](https://arxiv.org/pdf/1710.10628.pdf#page=13&zoom=100,110,890)<br />**FearNet**(ICLR 2018)[[paper]](https://openreview.net/forum?id=SJ1Xmf-Rb) <br /> |
| 2017 | **Expert Gate**(CVPR 2017)[[paper]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Aljundi_Expert_Gate_Lifelong_CVPR_2017_paper.pdf)[[code]](https://github.com/wannabeOG/ExpertNet-Pytorch)<br />**ILOD**(ICCV 2017)[[paper]](https://openaccess.thecvf.com/content_ICCV_2017/papers/Shmelkov_Incremental_Learning_of_ICCV_2017_paper.pdf)[[code]](https://github.com/kshmelkov/incremental_detectors)<br />**EBLL**(ICCV2017) [[paper]](https://arxiv.org/abs/1704.01920) <br />**IMM**(NIPS 2017)[[paper]](https://arxiv.org/abs/1703.08475)[[code]](https://github.com/btjhjeon/IMM_tensorflow) <br />**SI**(ICML 2017)[[paper]](https://arxiv.org/abs/1703.04200)[[code]](https://github.com/ganguli-lab/pathint) <br />**EWC**(PNAS 2017)[[paper]](https://arxiv.org/abs/1612.00796)[[code]](https://github.com/stokesj/EWC) | **iCARL**(CVPR 2017)[[paper]](https://arxiv.org/abs/1611.07725)[[code]](https://github.com/srebuffi/iCaRL) <br />**GEM**(NIPS 2017)[[paper]](https://arxiv.org/pdf/1706.08840.pdf)[[code]](https://github.com/facebookresearch/GradientEpisodicMemory) <br />**DGR**(NIPS 2017)[[paper]](https://arxiv.org/abs/1705.08690)[[code]](https://github.com/kuc2477/pytorch-deep-generative-replay) |
| 2016 | **LwF**(ECCV 2016) [[paper]](https://link.springer.com/chapter/10.1007/978-3-319-46493-0_37)[[code]](https://github.com/lizhitwo/LearningWithoutForgetting) |                                                              |

### 3.2 From a Label Space Perspective

**Class Incremental Learning**

to be added...

**Task Incremental Learning**

to be added...

**Domain Incremental Learning**

to be added...

### 3.3  From an Application Perspective

**Image Classification**

to be added...

**Object Detection**

to be added...

**Image Segmentation**

to be added...

### 3.4 From a Data Deployment Perspective

**Online incremental learning**

to be added...

**data decentralized incremental learning**

to be added...

**data centralized incremental learning**

to be added...

## 4 Tutorial, Workshop, & Talks

**VALSE Webinar**

[20211215【学无止境：深度连续学习】洪晓鹏：记忆拓扑保持的深度增量学习方法](https://www.bilibili.com/video/BV1Qi4y197uf?spm_id_from=333.999.0.0)

[20211215【学无止境：深度连续学习】李玺：基于深度神经网络的持续性学习理论与方法](https://www.bilibili.com/video/BV1XR4y1W7mr?spm_id_from=333.999.0.0)

**ACM MULTIMEDIA**

[ACM2021 Few-shot Learning for Multi-Modality Tasks](https://ingrid725.github.io/ACM-Multimedia-2021/)


**CVPR Workshop**

[CVPR 2022 Workshop on Continual Learning](https://sites.google.com/view/clvision2022/overview)

[CVPR2021 CLVision](https://sites.google.com/view/clvision2021)

[CVPR2020 CLVision](https://sites.google.com/view/clvision2020/overview)

[CVPR2017 Continuous and
Open-Set Learning
Workshop](https://erodner.github.io/continuouslearningcvpr2017/)

**ICML Workshop**

[ICML 2021 Workshop on Theory and Foundation of Continual Learning](https://sites.google.com/view/cl-theory-icml2021)

[ICML 2021 Continual Learning with Deep Architectures](https://sites.google.com/view/cltutorial-icml2021)

[ICML2020  Workshop on Continual Learning](https://sites.google.com/view/cl-icml/)

**NeurIPS Workshop**

[NeurIPS2021 4th Robot Learning Workshop: Self-Supervised and Lifelong Learning](http://www.robot-learning.ml/2021/)

[NeurIPS2018 Continual learning Workshop](https://sites.google.com/view/continual2018/home)

[NeurIPS2016 Continual Learning and Deep Networks Workshop](https://sites.google.com/site/cldlnips2016/)

**IJCAI Workshop**

[IJCAI 2021 International Workshop on Continual Semi-Supervised Learning](https://sites.google.com/view/sscl-workshop-ijcai-2021/overview)

**ContinualAI wiki**

[A Non-profit Research Organization and Open Community on Continual Learning for AI](https://www.continualai.org/)

## 5 Competitions

[3rd CLVISION CVPR Workshop Challenge 2022](https://sites.google.com/view/clvision2022/challenge)

[IJCAI 2021 - International Workshop on Continual Semi-Supervised Learning](https://sites.google.com/view/sscl-workshop-ijcai-2021/)

## 6 Reference

[1]https://github.com/xialeiliu/Awesome-Incremental-Learning

[2]https://zhuanlan.zhihu.com/p/301117945

## 7 Contact Us

Should there be any concerns on this page, please don't hesitate to let us know via [hongxiaopeng@ieee.org](mailto:hongxiaopeng@ieee.org) or [xl330@126.com](mailto:xl330@126.com).