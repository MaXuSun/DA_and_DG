# 1.Instruction
* This library contains papers, codes and results of unsupervised Domain Adaptation and Domain Generalization for classification tasks from all top conferences in recent three years.We only included results from the most commonly used open source datasets.You can click "link" to jump to the corresponding codes or papers, if there is one on the Internet, otherwise you will see a "-".

* In front of each table, you will see the backbone of the network used in this table.Different backbones are marked with '()'.

* Welcome to correct mistakes or add new content.

**The following only shows the accuracies of each method. Click [here](https://maxusun.github.io/DA_and_DG/) to view the full form.**

# 2.Result
## 2.1.DA
### 2.1.1.Office-31
>**Backbone:** *ResNet50*

|Name|A→W|D→W|W→D|A→D|D→A|W→A|Avg|
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|JDDA-I|82.1±0.3|95.2±0.1|99.7±0.0|76.1±0.2|56.9±0.0|65.1±0.3|79.2|AAAI|2019|[link](https://github.com/A-bone1/JDDA)|[link](https://ojs.aaai.org/index.php/AAAI/article/view/4202/4080)|Joint Domain Alignment and Discriminative Feature Learning for Unsupervised Deep Domain Adaptation 
|JDDA-C|82.6±0.4|95.2±0.2|99.7±0.0|79.8±0.1|57.4±0.0|66.7±0.2|80.2|AAAI|2019|[link](https://github.com/A-bone1/JDDA)|[link](https://ojs.aaai.org/index.php/AAAI/article/view/4202/4080)|Joint Domain Alignment and Discriminative Feature Learning for Unsupervised Deep Domain Adaptation 
|PFAN(AlexNet)|83.0±0.3|99.0±0.2|99.9±0.1|76.3±0.3|63.3±0.3|60.8±0.5|80.4|CVPR|2019|[link](https://github.com/Xiewp/PFAN)|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Chen_Progressive_Feature_Alignment_for_Unsupervised_Domain_Adaptation_CVPR_2019_paper.pdf)|Progressive Feature Alignment for Unsupervised Domain Adaptation 
|GCAN|82.7±0.1|97.1±0.1|99.8±0.1|76.4±0.5|64.9±0.1|62.6±0.3|80.6|CVPR|2019|[link](https://github.com/Mid-Push/Moving-Semantic-Transfer-Network)|[link](https://openaccess.thecvf.com/content_CVPR_2019/papers/Ma_GCAN_Graph_Convolutional_Adversarial_Network_for_Unsupervised_Domain_Adaptation_CVPR_2019_paper.pdf)|GCAN: Graph Convolutional Adversarial Network for Unsupervised Domain Adaptation
|DM-ADA|83.9±0.4|99.8±0.1|99.9±0.1|77.5±0.2|64.6±0.4|64.0±0.5|81.6|AAAI|2020|[link](https://github.com/ChrisAllenMing/Mixup_for_UDA)|[link](https://ojs.aaai.org/index.php/AAAI/article/view/6123/5979)|Adversarial Domain Adaptation with Domain Mixup
|ETD|92.1|100.0|100.0|88.0|71.0|67.8|86.2|CVPR|2020|[link](https://github.com/yimzhai3/ETD)|[link](http://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Enhanced_Transport_Distance_for_Unsupervised_Domain_Adaptation_CVPR_2020_paper.pdf)|Enhanced Transport Distance for Unsupervised Domain Adaptation
|KHoMM|91.7±0.3|98.9±0.0|100.0±0.0|89.1±0.3|71.2±0.2|70.6±0.3|86.9|AAAI|2020|[link](https://github.com/chenchao666/HoMM-Master)|[link](https://ojs.aaai.org/index.php/AAAI/article/download/5745/5601)|HoMM: Higher-order Moment Matching for Unsupervised Domain Adaptation
|CADA-W|93.9±0.1|99.1±0.2|99.6±0.2|93.2±0.3|68.9±0.1|68.3±0.2|87.2|CVPR|2019|[link](https://delta-lab-iitk.github.io/CADA/)|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Kurmi_Attending_to_Discriminative_Certainty_for_Domain_Adaptation_CVPR_2019_paper.pdf)|Attending to Discriminative Certainty for Domain Adaptation
|RDA|95.1|97.8|99.8|89.4|72.4|68.4|87.2|IJCAI|2020|[link](https://github.com/zhyhan/RDA)|[link](https://arxiv.org/pdf/2004.12529)|Towards Accurate and Robust Domain Adaptation under Noisy Environments 
|rRevGrad+CAT|94.4±0.1|98.0±0.2|100.0±0.0|90.8±1.8|72.2±0.6|70.2±0.1|87.6|ICCV|2019|[link](https://github.com/thudzj/CAT)|[link](http://openaccess.thecvf.com/content_ICCV_2019/papers/Deng_Cluster_Alignment_With_a_Teacher_for_Unsupervised_Domain_Adaptation_ICCV_2019_paper.pdf)|Cluster Alignment with a Teacher for Unsupervised Domain Adaptation
|SAFN+ENT*|90.3|98.7|100.0|92.1|73.4|71.2|87.6|ICCV|2019|[link](https://github.com/jihanyang/AFN)|[link](https://openaccess.thecvf.com/content_ICCV_2019/papers/Xu_Larger_Norm_More_Transferable_An_Adaptive_Feature_Norm_Approach_for_ICCV_2019_paper.pdf)|Larger Norm More Transferable An Adaptive Feature Norm Approach for Unsupervised Domain Adaptation
|BSP+DANN|93.0±0.2|98.0±0.2|100.0±0.0|90.0±0.4|71.9±0.3|73.0±0.3|87.7|ICML|2019|[link](https://github.com/thuml/Batch-Spectral-Penalization)|[link](http://proceedings.mlr.press/v97/chen19i/chen19i.pdf)|Transferability vs. Discriminability: Batch Spectral Penalization for Adversarial Domain Adaptation
|DEV|93.2|98.4|100.0|92.8|70.9|71.2|87.8|ICML|2019|[link](https://github.com/thuml/Deep-Embedded-Validation)|[link](http://proceedings.mlr.press/v97/you19a/you19a.pdf)|Towards Accurate Model Selection in Deep Unsupervised Domain Adaptation
|DMRL|90.8±0.3|99.0±0.2|100.0±0.0|93.4±0.5|73.0±0.3|71.2±0.3|87.9|ECCV|2020|-|[link](https://arxiv.org/pdf/2007.03141)|Dual Mixup Regularized Learning for Adversarial Domain Adaptation 
|MSTN+DSBN|93.3|99.1|100.0|90.8|72.7|73.9|88.3|CVPR|2019|[link](https://github.com/wgchang/DSBN)|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Chang_Domain-Specific_Batch_Normalization_for_Unsupervised_Domain_Adaptation_CVPR_2019_paper.pdf)|Domain-Specifific Batch Normalization for Unsupervised Domain Adaptation
|TADA|94.3±0.3|98.7±0.1|99.8±0.2|91.6±0.3|72.9±0.2|73.0±0.3|88.4|AAAI|2019|-|[link](https://ojs.aaai.org/index.php/AAAI/article/view/4472/4350)|Transferable Attention for Domain Adaptation 
|SymNets|90.8±0.1|98.8±0.3|100.0±0.0|93.9±0.5|74.6±0.6|72.5+0.5|88.4|CVPR|2019|[link](http://sites.scut.edu.cn/GPI/main.psp)|[link](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_Domain-Symmetric_Networks_for_Adversarial_Domain_Adaptation_CVPR_2019_paper.pdf)|Domain-Symmetric Networks for Adversarial Domain Adaptation
|BDG|93.6±0.4|99.0±0.1|100.0±0.0|93.6±0.3|73.2±0.2|72.0±0.1|88.5|AAAI|2020|-|[link](https://ojs.aaai.org/index.php/AAAI/article/download/6137/5993)|Bi-Directional Generation for Unsupervised Domain Adaptation
|CADA-A|96.8±0.2|99.0±0.1|99.8±0.1|93.4±0.1|71.7±0.2|70.5±0.3|88.5|CVPR|2019|[link](https://delta-lab-iitk.github.io/CADA/)|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Kurmi_Attending_to_Discriminative_Certainty_for_Domain_Adaptation_CVPR_2019_paper.pdf)|Attending to Discriminative Certainty for Domain Adaptation
|BSP+CDAN|93.3±0.2|98.2±0.2|100.0±0.0|93.0±0.2|73.6±0.3|72.6±0.3|88.5|ICML|2019|[link](https://github.com/thuml/Batch-Spectral-Penalization)|[link](http://proceedings.mlr.press/v97/chen19i/chen19i.pdf)|Transferability vs. Discriminability: Batch Spectral Penalization for Adversarial Domain Adaptation
|STAFF|96.4|99.6|99.8|94.0|71.7|70.2|88.6|AAAI|2020|-|[link](https://ojs.aaai.org/index.php/AAAI/article/download/6629/6483)|Structure-Aware Feature Fusion for Unsupervised Domain Adaptation
|SHOT|90.1|98.4|99.9|94.0|74.7|74.3|88.6|ICML|2020|[link](https://github.com/tim-learn/SHOT)|[link](http://proceedings.mlr.press/v119/liang20a/liang20a.pdf)|Do We Really Need to Access the Source Data? Source Hypothesis Transfer for Unsupervised Domain Adaptation
|ALDA|95.6±0.5|97.7±0.1|100.0±0.0|94.0±0.4|72.2±0.4|72.5±0.2|88.7|AAAI|2020|[link](https://github.com/ZJULearning/ALDA)|[link](https://ojs.aaai.org/index.php/AAAI/article/download/5757/5613)|Adversarial-Learned Loss for Domain Adaptation
|MDD+Implicit Alignment|90.3±0.2|98.7±0.1|99.8±0.0|92.1±0.5|75.3±0.2|74.9±0.3|88.8|ICML|2020|[link](https://github.com/xiangdal/implicit_alignment)|[link](http://proceedings.mlr.press/v119/jiang20d/jiang20d.pdf)|Implicit Class-Conditioned Domain Alignment for Unsupervised Domain Adaptation 
|MDD|94.5±0.3|98.4±0.1|100.0±0.0|93.5±0.2|74.6±0.3|72.2±0.1|88.9|ICML|2019|[link](https://github.com/thuml/MDD)|[link](http://proceedings.mlr.press/v97/zhang19i/zhang19i.pdf)|Bridging Theory and Algorithm for Domain Adaptation 
|DADA|92.3±0.1|99.2±0.1|100.0±0.0|93.9±0.2|74.4±0.1|74.2±0.1|89.0|AAAI|2020|[link](https://github.com/huitangtang/DADA-AAAI2020)|[link](https://ojs.aaai.org/index.php/AAAI/article/download/6054/5910)|Discriminative Adversarial Domain Adaptation 
|BCDM|95.4±0.3|98.6±0.1|100.0±0.0|93.8±0.3|73.1±0.3|73.0±0.2|89.0|AAAI|2021|[link](https://github.com/BIT-DA/BCDM)|[link](https://arxiv.org/pdf/2012.06995)|Bi-Classififier Determinacy Maximization for Unsupervised Domain Adaptation
|Method1|95.2|98.6|100.0|91.7|74.5|73.7|89.0|IJCAI|2020|-|[link](https://arxiv.org/pdf/2006.00223)|Self-adaptive Re-weighted Adversarial Domain Adaptation 
GVB-GD|94.8±0.5|98.7±0.3|100.0±0.0|95.0±0.4|73.4±0.3|73.7±0.3|89.3|CVPR|2020|[link](https://github.com/cuishuhao/GVB)|[link](http://openaccess.thecvf.com/content_CVPR_2020/papers/Cui_Gradually_Vanishing_Bridge_for_Adversarial_Domain_Adaptation_CVPR_2020_paper.pdf)|Gradually Vanishing Bridge for Adversarial Domain Adaptation
|MCC|95.5±0.2|98.6±0.1|100.0±0.0|94.4±0.3|72.9±0.2|74.9±0.3|89.4|ECCV|2020|[link](https://github.com/thuml/Versatile-Domain-Adaptation)|[link](https://arxiv.org/pdf/1912.03699)|Minimum Class Confusion for Versatile Domain Adaptation
|CADA-P|97.0±0.2|99.3±0.1|100.0±0.0|95.6±0.1|71.5±0.2|73.1±0.3|89.5|CVPR|2019|[link](https://delta-lab-iitk.github.io/CADA/)|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Kurmi_Attending_to_Discriminative_Certainty_for_Domain_Adaptation_CVPR_2019_paper.pdf)|Attending to Discriminative Certainty for Domain Adaptation
|GSDA|95.7|99.1|100.0|94.8|73.5|74.9|89.7|CVPR|2020|-|[link](https://openaccess.thecvf.com/content_CVPR_2020/papers/Hu_Unsupervised_Domain_Adaptation_With_Hierarchical_Gradient_Synchronization_CVPR_2020_paper.pdf)|Unsupervised Domain Adaptation with Hierarchical Gradient Synchronization 
|d-SNE(ResNet101)|96.58±0.14|99.10±0.24|100.00±0.00|94.60±0.39|75.51±0.44|74.20±0.24|90.01|CVPR|2019|[link](https://github.com/aws-samples/d-SNE)|[link](https://openaccess.thecvf.com/content_CVPR_2019/papers/Xu_d-SNE_Domain_Adaptation_Using_Stochastic_Neighborhood_Embedding_CVPR_2019_paper.pdf)|d-SNE: Domain Adaptation using Stochastic Neighborhood Embedding
|E-MixNet|93.0±0.3|99.0±0.1|100.0±0.0|95.6±0.2|78.9±0.5|74.7±0.7|90.2|AAAI|2021|[link](https://github.com/zhonglii/E-MixNet)|[link](https://arxiv.org/pdf/2101.01104)|How does the Combined Risk Affect the Performance of Unsupervised Domain Adaptation Approaches? 
|RSDA-DANN|95.3±0.3|99.3±0.2|100.0±0.0|95.2±0.2|77.4±0.8|76.0±0.6|90.2|CVPR|2020|[link](https://github.com/XJTU-XGU/RSDA)|[link](http://openaccess.thecvf.com/content_CVPR_2020/papers/Gu_Spherical_Space_Domain_Adaptation_With_Robust_Pseudo-Label_Loss_CVPR_2020_paper.pdf)|Spherical Space Domain Adaptation with Robust Pseudo-label Loss 
|CAN|94.5±0.3|99.1±0.2|99.8±0.2|95.0±0.3|78.0±0.3|77.0±0.3|90.6|CVPR|2019|[link](https://github.com/kgl-prml/Contrastive-Adaptation-Network-for-Unsupervised-Domain-Adaptation)|[link](https://openaccess.thecvf.com/content_CVPR_2019/papers/Kang_Contrastive_Adaptation_Network_for_Unsupervised_Domain_Adaptation_CVPR_2019_paper.pdf)|Contrastive Adaptation Network for Unsupervised Domain Adaptation
|RWOT|95.1±0.2|99.5±0.2|100.0±0.0|94.5±0.2|77.5±0.1|77.9±0.3|90.8|CVPR|2020|-|[link](https://openaccess.thecvf.com/content_CVPR_2020/papers/Xu_Reliable_Weighted_Optimal_Transport_for_Unsupervised_Domain_Adaptation_CVPR_2020_paper.pdf)|Reliable Weighted Optimal Transport for Unsupervised Domain Adaptation
|SRDC|95.7±0.2|99.2±0.1|100.0±0.0|95.8±0.2|76.7±0.3|77.1±0.1|90.8|CVPR|2020|[link](https://github.com/huitangtang/SRDC-CVPR2020)|[link](https://openaccess.thecvf.com/content_CVPR_2020/papers/Tang_Unsupervised_Domain_Adaptation_via_Structurally_Regularized_Deep_Clustering_CVPR_2020_paper.pdf)|Unsupervised Domain Adaptation via Structurally Regularized Deep Clustering
|RSDA-MSTN|96.1±0.2|99.3±0.2|100.0±0.0|95.8±0.3|77.4±0.8|78.9±0.3|91.1|CVPR|2020|[link](https://github.com/XJTU-XGU/RSDA)|[link](http://openaccess.thecvf.com/content_CVPR_2020/papers/Gu_Spherical_Space_Domain_Adaptation_With_Robust_Pseudo-Label_Loss_CVPR_2020_paper.pdf)|Spherical Space Domain Adaptation with Robust Pseudo-label Loss 

### 2.1.2.Office-Home
>**Backbone:** *ResNet50*

|Name|Ar→Cl|Ar→Pr|Ar→Rw|Cl→Ar|Cl→Pr|Cl→Rw|Pr→Ar|Pr→Cl|Pr→Rw|Rw→Ar|Rw→Cl|Rw→Pr|Avg|
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|GCAN|36.43|47.25|61.08|37.90|58.25|57.00|35.77|42.66|64.47|50.08|49.12|72.53|51.05|CVPR|2019|[link](https://github.com/Mid-Push/Moving-Semantic-Transfer-Network)|[link](https://openaccess.thecvf.com/content_CVPR_2019/papers/Ma_GCAN_Graph_Convolutional_Adversarial_Network_for_Unsupervised_Domain_Adaptation_CVPR_2019_paper.pdf)|GCAN: Graph Convolutional Adversarial Network for Unsupervised Domain Adaptation
|Method2|40.3|51.6|61.5|37.9|58.0|58.6|33.6|45.9|61.8|50.1|50.9|71.7|51.8|IJCAI|2019|-|[link](https://arxiv.org/pdf/1906.09693)|Bayesian Uncertainty Matching for Unsupervised Domain Adaptation
|LFP|41.53|53.66|64.90|41.53|54.57|57.66|38.87|40.08|65.97|55.13|47.18|76.02|53.10|AAAI|2019|-|[link](https://ojs.aaai.org/index.php/AAAI/article/view/4479/4357)|Exploiting Local Feature Patterns for Unsupervised Domain Adaptation 
|DPDA|39.2|54.4|61.4|50.3|57.8|59.9|53.5|40.7|67.9|59.4|43.8|68.7|54.8|IJCAI|2019|-|[link](https://pdfs.semanticscholar.org/77d7/a7b36abc7cd3cf0ef492183469abb0342cc1.pdf)|Differentially Private Optimal Transport: Application to Domain Adaptation 
|RDA|50.8|68.7|72.3|55.6|67.4|67.9|57.8|50.5|74.6|69.5|57.7|80.2|64.4|IJCAI|2020|[link](https://github.com/zhyhan/RDA)|[link](https://arxiv.org/pdf/2004.12529)|Towards Accurate and Robust Domain Adaptation under Noisy Environments 
|BSP+DANN|51.4|68.3|75.9|56.0|67.8|68.8|57.0|49.6|75.8|70.4|57.1|80.6|64.9|ICCV|2019|[link](https://github.com/thuml/Batch-Spectral-Penalization)|[link](http://proceedings.mlr.press/v97/chen19i/chen19i.pdf)|Transferability vs. Discriminability: Batch Spectral Penalization for Adversarial Domain Adaptation
|DWT-MEC|50.3|72.1|77.0|59.6|69.3|70.2|58.3|48.1|77.3|69.3|53.6|82.0|65.6|CVPR|2019|[link](https://github.com/roysubhankar/dwt-domain-adaptation)|[link](https://openaccess.thecvf.com/content_CVPR_2019/papers/Roy_Unsupervised_Domain_Adaptation_Using_Feature-Whitening_and_Consensus_Loss_CVPR_2019_paper.pdf)|Unsupervised Domain Adaptation using Feature-Whitening and Consensus Loss
|BSP+CDAN|52.0|68.6|76.1|58.0|70.3|70.2|58.6|50.2|77.6|72.2|59.3|81.9|66.3|ICCV|2019|[link](https://github.com/thuml/Batch-Spectral-Penalization)|[link](http://proceedings.mlr.press/v97/chen19i/chen19i.pdf)|Transferability vs. Discriminability: Batch Spectral Penalization for Adversarial Domain Adaptation
|ALDA|53.7|70.1|76.4|60.2|72.6|71.5|56.8|51.9|77.1|70.2|56.3|82.1|66.6|AAAI|2020|[link](https://github.com/ZJULearning/ALDA)|[link](https://ojs.aaai.org/index.php/AAAI/article/download/5757/5613)|Adversarial-Learned Loss for Domain Adaptation
|AADA+CCN|50.4|71.3|77.5|60.8|70.8|71.2|59.1|51.8|76.9|71.0|57.4|81.8|67.0|ECCV|2020|-|[link](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123690579.pdf)|Mind the Discriminability:Asymmetric Adversarial Domain Adaptation
|ETD|51.3|71.9|85.7|57.6|69.2|73.7|57.8|51.2|79.3|70.2|57.5|82.1|67.3|CVPR|2020|[link](https://github.com/yimzhai3/ETD)|[link](http://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Enhanced_Transport_Distance_for_Unsupervised_Domain_Adaptation_CVPR_2020_paper.pdf)|Enhanced Transport Distance for Unsupervised Domain Adaptation
|TADA|53.1|72.3|77.2|59.1|71.2|72.1|59.7|53.1|78.4|72.4|60.0|82.9|67.6|AAAI|2019|-|[link](https://ojs.aaai.org/index.php/AAAI/article/view/4472/4350)|Transferable Attention for Domain Adaptation 
|SymNets|47.7|72.9|78.5|64.2|71.3|74.2|64.2|48.8|79.5|74.5|52.6|82.7|67.6|CVPR|2019|[link](http://sites.scut.edu.cn/GPI/main.psp)|[link](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_Domain-Symmetric_Networks_for_Adversarial_Domain_Adaptation_CVPR_2019_paper.pdf)|Domain-Symmetric Networks for Adversarial Domain Adaptation
|DRMEA|52.3|73.0|77.3|64.3|72.0|71.8|63.6|52.7|78.5|72.0|57.7|81.6|68.1|AAAI|2020|[link](https://github.com/LavieLuo/DRMEA)|[link](https://ojs.aaai.org/index.php/AAAI/article/download/5943/5799)|Unsupervised Domain Adaptation via Discriminative Manifold Embedding and Alignment
|MDD|54.9|73.7|77.8|60.0|71.4|71.8|61.2|53.6|78.1|72.5|60.2|82.3|68.1|ICCV|2019|[link](https://github.com/thuml/MDD)|[link](http://proceedings.mlr.press/v97/zhang19i/zhang19i.pdf)|Bridging Theory and Algorithm for Domain Adaptation 
|STAFF|53.3|71.9|80.2|63.1|69.8|74.1|65.3|50.9|77.8|73.1|56.6|82.4|68.2|AAAI|2020|[link](https://github.com/cuishuhao/HAD)|[link](https://ojs.aaai.org/index.php/AAAI/article/download/6629/6483)|Structure-Aware Feature Fusion for Unsupervised Domain Adaptation
|SAFN*|54.4|73.3|77.9|65.2|71.5|73.2|63.6|52.6|78.2|72.3|58.0|82.1|68.5|ICCV|2019|[link](https://github.com/jihanyang/AFN)|[link](https://openaccess.thecvf.com/content_ICCV_2019/papers/Xu_Larger_Norm_More_Transferable_An_Adaptive_Feature_Norm_Approach_for_ICCV_2019_paper.pdf)|Larger Norm More Transferable An Adaptive Feature Norm Approach for Unsupervised Domain Adaptation
|BDG|51.5|73.4|78.7|65.3|71.5|73.7|65.1|49.7|81.1|74.6|55.1|84.8|68.7|AAAI|2020|-|[link](https://ojs.aaai.org/index.php/AAAI/article/download/6137/5993)|Bi-Directional Generation for Unsupervised Domain Adaptation
|Method3|55.5|73.5|78.7|60.7|74.1|73.1|59.5|55.0|80.4|72.4|60.3|84.3|68.9|IJCAI|2020|-|[link](https://arxiv.org/pdf/2006.00223)|Self-adaptive Re-weighted Adversarial Domain Adaptation 
|MDD+Implicit Alignment|56.2|77.9|79.2|64.4|73.1|74.4|64.2|54.2|79.9|71.2|58.1|83.1|69.5|ICML|2020|[link](https://github.com/xiangdal/implicit_alignment)|[link](http://proceedings.mlr.press/v119/jiang20d/jiang20d.pdf)|Implicit Class-Conditioned Domain Alignment for Unsupervised Domain Adaptation 
|RSDA-DANN|51.5±0.5|76.8±0.8|81.1±0.2|67.1±0.4|72.1±0.2|77.0±0.6|64.2±0.3|51.1±0.5|81.8±0.6|74.9±0.2|55.9±0.2|84.5±0.7|69.8|CVPR|2020|[link](https://github.com/XJTU-XGU/RSDA)|[link](http://openaccess.thecvf.com/content_CVPR_2020/papers/Gu_Spherical_Space_Domain_Adaptation_With_Robust_Pseudo-Label_Loss_CVPR_2020_paper.pdf)|Spherical Space Domain Adaptation with Robust Pseudo-label Loss 
|CADA-A|56.9|75.4|80.2|61.7|74.6|74.9|62.9|54.4|80.9|74.3|61.1|84.4|70.1|CVPR|2019|[link](https://delta-lab-iitk.github.io/CADA/)|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Kurmi_Attending_to_Discriminative_Certainty_for_Domain_Adaptation_CVPR_2019_paper.pdf)|Attending to Discriminative Certainty for Domain Adaptation
|CADA-P|56.9|76.4|80.7|61.3|75.2|75.2|63.2|54.5|80.7|73.9|61.5|84.1|70.2|CVPR|2019|[link](https://delta-lab-iitk.github.io/CADA/)|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Kurmi_Attending_to_Discriminative_Certainty_for_Domain_Adaptation_CVPR_2019_paper.pdf)|Attending to Discriminative Certainty for Domain Adaptation
|GSDA|61.3|76.1|79.4|65.4|73.3|74.3|65.0|53.2|80.0|72.2|60.6|83.1|70.3|CVPR|2020|-|[link](https://openaccess.thecvf.com/content_CVPR_2020/papers/Hu_Unsupervised_Domain_Adaptation_With_Hierarchical_Gradient_Synchronization_CVPR_2020_paper.pdf)|Unsupervised Domain Adaptation with Hierarchical Gradient Synchronization 
|GVB-GD|57.0|74.7|79.8|64.6|74.1|74.6|65.2|55.1|81.0|74.6|59.7|84.3|70.4|CVPR|2020|[link](https://github.com/cuishuhao/GVB)|[link](http://openaccess.thecvf.com/content_CVPR_2020/papers/Cui_Gradually_Vanishing_Bridge_for_Adversarial_Domain_Adaptation_CVPR_2020_paper.pdf)|Gradually Vanishing Bridge for Adversarial Domain Adaptation
|E-MixNet|57.7|76.6|79.8|63.6|74.1|75.0|63.4|56.4|79.7|72.8|62.4|85.5|70.6|AAAI|2021|[link](https://github.com/zhonglii/E-MixNet)|[link](https://arxiv.org/pdf/2101.01104)|How does the Combined Risk Affect the Performance of Unsupervised Domain Adaptation Approaches? 
|RSDA-MSTN|53.2±0.9|77.7±1.0|81.3±0.3|66.4±0.6|74.0±0.2|76.5±0.6|67.9±0.1|53.0±0.1|82.0±0.5|75.8±0.6|57.8±0.2|85.4±0.3|70.9|CVPR|2020|[link](https://github.com/XJTU-XGU/RSDA)|[link](http://openaccess.thecvf.com/content_CVPR_2020/papers/Gu_Spherical_Space_Domain_Adaptation_With_Robust_Pseudo-Label_Loss_CVPR_2020_paper.pdf)|Spherical Space Domain Adaptation with Robust Pseudo-label Loss 
|HDAN|56.8|75.2|79.8|65.1|73.9|75.2|66.3|56.7|81.8|75.4|59.7|84.7|70.9|NeurIPS|2020|[link](https://github.com/cuishuhao/HAD)||Heuristic Domain Adaptation
|SRDC|52.3|76.3|81.0|69.5|76.2|78.0|68.7|53.8|81.7|76.3|57.1|85.0|71.3|CVPR|2020|[link](https://github.com/huitangtang/SRDC-CVPR2020)|[link](https://openaccess.thecvf.com/content_CVPR_2020/papers/Tang_Unsupervised_Domain_Adaptation_via_Structurally_Regularized_Deep_Clustering_CVPR_2020_paper.pdf)|Unsupervised Domain Adaptation via Structurally Regularized Deep Clustering
|SHOT|57.1|78.1|81.5|68.0|78.2|78.1|67.4|54.9|82.2|73.3|58.8|84.3|71.8|ICML|2020|[link](https://github.com/tim-learn/SHOT)|[link](http://proceedings.mlr.press/v119/liang20a/liang20a.pdf)|Do We Really Need to Access the Source Data? Source Hypothesis Transfer for Unsupervised Domain Adaptation

### 2.1.3.ImageCLEF
>**Backbone:** *ResNet50*

|Name|I→P|P→I|I→C|C→I|C→P|P→C|Avg|
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|GCAN|68.2±0.5|84.1±0.2|92.2±0.1|82.5±0.1|67.2±0.2|91.3±0.1|80.9|CVPR|2019|[link](https://github.com/Mid-Push/Moving-Semantic-Transfer-Network)|[link](https://openaccess.thecvf.com/content_CVPR_2019/papers/Ma_GCAN_Graph_Convolutional_Adversarial_Network_for_Unsupervised_Domain_Adaptation_CVPR_2019_paper.pdf)|GCAN: Graph Convolutional Adversarial Network for Unsupervised Domain Adaptation
|PFAN|68.5±0.5|84.4±0.4|92.2±0.6|82.3±0.4|66.3±0.3|91.7±0.2|80.9|CVPR|2019|[link](https://github.com/Xiewp/PFAN)|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Chen_Progressive_Feature_Alignment_for_Unsupervised_Domain_Adaptation_CVPR_2019_paper.pdf)|Progressive Feature Alignment for Unsupervised Domain Adaptation 
|rGevGrad+CAT|77.2±0.2|91.0±0.3|95.5±0.3|91.3±0.3|75.3±0.6|93.6±0.5|87.3|ICCV|2019|[link](https://github.com/thudzj/CAT)|[link](http://openaccess.thecvf.com/content_ICCV_2019/papers/Deng_Cluster_Alignment_With_a_Teacher_for_Unsupervised_Domain_Adaptation_ICCV_2019_paper.pdf)|Cluster Alignment with a Teacher for Unsupervised Domain Adaptation
|DMRL|77.3±0.4|90.7±0.3|97.4±0.3|91.8±0.3|76.0±0.5|94.8±0.3|88.0|ECCV|2020|-|[link](https://arxiv.org/pdf/2007.03141)|Dual Mixup Regularized Learning for Adversarial Domain Adaptation 
|CADA-A|78.0|91.5|96.3|91.0|77.1|95.3|88.2|CVPR|2019|[link](https://delta-lab-iitk.github.io/CADA/)|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Kurmi_Attending_to_Discriminative_Certainty_for_Domain_Adaptation_CVPR_2019_paper.pdf)|Attending to Discriminative Certainty for Domain Adaptation
|CADA-P|78.0|90.5|96.7|92.0|77.2|95.5|88.3|CVPR|2019|[link](https://delta-lab-iitk.github.io/CADA/)|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Kurmi_Attending_to_Discriminative_Certainty_for_Domain_Adaptation_CVPR_2019_paper.pdf)|Attending to Discriminative Certainty for Domain Adaptation
|AADA+CCN|79.2|92.5|96.2|91.4|76.1|94.7|88.4|ECCV|2020|-|[link](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123690579.pdf)|Mind the Discriminability:Asymmetric Adversarial Domain Adaptation
|Method4|78.3|91.3|96.7|90.5|78.1|96.2|88.5|IJCAI|2020|-|[link](https://arxiv.org/pdf/2006.00223)|Self-adaptive Re-weighted Adversarial Domain Adaptation 
|BCDM|79.5|93.2|96.8|91.3|78.9|95.8|89.3|AAAI|2021|[link](https://github.com/BIT-DA/BCDM)|[link](https://arxiv.org/pdf/2012.06995)|Bi-Classififier Determinacy Maximization for Unsupervised Domain Adaptation
|SAFN+ENT*|80.2|93.8|96.7|92.8|78.4|95.7|89.6|ICCV|2019|[link](https://github.com/jihanyang/AFN)|[link](https://openaccess.thecvf.com/content_ICCV_2019/papers/Xu_Larger_Norm_More_Transferable_An_Adaptive_Feature_Norm_Approach_for_ICCV_2019_paper.pdf)|Larger Norm More Transferable An Adaptive Feature Norm Approach for Unsupervised Domain Adaptation
|ETD|81.0|91.7|97.9|93.3|79.5|95.0|89.7|CVPR|2020|[link](https://github.com/yimzhai3/ETD)|[link](http://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Enhanced_Transport_Distance_for_Unsupervised_Domain_Adaptation_CVPR_2020_paper.pdf)|Enhanced Transport Distance for Unsupervised Domain Adaptation
|SymNets|80.2±0.3|93.6±0.2|97.0±0.3|93.4±0.3|78.7±0.3|96.4±0.1|89.9|CVPR|2019|[link](http://sites.scut.edu.cn/GPI/main.psp)|[link](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_Domain-Symmetric_Networks_for_Adversarial_Domain_Adaptation_CVPR_2019_paper.pdf)|Domain-Symmetric Networks for Adversarial Domain Adaptation
|RSDA-DANN|79.2±0.4|93.0±0.2|98.3±0.4|93.6±0.4|78.5±0.3|98.2±0.2|90.1|CVPR|2020|[link](https://github.com/XJTU-XGU/RSDA)|[link](http://openaccess.thecvf.com/content_CVPR_2020/papers/Gu_Spherical_Space_Domain_Adaptation_With_Robust_Pseudo-Label_Loss_CVPR_2020_paper.pdf)|Spherical Space Domain Adaptation with Robust Pseudo-label Loss 
|RSDA-MSTN|79.8±0.2|94.5±0.5|98.0±0.4|94.2±0.4|79.2±0.3|97.3±0.3|90.5|CVPR|2020|[link](https://github.com/XJTU-XGU/RSDA)|[link](http://openaccess.thecvf.com/content_CVPR_2020/papers/Gu_Spherical_Space_Domain_Adaptation_With_Robust_Pseudo-Label_Loss_CVPR_2020_paper.pdf)|Spherical Space Domain Adaptation with Robust Pseudo-label Loss 
|SRDC|80.8±0.3|94.7±0.2|97.8±0.2|94.1±0.2|80.0±0.3|97.7±0.1|90.9|CVPR|2020|[link](https://github.com/huitangtang/SRDC-CVPR2020)|[link](https://openaccess.thecvf.com/content_CVPR_2020/papers/Tang_Unsupervised_Domain_Adaptation_via_Structurally_Regularized_Deep_Clustering_CVPR_2020_paper.pdf)|Unsupervised Domain Adaptation via Structurally Regularized Deep Clustering
|E-MixNet|80.5±0.4|96.0±0.1|97.7±0.3|95.2±0.4|79.9±0.2|97.0±0.3|91.0|AAAI|2021|[link](https://github.com/zhonglii/E-MixNet)|[link](https://arxiv.org/pdf/2101.01104)|How does the Combined Risk Affect the Performance of Unsupervised Domain Adaptation Approaches? 


### 2.1.4.VisDA-2007(VisDA-C)
>**Backbone:** *ResNet101*

|Name|plane|bcycl|bus|car|house|knife|mcycl|person|plant|sktbrd|train|truck|Avg|
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|DPDA|88.5|66.2|75.8|59.1|86.5|70.4|69.9|71.6|75.9|49.3|86.8|39.5|68.8|IJCAI|2019|-|[link](https://pdfs.semanticscholar.org/77d7/a7b36abc7cd3cf0ef492183469abb0342cc1.pdf)|Differentially Private Optimal Transport: Application to Domain Adaptation 
|BSP+DANN|92.2|72.5|83.8|47.5|87.0|54.0|86.8|72.4|80.6|66.9|84.5|37.1|72.1|ICML|2019|[link](https://github.com/thuml/Batch-Spectral-Penalization)|[link](http://proceedings.mlr.press/v97/chen19i/chen19i.pdf)|Transferability vs. Discriminability: Batch Spectral Penalization for Adversarial Domain Adaptation
|DEV|81.8|53.5|83.0|71.6|89.2|72.0|89.4|75.7|97.0|55.5|71.2|29.2|72.4|ICML|2019|[link](https://github.com/thuml/Deep-Embedded-Validation)|[link](http://proceedings.mlr.press/v97/you19a/you19a.pdf)|Towards Accurate Model Selection in Deep Unsupervised Domain Adaptation 
|GPDA|83.0|74.3|80.4|66.0|87.6|75.3|83.8|73.1|90.1|57.3|80.2|37.9|73.3|CVPR|2019|[link](https://github.com/seqam-lab/GPDA)|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Kim_Unsupervised_Visual_Domain_Adaptation_A_Deep_Max-Margin_Gaussian_Process_Approach_CVPR_2019_paper.pdf)|Unsupervised Visual Domain Adaptation:A Deep Max-Margin Gaussian Process Approach
|DMRL|-|-|-|-|-|-|-|-|-|-|-|-|75.5|ECCV|2020|-|[link](https://arxiv.org/pdf/2007.03141)|Dual Mixup Regularized Learning for Adversarial Domain Adaptation 
|DM-ADA(ResNet50)|-|-|-|-|-|-|-|-|-|-|-|-|75.6|AAAI|2020|[link](https://github.com/ChrisAllenMing/Mixup_for_UDA)|[link](https://ojs.aaai.org/index.php/AAAI/article/view/6123/5979)|Adversarial Domain Adaptation with Domain Mixup
|BSP+CDAN|92.4|61.0|81.0|57.5|89.0|80.6|90.1|77.0|84.2|77.9|82.1|38.4|75.9|ICML|2019|[link](https://github.com/thuml/Batch-Spectral-Penalization)|[link](http://proceedings.mlr.press/v97/chen19i/chen19i.pdf)|Transferability vs. Discriminability: Batch Spectral Penalization for Adversarial Domain Adaptation
|SAFN|93.6±0.2|61.3±0.4|84.1±0.5|70.6±2.2|94.1±0.5|79.0±4.1|91.8±0.5|79.6±1.3|89.9±0.7|55.6±3.4|89.0±0.3|24.4±2.9|76.1|ICCV|2019|[link](https://github.com/jihanyang/AFN)|[link](https://openaccess.thecvf.com/content_ICCV_2019/papers/Xu_Larger_Norm_More_Transferable_An_Adaptive_Feature_Norm_Approach_for_ICCV_2019_paper.pdf)|Larger Norm More Transferable An Adaptive Feature Norm Approach for Unsupervised Domain Adaptation
|ALDA(ResNet50)|87.0|61.3|78.7|67.9|83.7|89.4|89.5|71.0|95.4|71.9|89.6|33.1|76.5|AAAI|2020|[link](https://github.com/ZJULearning/ALDA)|[link](https://ojs.aaai.org/index.php/AAAI/article/download/5757/5613)|Adversarial-Learned Loss for Domain Adaptation
|ALDA|93.8|74.1|82.4|69.4|90.6|87.2|89.0|67.6|93.4|76.1|87.7|22.2|77.8|AAAI|2020|[link](https://github.com/ZJULearning/ALDA)|[link](https://ojs.aaai.org/index.php/AAAI/article/download/5757/5613)|Adversarial-Learned Loss for Domain Adaptation
|MCC|88.1|80.3|80.5|71.5|90.1|93.2|85.0|71.6|89.4|73.8|85.0|36.9|78.8|ECCV|2020|[link](https://github.com/thuml/Versatile-Domain-Adaptation)|[link](https://arxiv.org/pdf/1912.03699)|Minimum Class Confusion for Versatile Domain Adaptation
|DRMEA|92.1|75.0|78.9|75.5|91.2|81.9|89.0|77.2|93.3|77.4|84.8|35.1|79.3|AAAI|2020|[link](https://github.com/LavieLuo/DRMEA)|[link](https://ojs.aaai.org/index.php/AAAI/article/download/5943/5799)|Unsupervised Domain Adaptation via Discriminative Manifold Embedding and Alignment
|MSTN+DSBN|94.7|86.7|76.0|72.0|95.2|75.1|87.9|81.3|91.1|68.9|88.3|45.5|80.2|CVPR|2019|[link](https://github.com/wgchang/DSBN)|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Chang_Domain-Specific_Batch_Normalization_for_Unsupervised_Domain_Adaptation_CVPR_2019_paper.pdf)|Domain-Specifific Batch Normalization for Unsupervised Domain Adaptation
|TPN|93.7|85.1|69.2|81.6|93.5|61.9|89.3|81.4|93.5|81.6|84.5|49.9|80.4|CVPR|2019|[link](https://github.com/decisionforce/TPN)|[link](https://openaccess.thecvf.com/content_CVPR_2019/papers/Pan_Transferrable_Prototypical_Networks_for_Unsupervised_Domain_Adaptation_CVPR_2019_paper.pdf)|Transferrable Prototypical Networks for Unsupervised Domain Adaptation 
|GSDA|93.1|67.8|83.1|83.4|94.7|93.4|93.4|79.5|93.0|88.8|83.4|36.7|81.5|CVPR|2020|-|[link](https://openaccess.thecvf.com/content_CVPR_2020/papers/Hu_Unsupervised_Domain_Adaptation_With_Hierarchical_Gradient_Synchronization_CVPR_2020_paper.pdf)|Unsupervised Domain Adaptation with Hierarchical Gradient Synchronization 
|SHOT|94.3|88.5|80.1|57.3|93.1|94.9|80.7|80.3|91.5|89.1|86.3|58.2|82.9|ICML|2020|[link](https://github.com/tim-learn/SHOT)|[link](http://proceedings.mlr.press/v119/liang20a/liang20a.pdf)|Do We Really Need to Access the Source Data? Source Hypothesis Transfer for Unsupervised Domain Adaptation
BCDM|95.1|87.6|81.2|73.2|92.7|95.4|86.9|82.5|95.1|84.8|88.1|39.5|83.4|AAAI|2020|[link](https://github.com/BIT-DA/BCDM)|[link](https://arxiv.org/pdf/2012.06995)|Bi-Classififier Determinacy Maximization for Unsupervised Domain Adaptation
|RWOT|95.1|80.3|83.7|90.0|92.4|68.0|92.5|82.2|87.9|78.4|90.4|68.2|84.0|CVPR|2020|-|[link](https://openaccess.thecvf.com/content_CVPR_2020/papers/Xu_Reliable_Weighted_Optimal_Transport_for_Unsupervised_Domain_Adaptation_CVPR_2020_paper.pdf)|Reliable Weighted Optimal Transport for Unsupervised Domain Adaptation
|CAN|97.0|87.2|82.5|74.3|97.8|96.2|90.8|80.7|96.6|96.3|87.5|59.9|87.2|CVPR|2019|[link](https://github.com/kgl-prml/Contrastive-Adaptation-Network-for-Unsupervised-Domain-Adaptation)|[link](https://openaccess.thecvf.com/content_CVPR_2019/papers/Kang_Contrastive_Adaptation_Network_for_Unsupervised_Domain_Adaptation_CVPR_2019_paper.pdf)|Contrastive Adaptation Network for Unsupervised Domain Adaptation

### 2.1.5.Digit(MNIST,USPS,SVHN)
>**Backbone:** *CNN*

|Name|S→M|M→U|U→M|Avg|
|:--:|:--:|:--:|:--:|:--:|
|TPN|93.0|92.1|94.1|93.1|CVPR|2019|[link](https://github.com/decisionforce/TPN)|[link](https://openaccess.thecvf.com/content_CVPR_2019/papers/Pan_Transferrable_Prototypical_Networks_for_Unsupervised_Domain_Adaptation_CVPR_2019_paper.pdf)|Transferrable Prototypical Networks for Unsupervised Domain Adaptation 
|BSP+ADDA|91.4|93.3|94.5|93.1|ICML|2019|[link](https://github.com/thuml/Batch-Spectral-Penalization)|[link](http://proceedings.mlr.press/v97/chen19i/chen19i.pdf)|Transferability vs. Discriminability: Batch Spectral Penalization for Adversarial Domain Adaptation
|BSP+DANN|89.4|94.5|97.7|93.9|ICML|2019|[link](https://github.com/thuml/Batch-Spectral-Penalization)|[link](http://proceedings.mlr.press/v97/chen19i/chen19i.pdf)|Transferability vs. Discriminability: Batch Spectral Penalization for Adversarial Domain Adaptation
|CADA|90.4±0.4|95.6±0.2|96.5±0.1|94.2|AAAI|2019|-|[link](https://ojs.aaai.org/index.php/AAAI/article/download/4552/4430)|Consensus Adversarial Domain Adaptation
|DEV|93.18|92.54|96.93|94.22|ICML|2019|[link](https://github.com/thuml/Deep-Embedded-Validation)|[link](http://proceedings.mlr.press/v97/you19a/you19a.pdf)|Towards Accurate Model Selection in Deep Unsupervised Domain Adaptation 
|BSP+CDAN|92.1|95.0|98.1|95.1|ICML|2019|[link](https://github.com/thuml/Batch-Spectral-Penalization)|[link](http://proceedings.mlr.press/v97/chen19i/chen19i.pdf)|Transferability vs. Discriminability: Batch Spectral Penalization for Adversarial Domain Adaptation
|JDDA-I|93.1±0.2|-|97.0±0.2|95.1|AAAI|2019|[link](https://github.com/A-bone1/JDDA)|[link](https://ojs.aaai.org/index.php/AAAI/article/view/4202/4080)|Joint Domain Alignment and Discriminative Feature Learning for Unsupervised Deep Domain Adaptation 
|Our(Entro)|91.5±0.3|95.7±0.4|98.1±0.2|95.1|IJCAI|2019|-|[link](https://arxiv.org/pdf/1906.09693)|Bayesian Uncertainty Matching for Unsupervised Domain Adaptation
|DM-ADA|95.5±1.1|96.7±0.5|94.2±0.9|95.5|AAAI|2020|[link](https://github.com/ChrisAllenMing/Mixup_for_UDA)|[link](https://ojs.aaai.org/index.php/AAAI/article/view/6123/5979)|Adversarial Domain Adaptation with Domain Mixup
|JDDA-C|94.2±0.1|-|96.7±0.1|95.5|AAAI|2019|[link](https://github.com/A-bone1/JDDA)|[link](https://ojs.aaai.org/index.php/AAAI/article/view/4202/4080)|Joint Domain Alignment and Discriminative Feature Learning for Unsupervised Deep Domain Adaptation 
|rRevGrad+CAT|98.8±0.2|94.0±0.7|96.0±0.9|96.3|ECCV|2020|[link](https://github.com/thudzj/CAT)|[link](http://openaccess.thecvf.com/content_ICCV_2019/papers/Deng_Cluster_Alignment_With_a_Teacher_for_Unsupervised_Domain_Adaptation_ICCV_2019_paper.pdf)|Cluster Alignment with a Teacher for Unsupervised Domain Adaptation
|GPDA|-|96.45±0.15|96.37±0.1|96.41|CVPR|2019|[link](https://github.com/seqam-lab/GPDA)|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Kim_Unsupervised_Visual_Domain_Adaptation_A_Deep_Max-Margin_Gaussian_Process_Approach_CVPR_2019_paper.pdf)|Unsupervised Visual Domain Adaptation:A Deep Max-Margin Gaussian Process Approach
|IEDA|98.9|95.0|97.5|97.1|AAAI|2020|[link](https://sites.google.com/site/jwchoivision/)|[link](https://ojs.aaai.org/index.php/AAAI/article/download/6692/6546)|Visual Domain Adaptation by Consensus-Based Transfer to Intermediate Domain
|DMRL|96.2|96.1|99.0|97.2|ECCV|2020|-|[link](https://arxiv.org/pdf/2007.03141)|Dual Mixup Regularized Learning for Adversarial Domain Adaptation 
|ACAL|96.61|98.31|97.16|97.36|ICLR|2019|-|[link](https://arxiv.org/pdf/1807.00374)|Augmented cyclic adversarial learning for low resource domain adaptation
|ALDA|98.6±0.1|95.6±0.3|98.7±0.3|97.6|AAAI|2020|[link](https://github.com/ZJULearning/ALDA)|[link](https://ojs.aaai.org/index.php/AAAI/article/download/5757/5613)|Adversarial-Learned Loss for Domain Adaptation
|d-SNE|96.45±0.20|99.00±0.08|98.49±0.35|97.98|CVPR|2019|[link](https://github.com/aws-samples/d-SNE)|[link](https://openaccess.thecvf.com/content_CVPR_2019/papers/Xu_d-SNE_Domain_Adaptation_Using_Stochastic_Neighborhood_Embedding_CVPR_2019_paper.pdf)|d-SNE: Domain Adaptation using Stochastic Neighborhood Embedding
|STAFF|97.7|98.3|98.1|98.0|AAAI|2020|-|[link](https://ojs.aaai.org/index.php/AAAI/article/download/6629/6483)|Structure-Aware Feature Fusion for Unsupervised Domain Adaptation
|RWOT|98.8±0.1|98.5±0.2|97.5±0.2|98.30|CVPR|2020|-|[link](https://openaccess.thecvf.com/content_CVPR_2020/papers/Xu_Reliable_Weighted_Optimal_Transport_for_Unsupervised_Domain_Adaptation_CVPR_2020_paper.pdf)|Reliable Weighted Optimal Transport for Unsupervised Domain Adaptation
|SHOT|98.9±0.0|98.0±0.2|98.4±0.6|98.4|ICML|2020|[link](https://github.com/tim-learn/SHOT)|[link](http://proceedings.mlr.press/v119/liang20a/liang20a.pdf)|Do We Really Need to Access the Source Data? Source Hypothesis Transfer for Unsupervised Domain Adaptation
|DWT-MEC|97.80±0.07|99.01±0.06|99.02±0.05|98.61|CVPR|2019|[link](https://github.com/roysubhankar/dwt-domain-adaptation)|[link](https://openaccess.thecvf.com/content_CVPR_2019/papers/Roy_Unsupervised_Domain_Adaptation_Using_Feature-Whitening_and_Consensus_Loss_CVPR_2019_paper.pdf)|Unsupervised Domain Adaptation using Feature-Whitening and Consensus Loss
|KHoMM|99.0±0.0|-|99.2±0.0|99.1|AAAI|2020|[link](https://github.com/chenchao666/HoMM-Master)|[link](https://ojs.aaai.org/index.php/AAAI/article/download/5745/5601)|HoMM: Higher-order Moment Matching for Unsupervised Domain Adaptation

## 2.2.DG
### 2.2.1.PACS
|Name|Art Painting|Cartoon|Photo|Sketch|Avg|
|:--:|:--:|:--:|:--:|:--:|:--:|
|Epi-FCR(AlexNet)|64.7|72.3|86.1|65.0|72.0|ICCV|2019|[link](https://github.com/HAHA-DL/Episodic-DG)|[link](https://openaccess.thecvf.com/content_ICCV_2019/papers/Li_Episodic_Training_for_Domain_Generalization_ICCV_2019_paper.pdf)|Episodic Training for Domain Generalization
|Feature-Critic(AlexNet)|64.89|71.72|89.94|61.85|72.1|ICML|2019|[link](https://github.com/liyiying/Feature_Critic)|[link](http://proceedings.mlr.press/v97/li19l/li19l.pdf)|Feature-Critic Networks for Heterogeneous Domain Generalisation 
|DMG(AlexNet)|64.65|69.88|87.31|71.42|73.32|ECCV|2020|[link](https://github.com/prithv1/DMG)|[link](https://arxiv.org/pdf/2008.12839)|Learning to Balance Specifificity and Invariance for In and Out of Domain Generalization
|JiGen(AlexNet)|67.63|71.71|89.00|65.18|73.78|CVPR|2019|[link](https://github.com/fmcarlucci/JigenDG)|[link](https://openaccess.thecvf.com/content_CVPR_2019/papers/Carlucci_Domain_Generalization_by_Solving_Jigsaw_Puzzles_CVPR_2019_paper.pdf)|Domain Generalization by Solving Jigsaw Puzzles
|MMLD(AlexNet)|69.27|72.83|88.98|66.44|74.38|AAAI|2020|[link](https://github.com/mil-tokyo/dg_mmld)|[link](https://ojs.aaai.org/index.php/AAAI/article/view/6846/6701)|Domain Generalization Using a Mixture of Multiple Latent Domains 
|MASF(AlexNet)|70.35|72.46|90.68|72.46|75.21|NeurIPS|2020|[link](https://github.com/biomedia-mira/masf)|[link](https://arxiv.org/pdf/1910.13580)|Domain Generalization via  Model-Agnostic Learning of Semantic Features
|MetaVIB(AlexNet)|71.94±0.34|73.17±0.21|91.93±0.23|65.94±0.24|75.74|ECCV|2020|-|[link](https://arxiv.org/pdf/2007.07645.pdf)|Learning to Learn with Variational Information Bottleneck for Domain Generalization
|EISNet(AlexNet)|70.38±0.37|71.59±1.32|91.20±0.00|70.25±1.36|75.86|ECCV|2020|[link](https://github.com/EmmaW8/EISNet)|[link](https://arxiv.org/pdf/2007.09316)|Learning from Extrinsic and Intrinsic Supervisions for Domain Generalization
|RSC(AlexNet)|71.62|75.11|90.88|66.62|76.05|ECCV|2020|[link](https://github.com/DeLightCMU/RSC)|[link](https://arxiv.org/pdf/2007.02454)|Self-Challenging Improves Cross-Domain Generalization
|JiGen(ResNet18)|79.42|75.25|96.03|71.35|80.51|CVPR|2019|[link](https://github.com/fmcarlucci/JigenDG)|[link](https://openaccess.thecvf.com/content_CVPR_2019/papers/Carlucci_Domain_Generalization_by_Solving_Jigsaw_Puzzles_CVPR_2020_paper.pdf)|Domain Generalization by Solving Jigsaw Puzzles
|MASF(ResNet18)|80.29|77.17|94.99|71.69|81.04|NeurIPS|2020|[link](https://github.com/biomedia-mira/masf)|[link](https://arxiv.org/pdf/1910.13581)|Domain Generalization via  Model-Agnostic Learning of Semantic Features
|DG_via_ER(ResNet18)|80.70±0.71|76.40±0.34|96.65±0.21|71.77±1.27|81.38|NeurIPS|2020|[link](https://github.com/sshan-zhao/DG_via_ER)|[link](https://proceedings.neurips.cc/paper/2020/file/b98249b38337c5088bbc660d8f872d6a-Paper.pdf)|Domain Generalization via Entropy Regularization
FFO-S-MLDG(ResNet18)|80.0|77.4|94.6|73.8|81.4|CVPR|2021|-|[link](https://arxiv.org/pdf/2004.01377v1.pdf)|Sequential Learning for Domain Generalization
|DMG(ResNet18)|76.90|80.38|93.35|75.21|81.46|ECCV|2020|[link](https://github.com/prithv2/DMG)|[link](https://arxiv.org/pdf/2008.12840)|Learning to Balance Specifificity and Invariance for In and Out of Domain Generalization
|Epi-FCR(ResNet18)|82.1|77.0|93.0|73.0|81.5|ICCV|2019|[link](https://github.com/HAHA-DL/Episodic-DG)|[link](https://openaccess.thecvf.com/content_ICCV_2019/papers/Li_Episodic_Training_for_Domain_Generalization_ICCV_2020_paper.pdf)|Episodic Training for Domain Generalization
S-MLDG(ResNet18)|80.5|77.8|94.8|72.8|81.5|CVPR|2021|-|[link](https://arxiv.org/pdf/2004.01377v1.pdf)|Sequential Learning for Domain Generalization
|MMLD(ResNet18)|81.28|77.16|96.09|72.22|81.83|AAAI|2020|[link](https://github.com/mil-tokyo/dg_mmld)|[link](https://ojs.aaai.org/index.php/AAAI/article/view/6846/6700)|Domain Generalization Using a Mixture of Multiple Latent Domains 
|EISNet(ResNet18)|81.89±0.88|76.44±0.31|95.93±0.06|74.33±1.37|82.15|ECCV|2020|[link](https://github.com/EmmaW9/EISNet)|[link](https://arxiv.org/pdf/2007.09317)|Learning from Extrinsic and Intrinsic Supervisions for Domain Generalization
|MASF(ResNet50)|82.89|80.49|95.01|72.29|82.67|NeurIPS|2020|[link](https://github.com/biomedia-mira/masf)|[link](https://arxiv.org/pdf/1910.13582)|Domain Generalization via  Model-Agnostic Learning of Semantic Features
|L2A-OT(ResNet18)|83.8|78.2|96.2|73.6|82.8|ECCV|2020|[link](https://github.com/mousecpn/L2A-OT)|[link](https://arxiv.org/pdf/2007.03304)|Learning to Generate Novel Domains for Domain Generalization
|DMG(ResNet50)|82.57|78.11|94.49|78.32|83.37|ECCV|2020|[link](https://github.com/prithv3/DMG)|[link](https://arxiv.org/pdf/2008.12841)|Learning to Balance Specifificity and Invariance for In and Out of Domain Generalization
|MixStyle(ResNet18)|84.1±0.4|78.8±0.4|96.1±0.3|75.9±0.9|83.7|ICLR|2021|[link](https://github.com/KaiyangZhou/mixstyle-release)|[link](https://openreview.net/pdf/45cfce2bb7de7655e5129c349f609eba35911b60.pdf)|Domain Generalization with MixStyle
|DSON(ResNet18)|84.67|77.65|95.87|82.23|85.11|ECCV|2020|-|[link](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123670069.pdf)|Learning to Optimize Domain Specifific Normalization for Domain Generalization
|RSC(ResNet18)|83.43|80.31|95.99|80.85|85.15|ECCV|2020|[link](https://github.com/DeLightCMU/RSC)|[link](https://arxiv.org/pdf/2007.02455)|Self-Challenging Improves Cross-Domain Generalization
|DG_via_ER(ResNet50)|87.51±1.03|79.31±1.40|98.25±0.12|76.30±0.65|85.34|NeurIPS|2020|[link](https://github.com/sshan-zhao/DG_via_ER)|[link](https://proceedings.neurips.cc/paper/2020/file/b98249b38337c5088bbc660d8f872d6a-Paper.pdf)|Domain Generalization via Entropy Regularization
|EISNet(ResNet50)|86.64±1.41|81.53±0.64|97.11±0.40|78.07±1.43|85.84|ECCV|2020|[link](https://github.com/EmmaW10/EISNet)|[link](https://arxiv.org/pdf/2007.09318)|Learning from Extrinsic and Intrinsic Supervisions for Domain Generalization
|DSON(ResNet50)|87.04|80.62|95.99|82.90|86.64|ECCV|2020|-|[link](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123670070.pdf)|Learning to Optimize Domain Specifific Normalization for Domain Generalization
|RSC(ResNet50)|87.89|82.16|97.92|83.35|87.83|ECCV|2020|[link](https://github.com/DeLightCMU/RSC)|[link](https://arxiv.org/pdf/2007.02456)|Self-Challenging Improves Cross-Domain Generalization

### 2.2.2.VLCS
>**Backbone:** *AlexNet*

Name|Caltech|Labelme|Pascal|Sun|Avg|
|:--:|:--:|:--:|:--:|:--:|:--:|
FFO-S-MLDG|68.1|63.1|94.8|65.2|72.8|CVPR|2021|-|[link](https://arxiv.org/pdf/2004.01377v1.pdf)|Sequential Learning for Domain Generalization
|Epi-FCR|94.1|64.3|67.1|65.9|72.9|ICCV|2019|[link](https://github.com/HAHA-DL/Episodic-DG)|[link](https://openaccess.thecvf.com/content_ICCV_2019/papers/Li_Episodic_Training_for_Domain_Generalization_ICCV_2020_paper.pdf)|Episodic Training for Domain Generalization
|JiGen|96.93|60.90|70.62|64.30|73.19|CVPR|2019|[link](https://github.com/fmcarlucci/JigenDG)|[link](https://openaccess.thecvf.com/content_CVPR_2019/papers/Carlucci_Domain_Generalization_by_Solving_Jigsaw_Puzzles_CVPR_2020_paper.pdf)|Domain Generalization by Solving Jigsaw Puzzles
S-MLDG|68.7|64.8|96.4|64.0|73.5|CVPR|2021|-|[link](https://arxiv.org/pdf/2004.01377v1.pdf)|Sequential Learning for Domain Generalization
|MMLD(ResNet18)|96.66|58.77|71.96|68.13|73.88|AAAI|2020|[link](https://github.com/mil-tokyo/dg_mmld)|[link](https://ojs.aaai.org/index.php/AAAI/article/view/6846/6701)|Domain Generalization Using a Mixture of Multiple Latent Domains 
|MetaVIB|97.37±0.63|62.66±0.35|70.28±0.71|67.85±0.17|74.54|ECCV|2020|-|[link](https://arxiv.org/pdf/2007.07645.pdf)|Learning to Learn with Variational Information Bottleneck for Domain Generalization
|EISNet|97.33±0.36|63.49±0.82|69.83±0.48|68.02±0.81|74.67|ECCV|2020|[link](https://github.com/EmmaW10/EISNet)|[link](https://arxiv.org/pdf/2007.09318)|Learning from Extrinsic and Intrinsic Supervisions for Domain Generalization
|RSC|97.61|61.86|73.93|68.32|75.43|ECCV|2020|[link](https://github.com/DeLightCMU/RSC)|[link](https://arxiv.org/pdf/2007.02456)|Self-Challenging Improves Cross-Domain Generalization

### 2.2.3.Office-Home
>**Backbone:** *ResNet18*

|Name|Art|Clipart|Product|Real World|Avg|
|:--:|:--:|:--:|:--:|:--:|:--:|
|JiGen|53.04|47.51|71.47|72.79|61.20|CVPR|2019|[link](https://github.com/fmcarlucci/JigenDG)|[link](https://openaccess.thecvf.com/content_CVPR_2019/papers/Carlucci_Domain_Generalization_by_Solving_Jigsaw_Puzzles_CVPR_2020_paper.pdf)|Domain Generalization by Solving Jigsaw Puzzles
|L2A-OT|60.6|50.1|74.8|77.0|65.6|ECCV|2020|[link](https://github.com/mousecpn/L2A-OT)|[link](https://arxiv.org/pdf/2007.03304)|Learning to Generate Novel Domains for Domain Generalization
|DSON|59.37|44.70|71.84|74.68|62.90|ECCV|2020|-|[link](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123670069.pdf)|Learning to Optimize Domain Specifific Normalization for Domain Generalization
|RSC|58.42|47.90|71.63|74.54|63.12|ECCV|2020|[link](https://github.com/DeLightCMU/RSC)|[link](https://arxiv.org/pdf/2007.02456)|Self-Challenging Improves Cross-Domain Generalization

### 2.2.4 Rotated-Mnist<sup>1<sup>
> Use one domain as the target domain.

Name|M<sub>0</sub>|M<sub>15</sub>|M<sub>30</sub>|M<sub>45</sub>|M<sub>60</sub>|M<sub>75</sub>|Avg|
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
MMD-AAE|83.70|96.60|95.70|85.20|95.90|81.20|89.72|CVPR|2018|[link](https://github.com/YuqiCui/MMD_AAE)|[link](https://openaccess.thecvf.com/content_cvpr_2018/papers/Li_Domain_Generalization_With_CVPR_2018_paper.pdf)|Domain Generalization with Adversarial Feature Learning
CrossGrad|86.03|98.92|98.60|98.39|98.68|88.94|94.93|ICLR|2018|[link](https://github.com/gpascualg/CrossGrad)|[link](https://arxiv.org/pdf/1804.10745.pdf)|Generalizing across domains via cross-gradient training.
MetaReg|85.70±0.31|98.87±0.41|98.32±0.44|98.58±0.28|98.93±0.32|89.44±0.37|94.97|NeurIPS|2018|[link](https://github.com/elliotbeck/MetaReg_PyTorch)|[link](https://dl.acm.org/doi/pdf/10.5555/33326943.3327036)|MetaReg: Towards Domain Generalization using Meta-Regularization
Reptile|87.78|99.44|98.42|98.80|99.03|87.42|95.15|-|2018|-|[link](https://arxiv.org/pdf/1803.02999.pdf)|On fifirst-order meta-learning algorithms
Feature-Critic-Flatten|87.04±0.31|99.53±0.27|99.41±0.18|99.52±0.24|99.23±0.16|91.52±0.26|96.04|ICML|2019|[link](https://github.com/liyiying/Feature_Critic)|[link](http://proceedings.mlr.press/v97/li19l/li19l.pdf)|Feature-Critic Networks for Heterogeneous Domain Generalisation 
DG_via_ER|90.09±1.25|99.24±0.37|99.27±0.16|99.31±0.21|99.45±0.19|90.81±1.35|96.36|NeurIPS|2020|[link](https://github.com/sshan-zhao/DG_via_ER)|[link](https://proceedings.neurips.cc/paper/2020/file/b98249b38337c5088bbc660d8f872d6a-Paper.pdf)|Domain Generalization via Entropy Regularization
Feature-Critic-MLP|89.23±0.25|99.68±0.24|99.20±0.20|99.24±0.18|99.53±0.23|91.44±0.34|96.39|ICML|2019|[link](https://github.com/liyiying/Feature_Critic)|[link](http://proceedings.mlr.press/v97/li19l/li19l.pdf)|Feature-Critic Networks for Heterogeneous Domain Generalisation 

### 2.2.5 Rotated-Mnist<sup>2<sup>
> Mix M<sub>0</sub> and M<sub>90</sub> into a domain as the target domain 

Name|M<sub>15</sub>,M<sub>30</sub>,M<sub>45</sub>,M<sub>60</sub>,M<sub>75</sub>->M<sub>0</sub>,M<sub>90</sub>|M<sub>30</sub>,M<sub>45</sub>,M<sub>60</sub>->M<sub>0</sub>,M<sub>60</sub>|M<sub>30</sub>,M<sub>45</sub>->M<sub>0</sub>,M<sub>90</sub>|Avg|
|:--:|:--:|:--:|:--:|:--:|
MASF|93.2±0.2|69.4±1.32|60.8±1.53|74.5|NeurIPS|2020|[link](https://github.com/biomedia-mira/masf)|[link](https://arxiv.org/pdf/1910.13580)|Domain Generalization via  Model-Agnostic Learning of Semantic Features
ERM|93.9±0.67|77.9±2.44|64.6±3.23|78.7|ICML(workshop)|2020|[link](https://github.com/microsoft/robustdg)|[link](https://arxiv.org/pdf/2006.07500.pdf)|Domain Generalization using Causal Matching
CSD|94.7±0.2|79.2±2.47|68.7±1.01|80.9|ICML|2020|[link](https://github.com/vihari/CSD)|[link](https://arxiv.org/pdf/2003.12815v2.pdf)|Proceedings of the International Conference of Machine Learning
MatchDG|96.1±0.34|86.3±1.14|74.3±2.47|85.6|ICML(workshop)|2020|[link](https://github.com/microsoft/robustdg)|[link](https://arxiv.org/pdf/2006.07500.pdf)|Domain Generalization using Causal Matching


