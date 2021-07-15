# 1.Instruction
* This library contains papers, codes and results of unsupervised Domain Adaptation and Domain Generalization for classification tasks from all top conferences in recent three years.We only included results from the most commonly used open source datasets.You can click "link" to jump to the corresponding codes or papers, if there is one on the Internet, otherwise you will see a "-".

* In front of each table, you will see the backbone of the network used in this table.Different backbones are marked with '()'.

* Welcome to correct mistakes or add new content.

**The following only shows the accuracies of each method. Click [here](https://maxusun.github.io/DA_and_DG/) to view the full form.**

# 2.Result
## 2.1 Domain Adaptation
### 2.1.1 Classification
#### **Office-31**
>Type: **UDA**
>Backbone: **ResNet50**

|Name|A→W|D→W|W→D|A→D|D→A|W→A|Avg|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|JDDA-I|82.1±0.3|95.2±0.1|99.7±0.0|76.1±0.2|56.9±0.0|65.1±0.3|79.2|AAAI|2019|[link](https://github.com/A-bone1/JDDA)|[link](https://ojs.aaai.org/index.php/AAAI/article/view/4202/4080)|Joint Domain Alignment and Discriminative Feature Learning for Unsupervised Deep Domain Adaptation 
|JDDA-C|82.6±0.4|95.2±0.2|99.7±0.0|79.8±0.1|57.4±0.0|66.7±0.2|80.2|AAAI|2019|[link](https://github.com/A-bone1/JDDA)|[link](https://ojs.aaai.org/index.php/AAAI/article/view/4202/4080)|Joint Domain Alignment and Discriminative Feature Learning for Unsupervised Deep Domain Adaptation 
|PFAN(AlexNet)|83.0±0.3|99.0±0.2|99.9±0.1|76.3±0.3|63.3±0.3|60.8±0.5|80.4|CVPR|2019|[link](https://github.com/Xiewp/PFAN)|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Chen_Progressive_Feature_Alignment_for_Unsupervised_Domain_Adaptation_CVPR_2019_paper.pdf)|Progressive Feature Alignment for Unsupervised Domain Adaptation 
|GCAN|82.7±0.1|97.1±0.1|99.8±0.1|76.4±0.5|64.9±0.1|62.6±0.3|80.6|CVPR|2019|[link](https://github.com/Mid-Push/Moving-Semantic-Transfer-Network)|[link](https://openaccess.thecvf.com/content_CVPR_2019/papers/Ma_GCAN_Graph_Convolutional_Adversarial_Network_for_Unsupervised_Domain_Adaptation_CVPR_2019_paper.pdf)|GCAN: Graph Convolutional Adversarial Network for Unsupervised Domain Adaptation
|DM-ADA|83.9±0.4|99.8±0.1|99.9±0.1|77.5±0.2|64.6±0.4|64.0±0.5|81.6|AAAI|2020|[link](https://github.com/ChrisAllenMing/Mixup_for_UDA)|[link](https://ojs.aaai.org/index.php/AAAI/article/view/6123/5979)|Adversarial Domain Adaptation with Domain Mixup
|ETD|92.1|100.0|100.0|88.0|71.0|67.8|86.2|CVPR|2020|[link](https://github.com/yimzhai3/ETD)|[link](http://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Enhanced_Transport_Distance_for_Unsupervised_Domain_Adaptation_CVPR_2020_paper.pdf)|Enhanced Transport Distance for Unsupervised Domain Adaptation
|KHoMM|91.7±0.3|98.9±0.0|100.0±0.0|89.1±0.3|71.2±0.2|70.6±0.3|86.9|AAAI|2020|[link](https://github.com/chenchao666/HoMM-Master)|[link](https://ojs.aaai.org/index.php/AAAI/article/download/5745/5601)|HoMM: Higher-order Moment Matching for Unsupervised Domain Adaptation
DWL|89.2|99.2|100.0|91.2|73.1|69.8|87.1|CVPR|2021|[link](https://github.com/NiXiao-cqu/TransferLearning-dwl-cvpr2021)|[link](https://openaccess.thecvf.com/content/CVPR2021/papers/Xiao_Dynamic_Weighted_Learning_for_Unsupervised_Domain_Adaptation_CVPR_2021_paper.pdf)|Dynamic Weighted Learning for Unsupervised Domain Adaptation
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
GVB+MetaAlign|93.0±0.5|94.5±0.3|73.6±.0|100.0±.0|75.0±0.3|98.6±.0|89.2|CVPR|2021|-|[link](https://openaccess.thecvf.com/content/CVPR2021/papers/Wei_MetaAlign_Coordinating_Domain_Alignment_and_Classification_for_Unsupervised_Domain_Adaptation_CVPR_2021_paper.pdf)|MetaAlign: Coordinating Domain Alignment and Classifification for Unsupervised Domain Adaptation 
GVB-GD|94.8±0.5|98.7±0.3|100.0±0.0|95.0±0.4|73.4±0.3|73.7±0.3|89.3|CVPR|2020|[link](https://github.com/cuishuhao/GVB)|[link](http://openaccess.thecvf.com/content_CVPR_2020/papers/Cui_Gradually_Vanishing_Bridge_for_Adversarial_Domain_Adaptation_CVPR_2020_paper.pdf)|Gradually Vanishing Bridge for Adversarial Domain Adaptation
ILA-DA(with CDAN)|95.72|99.25|100.00|93.37|72.10|75.40|89.30|CVPR|2021|[link](https://github.com/astuti/ILA-DA)|[link](https://openaccess.thecvf.com/content/CVPR2021/papers/Sharma_Instance_Level_Affinity-Based_Transfer_for_Unsupervised_Domain_Adaptation_CVPR_2021_paper.pdf)|Instance Level Affifinity-Based Transfer for Unsupervised Domain Adaptation
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
FixBi|96.1±0.2|99.3±0.2|100.0±0.0|95.0±0.4|78.7±0.5|79.4±0.3|91.4|CVPR|2021|[link](https://github.com/NaJaeMin92/FixBi)|[link](https://openaccess.thecvf.com/content/CVPR2021/papers/Na_FixBi_Bridging_Domain_Spaces_for_Unsupervised_Domain_Adaptation_CVPR_2021_paper.pdf)|FixBi: Bridging Domain Spaces for Unsupervised Domain Adaptation
LAMDA|95.2|98.5|100|96|87.3|84.4|93.0|ICML|2021|-|[link](http://proceedings.mlr.press/v139/le21a/le21a.pdf)|LAMDA: Label Matching Deep Domain Adaptation 

#### **Office-Home**
>Type: **UDA**
>Backbone: **ResNet50**

|Name|Ar→Cl|Ar→Pr|Ar→Rw|Cl→Ar|Cl→Pr|Cl→Rw|Pr→Ar|Pr→Cl|Pr→Rw|Rw→Ar|Rw→Cl|Rw→Pr|Avg|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
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
CKB+MMD|54.2|74.1|77.5|64.6|72.2|71.0|64.5|53.4|78.7|72.6|58.4|82.8|68.7|CVPR|2021|-|[link](Conditional Bures Metric for Domain Adaptation)|Conditional Bures Metric for Domain Adaptation
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
GVB+MetaAlign|59.3|76.0|80.2|65.7|74.7|75.1|65.7|56.5|81.6|74.1|61.1|85.2|71.3|CVPR|2021|-|[link](https://openaccess.thecvf.com/content/CVPR2021/papers/Wei_MetaAlign_Coordinating_Domain_Alignment_and_Classification_for_Unsupervised_Domain_Adaptation_CVPR_2021_paper.pdf)|MetaAlign: Coordinating Domain Alignment and Classifification for Unsupervised Domain Adaptation 
|SHOT|57.1|78.1|81.5|68.0|78.2|78.1|67.4|54.9|82.2|73.3|58.8|84.3|71.8|ICML|2020|[link](https://github.com/tim-learn/SHOT)|[link](http://proceedings.mlr.press/v119/liang20a/liang20a.pdf)|Do We Really Need to Access the Source Data? Source Hypothesis Transfer for Unsupervised Domain Adaptation
LAMDA|57.2|78.4|82.6|66.1|80.2|81.2|65.6|55.1|82.8|71.6|59.2|83.9|72|ICML|2021|-|[link](http://proceedings.mlr.press/v139/le21a/le21a.pdf)|LAMDA: Label Matching Deep Domain Adaptation 
FixBi|58.1|77.3|80.4|67.7|79.5|78.1|65.8|57.9|81.7|76.4|62.9|86.7|72.7|CVPR|2021|[link](https://github.com/NaJaeMin92/FixBi)|[link](https://openaccess.thecvf.com/content/CVPR2021/papers/Na_FixBi_Bridging_Domain_Spaces_for_Unsupervised_Domain_Adaptation_CVPR_2021_paper.pdf)|FixBi: Bridging Domain Spaces for Unsupervised Domain Adaptation

#### **VisDA-C(VisDA-20)**
>Type: **UDA**
>Backbone: **ResNet101**

|Name|plane|bcycl|bus|car|house|knife|mcycl|person|plant|sktbrd|train|truck|Avg|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|DPDA|88.5|66.2|75.8|59.1|86.5|70.4|69.9|71.6|75.9|49.3|86.8|39.5|68.8|IJCAI|2019|-|[link](https://pdfs.semanticscholar.org/77d7/a7b36abc7cd3cf0ef492183469abb0342cc1.pdf)|Differentially Private Optimal Transport: Application to Domain Adaptation 
|BSP+DANN|92.2|72.5|83.8|47.5|87.0|54.0|86.8|72.4|80.6|66.9|84.5|37.1|72.1|ICML|2019|[link](https://github.com/thuml/Batch-Spectral-Penalization)|[link](http://proceedings.mlr.press/v97/chen19i/chen19i.pdf)|Transferability vs. Discriminability: Batch Spectral Penalization for Adversarial Domain Adaptation
|DEV|81.8|53.5|83.0|71.6|89.2|72.0|89.4|75.7|97.0|55.5|71.2|29.2|72.4|ICML|2019|[link](https://github.com/thuml/Deep-Embedded-Validation)|[link](http://proceedings.mlr.press/v97/you19a/you19a.pdf)|Towards Accurate Model Selection in Deep Unsupervised Domain Adaptation 
|GPDA|83.0|74.3|80.4|66.0|87.6|75.3|83.8|73.1|90.1|57.3|80.2|37.9|73.3|CVPR|2019|[link](https://github.com/seqam-lab/GPDA)|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Kim_Unsupervised_Visual_Domain_Adaptation_A_Deep_Max-Margin_Gaussian_Process_Approach_CVPR_2019_paper.pdf)|Unsupervised Visual Domain Adaptation:A Deep Max-Margin Gaussian Process Approach
|DMRL|-|-|-|-|-|-|-|-|-|-|-|-|75.5|ECCV|2020|-|[link](https://arxiv.org/pdf/2007.03141)|Dual Mixup Regularized Learning for Adversarial Domain Adaptation 
|DM-ADA(ResNet50)|-|-|-|-|-|-|-|-|-|-|-|-|75.6|AAAI|2020|[link](https://github.com/ChrisAllenMing/Mixup_for_UDA)|[link](https://ojs.aaai.org/index.php/AAAI/article/view/6123/5979)|Adversarial Domain Adaptation with Domain Mixup
|BSP+CDAN|92.4|61.0|81.0|57.5|89.0|80.6|90.1|77.0|84.2|77.9|82.1|38.4|75.9|ICML|2019|[link](https://github.com/thuml/Batch-Spectral-Penalization)|[link](http://proceedings.mlr.press/v97/chen19i/chen19i.pdf)|Transferability vs. Discriminability: Batch Spectral Penalization for Adversarial Domain Adaptation
|SAFN|93.6±0.2|61.3±0.4|84.1±0.5|70.6±2.2|94.1±0.5|79.0±4.1|91.8±0.5|79.6±1.3|89.9±0.7|55.6±3.4|89.0±0.3|24.4±2.9|76.1|ICCV|2019|[link](https://github.com/jihanyang/AFN)|[link](https://openaccess.thecvf.com/content_ICCV_2019/papers/Xu_Larger_Norm_More_Transferable_An_Adaptive_Feature_Norm_Approach_for_ICCV_2019_paper.pdf)|Larger Norm More Transferable An Adaptive Feature Norm Approach for Unsupervised Domain Adaptation
|ALDA(ResNet50)|87.0|61.3|78.7|67.9|83.7|89.4|89.5|71.0|95.4|71.9|89.6|33.1|76.5|AAAI|2020|[link](https://github.com/ZJULearning/ALDA)|[link](https://ojs.aaai.org/index.php/AAAI/article/download/5757/5613)|Adversarial-Learned Loss for Domain Adaptation
DWL|90.7|80.2|86.1|67.6|92.4|81.5|86.8|78|90.6|57.1|85.6|28.7|77.1|CVPR|2021|[link](https://github.com/NiXiao-cqu/TransferLearning-dwl-cvpr2021)|[link](https://openaccess.thecvf.com/content/CVPR2021/papers/Xiao_Dynamic_Weighted_Learning_for_Unsupervised_Domain_Adaptation_CVPR_2021_paper.pdf)|Dynamic Weighted Learning for Unsupervised Domain Adaptation
|ALDA|93.8|74.1|82.4|69.4|90.6|87.2|89.0|67.6|93.4|76.1|87.7|22.2|77.8|AAAI|2020|[link](https://github.com/ZJULearning/ALDA)|[link](https://ojs.aaai.org/index.php/AAAI/article/download/5757/5613)|Adversarial-Learned Loss for Domain Adaptation
|MCC|88.1|80.3|80.5|71.5|90.1|93.2|85.0|71.6|89.4|73.8|85.0|36.9|78.8|ECCV|2020|[link](https://github.com/thuml/Versatile-Domain-Adaptation)|[link](https://arxiv.org/pdf/1912.03699)|Minimum Class Confusion for Versatile Domain Adaptation
|DRMEA|92.1|75.0|78.9|75.5|91.2|81.9|89.0|77.2|93.3|77.4|84.8|35.1|79.3|AAAI|2020|[link](https://github.com/LavieLuo/DRMEA)|[link](https://ojs.aaai.org/index.php/AAAI/article/download/5943/5799)|Unsupervised Domain Adaptation via Discriminative Manifold Embedding and Alignment
|MSTN+DSBN|94.7|86.7|76.0|72.0|95.2|75.1|87.9|81.3|91.1|68.9|88.3|45.5|80.2|CVPR|2019|[link](https://github.com/wgchang/DSBN)|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Chang_Domain-Specific_Batch_Normalization_for_Unsupervised_Domain_Adaptation_CVPR_2019_paper.pdf)|Domain-Specifific Batch Normalization for Unsupervised Domain Adaptation
|TPN|93.7|85.1|69.2|81.6|93.5|61.9|89.3|81.4|93.5|81.6|84.5|49.9|80.4|CVPR|2019|[link](https://github.com/decisionforce/TPN)|[link](https://openaccess.thecvf.com/content_CVPR_2019/papers/Pan_Transferrable_Prototypical_Networks_for_Unsupervised_Domain_Adaptation_CVPR_2019_paper.pdf)|Transferrable Prototypical Networks for Unsupervised Domain Adaptation 
|GSDA|93.1|67.8|83.1|83.4|94.7|93.4|93.4|79.5|93.0|88.8|83.4|36.7|81.5|CVPR|2020|-|[link](https://openaccess.thecvf.com/content_CVPR_2020/papers/Hu_Unsupervised_Domain_Adaptation_With_Hierarchical_Gradient_Synchronization_CVPR_2020_paper.pdf)|Unsupervised Domain Adaptation with Hierarchical Gradient Synchronization 
CGDM|93.4|82.7|73.2|68.4|92.9|94.5|88.7|82.1|93.4|82.5|86.8|49.2|82.3|CVPR|2021|[link](https://github.com/lijin118/CGDM)|[link](https://openaccess.thecvf.com/content/CVPR2021/papers/Du_Cross-Domain_Gradient_Discrepancy_Minimization_for_Unsupervised_Domain_Adaptation_CVPR_2021_paper.pdf)|Cross-Domain Gradient Discrepancy Minimization for Unsupervised Domain Adaptation
|SHOT|94.3|88.5|80.1|57.3|93.1|94.9|80.7|80.3|91.5|89.1|86.3|58.2|82.9|ICML|2020|[link](https://github.com/tim-learn/SHOT)|[link](http://proceedings.mlr.press/v119/liang20a/liang20a.pdf)|Do We Really Need to Access the Source Data? Source Hypothesis Transfer for Unsupervised Domain Adaptation
BCDM|95.1|87.6|81.2|73.2|92.7|95.4|86.9|82.5|95.1|84.8|88.1|39.5|83.4|AAAI|2020|[link](https://github.com/BIT-DA/BCDM)|[link](https://arxiv.org/pdf/2012.06995)|Bi-Classififier Determinacy Maximization for Unsupervised Domain Adaptation
|RWOT|95.1|80.3|83.7|90.0|92.4|68.0|92.5|82.2|87.9|78.4|90.4|68.2|84.0|CVPR|2020|-|[link](https://openaccess.thecvf.com/content_CVPR_2020/papers/Xu_Reliable_Weighted_Optimal_Transport_for_Unsupervised_Domain_Adaptation_CVPR_2020_paper.pdf)|Reliable Weighted Optimal Transport for Unsupervised Domain Adaptation
|CAN|97.0|87.2|82.5|74.3|97.8|96.2|90.8|80.7|96.6|96.3|87.5|59.9|87.2|CVPR|2019|[link](https://github.com/kgl-prml/Contrastive-Adaptation-Network-for-Unsupervised-Domain-Adaptation)|[link](https://openaccess.thecvf.com/content_CVPR_2019/papers/Kang_Contrastive_Adaptation_Network_for_Unsupervised_Domain_Adaptation_CVPR_2019_paper.pdf)|Contrastive Adaptation Network for Unsupervised Domain Adaptation
FixBi|96.1|87.8|90.5|90.3|96.8|95.3|92.8|88.7|97.2|94.2|90.9|25.7|87.2|CVPR|2021|[link](https://github.com/NaJaeMin92/FixBi)|[link](https://openaccess.thecvf.com/content/CVPR2021/papers/Na_FixBi_Bridging_Domain_Spaces_for_Unsupervised_Domain_Adaptation_CVPR_2021_paper.pdf)|FixBi: Bridging Domain Spaces for Unsupervised Domain Adaptation


#### **ImageCLEF**
>Type: **UDA**
>Backbone: **ResNet50**

|Name|I→P|P→I|I→C|C→I|C→P|P→C|Avg|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|GCAN|68.2±0.5|84.1±0.2|92.2±0.1|82.5±0.1|67.2±0.2|91.3±0.1|80.9|CVPR|2019|[link](https://github.com/Mid-Push/Moving-Semantic-Transfer-Network)|[link](https://openaccess.thecvf.com/content_CVPR_2019/papers/Ma_GCAN_Graph_Convolutional_Adversarial_Network_for_Unsupervised_Domain_Adaptation_CVPR_2019_paper.pdf)|GCAN: Graph Convolutional Adversarial Network for Unsupervised Domain Adaptation
|PFAN|68.5±0.5|84.4±0.4|92.2±0.6|82.3±0.4|66.3±0.3|91.7±0.2|80.9|CVPR|2019|[link](https://github.com/Xiewp/PFAN)|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Chen_Progressive_Feature_Alignment_for_Unsupervised_Domain_Adaptation_CVPR_2019_paper.pdf)|Progressive Feature Alignment for Unsupervised Domain Adaptation 
|rGevGrad+CAT|77.2±0.2|91.0±0.3|95.5±0.3|91.3±0.3|75.3±0.6|93.6±0.5|87.3|ICCV|2019|[link](https://github.com/thudzj/CAT)|[link](http://openaccess.thecvf.com/content_ICCV_2019/papers/Deng_Cluster_Alignment_With_a_Teacher_for_Unsupervised_Domain_Adaptation_ICCV_2019_paper.pdf)|Cluster Alignment with a Teacher for Unsupervised Domain Adaptation
|DMRL|77.3±0.4|90.7±0.3|97.4±0.3|91.8±0.3|76.0±0.5|94.8±0.3|88.0|ECCV|2020|-|[link](https://arxiv.org/pdf/2007.03141)|Dual Mixup Regularized Learning for Adversarial Domain Adaptation 
|CADA-A|78.0|91.5|96.3|91.0|77.1|95.3|88.2|CVPR|2019|[link](https://delta-lab-iitk.github.io/CADA/)|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Kurmi_Attending_to_Discriminative_Certainty_for_Domain_Adaptation_CVPR_2019_paper.pdf)|Attending to Discriminative Certainty for Domain Adaptation
|CADA-P|78.0|90.5|96.7|92.0|77.2|95.5|88.3|CVPR|2019|[link](https://delta-lab-iitk.github.io/CADA/)|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Kurmi_Attending_to_Discriminative_Certainty_for_Domain_Adaptation_CVPR_2019_paper.pdf)|Attending to Discriminative Certainty for Domain Adaptation
|AADA+CCN|79.2|92.5|96.2|91.4|76.1|94.7|88.4|ECCV|2020|-|[link](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123690579.pdf)|Mind the Discriminability:Asymmetric Adversarial Domain Adaptation
|Method4|78.3|91.3|96.7|90.5|78.1|96.2|88.5|IJCAI|2020|-|[link](https://arxiv.org/pdf/2006.00223)|Self-adaptive Re-weighted Adversarial Domain Adaptation 
|BCDM|79.5|93.2|96.8|91.3|78.9|95.8|89.3|AAAI|2021|[link](https://github.com/BIT-DA/BCDM)|[link](https://arxiv.org/pdf/2012.06995)|Bi-Classififier Determinacy Maximization for Unsupervised Domain Adaptation
CGDM|78.7±0.2|93.3±0.1|97.5±0.3|92.7±0.2|79.2±0.1|95.7±0.2|89.5|CVPR|2021|[link](https://github.com/lijin118/CGDM)|[link](https://openaccess.thecvf.com/content/CVPR2021/papers/Du_Cross-Domain_Gradient_Discrepancy_Minimization_for_Unsupervised_Domain_Adaptation_CVPR_2021_paper.pdf)|Cross-Domain Gradient Discrepancy Minimization for Unsupervised Domain Adaptation
|SAFN+ENT*|80.2|93.8|96.7|92.8|78.4|95.7|89.6|ICCV|2019|[link](https://github.com/jihanyang/AFN)|[link](https://openaccess.thecvf.com/content_ICCV_2019/papers/Xu_Larger_Norm_More_Transferable_An_Adaptive_Feature_Norm_Approach_for_ICCV_2019_paper.pdf)|Larger Norm More Transferable An Adaptive Feature Norm Approach for Unsupervised Domain Adaptation
|ETD|81.0|91.7|97.9|93.3|79.5|95.0|89.7|CVPR|2020|[link](https://github.com/yimzhai3/ETD)|[link](http://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Enhanced_Transport_Distance_for_Unsupervised_Domain_Adaptation_CVPR_2020_paper.pdf)|Enhanced Transport Distance for Unsupervised Domain Adaptation
CKB+MMD|80.7±0.2|92.2±0.1|96.5±0.1|92.2±0.2|79.9±0.2|96.7±0.1|89.7|CVPR|2021|-|[link](Conditional Bures Metric for Domain Adaptation)|Conditional Bures Metric for Domain Adaptation
|SymNets|80.2±0.3|93.6±0.2|97.0±0.3|93.4±0.3|78.7±0.3|96.4±0.1|89.9|CVPR|2019|[link](http://sites.scut.edu.cn/GPI/main.psp)|[link](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_Domain-Symmetric_Networks_for_Adversarial_Domain_Adaptation_CVPR_2019_paper.pdf)|Domain-Symmetric Networks for Adversarial Domain Adaptation
|RSDA-DANN|79.2±0.4|93.0±0.2|98.3±0.4|93.6±0.4|78.5±0.3|98.2±0.2|90.1|CVPR|2020|[link](https://github.com/XJTU-XGU/RSDA)|[link](http://openaccess.thecvf.com/content_CVPR_2020/papers/Gu_Spherical_Space_Domain_Adaptation_With_Robust_Pseudo-Label_Loss_CVPR_2020_paper.pdf)|Spherical Space Domain Adaptation with Robust Pseudo-label Loss 
|RSDA-MSTN|79.8±0.2|94.5±0.5|98.0±0.4|94.2±0.4|79.2±0.3|97.3±0.3|90.5|CVPR|2020|[link](https://github.com/XJTU-XGU/RSDA)|[link](http://openaccess.thecvf.com/content_CVPR_2020/papers/Gu_Spherical_Space_Domain_Adaptation_With_Robust_Pseudo-Label_Loss_CVPR_2020_paper.pdf)|Spherical Space Domain Adaptation with Robust Pseudo-label Loss 
DWL|82.3|94.8|98.1|92.8|77.9|97.2|90.5|CVPR|2021|[link](https://github.com/NiXiao-cqu/TransferLearning-dwl-cvpr2021)|[link](https://openaccess.thecvf.com/content/CVPR2021/papers/Xiao_Dynamic_Weighted_Learning_for_Unsupervised_Domain_Adaptation_CVPR_2021_paper.pdf)|Dynamic Weighted Learning for Unsupervised Domain Adaptation
LAMDA|80.7|95|96.7|95|80.7|95.8|90.6|ICML|2021|-|[link](http://proceedings.mlr.press/v139/le21a/le21a.pdf)|LAMDA: Label Matching Deep Domain Adaptation 
|SRDC|80.8±0.3|94.7±0.2|97.8±0.2|94.1±0.2|80.0±0.3|97.7±0.1|90.9|CVPR|2020|[link](https://github.com/huitangtang/SRDC-CVPR2020)|[link](https://openaccess.thecvf.com/content_CVPR_2020/papers/Tang_Unsupervised_Domain_Adaptation_via_Structurally_Regularized_Deep_Clustering_CVPR_2020_paper.pdf)|Unsupervised Domain Adaptation via Structurally Regularized Deep Clustering
|E-MixNet|80.5±0.4|96.0±0.1|97.7±0.3|95.2±0.4|79.9±0.2|97.0±0.3|91.0|AAAI|2021|[link](https://github.com/zhonglii/E-MixNet)|[link](https://arxiv.org/pdf/2101.01104)|How does the Combined Risk Affect the Performance of Unsupervised Domain Adaptation Approaches? 

#### **CIFAR10 → STL**
> Type: **UDA**

Name|STL→CIFAR10|CIFAR10→STL|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
IEDA|62.3|78.3|AAAI|2020|[link](https://sites.google.com/site/jwchoivision/)|[link](https://ojs.aaai.org/index.php/AAAI/article/download/6692/6546)|Visual Domain Adaptation by Consensus-Based Transfer to Intermediate Domain
VADA|73.5|80.0|ICLR|2018|[link](https://github.com/RuiShu/dirt-t)|[link](https://arxiv.org/pdf/1802.08735)|A DIRT-T Approach to Unsupervised Domain Adaptation
DIRT-T |75.3|-|ICLR|2018|[link](https://github.com/RuiShu/dirt-t)|[link](https://arxiv.org/pdf/1802.08735)|A DIRT-T Approach to Unsupervised Domain Adaptation
RCA|77.76|81.65|ICCV|2019|-|[link](http://openaccess.thecvf.com/content_ICCV_2019/papers/Cicek_Unsupervised_Domain_Adaptation_via_Regularized_Conditional_Alignment_ICCV_2019_paper.pdf)|Unsupervised Domain Adaptation via Regularized Conditional Alignment 
SupSrc+TFA|59.37±0.58|75.18±0.76|ICLR|2018|[link](https://github.com/Britefury/self-ensemble-visual-domain-adapt)|[link](https://arxiv.org/pdf/1706.05208.pdf).)|Self-ensembling for Visual Domain Adaptation
MT+CT+TFA |69.86±1.97|80.09±0.31|ICLR|2018|[link](https://github.com/Britefury/self-ensemble-visual-domain-adapt)|[link](https://arxiv.org/pdf/1706.05208.pdf).)|Self-ensembling for Visual Domain Adaptation
DWT |71.18±0.56|79.75±0.25 |CVPR|2019|[link](https://github.com/roysubhankar/dwt-domain-adaptation)|[link](https://openaccess.thecvf.com/content_CVPR_2019/papers/Roy_Unsupervised_Domain_Adaptation_Using_Feature-Whitening_and_Consensus_Loss_CVPR_2019_paper.pdf)|Unsupervised Domain Adaptation using Feature-Whitening and Consensus Loss
SupTgt+TFA|90.44±0.38|70.03±1.13|ICLR|2018|[link](https://github.com/Britefury/self-ensemble-visual-domain-adapt)|[link](https://arxiv.org/pdf/1706.05208.pdf).)|Self-ensembling for Visual Domain Adaptation
LAMDA|78|71.6|-|[link](http://proceedings.mlr.press/v139/le21a/le21a.pdf)|LAMDA: Label Matching Deep Domain Adaptation 



#### **Office-Caltech**
* **UDA**

Name|BackBone|A->C|A->D|A->W|C->A|C->D|C->W|D->A|D->C|D->W|W->A|W->C|W->D|Avg|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
MCS|VGG-FC7|86.3|72.8|86.6|92.8|73|89.3|84.6|76.5|95.5|90.4|85.6|88.9|85.2|CVPR|2019|-|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Liang_Distant_Supervised_Centroid_Shift_A_Simple_and_Efficient_Approach_to_CVPR_2019_paper.pdf)|Distant Supervised Centroid Shift: A Simple and Effificient Approach to Visual Domain Adaptation
MCS|VGG-FC7|87.1|74.8|84.8|92.3|77.3|87.1|84.7|76|95.9|88.9|87.4|92.9|85.8|CVPR|2019|-|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Liang_Distant_Supervised_Centroid_Shift_A_Simple_and_Efficient_Approach_to_CVPR_2019_paper.pdf)|Distant Supervised Centroid Shift: A Simple and Effificient Approach to Visual Domain Adaptation
DPDA|ResNet50|87.6|91|96.4|91.9|92|93.9|89.1|79|96.1|93.1|86|98|91.2|IJCAI|2019|-|[link](https://pdfs.semanticscholar.org/77d7/a7b36abc7cd3cf0ef492183469abb0342cc1.pdf)|Differentially Private Optimal Transport: Application to Domain Adaptation 
CKB+MMD|ResNet50|87.5|93|89.8|93.3|91.7|92.9|92.3|83.4|99.7|92.8|85.8|100|91.9|CVPR|2021|-|[link](Conditional Bures Metric for Domain Adaptation)|Conditional Bures Metric for Domain Adaptation
RTN(mmd+ent)|ResNet50|88.1|95.5|95.2|93.7|94.2|96.9|93.8|84.6|99.2|92.5|86.6|100|93.4|NeurIPS|2016|-|[link](https://arxiv.org/pdf/1602.04433)|Unsupervised Domain Adaptation with Residual Transfer Networks

* **MSDA(Multi-Source Domain Adaptation)**

Name|BackBone|W|D|C|A|Avg|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
FADA+disentangle(III)|ResNet101|88.1±0.4|87.1±0.6|88.7±0.5|84.2±0.5|87.1|ICLR|2020|-|[link](https://arxiv.org/pdf/1911.02054)|Federated Adversarial Domain Adaptation
MOSDANET|ResNet50|99.2|98.9|90.6|94.8|95.8|ECCV|2020|-|[link](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123710732.pdf)|Multi-Source Open-Set Deep Adversaria Domain Adaptation
M<sup>3</sup>SDA-β|ResNet101|99.5|99.2|92.2|94.5|96.4|ICCV|2019|[link](https://github.com/xiechen0692/Moment-Matching-for-Multi-Source-Domain-Adaptation-M3SDA)|[link](https://openaccess.thecvf.com/content_ICCV_2019/papers/Peng_Moment_Matching_for_Multi-Source_Domain_Adaptation_ICCV_2019_paper.pdf)|Moment Matching for Multi-Source Domain Adaptation
CMSS |ResNet101|99.6|99.3|93.7|96.0|97.2|ECCV|2020|-|[link](https://arxiv.org/pdf/2007.01261)|Curriculum Manager for Source Selection in Multi-Source Domain Adaptation
SImpAl|ResNet50|99.3±0.1|99.8±0.1|92.2±0.1|95.3±0.2|96.7±0.1|NeurIPS|2020|-|[link](https://arxiv.org/pdf/2103.11169)|Your Classifier can Secretly Suffice Multi-Source Domain Adaptation
SImpAl|ResNet101|100.0±0.0|100.0±0.0|94.6±0.2|95.6±0.3|97.5±0.1|NeurIPS|2020|-|[link](https://arxiv.org/pdf/2103.11169)|Your Classifier can Secretly Suffice Multi-Source Domain Adaptation

#### **SynSign → GTSRB**
> Type: **UDA**

Name|Avg|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
DANN|88.66|ICML|2015|[link](https://github.com/shucunt/domain_adaptation)|[link](http://proceedings.mlr.press/v37/ganin15.pdf)|Unsupervised Domain Adaptation by Backpropagation
DSN w/MMD|92.6|NeurIPS|2016|[link](https://github.com/fungtion/DSN)|[link](https://arxiv.org/pdf/1608.06019)|Domain Separation Networks
DSN w/DANN |93.1|NeurIPS|2016|[link](https://github.com/fungtion/DSN)|[link](https://arxiv.org/pdf/1608.06019)|Domain Separation Networks
GPDA|96.19|CVPR|2019|[link](https://seqam-lab.github.io/GPDA/)|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Kim_Unsupervised_Visual_Domain_Adaptation_A_Deep_Max-Margin_Gaussian_Process_Approach_CVPR_2019_paper.pdf)|Unsupervised Visual Domain Adaptation: A Deep Max-Margin Gaussian Process Approach
SupSrc+TFA|98.02±0.20|ICLR|2018|[link](https://github.com/Britefury/self-ensemble-visual-domain-adapt)|[link](https://arxiv.org/pdf/1706.05208.pdf).)|Self-ensembling for Visual Domain Adaptation
VADA|99.2|ICLR|2018|[link](https://github.com/RuiShu/dirt-t)|[link](https://arxiv.org/pdf/1802.08735)|A DIRT-T Approach to Unsupervised Domain Adaptation
DIRT-T |99.6|ICLR|2018|[link](https://github.com/RuiShu/dirt-t)|[link](https://arxiv.org/pdf/1802.08735)|A DIRT-T Approach to Unsupervised Domain Adaptation
SupTgt+TFA|99.22±0.22|ICLR|2018|[link](https://github.com/Britefury/self-ensemble-visual-domain-adapt)|[link](https://arxiv.org/pdf/1706.05208.pdf).)|Self-ensembling for Visual Domain Adaptation
MT+CT+TFA |99.37±0.09|ICLR|2018|[link](https://github.com/Britefury/self-ensemble-visual-domain-adapt)|[link](https://arxiv.org/pdf/1706.05208.pdf).)|Self-ensembling for Visual Domain Adaptation
Method(Data Free)|99.6±0.1|CVPR|2020|-|[link](https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Model_Adaptation_Unsupervised_Domain_Adaptation_Without_Source_Data_CVPR_2020_paper.pdf)|Model Adaptation: Unsupervised Domain Adaptation without Source Data

#### Digit(MNIST，USPS，SVHN)
>Type: **UDA**
>Backbone: **LeNet**

|Name|S→M|M→U|U→M|Avg|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
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
CKB+MMD|-|96.6 ± 0.1|96.3±0.1|96.4|CVPR|2021|-|[link](Conditional Bures Metric for Domain Adaptation)|Conditional Bures Metric for Domain Adaptation
|GPDA|-|96.45±0.15|96.37±0.1|96.41|CVPR|2019|[link](https://github.com/seqam-lab/GPDA)|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Kim_Unsupervised_Visual_Domain_Adaptation_A_Deep_Max-Margin_Gaussian_Process_Approach_CVPR_2019_paper.pdf)|Unsupervised Visual Domain Adaptation:A Deep Max-Margin Gaussian Process Approach
|IEDA|98.9|95.0|97.5|97.1|AAAI|2020|[link](https://sites.google.com/site/jwchoivision/)|[link](https://ojs.aaai.org/index.php/AAAI/article/download/6692/6546)|Visual Domain Adaptation by Consensus-Based Transfer to Intermediate Domain
|DMRL|96.2|96.1|99.0|97.2|ECCV|2020|-|[link](https://arxiv.org/pdf/2007.03141)|Dual Mixup Regularized Learning for Adversarial Domain Adaptation 
|ACAL|96.61|98.31|97.16|97.36|ICLR|2019|-|[link](https://arxiv.org/pdf/1807.00374)|Augmented cyclic adversarial learning for low resource domain adaptation
ILA-DA(with CDAN)(ResNet-50)|92.30|94.87|97.47|94.88|CVPR|2021|[link](https://github.com/astuti/ILA-DA)|[link](https://openaccess.thecvf.com/content/CVPR2021/papers/Sharma_Instance_Level_Affinity-Based_Transfer_for_Unsupervised_Domain_Adaptation_CVPR_2021_paper.pdf)|Instance Level Affifinity-Based Transfer for Unsupervised Domain Adaptation
|ALDA|98.6±0.1|95.6±0.3|98.7±0.3|97.6|AAAI|2020|[link](https://github.com/ZJULearning/ALDA)|[link](https://ojs.aaai.org/index.php/AAAI/article/download/5757/5613)|Adversarial-Learned Loss for Domain Adaptation
DWL|98.1|97.3|97.4|97.6|CVPR|2021|[link](https://github.com/NiXiao-cqu/TransferLearning-dwl-cvpr2021)|[link](https://openaccess.thecvf.com/content/CVPR2021/papers/Xiao_Dynamic_Weighted_Learning_for_Unsupervised_Domain_Adaptation_CVPR_2021_paper.pdf)|Dynamic Weighted Learning for Unsupervised Domain Adaptation
|d-SNE|96.45±0.20|99.00±0.08|98.49±0.35|97.98|CVPR|2019|[link](https://github.com/aws-samples/d-SNE)|[link](https://openaccess.thecvf.com/content_CVPR_2019/papers/Xu_d-SNE_Domain_Adaptation_Using_Stochastic_Neighborhood_Embedding_CVPR_2019_paper.pdf)|d-SNE: Domain Adaptation using Stochastic Neighborhood Embedding
|STAFF|97.7|98.3|98.1|98.0|AAAI|2020|-|[link](https://ojs.aaai.org/index.php/AAAI/article/download/6629/6483)|Structure-Aware Feature Fusion for Unsupervised Domain Adaptation
|RWOT|98.8±0.1|98.5±0.2|97.5±0.2|98.30|CVPR|2020|-|[link](https://openaccess.thecvf.com/content_CVPR_2020/papers/Xu_Reliable_Weighted_Optimal_Transport_for_Unsupervised_Domain_Adaptation_CVPR_2020_paper.pdf)|Reliable Weighted Optimal Transport for Unsupervised Domain Adaptation
|SHOT|98.9±0.0|98.0±0.2|98.4±0.6|98.4|ICML|2020|[link](https://github.com/tim-learn/SHOT)|[link](http://proceedings.mlr.press/v119/liang20a/liang20a.pdf)|Do We Really Need to Access the Source Data? Source Hypothesis Transfer for Unsupervised Domain Adaptation
|DWT-MEC|97.80±0.07|99.01±0.06|99.02±0.05|98.61|CVPR|2019|[link](https://github.com/roysubhankar/dwt-domain-adaptation)|[link](https://openaccess.thecvf.com/content_CVPR_2019/papers/Roy_Unsupervised_Domain_Adaptation_Using_Feature-Whitening_and_Consensus_Loss_CVPR_2019_paper.pdf)|Unsupervised Domain Adaptation using Feature-Whitening and Consensus Loss
|KHoMM|99.0±0.0|-|99.2±0.0|99.1|AAAI|2020|[link](https://github.com/chenchao666/HoMM-Master)|[link](https://ojs.aaai.org/index.php/AAAI/article/download/5745/5601)|HoMM: Higher-order Moment Matching for Unsupervised Domain Adaptation

#### **Digit-Five(MNIST，MNIST-M，Synth Digit，SVHN，USPS)**
* **MSDA**

Name|MNIST-M|MNIST|SVHN|Synth Digit|USPS|Avg|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
FADA+disentangle(III)|62.5±0.7|91.4±0.7|50.5±0.3|71.8±0.5|91.7±1.0|73.6|ICLR|2020|-|[link](https://arxiv.org/pdf/1911.02054)|Federated Adversarial Domain Adaptation
MDDA|78.6|98.8|79.3|89.7|93.9|88.1|AAAI|2020|[link](https://github.com/daoyuan98/MDDA)|[link](https://ojs.aaai.org/index.php/AAAI/article/view/6997/6851)|Multi-Source Distilling Domain Adaptation
TAR|94.66±0.10|99.02±0.02|87.40±0.17|96.90±0.09|-|94.49±0.07|ICML|2020|-|[link](http://proceedings.mlr.press/v119/wen20b/wen20b.pdf)|Domain Aggregation Networks for Multi-Source Domain Adaptation

* **UDA**

Name|MNIST→MNIST-M|Synth Digit →SVHN|SVHN→MNIST|USPS→MNIST|MNIST→USPS|Synth Digit→MNIST|Avg|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
DSN w/ MMD|80.5|88.5|72.2|-|-|-|-|NeurIPS|2016|[link](https://github.com/fungtion/DSN)|[link](https://arxiv.org/pdf/1608.06019)|Domain Separation Networks 
DSN w/ DANN|83.2|91.2|82.7|-|-|-|-|NeurIPS|2016|[link](https://github.com/fungtion/DSN)|[link](https://arxiv.org/pdf/1608.06019)|Domain Separation Networks 
DANN|81.49|90.48|71.07|-|-|-|-|ICML|2015|[link](https://github.com/wogong/pytorch-dann)|[link](https://arxiv.org/pdf/1409.7495)|Unsupervised Domain Adaptation by Backpropagation 
CLARINET |71.717±1.262 |84.499±0.537|63.070±1.990|83.692±0.928|94.538±0.292 |97.040±0.212|82.426|IJCAI|2020|[link](https://github.com/Yiyang98/BFUDA)|[link](https://arxiv.org/pdf/2007.14612)|Clarinet: A One-step Approach Towards Budget-friendly Unsupervised Domain Adaptation
DRANet|98.7|-|-|97.8|-|-|-|CVPR|2021|-|[link](https://openaccess.thecvf.com/content/CVPR2021/papers/Lee_DRANet_Disentangling_Representation_and_Adaptation_Networks_for_Unsupervised_Cross-Domain_Adaptation_CVPR_2021_paper.pdf)|DRANet: Disentangling Representation and Adaptation Networks for Unsupervised Cross-Domain Adaptation
LAMDA|98.4|-|99.5|98.3|99.5|-|-|ICML|2021|-|[link](http://proceedings.mlr.press/v139/le21a/le21a.pdf)|LAMDA: Label Matching Deep Domain Adaptation




#### **ImageNet-Caltech**
Name|Tpye|I→C|C→I|Avg|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
USFDA|Universal DA,Source-Free|51.21|48.76|49.99|CVPR|2020|[link](https://github.com/val-iisc/USFDA)|[link](http://openaccess.thecvf.com/content_CVPR_2020/papers/Kundu_Universal_Source-Free_Domain_Adaptation_CVPR_2020_paper.pdf)|Universal Source-Free Domain Adaptation
UAN|Universal DA|75.28|70.17|72.73|CVPR|2019|[link](https://github.com/thuml/Universal-Domain-Adaptation)|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/You_Universal_Domain_Adaptation_CVPR_2019_paper.pdf)|Universal Domain Adaptation 
ASSA|Universal DA|76.13|74.67|75.40|AAAI|2021|-|[link](https://arxiv.org/pdf/2001.05071)|A Sample Selection Approach for Universal Domain Adaptation
FRODA|ODA|79.9±1.7|74.5±1.7|77.2|ICLR|2019|-|[link](https://arxiv.org/pdf/1805.12277)|Learning Factorized Representations for Open-Set Domain Adaptation
D-FRODA|ODA|80.5±1.6|75.0±1.8|77.8|ICLR|2019|-|[link](https://arxiv.org/pdf/1805.12277)|Learning Factorized Representations for Open-Set Domain Adaptation
BA<sup>3</sup>US|PDA|84.00±0.15|83,35±0.28|83.68|ECCV|2020|[link](https://github.com/tim-learn/BA3US)|[link](https://arxiv.org/pdf/2003.02541)|A Balanced and Uncertainty-aware Approach for Partial Domain Adaptation 
RWOT|UDA|97.9±0.1 |92.7±0.2 |95.3|CVPR|2020|-|[link](https://openaccess.thecvf.com/content_CVPR_2020/papers/Xu_Reliable_Weighted_Optimal_Transport_for_Unsupervised_Domain_Adaptation_CVPR_2020_paper.pdf)|Reliable Weighted Optimal Transport for Unsupervised Domain Adaptation
ETN|PDA|83.23±0.24|74.93±0.28|79.08±0.26|CVPR|2019|[link](https://github.com/thuml/ETN)|[link](https://openaccess.thecvf.com/content_CVPR_2019/papers/Cao_Learning_to_Transfer_Examples_for_Partial_Domain_Adaptation_CVPR_2019_paper.pdf)|Learning to Transfer Examples for Partial Domain Adaptation

#### **BCIS(Bing，Caltech，ImageNet，SUN)**
* **ODA**

Name|B→C|B→I|B→S|C→B|C→I|C→S|I→B|I→C|I→S|S→B|S→C|S→I|Avg|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
FRODA|73.8±6.1|71.0±2.0|54.7±2.9|67.5±1.4|74.5±1.7|61.6±2.2|66.0±1.9|79.9±1.7|59.2±2.1|55.7±2.5|61.2±1.8|59.4±1.9|65.4±2.3|ICLR|2019|-|[link](https://arxiv.org/pdf/1805.12277)|Learning Factorized Representations for Open-Set Domain Adaptation
D-FRODA|74.6±5.5|71.4±2.0|55.4±1.1|67.6±1.2|75.0±1.8|61.7±2.1|66.4±1.7|80.5±1.6|59.8±2.0|55.5±2.4|61.2±1.9|59.6±2.2|65.7±2.2|ICLR|2019|-|[link](https://arxiv.org/pdf/1805.12277)|Learning Factorized Representations for Open-Set Domain Adaptation

* **RDA**

Name|B→C|B→I|B→S|C→B|C→I|C→S|I→B|I→C|I→S|S→B|S→C|S→I|Avg|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
RDA|81.7|-|-|-|-|-|-|-|-|-|-|-|-|IJCAI|2020|-|[link](https://arxiv.org/pdf/2004.12529)|Towards Accurate and Robust Domain Adaptation under Noisy Environments 

#### **DomainNet**
* **MSDA**

Name|Backbone|i,p,q,r,s→c|c,p,q,r,s→i|c,i,q,r,s→p|c,i,p,r,s→q|c,i,p,q,s→r|c,i,p,q,r→s|Avg|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
FADA+disentangle|AlexNet|45.3±0.7|16.3±0.8|38.9±0.7|7.9±0.4|46.7±0.4|26.8±0.4|30.3|ICLR|2020|-|[link](https://arxiv.org/pdf/1911.02054)|Federated Adversarial Domaine Adaptation
LtC-MSDA|GCN|63.1±0.5|28.7±0.7|56.1±0.5|16.3±0.5|66.1±0.6|53.8±0.6|47.4|ECCV|2020|[link](https://github.com/ChrisAllenMing/LtC-MSDA)|[link](https://arxiv.org/pdf/2007.08801)|Learning to Combine: Knowledge Aggregation for Multi-Source Domain Adaptation 
MCC|ResNet101|65.5|26|56.6|16.5|68|52.7|47.6|ECCV|2020|[link](https://github.com/thuml/Versatile-Domain-Adaptation)|[link](https://arxiv.org/pdf/1912.03699)|Minimum Class Confusion for Versatile Domain Adaptation
M<sup>3</sup>SDA*|AlexNet|57.0±0.79|22.1±0.68|50.5±0.45|4.4±0.21|62.0±0.45|48.5±0.56|40.8±0.52|ICCV|2019|[link](http://ai.bu.edu/M3SDA/ )|[link](https://openaccess.thecvf.com/content_ICCV_2019/papers/Peng_Moment_Matching_for_Multi-Source_Domain_Adaptation_ICCV_2019_paper.pdf)|Moment Matching for Multi-Source Domain Adaptation
Meta-MCD|ResNet18|58.38+=0.21|19.09±0.08|47.63±0.12|13.70±0.14|61.30±0.18|45.90±0.18|41.00±0.05|ECCV|2020|-|[link](https://arxiv.org/pdf/2004.04398)|Online Meta-Learning for Multi-Source and Semi-Supervised Domain Adaptation
M<sup>3</sup>SDA|AlexNet|57.2±0.98|24.2±1.21|51.6±0.44|5.2±0.45|61.6±0.89|49.6±0.56|41.5±0.74|ICCV|2019|[link](http://ai.bu.edu/M3SDA/ )|[link](https://arxiv.org/pdf/2004.04398)|Moment Matching for Multi-Source Domain Adaptation
M<sup>3</sup>SDA-beta|AlexNet|58.6±0.53|26.0±0.89|52.3±0.55|6.3±0.58|62.7±0.51|49.5±0.76|42.6±0.64|ICCV|2019|[link](http://ai.bu.edu/M3SDA/ )|[link](https://arxiv.org/pdf/2004.04398)|Moment Matching for Multi-Source Domain Adaptation
Meta-MCD|ResNet34|62.81±0.22|21.37±0.07|50.53±0.08|15.47±0.22|64.58±0.16|50.40±0.12|44.19±0.07|ECCV|2020|-|[link](https://arxiv.org/pdf/2004.04398)|Online Meta-Learning for Multi-Source and Semi-Supervised Domain Adaptation
CMSS|ResNet18|64.2±0.18|28.0±0.20|53.6±0.39|16.0±0.12|63.4±0.21|53.8±0.35|46.5±0.24|ECCV|2020|-|[link](https://arxiv.org/pdf/2007.01261)|Curriculum Manager for Source Selection in Multi-Source Domain Adaptation
HDAN|ResNet101|63.6±0.35|25.9±0.16|56.1±0.38|16.6±0.54|69.1±0.42|54.3±0.26|47.6±0.40|NeurIPS|2020|[link](https://github.com/cuishuhao/HAD)|[link](https://arxiv.org/pdf/2011.14540)|Heuristic Domain Adaptation 
SImpAI101|ResNet101|66.4±0.8|26.5±0.5|56.6±0.7|18.9±0.8|68.0±0.5|55.5±0.3|48.6±0.6|NeurIPS|2020|-|[link](https://arxiv.org/pdf/2103.11169)|Your Classifier can Secretly Suffice Multi-Source Domain Adaptation


* **MTDA**

Name|Backbone|i,p,q,r,s→c|c,p,q,r,s→i|c,i,q,r,s→p|c,i,p,r,s→q|c,i,p,q,s→r|c,i,p,q,r→s|Avg|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
MCC|ResNet101|33.6|30|32.4|13.5|28|35.3|28.8|ECCV|2020|[link](https://github.com/thuml/Versatile-Domain-Adaptation)|[link](https://arxiv.org/pdf/1912.03699)|Minimum Class Confusion for Versatile Domain Adaptation

* **Semi-supervised DA**

Name|Backbone|R→C|R→P|P→C|C→S|S→P|R→S|P→R|Avg|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
Meta-MME(AlexNet)||56.4|50.2|51.9|39.6|43.7|38.7|60.7|48.8||ECCV|2020|-|Online Meta-Learning for Multi-Source and Semi-Supervised Domain Adaptation
Meta-MME(ResNet34)||73.5|70.3|72.8|62.8|68.0|63.8|79.2|70.1||ECCV|2020|-|Online Meta-Learning for Multi-Source and Semi-Supervised Domain Adaptation

* **PDA**

Name|Backbone|DomainNet→VisDa|DomainNet→Ytb Bbox|DomainNet→PASCAL|DomainNet→COCO|Avg|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
Domain2Vec|UnKnown|36.6±0.5|76.8±0.4|70.0±0.3|78.8±0.4|65.5|ECCV|2020|[link](https://github.com/VisionLearningGroup/Domain2Vec)|[link](https://arxiv.org/pdf/2007.09257)|Domain2Vec: Domain Embedding for Unsupervised Domain Adaptation 

* **Universal DA**

Name|Backbone|P→R|R→P|P→S|S→P|R→S|S→R|Avg|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
CMU|ResNet50|50.78|52.16|45.12|44.82|45.64|50.97|48.25|ECCV|2020|[link](https://github.com/thuml/Calibrated-Multiple-Uncertainties)|[link](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123600562.pdf)|Learning to Detect Open Classes for Universal Domain Adaptation

* **1-shot**

Name|Backbone|R→C|R→P|P→C|C→S|S→P|R→S|P→R|Avg|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
Method|AlexNet|47.7|49.0|46.9|38.5|38.5|33.8|57.5|44.6|ECCV|2020|[link](https://github.com/TKKim93/APE)|[link](https://arxiv.org/pdf/2007.09375)|Attract, Perturb, and Explore: Learning a Feature Alignment Network for Semi-supervised Domain Adaptation
MME|AlexNet|48.9|48.0|46.7|36.3|39.4|33.3|56.8|44.2|ICCV|2019|[link](https://github.com/VisionLearningGroup/SSDA_MME)|[link](https://openaccess.thecvf.com/content_ICCV_2019/papers/Saito_Semi-Supervised_Domain_Adaptation_via_Minimax_Entropy_ICCV_2019_paper.pdf)|Semi-supervised domain adaptation via minimax entropy.
BiAT|AlexNet|54.2|49.2|44.0|37.7|39.6|37.2|56.9|45.5|IJCAI|2020|-|[link](https://www.ijcai.org/Proceedings/2020/0130.pdf)|Bidirectional Adversarial Training for Semi-Supervised Domain Adaptation 
MME|VGG|60.6|63.3|57.0|50.9|60.5|50.2|72.2|59.2|ICCV|2019|[link](https://github.com/VisionLearningGroup/SSDA_MME)|[link](https://openaccess.thecvf.com/content_ICCV_2019/papers/Saito_Semi-Supervised_Domain_Adaptation_via_Minimax_Entropy_ICCV_2019_paper.pdf)|Semi-supervised domain adaptation via minimax entropy.
MME|ResNet34|70.0|67.7|69.0|56.3|64.8|61.0|76.1|66.4|ICCV|2019|[link](https://github.com/VisionLearningGroup/SSDA_MME)|[link](https://openaccess.thecvf.com/content_ICCV_2019/papers/Saito_Semi-Supervised_Domain_Adaptation_via_Minimax_Entropy_ICCV_2019_paper.pdf)|Semi-supervised domain adaptation via minimax entropy.
BiAT|ResNet34|73.0|68.0|71.6|57.9|63.9|58.5|77.0|67.1|IJCAI|2020|-|[link](https://www.ijcai.org/Proceedings/2020/0130.pdf)|Bidirectional Adversarial Training for Semi-Supervised Domain Adaptation 
Method|ResNet34|70.4|7-.8|72.9|56.7|64.5|63.0|76.6|67.6|ECCV|2020|[link](https://github.com/TKKim93/APE)|[link](https://arxiv.org/pdf/2007.09375)|Attract, Perturb, and Explore: Learning a Feature Alignment Network for Semi-supervised Domain Adaptation
HDAN|ResNet34|71.7|67.1|72.8|63.7|65.7|69.2|76.6|69.5|NeurIPS|2020|[link](https://github.com/cuishuhao/HAD)|[link](https://arxiv.org/pdf/2011.14540)|Heuristic Domain Adaptation 

* **3-shot**

Name|Backbone|R→C|R→P|P→C|C→S|S→P|R→S|P→R|Avg|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
MME|AlexNet|55.6|49.0|51.7|39.4|43.0|37.9|60.7|48.2|ICCV|2019|[link](https://github.com/VisionLearningGroup/SSDA_MME)|[link](https://openaccess.thecvf.com/content_ICCV_2019/papers/Saito_Semi-Supervised_Domain_Adaptation_via_Minimax_Entropy_ICCV_2019_paper.pdf)|Semi-supervised domain adaptation via minimax entropy.
Method|AlexNet|54.6|50.5|52.1|42.6|42.2|38.7|61.4|48.9|ECCV|2020|[link](https://github.com/TKKim93/APE)|[link](https://arxiv.org/pdf/2007.09375)|Attract, Perturb, and Explore: Learning a Feature Alignment Network for Semi-supervised Domain Adaptation
BiAT|AlexNet|58.6|50.6|52.0|41.9|42.1|42.0|58.8|49.4|IJCAI|2020|-|[link](https://www.ijcai.org/Proceedings/2020/0130.pdf)|Bidirectional Adversarial Training for Semi-Supervised Domain Adaptation 
MME|VGG|64.1|63.5|60.7|55.4|60.9|54.8|75.3|62.1|ICCV|2019|[link](https://github.com/VisionLearningGroup/SSDA_MME)|[link](https://openaccess.thecvf.com/content_ICCV_2019/papers/Saito_Semi-Supervised_Domain_Adaptation_via_Minimax_Entropy_ICCV_2019_paper.pdf)|Semi-supervised domain adaptation via minimax entropy.
MME|ResNet34|72.2|69.7|71.7|61.8|66.8|61.9|78.5|68.9|ICCV|2019|[link](https://github.com/VisionLearningGroup/SSDA_MME)|[link](https://openaccess.thecvf.com/content_ICCV_2019/papers/Saito_Semi-Supervised_Domain_Adaptation_via_Minimax_Entropy_ICCV_2019_paper.pdf)|Semi-supervised domain adaptation via minimax entropy.
BiAT|ResNet34|74.9|68.8|74.6|61.5|67.5|62.1|78.6|69.7|IJCAI|2020|-|[link](https://www.ijcai.org/Proceedings/2020/0130.pdf)|Bidirectional Adversarial Training for Semi-Supervised Domain Adaptation 
HDAN|ResNet34|73.9|69.1|73.0|66.3|67.5|69.5|79.7|71.3|NeurIPS|2020|[link](https://github.com/cuishuhao/HAD)|[link](https://arxiv.org/pdf/2011.14540)|Heuristic Domain Adaptation 
Method|ResNet34|76.6|72.1|76.7|63.1|66.1|67.8|79.4|71.7|ECCV|2020|[link](https://github.com/TKKim93/APE)|[link](https://arxiv.org/pdf/2007.09375)|Attract, Perturb, and Explore: Learning a Feature Alignment Network for Semi-supervised Domain Adaptation

* **UDA: Part Domains**

Name|Backbone|R→C|R→P|P→C|C→S|S→P|R→S|P→R|Avg|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
MME||47.6|44.7|39.9|34.0|33.0|29.0|53.5|40.2|ICCV|2019|[link](https://github.com/VisionLearningGroup/SSDA_MME)|[link](https://openaccess.thecvf.com/content_ICCV_2019/papers/Saito_Semi-Supervised_Domain_Adaptation_via_Minimax_Entropy_ICCV_2019_paper.pdf)|Semi-supervised domain adaptation via minimax entropy.

* **UDA: All Domains**

Name: *BCDM*

1. ResNet50

||clipart|infograph|painting|quickdraw|real|sketch|Avg
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
clipart|-|17.2|35.2|10.6|50.1|40.0|30.6
infograph|29.3|-|29.4|3.8|41.3|25.0|25.8
painting|39.2|17.7|-|4.8|51.2|34.9|29.6
quickdraw|19.4|2.6|7.2|-|13.6|12.8|11.1
real|48.2|21.5|48.3|5.4|-|36.7|32.0
sketch|50.6|17.3|41.9|10.6|49.0|-|33.9
avg|37.3|15.3|32.4|7.0|41.0|29.9|27.2

2. ResNet101

||clipart|infograph|painting|quickdraw|real|sketch|Avg|
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
clipart|-|19.9|38.5|15.1|53.2|43.9|34.1
infograph|31.9|-|32.7|6.9|44.7|28.5|28.9
painting|42.5|19.8|-|7.9|54.5|38.5|32.6
quickdraw|23.0|4.0|9.5|-|16.9|16.2|13.9
real|51.9|24.9|51.2|8.7|-|40.6|35.5
sketch|53.7|20.5|46.0|13.1|53.4|-|37.1
avg|40.6|17.8|35.6|10.3|44.3|33.5|30.4

### 2.1.2 Segmentation UDA
#### **GTA5 → Cityscapes**
Name|Backbone|road|sidewalk|buiding|wall|fence|pole|light|sign|veg|terrain|sky|person|rider|car|truck|bus|train|motor|bike|mIoU|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
MCD<sub>DA</sub>|VGG16|86.4|8.5|76.1|18.6|9.7|14.9|7.8|0.6|82.8|32.7|71.4|25.2|1.1|76.3|16.1|17.1|1.4|0.2|0.0|28.8|CVPR|2018|[link](https://github.com/miltokyo/MCD_DA)|[link](http://openaccess.thecvf.com/content_cvpr_2018/papers/Saito_Maximum_Classifier_Discrepancy_CVPR_2018_paper.pdf)|Maximum Classififier Discrepancy for Unsupervised Domain Adaptation
ADVENT(MinEnt)|VGG16|85.1|18.9|76.3|32.4|19.7|19.9|21.0|8.9|76.3|26.2|63.1|42.8|5.9|80.8|20.2|9.8|0.0|14.8|0.6|32.8|CVPR|2019|[link](https://github.com/arshinova/domain_adaptation)|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Vu_ADVENT_Adversarial_Entropy_Minimization_for_Domain_Adaptation_in_Semantic_Segmentation_CVPR_2019_paper.pdf)|ADVENT: Adversarial Entropy Minimization for Domain Adaptation in Semantic Segmentation
CRST(MRKLD)+TPLD|VGG16|83.5|49.9|72.3|17.6|10.7|29.6|28.3|9.0|78.2|20.1|25.7|47.4|13.3|79.6|3.3|19.3|1.3|14.3|33.5|34.1|ECCV|2020|-|[link](https://arxiv.org/pdf/2012.04828)|Two-phase Pseudo Label Densification for Self-training based Domain Adaptation
DTA|ResNet50|88.8|36.9|76.9|20.9|15.4|19.6|21.8|7.9|82.9|26.7|76.1|51.7|9.4|76.1|22.4|28.9|1.7|15.2|0.0|35.8|ICCV|2019|[link](https://github.com/postBG/DTA.pytorch)|[link](https://openaccess.thecvf.com/content_ICCV_2019/papers/Lee_Drop_to_Adapt_Learning_Discriminative_Features_for_Unsupervised_Domain_Adaptation_ICCV_2019_paper.pdf)|Drop to Adapt:Learning Discriminative Features for Unsupervised Domain Adaptation
ADVENT(AdvEnt)|VGG16|86.9|28.7|78.7|28.5|25.2|17.1|20.3|10.9|80.0|26.4|70.2|47.1|8.4|81.5|26.0|17.2|18.9|11.7|1.6|36.1|CVPR|2019|[link](https://github.com/arshinova/domain_adaptation)|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Vu_ADVENT_Adversarial_Entropy_Minimization_for_Domain_Adaptation_in_Semantic_Segmentation_CVPR_2019_paper.pdf)|ADVENT: Adversarial Entropy Minimization for Domain Adaptation in Semantic Segmentation
CLAN|VGG16|88.0|30.6|79.2|23.4|20.5|26.1|23.0|14.8|81.6|34.5|72.0|45.8|7.9|80.5|26.6|29.9|0.0|10.7|0.0|36.6|CVPR|2019|[link](https://github.com/RoyalVane/CLAN)|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Luo_Taking_a_Closer_Look_at_Domain_Shift_Category-Level_Adversaries_for_CVPR_2019_paper.pdf)|Taking A Closer Look at Domain Shift: Category-level Adversaries for Semantics Consistent Domain Adaptation
Adapt-Seg|VGG16|87.3|35.7|79.5|32.0|14.5|21.5|24.8|13.7|80.4|32.0|70.5|50.5|16.9|81.0|20.8|28.1|4.1|15.5|4.1|37.5|ICCV|2019|-|[link](https://openaccess.thecvf.com/content_ICCV_2019/papers/Tsai_Domain_Adaptation_for_Structured_Output_via_Discriminative_Patch_Representations_ICCV_2019_paper.pdf)|Domain Adaptation for Structured Output via Discriminative Patch Representations
Method|VGG16|88.4|34.2|77.6|23.7|18.3|24.8|24.9|12.4|80.7|30.4|68.6|48.9|17.9|80.8|27.0|27.2|6.2|19.1|10.2|38.0|AAAI|2020|-|[link](https://ojs.aaai.org/index.php/AAAI/article/download/6952/6806)|An Adversarial Perturbation Oriented Domain Adaptation Approach for Semantic Segmentation
LSE+FL|VGG16|86.0|26.0|76.7|33.1|13.2|21.8|30.1|16.5|78.8|25.8|74.7|50.6|18.7|81.8|22.5|30.5|12.3|16.9|25.4|39.0|ECCV|2020|-|[link](https://arxiv.org/pdf/2007.14449)|Learning from Scale-Invariant Examples for Domain Adaptation in Semantic Segmentation
CrCDA|VGG16|86.8|37.5|80.4|30.7|18.1|26.8|25.3|15.1|81.5|30.9|72.1|52.8|19.0|82.1|25.4|29.2|10.1|15.8|3.7|39.1|ECCV|2020|[link](https://github.com/jxhuang0508/CrCDA)|[link](https://arxiv.org/pdf/2007.02424)|Contextual-Relation Consistent Domain Adaptation for Semantic Segmentation
BDL|VGG16|89.2|40.9|81.2|29.1|19.2|14.2|29.0|19.6|83.7|35.9|80.7|54.7|23.3|82.7|25.8|28.0|2.3|25.7|19.9|41.3|CVPR|2019|[link](https://github.com/liyunsheng13/Bidirectional-Learning-for-Domain-Adaptation-of-Semantic-Segmentation)|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Li_Bidirectional_Learning_for_Domain_Adaptation_of_Semantic_Segmentation_CVPR_2019_paper.pdf)|Bidirectional Learning for Domain Adaptation of Semantic Segmentation
FDA-MBT|VGG16|86.1|35.1|80.6|30.8|20.4|27.5|30.0|26.0|82.1|30.3|73.6|52.5|21.7|81.7|24.0|30.5|29.9|14.6|24.0|42.2|CVPR|2020|[link](https://github.com/YanchaoYang/FDA )|[link](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yang_FDA_Fourier_Domain_Adaptation_for_Semantic_Segmentation_CVPR_2020_paper.pdf)|FDA: Fourier Domain Adaptation for Semantic Segmentation
TIR|VGG16|92.5|54.5|83.9|34.5|25.5|31.0|30.4|18.0|84.1|39.6|83.9|53.6|19.3|81.7|21.1|13.6|17.7|12.3|6.5|42.3|CVPR|2020|[link](https://github.com/MyeongJin-Kim/Learning-Texture-Invariant-Representation)|[link](https://openaccess.thecvf.com/content_CVPR_2020/papers/Kim_Learning_Texture_Invariant_Representation_for_Domain_Adaptation_of_Semantic_Segmentation_CVPR_2020_paper.pdf)|Learning Texture Invariant Representation for Domain Adaptation of Semantic Segmentation
DTST|VGG16|88.1|35.8|83.1|25.8|23.9|29.2|28.8|28.6|83.0|36.7|82.3|53.7|22.8|82.3|26.4|38.6|0.0|19.6|17.1|42.4|CVPR|2020|[link](https://github.com/SHI-Labs/Unsupervised-Domain-Adaptation-with-Differential-Treatment)|[link](http://openaccess.thecvf.com/content_CVPR_2020/papers/Wang_Differential_Treatment_for_Stuff_and_Things_A_Simple_Unsupervised_Domain_CVPR_2020_paper.pdf)|Differential Treatment for Stuff and Things:A Simple Unsupervised Domain Adaptation Method for Semantic Segmentation 
TGCF+SE|VGG16|90.2|51.5|81.1|15.0|10.7|37.5|35.2|28.9|84.1|32.7|75.9|62.7|19.9|82.6|22.9|28.3|0.0|23.0|25.4|42.5|CVPR|2019|-|[link](https://openaccess.thecvf.com/content_ICCV_2019/papers/Choi_Self-Ensembling_With_GAN-Based_Data_Augmentation_for_Domain_Adaptation_in_Semantic_ICCV_2019_paper.pdf)|Self-Ensembling with GAN-based Data Augmentation for Domain Adaptation in Semantic Segmentation
CLAN|ResNet101|87.0|27.1|79.6|27.3|23.3|28.3|35.5|24.2|83.6|27.4|74.2|58.6|28.0|76.2|33.1|36.7|6.7|31.9|31.4|43.2|CVPR|2019|[link](https://github.com/RoyalVane/CLAN)|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Luo_Taking_a_Closer_Look_at_Domain_Shift_Category-Level_Adversaries_for_CVPR_2019_paper.pdf)|Taking A Closer Look at Domain Shift: Category-level Adversaries for Semantics Consistent Domain Adaptation
BiSIDA|VGG16|89.3|40.9|82.5|30.9|24.7|20.9|26.9|32.1|81.8|33.1|81.6|53.4|20.3|83.0|24.8|29.4|0.0|28.6|36.6|43.2|AAAI|2021|[link](https://github.com/wangkaihong/BiSIDA)|[link](https://arxiv.org/pdf/2009.08610)|Consistency Regularization with High-dimensional Non-adversarial Source-guided Perturbation for Unsupervised Domain Adaptation in Segmentation
STAR|ResNet101|88.4|27.9|80.8|27.3|25.6|26.9|31.6|20.8|83.5|34.1|76.6|60.5|27.2|84.2|32.9|38.2|1.0|30.2|31.2|43.6|CVPR|2020|-|[link](https://openaccess.thecvf.com/content_CVPR_2020/papers/Lu_Stochastic_Classifiers_for_Unsupervised_Domain_Adaptation_CVPR_2020_paper.pdf)|Stochastic Classififiers for Unsupervised Domain Adaptation
LDRDA|VGG16|90.1|41.2|82.2|30.3|21.3|18.3|33.5|23.0|84.1|37.5|81.4|54.2|24.3|83.0|27.6|32.0|8.1|29.7|26.9|43.6|ECCV|2020|-|[link](https://arxiv.org/pdf/2003.04614)|Label-Driven Reconstruction for Domain Adaptation in Semantic Segmentation
DAST|VGG16|90.5|49.2|81.9|34.0|27.0|26.5|26.6|21.5|83.0|37.3|76.3|52.0|23.1|83.5|29.9|42.0|12.1|19.8|25.8|44.3|AAAI|2021|[link](https://github.com/yufei1900/DAST_segmentation)|[link](http://bicmr.pku.edu.cn/~dongbin/Publications/DAST-AAAI2020.pdf)|DAST: Unsupervised Domain Adaptation in Semantic Segmentation Based on Discriminator Attention and Self-Training
ASM|ResNet101 one-shot|86.2|35.2|81.4|24.2|25.5|31.5|31.5|21.9|82.9|30.5|80.1|57.3|22.9|85.3|43.7|44.9|0.0|26.5|34.9|44.5|NeurIPS|2020|[link](https://github.com/RoyalVane/ASM)|[link](https://arxiv.org/pdf/2004.06042)|Adversarial Style Mining for One-Shot Unsupervised Domain Adaptation
PCEDA|VGG16|90.2|44.7|82.0|28.4|28.4|24.4|33.7|35.6|83.7|40.5|75.1|54.4|28.2|80.3|23.8|39.4|0.0|22.8|30.8|44.6|CVPR|2020|[link](https://github.com/donglao/PCEDA )|[link](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yang_Phase_Consistent_Ecological_Domain_Adaptation_CVPR_2020_paper.pdf)|Phase Consistent Ecological Domain Adaptation 
FDA-ENT|ResNet101|90.8|42.7|80.8|28.1|26.6|31.8|32.8|29.1|81.6|31.2|76.2|56.9|27.7|82.8|25.3|44.1|15.3|21.1|30.2|45.0|CVPR|2020|[link](https://github.com/YanchaoYang/FDA )|[link](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yang_FDA_Fourier_Domain_Adaptation_for_Semantic_Segmentation_CVPR_2020_paper.pdf)|FDA: Fourier Domain Adaptation for Semantic Segmentation
SSF-DAN|ResNet101|90.3|38.9|81.7|24.8|22.9|30.5|37.0|21.2|84.8|38.8|76.9|58.8|30.7|85.7|30.6|38.1|5.9|28.3|36.9|45.4|ICCV|2019|-|[link](https://openaccess.thecvf.com/content_ICCV_2019/papers/Du_SSF-DAN_Separated_Semantic_Feature_Based_Domain_Adaptation_Network_for_Semantic_ICCV_2019_paper.pdf)|SSF-DAN: Separated Semantic Feature based Domain Adaptation Network for Semantic Segmentation
ASM|ResNet101|89.8|38.2|77.8|25.5|28.6|24.9|31.2|24.5|83.1|36.0|82.3|55.7|28.0|84.5|45.9|44.7|5.3|26.4|31.3|45.5|NeurIPS|2020|[link](https://github.com/RoyalVane/ASM)|[link](https://arxiv.org/pdf/2004.06042)|Adversarial Style Mining for One-Shot Unsupervised Domain Adaptation
ADVENT(AdvEnt+MinEnt)|ResNet101|89.4|33.1|81.0|26.6|26.8|27.2|33.5|24.7|83.9|36.7|78.8|58.7|30.5|84.8|38.5|44.5|1.7|31.6|32.4|45.5|CVPR|2019|[link](https://github.com/arshinova/domain_adaptation)|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Vu_ADVENT_Adversarial_Entropy_Minimization_for_Domain_Adaptation_in_Semantic_Segmentation_CVPR_2019_paper.pdf)|ADVENT: Adversarial Entropy Minimization for Domain Adaptation in Semantic Segmentation
Method|ResNet101|85.6|32.8|79.0|29.5|25.5|26.8|34.6|19.9|83.7|40.6|77.9|59.2|28.3|84.6|34.6|49.2|8.0|32.6|39.6|45.9|AAAI|2020|-|[link](https://ojs.aaai.org/index.php/AAAI/article/download/6952/6806)|An Adversarial Perturbation Oriented Domain Adaptation Approach for Semantic Segmentation
IntraDA|ResNet101|90.6|37.1|82.6|30.1|19.1|29.5|32.4|20.6|85.7|40.5|79.7|58.7|31.1|86.3|31.5|48.3|0.0|30.2|35.8|46.3|CVPR|2020|[link](https://github.com/feipan664/IntraDA)|[link](http://openaccess.thecvf.com/content_CVPR_2020/papers/Pan_Unsupervised_Intra-Domain_Adaptation_for_Semantic_Segmentation_Through_Self-Supervision_CVPR_2020_paper.pdf)|Unsupervised Intra-domain Adaptation for Semantic Segmentation through Self-Supervision
MaxSquare+IW+Multi|ResNet101|89.4|43.0|82.1|30.5|21.3|30.3|34.7|24.0|85.3|39.4|78.2|63.0|22.9|84.6|36.4|43.0|5.5|34.7|33.5|46.4|CVPR|2019|[link](https://github.com/ZJULearning/MaxSquareLoss )|[link](http://openaccess.thecvf.com/content_ICCV_2019/papers/Chen_Domain_Adaptation_for_Semantic_Segmentation_With_Maximum_Squares_Loss_ICCV_2019_paper.pdf)|Domain Adaptation for Semantic Segmentation with Maximum Squares Loss
Adapt-Seg|ResNet101|92.3|51.9|82.1|29.2|25.1|24.5|33.8|33.0|82.4|32.8|82.2|58.6|27.2|84.3|33.4|46.3|2.2|29.5|32.3|46.5|ICCV|2019|-|[link](https://openaccess.thecvf.com/content_ICCV_2019/papers/Tsai_Domain_Adaptation_for_Structured_Output_via_Discriminative_Patch_Representations_ICCV_2019_paper.pdf)|Domain Adaptation for Structured Output via Discriminative Patch Representations
LSE+FL|ResNet101|90.2|40.0|83.5|31.9|26.4|32.6|38.7|37.5|81.0|34.2|84.6|61.6|33.4|82.5|32.8|45.9|6.7|29.1|30.6|47.5|ECCV|2020|-|[link](https://arxiv.org/pdf/2007.14449)|Learning from Scale-Invariant Examples for Domain Adaptation in Semantic Segmentation
BDL|ResNet101|91.0|44.7|84.2|34.6|27.6|30.2|36.0|36.0|85.0|43.6|83.0|58.6|31.6|83.3|35.3|49.7|3.3|28.8|35.6|48.5|CVPR|2019|[link](https://github.com/liyunsheng13/Bidirectional-Learning-for-Domain-Adaptation-of-Semantic-Segmentation)|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Li_Bidirectional_Learning_for_Domain_Adaptation_of_Semantic_Segmentation_CVPR_2019_paper.pdf)|Bidirectional Learning for Domain Adaptation of Semantic Segmentation
CSCL|ResNet101|89.6|50.4|83.0|35.6|26.9|31.1|37.3|35.1|83.5|40.6|84.0|60.6|34.3|80.9|35.1|47.3|0.5|34.5|33.7|48.6|ECCV|2020|-|[link](https://arxiv.org/pdf/2008.10464)|CSCL: Critical Semantic-Consistent Learning for Unsupervised Domain Adaptation
CrCDA|ResNet101|92.4|55.3|82.3|31.2|29.1|32.5|33.2|35.6|83.5|34.8|84.2|58.9|32.2|84.7|40.6|46.1|2.1|31.1|32.7|48.6|ECCV|2020|[link](https://github.com/jxhuang0508/CrCDA)|[link](https://arxiv.org/pdf/2007.02424)|Contextual-Relation Consistent Domain Adaptation for Semantic Segmentation
DTST|ResNet101|90.6|44.7|84.8|34.3|28.7|31.6|35.0|37.6|84.7|43.3|85.3|57.0|31.5|83.8|42.6|48.5|1.9|30.4|39.0|49.2|CVPR|2020|[link](https://github.com/SHI-Labs/Unsupervised-Domain-Adaptation-with-Differential-Treatment)|[link](http://openaccess.thecvf.com/content_CVPR_2020/papers/Wang_Differential_Treatment_for_Stuff_and_Things_A_Simple_Unsupervised_Domain_CVPR_2020_paper.pdf)|Differential Treatment for Stuff and Things:A Simple Unsupervised Domain Adaptation Method for Semantic Segmentation 
LDRDA|ResNet101|90.8|41.4|84.7|35.1|27.5|31.2|38.0|32.8|85.6|42.1|84.9|59.6|34.4|85.0|42.8|52.7|3.4|30.9|38.1|49.5|ECCV|2020|-|[link](https://arxiv.org/pdf/2003.04614)|Label-Driven Reconstruction for Domain Adaptation in Semantic Segmentation
Method|ResNet101|95.3|65.1|84.6|33.2|23.7|32.8|32.7|36.9|86.0|41.0|85.6|56.1|25.9|86.3|34.5|39.1|11.5|28.3|43.0|49.6|AAAI|2021|-|[link](https://arxiv.org/pdf/2012.12545)|Unsupervised Domain Adaptation for Semantic Segmentation by Content Transfer
DAST|ResNet101|92.2|49.0|84.3|36.5|28.9|33.9|38.8|28.4|84.9|41.6|83.2|60.0|28.7|87.2|45.0|45.3|7.4|33.8|32.8|49.6|AAAI|2021|[link](https://github.com/yufei1900/DAST_segmentation)|[link](http://bicmr.pku.edu.cn/~dongbin/Publications/DAST-AAAI2020.pdf)|DAST: Unsupervised Domain Adaptation in Semantic Segmentation Based on Discriminator Attention and Self-Training
TIR|ResNet101|92.9|55.0|85.3|34.2|31.1|34.9|40.7|34.0|85.2|40.1|87.1|61.0|31.1|82.5|32.3|42.9|0.3|36.4|46.1|50.2|CVPR|2020|[link](https://github.com/MyeongJin-Kim/Learning-Texture-Invariant-Representation)|[link](https://openaccess.thecvf.com/content_CVPR_2020/papers/Kim_Learning_Texture_Invariant_Representation_for_Domain_Adaptation_of_Semantic_Segmentation_CVPR_2020_paper.pdf)|Learning Texture Invariant Representation for Domain Adaptation of Semantic Segmentation
CAG-UDA|ResNet101|90.4|51.6|83.8|34.2|27.8|38.4|25.3|48.4|85.4|38.2|78.1|58.6|34.6|84.7|21.9|42.7|41.1|29.3|37.2|50.2|NeurIPS|2019|[link](https://github.com/RogerZhangzz/CAG_UDA)|[link](https://arxiv.org/pdf/1910.13049)|Category Anchor-Guided Unsupervised Domain Adaptation for Semantic Segmentation
FDA-MBT|ResNet101|92.5|53.3|82.4|26.5|27.6|36.4|40.6|38.9|82.3|39.8|78.0|62.6|34.4|84.9|34.1|53.1|16.9|27.7|46.4|50.5|CVPR|2020|[link](https://github.com/YanchaoYang/FDA )|[link](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yang_FDA_Fourier_Domain_Adaptation_for_Semantic_Segmentation_CVPR_2020_paper.pdf)|FDA: Fourier Domain Adaptation for Semantic Segmentation
PCEDA|ResNet101|91.0|49.2|85.6|37.2|29.7|33.7|38.1|39.2|85.4|35.4|85.1|61.1|32.8|84.1|45.6|46.9|0.0|34.2|44.5|50.5|CVPR|2020|[link](https://github.com/donglao/PCEDA)|[link](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yang_Phase_Consistent_Ecological_Domain_Adaptation_CVPR_2020_paper.pdf)|Phase Consistent Ecological Domain Adaptation 
CRST(MRKLD)+TPLD|ResNet101|94.2|60.5|82.8|36.6|16.6|39.3|29.0|25.5|85.6|44.9|84.4|60.6|27.4|84.1|37.0|47.0|31.2|36.1|50.3|51.2|ECCV|2020|-|[link](https://arxiv.org/pdf/2012.04828)|Two-phase Pseudo Label Densification for Self-training based Domain Adaptation
IAST|ResNet101|93.8|57.8|85.1|39.5|26.7|26.2|43.1|34.7|84.9|32.9|88.0|62.6|29.0|87.3|39.2|49.6|23.2|34.7|39.6|51.5|ECCV|2020|[link](https://github.com/Raykoooo/IAST)|[link](https://arxiv.org/pdf/2008.12197)|Instance Adaptive Self-Training for Unsupervised Domain Adaptation
IAST-MST|ResNet101|94.1|58.8|85.4|39.7|29.2|25.1|43.1|34.2|84.8|34.6|88.7|62.7|30.3|87.6|42.3|50.3|24.7|35.2|40.2|52.2|ECCV|2020|[link](https://github.com/Raykoooo/IAST)|[link](https://arxiv.org/pdf/2008.12197)|Instance Adaptive Self-Training for Unsupervised Domain Adaptation

#### **SYNTHIA → Cityscapes**
Name|Backbone|road|sidewalk|buiding|wall|fence|pole|light|sign|veg|sky|person|rider|car|bus|motor|bike|mIoU|mIoU*|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
ADVENT(MinEnt+CP)|VGG16|45.9|19.6|65.8|5.3|0.2|20.7|2.1|8.2|74.4|76.7|47.5|12.2|71.1|22.8|4.5|9.2|30.4|35.4|CVPR|2019|[link](https://github.com/arshinova/domain_adaptation)|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Vu_ADVENT_Adversarial_Entropy_Minimization_for_Domain_Adaptation_in_Semantic_Segmentation_CVPR_2019_paper.pdf)|ADVENT: Adversarial Entropy Minimization for Domain Adaptation in Semantic Segmentation
ADVENT(AdvEnt+CP)|VGG16|67.9|29.4|71.9|6.3|0.3|19.9|0.6|2.6|74.9|74.9|35.4|9.6|67.8|21.4|4.1|15.5|31.4|36.6|CVPR|2019|[link](https://github.com/arshinova/domain_adaptation)|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Vu_ADVENT_Adversarial_Entropy_Minimization_for_Domain_Adaptation_in_Semantic_Segmentation_CVPR_2019_paper.pdf)|ADVENT: Adversarial Entropy Minimization for Domain Adaptation in Semantic Segmentation
Adapt-Seg|VGG16|72.6|29.5|77.2|3.5|0.4|21.0|1.4|7.9|73.3|79.0|45.7|14.5|69.4|19.6|7.4|16.5|33.7|39.6|ICCV|2019|-|[link](https://openaccess.thecvf.com/content_ICCV_2019/papers/Tsai_Domain_Adaptation_for_Structured_Output_via_Discriminative_Patch_Representations_ICCV_2019_paper.pdf)|Domain Adaptation for Structured Output via Discriminative Patch Representations
CrCDA|VGG16|74.5|30.5|78.6|6.6|0.7|21.2|2.3|8.4|77.4|79.1|45.9|16.5|73.1|24.1|9.6|14.2|35.2|41.1|ECCV|2020|[link](https://github.com/jxhuang0508/CrCDA)|[link](https://arxiv.org/pdf/2007.02424)|Contextual-Relation Consistent Domain Adaptation for Semantic Segmentation
CRST(MRKLD)+TPLD|VGG16|81.3|34.5|73.3|11.9|0.0|26.9|0.2|6.3|79.9|71.2|55.1|14.2|73.6|5.7|0.5|41.7|36.0|41.3|ECCV|2020|-|[link](https://arxiv.org/pdf/2012.04828)|Two-phase Pseudo Label Densifification for Self-training based Domain Adaptation
TGCF+SE|VGG16|90.1|48.6|80.7|2.2|0.2|27.2|3.2|14.3|82.1|78.4|54.4|16.4|82.5|12.3|1.7|21.8|38.5|46.6|CVPR|2019|-|[link](https://openaccess.thecvf.com/content_ICCV_2019/papers/Choi_Self-Ensembling_With_GAN-Based_Data_Augmentation_for_Domain_Adaptation_in_Semantic_ICCV_2019_paper.pdf)|Self-Ensembling with GAN-based Data Augmentation for Domain Adaptation in Semantic Segmentation
BDL|VGG16|72.0|30.3|74.5|0.1|0.3|24.6|10.2|25.2|80.5|80.0|54.7|23.2|72.7|24.0|7.5|44.9|39.0|-|CVPR|2019|[link](https://github.com/liyunsheng13/Bidirectional-Learning-for-Domain-Adaptation-of-Semantic-Segmentation)|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Li_Bidirectional_Learning_for_Domain_Adaptation_of_Semantic_Segmentation_CVPR_2019_paper.pdf)|Bidirectional Learning for Domain Adaptation of Semantic Segmentation
CLAN|VGG16|80.4|30.7|74.7|-|-|-|1.4|8.0|77.1|79.0|46.5|8.9|73.8|18.2|2.2|9.9|39.3|-|CVPR|2019|[link](https://github.com/RoyalVane/CLAN)|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Luo_Taking_a_Closer_Look_at_Domain_Shift_Category-Level_Adversaries_for_CVPR_2019_paper.pdf)|Taking A Closer Look at Domain Shift: Category-level Adversaries for Semantics Consistent Domain Adaptation
DAST|VGG16|86.1|35.7|79.9|5.2|0.8|23.1|0.0|6.9|80.9|82.5|50.6|19.8|79.7|21.9|21.3|38.8|39.6|46.5|AAAI|2021|[link](https://github.com/yufei1900/DAST_segmentation)|[link](http://bicmr.pku.edu.cn/~dongbin/Publications/DAST-AAAI2020.pdf)|DAST: Unsupervised Domain Adaptation in Semantic Segmentation Based on Discriminator Attention and Self-Training
LSE+FL|VGG16|83.6|39.6|79.3|3.6|0.9|25.3|14.1|26.1|79.4|76.5|51.0|18.1|75.7|22.5|12.0|32.1|40.0|47.0|ECCV|2020|-|[link](https://arxiv.org/pdf/2007.14449)|Learning from Scale-Invariant Examples for Domain Adaptation in Semantic Segmentation
Adapt-Seg|ResNet101|82.4|38.0|78.6|8.7|0.6|26.0|3.9|11.1|75.5|84.6|53.5|21.6|71.4|32.6|19.3|31.7|40.0|46.5|ICCV|2019|-|[link](https://openaccess.thecvf.com/content_ICCV_2019/papers/Tsai_Domain_Adaptation_for_Structured_Output_via_Discriminative_Patch_Representations_ICCV_2019_paper.pdf)|Domain Adaptation for Structured Output via Discriminative Patch Representations
FDA-MBT|VGG16|84.2|35.1|78.0|6.1|0.4|27.0|8.5|22.1|77.2|79.6|55.5|19.9|74.8|24.9|14.3|40.7|40.5|-|CVPR|2020|[link](https://github.com/YanchaoYang/FDA )|[link](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yang_FDA_Fourier_Domain_Adaptation_for_Semantic_Segmentation_CVPR_2020_paper.pdf)|FDA: Fourier Domain Adaptation for Semantic Segmentation
Method|VGG16|82.9|31.4|72.1|-|-|-|10.4|9.7|75.0|76.3|48.5|15.5|70.3|11.3|1.2|29.4|41.1|-|AAAI|2020|-|[link](https://ojs.aaai.org/index.php/AAAI/article/download/6952/6806)|An Adversarial Perturbation Oriented Domain Adaptation Approach for Semantic Segmentation
LDRDA|VGG16|73.7|29.6|77.6|1.0|0.4|26.0|14.7|26.6|80.6|81.8|57.2|24.5|76.1|27.6|13.6|46.6|41.1|-|ECCV|2020|-|[link](https://arxiv.org/pdf/2003.04614)|Label-Driven Reconstruction for Domain Adaptation in Semantic Segmentation
PCEDA|VGG16|79.7|35.2|78.7|1.4|0.6|23.1|10.0|28.9|79.6|81.2|51.2|25.1|72.2|24.1|16.7|50.4|41.1|48.7|CVPR|2020|[link](https://github.com/donglao/PCEDA )|[link](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yang_Phase_Consistent_Ecological_Domain_Adaptation_CVPR_2020_paper.pdf)|Phase Consistent Ecological Domain Adaptation 
ADVENT(AdvEnt+MinEnt)|ResNet101|85.6|42.2|79.7|8.7|0.4|25.9|5.4|8.1|80.4|84.1|57.9|23.8|73.3|36.4|14.2|33.0|41.2|48.0|CVPR|2019|[link](https://github.com/arshinova/domain_adaptation)|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Vu_ADVENT_Adversarial_Entropy_Minimization_for_Domain_Adaptation_in_Semantic_Segmentation_CVPR_2019_paper.pdf)|ADVENT: Adversarial Entropy Minimization for Domain Adaptation in Semantic Segmentation
MaxSquare+IW+Multi|ResNet101|82.9|40.7|80.3|10.2|0.8|25.8|12.8|18.2|82.5|82.2|53.1|18.0|79.0|31.4|10.4|35.6|41.4|48.2|CVPR|2019|[link](https://github.com/ZJULearning/MaxSquareLoss )|[link](http://openaccess.thecvf.com/content_ICCV_2019/papers/Chen_Domain_Adaptation_for_Semantic_Segmentation_With_Maximum_Squares_Loss_ICCV_2019_paper.pdf)|Domain Adaptation for Semantic Segmentation with Maximum Squares Loss
IntraDA|ResNet101|84.3|37.7|79.5|5.3|0.4|24.9|9.2|8.4|80.0|84.1|57.2|23.0|78.0|38.1|20.3|36.5|41.7|48.9|CVPR|2020|[link](https://github.com/feipan664/IntraDA)|[link](http://openaccess.thecvf.com/content_CVPR_2020/papers/Pan_Unsupervised_Intra-Domain_Adaptation_for_Semantic_Segmentation_Through_Self-Supervision_CVPR_2020_paper.pdf)|Unsupervised Intra-domain Adaptation for Semantic Segmentation through Self-Supervision
BiSIDA|VGG16|87.4|42.4|79.0|17.0|0.1|23.9|2.8|22.9|82.0|80.4|51.1|19.1|76.7|33.3|14.4|41.2|42.1|48.7|AAAI|2021|[link](https://github.com/wangkaihong/BiSIDA)|[link](https://arxiv.org/pdf/2009.08610)|Consistency Regularization with High-dimensional Non-adversarial Source-guided Perturbation for Unsupervised Domain Adaptation in Segmentation
LSE+FL|ResNet101|82.9|43.1|78.1|9.3|0.6|28.2|9.1|14.4|77.0|83.5|58.1|25.9|71.9|38.0|29.4|31.2|42.6|49.4|ECCV|2020|-|[link](https://arxiv.org/pdf/2007.14449)|Learning from Scale-Invariant Examples for Domain Adaptation in Semantic Segmentation
CrCDA|ResNet101|86.2|44.9|79.5|8.3|0.7|27.8|9.4|11.8|78.6|86.5|57.2|26.1|76.8|39.9|21.5|32.1|42.9|50.0|ECCV|2020|[link](https://github.com/jxhuang0508/CrCDA)|[link](https://arxiv.org/pdf/2007.02424)|Contextual-Relation Consistent Domain Adaptation for Semantic Segmentation
TIR|VGG16|89.8|48.6|78.9|-|-|-|0.0|4.7|80.6|81.7|36.2|13.0|74.4|22.5|6.5|32.8|43.8|-|CVPR|2020|[link](https://github.com/MyeongJin-Kim/Learning-Texture-Invariant-Representation)|[link](https://openaccess.thecvf.com/content_CVPR_2020/papers/Kim_Learning_Texture_Invariant_Representation_for_Domain_Adaptation_of_Semantic_Segmentation_CVPR_2020_paper.pdf)|Learning Texture Invariant Representation for Domain Adaptation of Semantic Segmentation
CAG-UDA|ResNet101|84.7|40.8|81.7|7.8|0.0|35.1|13.3|22.7|84.5|77.6|64.2|27.8|80.9|19.7|22.7|48.3|44.5|-|NeurIPS|2019|[link](https://github.com/RogerZhangzz/CAG_UDA)|[link](https://arxiv.org/pdf/1910.13049)|Category Anchor-Guided Unsupervised Domain Adaptation for Semantic Segmentation
DAST|ResNet101|87.1|44.5|82.3|10.7|0.8|29.9|13.9|13.1|81.6|86.0|60.3|25.1|83.1|40.1|24.4|40.5|45.2|52.5|AAAI|2021|[link](https://github.com/yufei1900/DAST_segmentation)|[link](http://bicmr.pku.edu.cn/~dongbin/Publications/DAST-AAAI2020.pdf)|DAST: Unsupervised Domain Adaptation in Semantic Segmentation Based on Discriminator Attention and Self-Training
PCEDA|ResNet101|85.9|44.6|80.8|9.0|0.8|32.1|24.8|23.1|79.5|83.1|57.2|29.3|73.5|34.8|32.4|48.2|46.2|53.6|CVPR|2020|[link](https://github.com/donglao/PCEDA)|[link](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yang_Phase_Consistent_Ecological_Domain_Adaptation_CVPR_2020_paper.pdf)|Phase Consistent Ecological Domain Adaptation 
Method|ResNet101|93.3|54.0|81.3|14.3|0.7|28.8|21.3|22.8|82.6|83.3|57.7|22.8|83.4|30.7|20.2|47.2|46.5|53.9|AAAI|2021|||Unsupervised Domain Adaptation for Semantic Segmentation by Content Transfer
CSCL|ResNet101|80.2|41.1|78.9|23.6|0.6|31.0|27.1|29.5|82.5|83.2|62.1|26.8|81.5|37.2|27.3|42.9|47.2|-|ECCV|2020|-|[link](https://arxiv.org/pdf/2008.10464)|CSCL: Critical Semantic-Consistent Learning for Unsupervised Domain Adaptation
CRST(MRKLD)+TPLD|ResNet101|80.9|44.3|82.2|19.9|0.3|40.6|20.5|30.1|77.2|80.9|60.6|25.5|84.8|41.1|24.7|43.7|47.3|53.5|ECCV|2020|-|[link](https://arxiv.org/pdf/2012.04828)|Two-phase Pseudo Label Densifification for Self-training based Domain Adaptation
CLAN|ResNet101|81.3|37.0|80.1|-|-|-|16.1|13.7|78.2|81.5|53.4|21.2|73.0|32.9|22.6|30.7|47.8|-|CVPR|2019|[link](https://github.com/RoyalVane/CLAN)|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Luo_Taking_a_Closer_Look_at_Domain_Shift_Category-Level_Adversaries_for_CVPR_2019_paper.pdf)|Taking A Closer Look at Domain Shift: Category-level Adversaries for Semantics Consistent Domain Adaptation
STAR|ResNet101|82.6|36.2|81.1|-|-|-|12.2|8.7|78.4|82.2|59.0|22.5|76.3|33.6|11.9|40.8|48.1|-|CVPR|2020|-|[link](https://openaccess.thecvf.com/content_CVPR_2020/papers/Lu_Stochastic_Classifiers_for_Unsupervised_Domain_Adaptation_CVPR_2020_paper.pdf)|Stochastic Classififiers for Unsupervised Domain Adaptation
TIR|ResNet101|92.6|53.2|79.2|-|-|-|1.6|7.5|78.6|84.4|52.6|20.0|82.1|34.8|14.6|39.4|49.3|-|CVPR|2020|[link](https://github.com/MyeongJin-Kim/Learning-Texture-Invariant-Representation)|[link](https://openaccess.thecvf.com/content_CVPR_2020/papers/Kim_Learning_Texture_Invariant_Representation_for_Domain_Adaptation_of_Semantic_Segmentation_CVPR_2020_paper.pdf)|Learning Texture Invariant Representation for Domain Adaptation of Semantic Segmentation
IAST|ResNet101|81.9|41.5|83.3|17.7|4.6|32.3|30.9|28.8|83.4|85.0|65.5|30.8|86.5|38.2|33.1|52.7|49.8|57.0|ECCV|2020|[link](https://github.com/Raykoooo/IAST)|[link](https://arxiv.org/pdf/2008.12197)|Instance Adaptive Self-Training for Unsupervised Domain Adaptation
SSF-DAN|ResNet101|84.6|41.7|80.8|-|-|-|11.5|14.7|80.8|85.3|57.5|21.6|82.0|36.0|19.3|34.5|50.0||ICCV|2019|-|[link](https://openaccess.thecvf.com/content_ICCV_2019/papers/Du_SSF-DAN_Separated_Semantic_Feature_Based_Domain_Adaptation_Network_for_Semantic_ICCV_2019_paper.pdf)|SSF-DAN: Separated Semantic Feature based Domain Adaptation Network for Semantic Segmentation
BDL|ResNet101|86.0|46.7|80.3|-|-|-|14.1|11.6|79.2|81.3|54.1|27.9|73.7|42.2|25.7|45.3|51.4|-|CVPR|2019|[link](https://github.com/liyunsheng13/Bidirectional-Learning-for-Domain-Adaptation-of-Semantic-Segmentation)|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Li_Bidirectional_Learning_for_Domain_Adaptation_of_Semantic_Segmentation_CVPR_2019_paper.pdf)|Bidirectional Learning for Domain Adaptation of Semantic Segmentation
DTST|ResNet101|83.0|44.0|80.3|-|-|-|17.1|15.8|80.5|81.8|59.9|33.1|70.2|37.3|28.5|45.8|52.1|-|CVPR|2020|[link](https://github.com/SHI-Labs/Unsupervised-Domain-Adaptation-with-Differential-Treatment)|[link](http://openaccess.thecvf.com/content_CVPR_2020/papers/Wang_Differential_Treatment_for_Stuff_and_Things_A_Simple_Unsupervised_Domain_CVPR_2020_paper.pdf)|Differential Treatment for Stuff and Things:A Simple Unsupervised Domain Adaptation Method for Semantic Segmentation 
FDA-MBT|ResNet101|79.3|35.0|73.2|-|-|-|19.9|24.0|61.7|82.6|61.4|31.1|83.9|40.8|38.4|51.1|52.5|-|CVPR|2020|[link](https://github.com/YanchaoYang/FDA )|[link](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yang_FDA_Fourier_Domain_Adaptation_for_Semantic_Segmentation_CVPR_2020_paper.pdf)|FDA: Fourier Domain Adaptation for Semantic Segmentation
Method|ResNet101|86.4|41.3|79.3|-|-|-|22.6|17.3|80.3|81.6|56.9|21.0|84.1|49.1|24.6|45.7|53.1|-|AAAI|2020|-|[link](https://ojs.aaai.org/index.php/AAAI/article/download/6952/6806)|An Adversarial Perturbation Oriented Domain Adaptation Approach for Semantic Segmentation
LDRDA|ResNet101|85.1|44.5|81.0|-|-|-|16.4|15.2|80.1|84.8|59.4|31.9|73.2|41.0|32.6|44.7|53.1|-|ECCV|2020|-|[link](https://arxiv.org/pdf/2003.04614)|Label-Driven Reconstruction for Domain Adaptation in Semantic Segmentation

## 2.2 Domain Generalization
#### **PACS**
Name|Backbone|Art Painting|Cartoon|Photo|Sketch|Avg|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
CIDDG|AlexNet|62.70|69.73|78.65|64.45|68.88|ECCV|2018|-|[link](http://openaccess.thecvf.com/content_ECCV_2018/papers/Ya_Li_Deep_Domain_Generalization_ECCV_2018_paper.pdf)|Deep Domain Generalization via Conditional Invariant Adversarial Networks
MLDG|AlexNet|66.23|66.88|88|58.96|70.01|AAAI|2017|[link](https://github.com/HAHA-DL/MLDG)|[link](https://ojs.aaai.org/index.php/AAAI/article/download/11596/11455)|Learning to Generalize: Meta-Learning for Domain Generalization
Epi-FCR|AlexNet|64.7|72.3|86.1|65.0|72.0|ICCV|2019|[link](https://github.com/HAHA-DL/Episodic-DG)|[link](https://openaccess.thecvf.com/content_ICCV_2019/papers/Li_Episodic_Training_for_Domain_Generalization_ICCV_2019_paper.pdf)|Episodic Training for Domain Generalization
Feature-Critic|AlexNet|64.89|71.72|89.94|61.85|72.1|ICML|2019|[link](https://github.com/liyiying/Feature_Critic)|[link](http://proceedings.mlr.press/v97/li19l/li19l.pdf)|Feature-Critic Networks for Heterogeneous Domain Generalisation 
MetaReg|AlexNet|69.82±0.76|70.35±0.63|91.07±0.41|59.26±0.31|72.62|NeurIPS|2018|[link](https://github.com/elliotbeck/MetaReg_PyTorch)|[link](http://papers.neurips.cc/paper/7378-metareg-towards-domain-generalization-using-meta-regularization.pdf)|MetaReg: Towards Domain Generalization using Meta-Regularization
DMG|AlexNet|64.65|69.88|87.31|71.42|73.32|ECCV|2020|[link](https://github.com/prithv1/DMG)|[link](https://arxiv.org/pdf/2008.12839)|Learning to Balance Specifificity and Invariance for In and Out of Domain Generalization
JiGen|AlexNet|67.63|71.71|89.00|65.18|73.78|CVPR|2019|[link](https://github.com/fmcarlucci/JigenDG)|[link](https://openaccess.thecvf.com/content_CVPR_2019/papers/Carlucci_Domain_Generalization_by_Solving_Jigsaw_Puzzles_CVPR_2019_paper.pdf)|Domain Generalization by Solving Jigsaw Puzzles
MMLD|AlexNet|69.27|72.83|88.98|66.44|74.38|AAAI|2020|[link](https://github.com/mil-tokyo/dg_mmld)|[link](https://ojs.aaai.org/index.php/AAAI/article/view/6846/6701)|Domain Generalization Using a Mixture of Multiple Latent Domains 
MASF|AlexNet|70.35|72.46|90.68|72.46|75.21|NeurIPS|2020|[link](https://github.com/biomedia-mira/masf)|[link](https://arxiv.org/pdf/1910.13580)|Domain Generalization via  Model-Agnostic Learning of Semantic Features
MetaVIB|AlexNet|71.94±0.34|73.17±0.21|91.93±0.23|65.94±0.24|75.74|ECCV|2020|-|[link](https://arxiv.org/pdf/2007.07645.pdf)|Learning to Learn with Variational Information Bottleneck for Domain Generalization
EISNet|AlexNet|70.38±0.37|71.59±1.32|91.20±0.00|70.25±1.36|75.86|ECCV|2020|[link](https://github.com/EmmaW8/EISNet)|[link](https://arxiv.org/pdf/2007.09316)|Learning from Extrinsic and Intrinsic Supervisions for Domain Generalization
RSC|AlexNet|71.62|75.11|90.88|66.62|76.05|ECCV|2020|[link](https://github.com/DeLightCMU/RSC)|[link](https://arxiv.org/pdf/2007.02454)|Self-Challenging Improves Cross-Domain Generalization
JiGen|ResNet18|79.42|75.25|96.03|71.35|80.51|CVPR|2019|[link](https://github.com/fmcarlucci/JigenDG)|[link](https://openaccess.thecvf.com/content_CVPR_2019/papers/Carlucci_Domain_Generalization_by_Solving_Jigsaw_Puzzles_CVPR_2020_paper.pdf)|Domain Generalization by Solving Jigsaw Puzzles
MASF|ResNet18|80.29|77.17|94.99|71.69|81.04|NeurIPS|2020|[link](https://github.com/biomedia-mira/masf)|[link](https://arxiv.org/pdf/1910.13581)|Domain Generalization via  Model-Agnostic Learning of Semantic Features
DG_via_ER|ResNet18|80.70±0.71|76.40±0.34|96.65±0.21|71.77±1.27|81.38|NeurIPS|2020|[link](https://github.com/sshan-zhao/DG_via_ER)|[link](https://proceedings.neurips.cc/paper/2020/file/b98249b38337c5088bbc660d8f872d6a-Paper.pdf)|Domain Generalization via Entropy Regularization
FFO-S-MLDG|ResNet18|80.0|77.4|94.6|73.8|81.4|CVPR|2021|-|[link](https://arxiv.org/pdf/2004.01377v1.pdf)|Sequential Learning for Domain Generalization
DMG|ResNet18|76.90|80.38|93.35|75.21|81.46|ECCV|2020|[link](https://github.com/prithv2/DMG)|[link](https://arxiv.org/pdf/2008.12840)|Learning to Balance Specifificity and Invariance for In and Out of Domain Generalization
Epi-FCR|ResNet18|82.1|77.0|93.0|73.0|81.5|ICCV|2019|[link](https://github.com/HAHA-DL/Episodic-DG)|[link](https://openaccess.thecvf.com/content_ICCV_2019/papers/Li_Episodic_Training_for_Domain_Generalization_ICCV_2020_paper.pdf)|Episodic Training for Domain Generalization
S-MLDG|ResNet18|80.5|77.8|94.8|72.8|81.5|CVPR|2021|-|[link](https://arxiv.org/pdf/2004.01377v1.pdf)|Sequential Learning for Domain Generalization
MetaReg|ResNet18|83.7±0.19|77.2±0.31|95.5±0.24|70.3±0.28|81.70|NeurIPS|2018|[link](https://github.com/elliotbeck/MetaReg_PyTorch)|[link](http://papers.neurips.cc/paper/7378-metareg-towards-domain-generalization-using-meta-regularization.pdf)|MetaReg: Towards Domain Generalization using Meta-Regularization
MMLD|ResNet18|81.28|77.16|96.09|72.22|81.83|AAAI|2020|[link](https://github.com/mil-tokyo/dg_mmld)|[link](https://ojs.aaai.org/index.php/AAAI/article/view/6846/6700)|Domain Generalization Using a Mixture of Multiple Latent Domains 
EISNet|ResNet18|81.89±0.88|76.44±0.31|95.93±0.06|74.33±1.37|82.15|ECCV|2020|[link](https://github.com/EmmaW9/EISNet)|[link](https://arxiv.org/pdf/2007.09317)|Learning from Extrinsic and Intrinsic Supervisions for Domain Generalization
MASF|ResNet50|82.89|80.49|95.01|72.29|82.67|NeurIPS|2020|[link](https://github.com/biomedia-mira/masf)|[link](https://arxiv.org/pdf/1910.13582)|Domain Generalization via  Model-Agnostic Learning of Semantic Features
DAML|ResNet18|83.0|74.1|95.6|78.1|82.7|CVPR|2021.0|-|[link](https://openaccess.thecvf.com/content/CVPR2021/papers/Shu_Open_Domain_Generalization_with_Domain-Augmented_Meta-Learning_CVPR_2021_paper.pdf)|Open Domain Generalization with Domain-Augmented Meta-Learning
L2A-OT|ResNet18|83.8|78.2|96.2|73.6|82.8|ECCV|2020|[link](https://github.com/mousecpn/L2A-OT)|[link](https://arxiv.org/pdf/2007.03304)|Learning to Generate Novel Domains for Domain Generalization
DMG|ResNet50|82.57|78.11|94.49|78.32|83.37|ECCV|2020|[link](https://github.com/prithv3/DMG)|[link](https://arxiv.org/pdf/2008.12841)|Learning to Balance Specifificity and Invariance for In and Out of Domain Generalization
MetaReg|ResNet50|87.2±0.13|79.2±0.27|97.6±0.31|70.3±0.18|83.60|NeurIPS|2018|[link](https://github.com/elliotbeck/MetaReg_PyTorch)|[link](http://papers.neurips.cc/paper/7378-metareg-towards-domain-generalization-using-meta-regularization.pdf)|MetaReg: Towards Domain Generalization using Meta-Regularization
MixStyle|ResNet18|84.1±0.4|78.8±0.4|96.1±0.3|75.9±0.9|83.7|ICLR|2021|[link](https://github.com/KaiyangZhou/mixstyle-release)|[link](https://openreview.net/pdf/45cfce2bb7de7655e5129c349f609eba35911b60.pdf)|Domain Generalization with MixStyle
FACT|ResNet18|85.37|78.38|95.15|79.15|84.51|CVPR|2021|"[link](https://github.com/MediaBrain-SJTU/FACT)"|[link](https://openaccess.thecvf.com/content/CVPR2021/papers/Xu_A_Fourier-Based_Framework_for_Domain_Generalization_CVPR_2021_paper.pdf)|A Fourier-based Framework for Domain Generalization
DSON|ResNet18|84.67|77.65|95.87|82.23|85.11|ECCV|2020|-|[link](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123670069.pdf)|Learning to Optimize Domain Specifific Normalization for Domain Generalization
RSC|ResNet18|83.43|80.31|95.99|80.85|85.15|ECCV|2020|[link](https://github.com/DeLightCMU/RSC)|[link](https://arxiv.org/pdf/2007.02455)|Self-Challenging Improves Cross-Domain Generalization
DG_via_ER|ResNet50|87.51±1.03|79.31±1.40|98.25±0.12|76.30±0.65|85.34|NeurIPS|2020|[link](https://github.com/sshan-zhao/DG_via_ER)|[link](https://proceedings.neurips.cc/paper/2020/file/b98249b38337c5088bbc660d8f872d6a-Paper.pdf)|Domain Generalization via Entropy Regularization
ERM|ResNet50|84.70|80.80|97.20|79.30|85.50|ICLR|2021|-|[link](https://arxiv.org/pdf/2007.01434)|In Search of Lost Domain Generalization
V-REx|ResNet18|-|-|-|-|85.8±0.6|ICML|2021|-|[link](http://proceedings.mlr.press/v139/krueger21a/krueger21a.pdf)|Out-of-Distribution Generalization via Risk Extrapolation
EISNet|ResNet50|86.64±1.41|81.53±0.64|97.11±0.40|78.07±1.43|85.84|ECCV|2020|[link](https://github.com/EmmaW10/EISNet)|[link](https://arxiv.org/pdf/2007.09318)|Learning from Extrinsic and Intrinsic Supervisions for Domain Generalization
RSC+ASR|ResNet18|84.8|81.8|96.1|82.6|86.3|CVPR|2021|-|[link](https://openaccess.thecvf.com/content/CVPR2021/papers/Fan_Adversarially_Adaptive_Normalization_for_Single_Domain_Generalization_CVPR_2021_paper.pdf)|Adversarially Adaptive Normalization for Single Domain Generalization
DSON|ResNet50|87.04|80.62|95.99|82.90|86.64|ECCV|2020|-|[link](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123670070.pdf)|Learning to Optimize Domain Specifific Normalization for Domain Generalization
RSC|ResNet50|87.89|82.16|97.92|83.35|87.83|ECCV|2020|[link](https://github.com/DeLightCMU/RSC)|[link](https://arxiv.org/pdf/2007.02456)|Self-Challenging Improves Cross-Domain Generalization
FACT|ResNet50|89.63|81.77|96.75|84.46|88.15|CVPR|2021|"[link](https://github.com/MediaBrain-SJTU/FACT)"|[link](https://openaccess.thecvf.com/content/CVPR2021/papers/Xu_A_Fourier-Based_Framework_for_Domain_Generalization_CVPR_2021_paper.pdf)|A Fourier-based Framework for Domain Generalization

#### **VLCS**
Name|Backbone|Caltech|Labelme|Pascal|Sun|Avg|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
MTAE+1HNN|AlexNet|90.71|59.24|61.09|60.2|67.81|ICCV|2015|[link](https://github.com/Emma0118/mate)|[link](https://arxiv.org/pdf/1508.07680v1)|Domain Generalization for Object Recognition with Multi-task Autoencoders
D-MTAE+1HNN|AlexNet|89.05|60.13|63.9|61.33|68.6|ICCV|2015|[link](https://github.com/Emma0118/mate)|[link](https://arxiv.org/pdf/1508.07680v1)|Domain Generalization for Object Recognition with Multi-task Autoencoders
MCS<sub>A</sub>|AlexNet|92.40±0.62|57.42±0.48|65.74±1.26|62.07±0.82|69.41|CVPR|2019|-|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Liang_Distant_Supervised_Centroid_Shift_A_Simple_and_Efficient_Approach_to_CVPR_2019_paper.pdf)|Distant Supervised Centroid Shift: A Simple and Efficient Approach to Visual Domain Adaptation
CIDDG|AlexNet|88.83|63.06|64.38|62.10|69.59|ECCV|2018|-|[link](http://openaccess.thecvf.com/content_ECCV_2018/papers/Ya_Li_Deep_Domain_Generalization_ECCV_2018_paper.pdf)|Deep Domain Generalization via Conditional Invariant Adversarial Networks
MCS<sub>B</sub>|AlexNet|89.30±0.37|59.95±0.40|65.17±0.44|65.16±0.68|69.90|CVPR|2019|-|[link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Liang_Distant_Supervised_Centroid_Shift_A_Simple_and_Efficient_Approach_to_CVPR_2019_paper.pdf)|Distant Supervised Centroid Shift: A Simple and Efficient Approach to Visual Domain Adaptation
MMD+AAE|AlexNet|94.4|62.6|67.7|64.4|72.3|CVPR|2018|[link](https://github.com/YuqiCui/MMD_AAE)|[link](http://openaccess.thecvf.com/content_cvpr_2018/papers/Li_Domain_Generalization_With_CVPR_2018_paper.pdf)|Domain Generalization with Adversarial Feature Learning 
FFO-S-MLDG|ResNet18|68.1|63.1|94.8|65.2|72.8|CVPR|2021|-|[link](https://arxiv.org/pdf/2004.01377v1.pdf)|Sequential Learning for Domain Generalization
Epi-FCR|AlexNet|94.1|64.3|67.1|65.9|72.9|ICCV|2019|[link](https://github.com/HAHA-DL/Episodic-DG)|[link](https://openaccess.thecvf.com/content_ICCV_2019/papers/Li_Episodic_Training_for_Domain_Generalization_ICCV_2020_paper.pdf)|Episodic Training for Domain Generalization
JiGen|AlexNet|96.93|60.90|70.62|64.30|73.19|CVPR|2019|[link](https://github.com/fmcarlucci/JigenDG)|[link](https://openaccess.thecvf.com/content_CVPR_2019/papers/Carlucci_Domain_Generalization_by_Solving_Jigsaw_Puzzles_CVPR_2020_paper.pdf)|Domain Generalization by Solving Jigsaw Puzzles
S-MLDG|ResNet18|68.7|64.8|96.4|64.0|73.5|-|2020|-|[link](https://arxiv.org/pdf/2004.01377v1.pdf)|Sequential Learning for Domain Generalization
MMLD|ResNet18|96.66|58.77|71.96|68.13|73.88|AAAI|2020|[link](https://github.com/mil-tokyo/dg_mmld)|[link](https://ojs.aaai.org/index.php/AAAI/article/view/6846/6701)|Domain Generalization Using a Mixture of Multiple Latent Domains 
MASF|AlexNet|94.78±0.16|64.90±0.08|69.14±0.19|67.64±0.12|74.11|NeurIPS|2020|[link](https://github.com/biomedia-mira/masf)|[link](https://arxiv.org/pdf/1910.13581)|Domain Generalization via  Model-Agnostic Learning of Semantic Features
MetaVIB|AlexNet|97.37±0.63|62.66±0.35|70.28±0.71|67.85±0.17|74.54|ECCV|2020|-|[link](https://arxiv.org/pdf/2007.07645.pdf)|Learning to Learn with Variational Information Bottleneck for Domain Generalization
EISNet|AlexNet|97.33±0.36|63.49±0.82|69.83±0.48|68.02±0.81|74.67|ECCV|2020|[link](https://github.com/EmmaW10/EISNet)|[link](https://arxiv.org/pdf/2007.09318)|Learning from Extrinsic and Intrinsic Supervisions for Domain Generalization
RSC|AlexNet|97.61|61.86|73.93|68.32|75.43|ECCV|2020|[link](https://github.com/DeLightCMU/RSC)|[link](https://arxiv.org/pdf/2007.02456)|Self-Challenging Improves Cross-Domain Generalization
ERM|ResNet50|97.7|64.3|73.4|74.6|77.5|ICLR|2021|-|[link](https://arxiv.org/pdf/2007.01434)|In Search of Lost Domain Generalization
V-REx|ResNet50|-|-|-|-|77.9±0.5|ICML|2021|-|[link](http://proceedings.mlr.press/v139/krueger21a/krueger21a.pdf)|Out-of-Distribution Generalization via Risk Extrapolation

#### **Office-Home**
Name|Backbone|Art|Clipart|Product|Real World|Avg|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
JiGen|ResNet18|53.04|47.51|71.47|72.79|61.20|CVPR|2019|[link](https://github.com/fmcarlucci/JigenDG)|[link](https://openaccess.thecvf.com/content_CVPR_2019/papers/Carlucci_Domain_Generalization_by_Solving_Jigsaw_Puzzles_CVPR_2020_paper.pdf)|Domain Generalization by Solving Jigsaw Puzzles
DSON|ResNet18|59.37|44.70|71.84|74.68|62.90|ECCV|2020|-|[link](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123670069.pdf)|Learning to Optimize Domain Specifific Normalization for Domain Generalization
RSC|ResNet18|58.42|47.90|71.63|74.54|63.12|ECCV|2020|[link](https://github.com/DeLightCMU/RSC)|[link](https://arxiv.org/pdf/2007.02456)|Self-Challenging Improves Cross-Domain Generalization
L2A-OT|ResNet18|60.6|50.1|74.8|77.0|65.6|ECCV|2020|[link](https://github.com/mousecpn/L2A-OT)|[link](https://arxiv.org/pdf/2007.03304)|Learning to Generate Novel Domains for Domain Generalization
ERM|ResNet50|61.3|52.4|75.8|76.6|66.5|ICLR|2021|-|[link](https://arxiv.org/pdf/2007.01434)|In Search of Lost Domain Generalization
FACT|ResNet18|60.34|54.85|74.48|76.55|66.56|CVPR|2021|[link](https://github.com/MediaBrain-SJTU/FACT)|[link](https://openaccess.thecvf.com/content/CVPR2021/papers/Xu_A_Fourier-Based_Framework_for_Domain_Generalization_CVPR_2021_paper.pdf)|A Fourier-based Framework for Domain Generalization
V-REx|ResNet18|-|-|-|-|66.7±0.5|ICML|2021|-|[link](http://proceedings.mlr.press/v139/krueger21a/krueger21a.pdf)|Out-of-Distribution Generalization via Risk Extrapolation

#### **Rotated Mnist<sup>1</sup>**
> Backbone: **LeNet**

Name|M<sub>0</sub>|M<sub>15</sub>|M<sub>30</sub>|M<sub>45</sub>|M<sub>60</sub>|M<sub>75</sub>|Avg|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
MTAE|77.9|95.7|91.2|77.3|92.4|79.9|85.7|ICCV|2015|[link](https://github.com/Emma0118/mate)|[link](https://arxiv.org/pdf/1508.07680v1)|Domain Generalization for Object Recognition with Multi-task Autoencoders
D-MTAE|82.5|96.3|93.4|78.6|94.2|80.5|87.6|ICCV|2015|[link](https://github.com/Emma0118/mate)|[link](https://arxiv.org/pdf/1508.07680v1)|Domain Generalization for Object Recognition with Multi-task Autoencoders
MMD-AAE|83.70|96.60|95.70|85.20|95.90|81.20|89.72|CVPR|2018|[link](https://github.com/YuqiCui/MMD_AAE)|[link](https://openaccess.thecvf.com/content_cvpr_2018/papers/Li_Domain_Generalization_With_CVPR_2018_paper.pdf)|Domain Generalization with Adversarial Feature Learning
CrossGrad|86.03|98.92|98.60|98.39|98.68|88.94|94.93|ICLR|2018|[link](https://github.com/gpascualg/CrossGrad)|[link](https://arxiv.org/pdf/1804.10745.pdf)|Generalizing across domains via cross-gradient training.
MetaReg|85.70±0.31|98.87±0.41|98.32±0.44|98.58±0.28|98.93±0.32|89.44±0.37|94.97|NeurIPS|2018|[link](https://github.com/elliotbeck/MetaReg_PyTorch)|[link](https://dl.acm.org/doi/pdf/10.5555/33326943.3327036)|MetaReg: Towards Domain Generalization using Meta-Regularization
Reptile|87.78|99.44|98.42|98.80|99.03|87.42|95.15|-|2018|-|[link](https://arxiv.org/pdf/1803.02999.pdf)|On fifirst-order meta-learning algorithms
Feature-Critic-Flatten|87.04±0.31|99.53±0.27|99.41±0.18|99.52±0.24|99.23±0.16|91.52±0.26|96.04|ICML|2019|[link](https://github.com/liyiying/Feature_Critic)|[link](http://proceedings.mlr.press/v97/li19l/li19l.pdf)|Feature-Critic Networks for Heterogeneous Domain Generalisation 
DG_via_ER|90.09±1.25|99.24±0.37|99.27±0.16|99.31±0.21|99.45±0.19|90.81±1.35|96.36|NeurIPS|2020|[link](https://github.com/sshan-zhao/DG_via_ER)|[link](https://proceedings.neurips.cc/paper/2020/file/b98249b38337c5088bbc660d8f872d6a-Paper.pdf)|Domain Generalization via Entropy Regularization
Feature-Critic-MLP|89.23±0.25|99.68±0.24|99.20±0.20|99.24±0.18|99.53±0.23|91.44±0.34|96.39|ICML|2019|[link](https://github.com/liyiying/Feature_Critic)|[link](http://proceedings.mlr.press/v97/li19l/li19l.pdf)|Feature-Critic Networks for Heterogeneous Domain Generalisation 
MetaVIB|91.28±0.21|99.90±0.02|99.29±0.11|99.78±0.10|99.57±0.13|92.75±0.31|97.08|ECCV|2020|-|[link](https://arxiv.org/pdf/2007.07645.pdf)|Learning to Learn with Variational Information Bottleneck for Domain Generalization
ERM|95.9|98.9|98.8|98.9|98.9|96.4|98.0|ICLR|2021|-|[link](https://arxiv.org/pdf/2007.01434)|In Search of Lost Domain Generalization

#### **Rotated Mnist<sup>2</sup>**
> Backbone: **LeNet**

Name|M<sub>15</sub>,M<sub>30</sub>,M<sub>45</sub>,M<sub>60</sub>,M<sub>75</sub>->M<sub>0</sub>,M<sub>90</sub>|M<sub>30</sub>,M<sub>45</sub>,M<sub>60</sub>->M<sub>0</sub>,M<sub>60</sub>|M<sub>30</sub>,M<sub>45</sub>->M<sub>0</sub>,M<sub>90</sub>|Avg|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
MASF|93.2±0.2|69.4±1.32|60.8±1.53|74.5|NeurIPS|2020|[link](https://github.com/biomedia-mira/masf)|[link](https://arxiv.org/pdf/1910.13580)|Domain Generalization via  Model-Agnostic Learning of Semantic Features
ERM|93.9±0.67|77.9±2.44|64.6±3.23|78.7|ICML(workshop)|2020|[link](https://github.com/microsoft/robustdg)|[link](https://arxiv.org/pdf/2006.07500.pdf)|Domain Generalization using Causal Matching
CSD|94.7±0.2|79.2±2.47|68.7±1.01|80.9|ICML|2020|[link](https://github.com/vihari/CSD)|[link](https://arxiv.org/pdf/2003.12815v2.pdf)|Proceedings of the International Conference of Machine Learning
MatchDG|95.1±0.25|83.6±1.44|69.7±1.30|-|ICML|2021|[link](https://github.com/microsoft/robustdg)|[link](https://arxiv.org/pdf/2006.07500.pdf)|Domain Generalization using Causal Matching

#### **Digit-Five**
> Backbone: **LeNet**

Name|Mnist|Mnist-M|USPS|SVHN|SYN|Avg|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
L2A-OT|96.7|63.9|-|68.6|83.2|78.1|ECCV|2020|[link](https://github.com/mousecpn/L2A-OT)|[link](https://arxiv.org/pdf/2007.03304)|Learning to Generate Novel Domains for Domain Generalization
DSON|89.62|79.00|91.63|81.02|95.34|87.32|ECCV|2020|-|[link](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123670069.pdf)|Learning to Optimize Domain Specifific Normalization for Domain Generalization



#### **DomainNet**

Name|Backbone|C|I|P|Q|R|S|Avg|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
DMG|AlexNet|50.06|12.23|34.44|13.07|46.98|30.13|31.15|ECCV|2020|[link](https://github.com/prithv1/DMG)|[link](https://arxiv.org/pdf/2008.12839)|Learning to Balance Specifificity and Invariance for In and Out of Domain Generalization 
DMG|ResNet18|60.07|18.76|44.53|14.16|54.72|41.73|39.00|ECCV|2020|[link](https://github.com/prithv1/DMG)|[link](https://arxiv.org/pdf/2008.12839)|Learning to Balance Specifificity and Invariance for In and Out of Domain Generalization 
DMG|ResNet50|58.1±0.3|18.8±0.3|467.±0.3|12.2±0.4|59.6±0.1|49.8±0.4|40.9|ECCV|2020|[link](https://github.com/prithv1/DMG)|[link](https://arxiv.org/pdf/2008.12839)|Learning to Balance Specifificity and Invariance for In and Out of Domain Generalization 
ERM|ResNet50|65.24|22.15|50.03|15.68|59.63|49.02|43.63|ICLR|2021|-|[link](https://arxiv.org/pdf/2007.01434)|In Search of Lost Domain Generalization

#### **LT-ImageNet**
Name|Backbone|Avg|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
ERM|ResNet50|53.7|CVPR|2021|[link](https://github.com/abhimanyudubey/GeoYFCC)|[link](https://openaccess.thecvf.com/content/CVPR2021/papers/Dubey_Adaptive_Methods_for_Real-World_Domain_Generalization_CVPR_2021_paper.pdf)|Adaptive Methods for Real-World Domain Generalization
DA-ERM|ResNet50|56.1|CVPR|2021|[link](https://github.com/abhimanyudubey/GeoYFCC)|[link](https://openaccess.thecvf.com/content/CVPR2021/papers/Dubey_Adaptive_Methods_for_Real-World_Domain_Generalization_CVPR_2021_paper.pdf)|Adaptive Methods for Real-World Domain Generalization

#### **Geo-YFCC**
Name|Backbone|Avg|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
ERM|ResNet50|22.4|CVPR|2021|[link](https://github.com/abhimanyudubey/GeoYFCC)|[link](https://openaccess.thecvf.com/content/CVPR2021/papers/Dubey_Adaptive_Methods_for_Real-World_Domain_Generalization_CVPR_2021_paper.pdf)|Adaptive Methods for Real-World Domain Generalization
DA-ERM|ResNet50|23.4|CVPR|2021|[link](https://github.com/abhimanyudubey/GeoYFCC)|[link](https://openaccess.thecvf.com/content/CVPR2021/papers/Dubey_Adaptive_Methods_for_Real-World_Domain_Generalization_CVPR_2021_paper.pdf)|Adaptive Methods for Real-World Domain Generalization

## 2.3 Sigle Source DG
#### **Digit-Five**
> Backbone: **LeNet**

Name|Mnist|Mnist-M|USPS|SVHN|SYN|Avg|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
RSDA+ASR|-|80.8±0.6|82.4±1.4|52.8±3.8 |64.5±1.1 |70.1|CVPR|2021|-|[link](https://openaccess.thecvf.com/content/CVPR2021/papers/Fan_Adversarially_Adaptive_Normalization_for_Single_Domain_Generalization_CVPR_2021_paper.pdf)
PDEN|-|82.2|85.26|62.21|69.39|74.77|CVPR|2021|[link](https://github.com/lileicv/PDEN)|[link](https://openaccess.thecvf.com/content/CVPR2021/papers/Li_Progressive_Domain_Expansion_Network_for_Single_Domain_Generalization_CVPR_2021_paper.pdf)

#### **CIFAR10-C**
Name|BackBone|Level1|Level2|Level3|Level4|Level5|Avg|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
ADA+ASR|WRN|91.5±0.2|89.3±0.6|86.9±0.5|83.7±0.7|78.4±0.8|86|CVPR|2021|-|[link](https://openaccess.thecvf.com/content/CVPR2021/papers/Fan_Adversarially_Adaptive_Normalization_for_Single_Domain_Generalization_CVPR_2021_paper.pdf)|Adversarially Adaptive Normalization for Single Domain Generalization
PDEN|STN|90.62|88.91|87.03|83.71|77.47|85.55|CVPR|2021|[link](https://github.com/lileicv/PDEN)|[link](https://openaccess.thecvf.com/content/CVPR2021/papers/Li_Progressive_Domain_Expansion_Network_for_Single_Domain_Generalization_CVPR_2021_paper.pdf)|Progressive Domain Expansion Network for Single Domain Generalization


#### **PACS**
Name|Backbone|Art Painting|Cartoon|Photo|Sketch|Avg|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
RSC+ASR|ResNet18|76.7|79.3|54.6|61.6|68.1|CVPR|2021|-|[link](https://openaccess.thecvf.com/content/CVPR2021/papers/Fan_Adversarially_Adaptive_Normalization_for_Single_Domain_Generalization_CVPR_2021_paper.pdf)|Adversarially Adaptive Normalization for Single Domain Generalization

## 2.4 FedDG
* Only one paper about medical segmentation so far

Name|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|
ELCFS|CVPR|2021|[link](https://github.com/liuquande/FedDG-ELCFS)|[link](https://openaccess.thecvf.com/content/CVPR2021/papers/Liu_FedDG_Federated_Domain_Generalization_on_Medical_Image_Segmentation_via_Episodic_CVPR_2021_paper.pdf)|FedDG: Federated Domain Generalization on Medical Image Segmentation via Episodic Learning in Continuous Frequency Space|

## 2.5 Open Domain Generalization
#### **PACS**
Name|Backbone|Art Painting|Cartoon|Photo|Sketch|Avg|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
DAML|-|54.10|58.50|75.69|73.65|65.49±0.36|CVPR|2021.0|-|[link](https://openaccess.thecvf.com/content/CVPR2021/papers/Shu_Open_Domain_Generalization_with_Domain-Augmented_Meta-Learning_CVPR_2021_paper.pdf)|Open Domain Generalization with Domain-Augmented Meta-Learning

#### **VLCS**
Name|Backbone|Art Painting|Cartoon|Photo|Sketch|Avg|Conference|Year|Code Url|Paper Url|Title
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
DAML|-|45.13|65.99|61.54|53.13|56.45±0.21|CVPR|2021.0|-|[link](https://openaccess.thecvf.com/content/CVPR2021/papers/Shu_Open_Domain_Generalization_with_Domain-Augmented_Meta-Learning_CVPR_2021_paper.pdf)|Open Domain Generalization with Domain-Augmented Meta-Learning
