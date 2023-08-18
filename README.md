# Reliable MRC
> Paper list for Reliable Machine Reading Comprehension, including topics related to robustness, prediction safety, and continual learning.

## Table of Contents
- [Machine Reading Comprehension Overview](#Machine-Reading-Comprehension-Overview)
- [Enhancing Robustness in Machine Reading Comprehension](#Enhancing-Robustness-in-Machine-Reading-Comprehension)
- [Ensuring Prediction Safety in Machine Reading Comprehension](#Ensuring-Prediction-Safety-in-Machine-Reading-Comprehension)
- [Advancing Continual Learning in Machine Reading Comprehension](#Advancing-Continual-Learning-in-Machine-Reading-Comprehension)



## Machine Reading Comprehension Overview
### Datasets
- Hermann K M, Kociský T, Grefenstette E, et al. **Teaching machines to read and comprehend.** Proceedings of the 28th International Conference on Neural Information Processing Systems. 2015: 1693-1701. [paper](https://proceedings.neurips.cc/paper_files/paper/2015/file/afdec7005cc9f14302cd0474fd0f3c96-Paper.pdf)
- Rajpurkar P, Zhang J, Lopyrev K, et al. **Squad: 100, 000+ questions for machine comprehension of text.** Proceedings of the 2016 Conference on Empirical Methods in Natural Language Processing. 2016: 2383-2392. [paper](https://aclanthology.org/D16-1264/)
- Dhingra B, Mazaitis K, Cohen W W. **Quasar: Datasets for question answering by search and reading.** CoRR, 2017, abs/1707.03904. [paper](http://arxiv.org/abs/1707.03904)
- Yagcioglu S, Erdem A, Erdem E, et al. **Recipeqa: A challenge dataset for multimodal compreension of cooking recipes.** Proceedings of the 2018 Conference on Empirical Methods in Natural Language Processing. 2018: 1358-1368. [paper](https://aclanthology.org/D18-1166.pdf)
- Trischler A, Wang T, Yuan X, et al. **Newsqa: A machine comprehension dataset. Proceedings of the 2nd Workshop on Representation Learning for NLP.** 2017: 191-200. [paper](https://aclanthology.org/W17-2623.pdf)
- Dunn M, Sagun L, Higgins M, et al. **Searchqa: A new q&a dataset augmented with context from a search engine.** CoRR, 2017, abs/1704.05179. [paper](https://arxiv.org/abs/1704.05179)
- Lai G, Xie Q, Liu H, et al. **RACE: large-scale reading comprehension dataset from examinations.** Proceedings of the 2017 Conference on Empirical Methods in Natural Language Processing. 2017: 785-794. [paper](https://aclanthology.org/D17-1082/)
- Ostermann S, Modi A, Roth M, et al. **Mcscript: A novel dataset for assessing machine comprehension using script knowledge.** Proceedings of the Eleventh International Conference on Language Resources and Evaluation. 2018. [paper](http://www.lrec-conf.org/proceedings/lrec2018/pdf/225.pdf)
- Tapaswi M, Zhu Y, Stiefelhagen R, et al. **Movieqa: Understanding stories in movies through question-answering.** Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2016: 4631-4640. [paper](https://ieeexplore.ieee.org/document/7780870)
- Nguyen T, Rosenberg M, Song X, et al. **MS MARCO: A human generated machine reading comprehension dataset.** choice, 2016, 2640: 660. [paper](https://arxiv.org/abs/1611.09268)
- Kociský T, Schwarz J, Blunsom P, et al. **The narrativeqa reading comprehension challenge.** Transactions of the Association for Computational Linguistics, 2018, 6: 317-328. [paper](https://aclanthology.org/Q18-1023/)
- Zhang S, Liu X, Liu J, et al. **Record: Bridging the gap between human and machine commonsense reading comprehension.** CoRR, 2018, abs/1810.12885. [paper](https://arxiv.org/abs/1810.12885)
- Yang Z, Qi P, Zhang S, et al. **Hotpotqa: A dataset for diverse, explainable multi-hop question answering.** Proceedings of the 2018 Conference on Empirical Methods in Natural Language Processing. 2018: 2369-2380. [paper](https://aclanthology.org/D18-1259/)
- Reddy S, Chen D, Manning C D. **Coqa: A conversational question answering challenge.** Transactions of the Association for Computational Linguistics, 2019, 7: 249-266. [paper](https://aclanthology.org/Q19-1016.pdf)



### MRC Models based on Attention Mechanism  
- Mikolov T, Sutskever I, Chen K, et al. **Distributed representations of words and phrases and their compositionality.** Proceedings of the 26th International Conference on Neural Information Processing Systems. 2013: 3111-3119. [paper](https://papers.nips.cc/paper_files/paper/2013/file/9aa42b31882ec039965f3c4923ce901b-Paper.pdf)
- Pennington J, Socher R, Manning C D. **Glove: Global vectors for word representation.**  Proceedings of the 2014 Conference on Empirical Methods in Natural Language Processing. 2014: 1532-1543. [paper](https://aclanthology.org/D14-1162/)
- Bojanowski P, Grave E, Joulin A, et al. **Enriching word vectors with subword information.** Transactions of the Association for Computational Linguistics, 2017, 5: 135-146. [paper](https://aclanthology.org/Q17-1010.pdf)
- Peters M E, Neumann M, Iyyer M, et al. **Deep contextualized word representations.**  Proceedings of the 2018 Conference of the North American Chapter of the Association for Computational Linguistics. 2018: 2227-2237. [paper](https://aclanthology.org/N18-1202/)
- Seo M J, Kembhavi A, Farhadi A, et al. **Bidirectional attention flow for machine comprehension.** The 5th International Conference on Learning Representations. 2017. [paper](https://openreview.net/forum?id=HJ0UKP9ge)
- Chen D, Fisch A, Weston J, et al. **Reading wikipedia to answer open-domain questions.**  Proceedings of the 55th Annual Meeting of the Association for Computational Linguistics. 2017: 1870-1879. [paper](https://aclanthology.org/P17-1171/)
- Hermann K M, Kociský T, Grefenstette E, et al. **Teaching machines to read and comprehend.**  Proceedings of the 28th International Conference on Neural Information Processing Systems. 2015: 1693-1701. [paper](https://proceedings.neurips.cc/paper_files/paper/2015/file/afdec7005cc9f14302cd0474fd0f3c96-Paper.pdf)
- Chen D, Bolton J, Manning C D. **A thorough examination of the cnn/daily mail reading comprehension task.** Proceedings of the 54th Annual Meeting of the Association for Computational Linguistics. 2016: 2358-2367. [paper](https://aclanthology.org/P16-1223/)
- Kadlec R, Schmid M, Bajgar O, et al. **Text understanding with the attention sum reader network.** Proceedings of the 54th Annual Meeting of the Association for Computational Linguistics. 2016: 908-918. [paper](https://aclanthology.org/P16-1086/)
- Cui Y, Chen Z, Wei S, et al. **Attention-over-attention neural networks for reading comprehension.** Proceedings of the 55th Annual Meeting of the Association for Computational Linguistics. 2017: 593-602. [paper](https://aclanthology.org/P17-1055/)
- Wang W, Yang N, Wei F, et al. **Gated self-matching networks for reading comprehension and question answering.** Proceedings of the 55th Annual Meeting of the Association for Computational Linguistics. 2017: 189-198. [paper](https://aclanthology.org/P17-1018/)
- Yu A W, Dohan D, Luong M, et al. **Qanet: Combining local convolution with global self-attention for reading comprehension.** The 6th International Conference on Learning Repre sentations. 2018. [paper](https://openreview.net/forum?id=B14TlG-RW)
- Zhang S, Zhao H, Wu Y, et al. **DCMN+: dual co-matching network for multi-choice reading comprehension.** Proceedings of the AAAI Conference on Artificial Intelligence. 2020: 9563-9570. [paper](https://ojs.aaai.org/index.php/AAAI/article/view/6502/6358)
- Chen Z, Cui Y, Ma W, et al. **Convolutional spatial attention model for reading comprehension with multiple-choice questions.** Proceedings of the AAAI Conference on Artificial Intelligence. 2019: 6276-6283. [paper](https://ojs.aaai.org/index.php/AAAI/article/view/4588/4466)
- Ran Q, Li P, Hu W, et al. **Option comparison network for multiple-choice reading comprehension.** CoRR, 2019, abs/1903.03033. [paper](https://arxiv.org/abs/1903.03033)
- Wang W, Wu C, Yan M. **Multi-granularity hierarchical attention fusion networks for reading comprehension and question answering.** Proceedings of the 56th Annual Meeting of the Association for Computational Linguistics. 2018: 1705-1714. [paper](https://aclanthology.org/P18-1158/)
- Wang S, Jiang J. **Machine comprehension using match-lstm and answer pointer.** The 5th International Conference on Learning Representations. 2017. [paper](https://openreview.net/forum?id=B1-q5Pqxl)
- Hu M, Wei F, Peng Y, et al. **Read + verify: Machine reading comprehension with unanswerable questions.** Proceedings of the AAAI Conference on Artificial Intelligence. 2019: 6529-6537. [paper](https://ojs.aaai.org/index.php/AAAI/article/view/4619/4497)
- Tan C, Wei F, Yang N, et al. **S-net: From answer extraction to answer synthesis for machine reading comprehension.** Proceedings of the AAAI Conference on Artificial Intelligence. 2018: 5940-5947. [paper](https://ojs.aaai.org/index.php/AAAI/article/view/12035/11894)

### MRC Models based on Pretrained Language Models 
- Vaswani A, Shazeer N, Parmar N, et al. **Attention is all you need.** Proceedings of the 31st International Conference on Neural Information Processing Systems. 2017: 5998-6008. [paper](https://proceedings.neurips.cc/paper_files/paper/2017/file/3f5ee243547dee91fbd053c1c4a845aa-Paper.pdf)
- Radford A, Narasimhan K, Salimans T, et al. **Improving language understanding by generative pre-training.** OpenAI, 2018. [paper](https://s3-us-west-2.amazonaws.com/openai-assets/research-covers/language-unsupervised/language_understanding_paper.pdf)
- Devlin J, Chang M, Lee K, et al. **BERT: pre-training of deep bidirectional transformers for language understanding.** Proceedings of the 2019 Conference of the North American Chapter of the Association for Computational Linguistics. 2019: 4171-4186. [paper](https://aclanthology.org/N19-1423)
- Liu Y, Ott M, Goyal N, et al. **Roberta: A robustly optimized BERT pretraining approach.** CoRR, 2019, abs/1907.11692. [paper](https://openreview.net/forum?id=SyxS0T4tvS)
- Raffel C, Shazeer N, Roberts A, et al. **Exploring the limits of transfer learning with a unified text-to-text transformer.** Journal of Machine Learning Research, 2020, 21: 140:1-140:67. [paper](https://jmlr.org/papers/volume21/20-074/20-074.pdf)
- Joshi M, Chen D, Liu Y, et al. **Spanbert: Improving pre-training by representing and predicting spans.** Transactions of the Association for Computational Linguistics, 2020, 8: 64-77. [paper](https://aclanthology.org/2020.tacl-1.5/)
- Yang A, Wang Q, Liu J, et al. **Enhancing pre-trained language representations with rich knowledge for machine reading comprehension.** Proceedings of the 57th Conference of the Association for Computational Linguistics. 2019: 2346-2357. [paper](https://aclanthology.org/P19-1226/)
- Ram O, Kirstain Y, Berant J, et al. **Few-shot question answering by pretraining span selection.** Proceedings of the 59th Annual Meeting of the Association for Computational Linguistics. 2021: 3066-3079. [paper](https://aclanthology.org/2021.acl-long.239.pdf)
- Jiao F, Guo Y, Niu Y, et al. **REPT: bridging language models and machine reading comprehension via retrieval-based pre-training.** Findings of the Association for Computational Linguistics: ACL 2021. 2021: 150-163. [paper](https://aclanthology.org/2021.findings-acl.13/)
- Dua D, Wang Y, Dasigi P, et al. **DROP: A reading comprehension benchmark requiring discrete reasoning over paragraphs.** Proceedings of the 2019 Conference of the North American Chapter of the Association for Computational Linguistics. 2019: 2368-2378. [paper](https://aclanthology.org/N19-1246/)
- Ran Q, Lin Y, Li P, et al. **Numnet: Machine reading comprehension with numerical reasoning.** Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing. 2019: 2474-2484. [paper](https://aclanthology.org/D19-1251/)
- Zhou Y, Bao J, Duan C, et al. **OPERA: operation-pivoted discrete reasoning over text.** Proceedings of the 2022 Conference of the North American Chapter of the Association for Computational Linguistics. 2022: 1655-1666. [paper](https://aclanthology.org/2022.naacl-main.119/)
- Shakeri S, dos Santos C N, Zhu H, et al. **End-to-end synthetic data generation for domain adaptation of question answering systems.** Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing. 2020: 5445-5460. [paper](https://aclanthology.org/2020.emnlp-main.439/)
- Cao Y, Fang M, Yu B, et al. **Unsupervised domain adaptation on reading comprehension.** Proceedings of the AAAI Conference on Artificial Intelligence. 2020: 7480-7487. [paper](https://ojs.aaai.org/index.php/AAAI/article/view/6245/6101)
- Wang H, Yu D, Sun K, et al. **Evidence sentence extraction for machine reading comprehension.** Proceedings of the 23rd Conference on Computational Natural Language Learning. 2019: 696-707. [paper](https://aclanthology.org/K19-1065/)
- Chen N, Shou L, Gong M, et al. **From good to best: Two-stage training for cross-lingual machine reading comprehension.** Proceedings of the AAAI Conference on Artificial Intelligence. 2022: 10501-10508. [paper](https://ojs.aaai.org/index.php/AAAI/article/view/21293/21042)
- Wu L, Wu S, Zhang X, et al. **Learning disentangled semantic representations for zero-shot cross-lingual transfer in multilingual machine reading comprehension.** Proceedings of the 60th Annual Meeting of the Association for Computational Linguistics. 2022: 991-1000. [paper](https://aclanthology.org/2022.acl-long.70)
- Liu J, Chen Y, Liu K, et al. **Event extraction as machine reading comprehension.** Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing. 2020: 1641-1651. [paper](https://aclanthology.org/2020.emnlp-main.128/)
- Yu M, Liu J, Chen Y, et al. **Cross-domain slot filling as machine reading comprehension.**  Proceedings of the Thirtieth International Joint Conference on Artificial Intelligence. 2021: 3992-3998. [paper](https://www.ijcai.org/proceedings/2021/0550.pdf)
- Yang Y, Zhao H. **Aspect-based sentiment analysis as machine reading comprehension.**  Proceedings of the 29th International Conference on Computational Linguistics. 2022: 2461-2471. [paper](https://aclanthology.org/2022.coling-1.217/)
- Khashabi D, Min S, Khot T, et al. **Unifiedqa: Crossing format boundaries with a single QA system.** Findings of the Association for Computational Linguistics: EMNLP 2020. 2020: 1896-1907. [paper](https://aclanthology.org/2020.findings-emnlp.171/)
- Khashabi D, Kordi Y, Hajishirzi H. **Unifiedqa-v2: Stronger generalization via broader crossformat training.** CoRR, 2022, abs/2202.12359. [paper](https://arxiv.org/abs/2202.12359)
- Wang J, Wang C, Qiu M, et al. **KECP: knowledge enhanced contrastive prompting for few-shot extractive question answering.** Proceedings of the 2022 Conference on Empirical Methods in Natural Language Processing. 2022: 3152-3163. [paper](https://aclanthology.org/2022.emnlp-main.206/)


## Enhancing Robustness in Machine Reading Comprehension
### Attack Method 
- Feng S, Wallace E, Grissom II A, et al. **Pathologies of neural models make interpretations difficult.** Proceedings of the 2018 Conference on Empirical Methods in Natural Language Processing. Association for Computational Linguistics, 2018: 3719-3728. [paper](https://aclanthology.org/D18-1407/)
- MinS, ZhongV, SocherR, et al. **Efficient and robust question answering from minimal context over documents.** Proceedings of the 56th Annual Meeting of the Association for Computational Linguistics. 2018: 1725-1735. [paper](https://aclanthology.org/P18-1160/)
- Jiang Y, Bansal M. **Avoiding reasoning shortcuts: Adversarial evaluation, training, and model development for multi-hop QA.** Proceedings of the 57th Conference of the Association for Computational Linguistics. 2019: 2726-2736. [paper](https://aclanthology.org/P19-1262/)
- Lai Y, Zhang C, Feng Y, et al. **Why machine reading comprehension models learn shortcuts?.** Findings of the Association for Computational Linguistics: ACL 2021. 2021: 989-1002. [paper](https://aclanthology.org/2021.findings-acl.85/)
- Zhou X, Luo S, Wu Y. **Co-attention hierarchical network: Generating coherent long distractors for reading comprehension.** Proceedings of the AAAI Conference on Artificial Intelligence. 2020: 9725-9732. [paper](https://ojs.aaai.org/index.php/AAAI/article/view/6522/6378)
- Gao Y, Bing L, Li P, et al. **Generating distractors for reading comprehension questions from real examinations.** Proceedings of the AAAI Conference on Artificial Intelligence. 2019: 6423-6430. [paper](https://ojs.aaai.org/index.php/AAAI/article/view/4606/4484)
- Welbl J, Liu NF, Gardner M. **Crowdsourcing multiple choice science questions.** Proceedings of the 3rd Workshop on Noisy User-generated Text. 2017: 94-106. [paper](https://aclanthology.org/W17-4413/)
- Chen C, Liou H, Chang J S. **FAST - an automatic generation system for grammar tests.**  Proceedings of the 44th Annual Meeting of the Association for Computational Linguistics. 2006. [paper](https://aclanthology.org/P06-4001/)
- Stasaski K, Hearst M A. **Multiple choice question generation utilizing an ontology.**  Proceedings of the 12th Workshop on Innovative Use of NLP for Building Educational Applications. 2017: 303-312. [paper](https://aclanthology.org/W17-5034/)
- Jia R, Liang P. **Adversarial examples for evaluating reading comprehension systems.**  Proceedings of the 2017 Conference on Empirical Methods in Natural Language Processing. 2017: 2021-2031. [paper](https://aclanthology.org/D17-1215/)
- Wang Y, Bansal M. **Robust machine comprehension models via adversarial training.** Proceedings of the 2018 Conference of the North American Chapter of the Association for Computational Linguistics. 2018: 575-581. [paper](https://aclanthology.org/N18-2091/)
- Gan W C, Ng H T. **Improving the robustness of question answering systems to question paraphrasing.** Proceedings of the 57th Conference of the Association for Computational Linguistics. 2019: 6065-6075. [paper](https://aclanthology.org/P19-1610/)
- Wu W, Arendt D, Volkova S. **Evaluating neural machine comprehension model robustness to noisy inputs and adversarial attacks.** CoRR, 2020, abs/2005.00190. [paper](https://aclanthology.org/2021.eacl-main.210)
- Wallace E, Feng S, Kandpal N, et al. **Universal adversarial triggers for attacking and analyzing NLP.** Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing. 2019: 2153-2162. [paper](https://aclanthology.org/D19-1221/)
- Ribeiro MT, Wu T, Guestrin C, e tal. **Beyond accuracy: Behavior altesting of NLP models with checklist.** Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics. 2020: 4902-4912. [paper](https://aclanthology.org/2020.acl-main.442/)

### Defense Method 
- Jia R, Liang P. **Adversarial examples for evaluating reading comprehension systems.**  Proceedings of the 2017 Conference on Empirical Methods in Natural Language Processing. 2017: 2021-2031. [paper](https://aclanthology.org/D17-1215/)
- Wallace E, Feng S, Kandpal N, et al. **Universal adversarial triggers for attacking and analyzing NLP.** Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing. 2019: 2153-2162. [paper](https://aclanthology.org/D19-1221/)
- Wang Y, Bansal M. **Robust machine comprehension models via adversarial training.**  Proceedings of the 2018 Conference of the North American Chapter of the Association for Computational Linguistics. 2018: 575-581. [paper](https://aclanthology.org/N18-2091/)
- Gan W C, Ng H T. **Improving the robustness of question answering systems to question paraphrasing.** Proceedings of the 57th Conference of the Association for Computational Linguistics. 2019: 6065-6075. [paper](https://aclanthology.org/P19-1610/)
- Yang Z, Cui Y, Che W, et al. **Improving machine reading comprehension via adversarial training.** CoRR, 2019, abs/1911.03614. [paper](https://arxiv.org/abs/1911.03614)
- Liu K, Liu X, Yang A, et al. **A robust adversarial training approach to machine reading comprehension.** Proceedings of the AAAI Conference on Artificial Intelligence. 2020: 8392-8400. [paper](https://ojs.aaai.org/index.php/AAAI/article/view/6357)
- Yeh Y, Chen Y. **Qainfomax: Learning robust question answering system by mutual information maximization.** Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing. 2019: 3368-3373. [paper](https://aclanthology.org/D19-1333/)
- Zhou M, Huang M, Zhu X. **Robust reading comprehension with linguistic constraints via posterior regularization.** IEEE Transactions on Audio, Speech, and Language Processing, 2020, 28: 2500-2510. [paper](https://ieeexplore.ieee.org/document/9165888)
- Wang C, Jiang H. **Explicit utilization of general knowledge in machine reading comprehension.** Proceedings of the 57th Conference of the Association for Computational Linguistics. 2019: 2263-2272. [paper](https://aclanthology.org/P19-1219/)
- Mihaylov T, Frank A. **Knowledgeable reader: Enhancing cloze-style reading comprehension with external commonsense knowledge.** Proceedings of the 56th Annual Meeting of the Association for Computational Linguistics. 2018: 821-832. [paper](https://aclanthology.org/P18-1076/)
- ChenQ, ZhuX, LingZ, et al. **Neural natural language inference models enhanced with external knowledge.** Proceedings of the 56th Annual Meeting of the Association for Computational Linguistics. 2018: 2406-2417. [paper](https://aclanthology.org/P18-1224/)
- Feng S, Wallace E, Grissom II A, et al. **Pathologies of neural models make interpretations difficult.** Proceedings of the 2018 Conference on Empirical Methods in Natural Language Processing. Association for Computational Linguistics, 2018: 3719-3728. [paper](https://aclanthology.org/D18-1407/)
- Yang A, Wang Q, Liu J, et al. **Enhancing pre-trained language representations with rich knowledge for machine reading comprehension.** Proceedings of the 57th Conference of the Association for Computational Linguistics. 2019: 2346-2357. [paper](https://aclanthology.org/P19-1226/)

## Ensuring Prediction Safety in Machine Reading Comprehension
### Traditional Uncertainty Estimation Methods 
- Hendrycks D, Gimpel K. **A baseline for detecting misclassified and out-of-distribution examples in neural networks.** The 5th International Conference on Learning Representations. 2017. [paper](https://openreview.net/forum?id=Hkg4TI9xl)
- Guo C, Pleiss G, Sun Y, et al. **On calibration of modernneural networks.** Proceedingsofthe 34th International Conference on Machine Learning. 2017: 1321-1330. [paper](https://proceedings.mlr.press/v70/guo17a/guo17a.pdf)
- Kuleshov V, Fenner N, Ermon S. **Accurate uncertainties for deep learning using calibrated regression.** Proceedings of the 35th International Conference on Machine Learning. 2018: 2801-2809. [paper](https://proceedings.mlr.press/v80/kuleshov18a/kuleshov18a.pdf)
- Maroñas J, Paredes R, Ramos D. **Calibration of deep probabilistic models with decoupled bayesian neural networks.** Neurocomputing, 2020, 407: 194-205. [paper](https://www.sciencedirect.com/science/article/abs/pii/S0925231220307438)
- Gal Y, Ghahramani Z. **Dropout as a bayesian approximation: Representing model uncertainty in deep learning.** Proceedings of the 33rd International Conference on Machine Learning. 2016: 1050-1059. [paper](http://proceedings.mlr.press/v48/gal16.pdf)
- Kamath A, Jia R, Liang P. **Selective question answering under domain shift.** Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics. 2020: 5684-5696. [paper](https://aclanthology.org/2020.acl-main.503/)
- Jeong S, Baek J, Hwang S J, et al. **Realistic conversational question answering with answer selection based on calibrated confidence and uncertainty measurement.** Proceedings of the 18th Conference of the European Chapter of the Association for Computational Linguistics. 2023. [paper](https://aclanthology.org/2023.eacl-main.35/)
- Raina V, Gales M J F. **Answer uncertainty and unanswerability in multiple-choice machine reading comprehension.** Findings of the Association for Computational Linguistics: ACL 2022. 2022: 1020-1034. [paper](https://aclanthology.org/2022.findings-acl.82/)
- Li M, Li M, Xiong K, et al. **Multi-task dense retrieval via model uncertainty fusion for open-domain question answering.** Findings of the Association for Computational Linguistics: EMNLP 2021. 2021: 274-287. [paper](https://aclanthology.org/2021.findings-emnlp.26/)


### Methods in Machine Reading Comprehension
- Hendrycks D, Gimpel K. **A baseline for detecting misclassified and out-of-distribution examples in neural networks.** The 5th International Conference on Learning Representations. 2017. [paper](https://openreview.net/forum?id=Hkg4TI9xl)
- Gonzalez A V, Bansal G, Fan A, et al. **Human evaluation of spoken vs. visual explanations for open-domain QA.** CoRR, 2020, abs/2012.15075. [paper](https://arxiv.org/abs/2012.15075)
- Liusie A, Raina V, Gales MJF. **“worldknowledge” in multiple choice reading comprehension.** CoRR, 2022, abs/2211.07040. [paper](https://aclanthology.org/2023.fever-1.5/)
- Jiang Z, Araki J, Ding H, et al. **How can we know when language models know? on the calibration of language models for question answering.** Transactions of the Association for Computational Linguistics, 2021, 9: 962-977. [paper](https://aclanthology.org/2021.tacl-1.57/)
- Si C, Zhao C, Min S, et al. **Re-examining calibration: The case of question answering.**  Findings of the Association for Computational Linguistics: EMNLP 2022. 2022: 2814-2829. [paper](https://aclanthology.org/2022.findings-emnlp.204/)
- Kamath A, Jia R, Liang P. **Selective question answering under domain shift.** Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics. 2020: 5684-5696. [paper](https://aclanthology.org/2020.acl-main.503/)
- Su L, Guo J, Fan Y, et al. **Controlling risk of web question answering.** Proceedings of the 42nd International ACM SIGIR Conference on Research and Development in Information Retrieval. 2019: 115-124. [paper](https://dl.acm.org/doi/10.1145/3331184.3331261)
- Zhang S, Gong C, Choi E. **Knowing more about questions can help: Improving calibration in question answering.** Findings of the Association for Computational Linguistics: ACL 2021. 2021: 1958-1970. [paper](https://aclanthology.org/2021.findings-acl.172/)
- YeX, DurrettG. **Can explanations be useful for calibrating blackbox models?.** Proceedings of the 60th Annual Meeting of the Association for Computational Linguistics. 2022: 6199-6212. [paper](https://aclanthology.org/2022.acl-long.429/)
- Xing L, Hu Y, Xie Y, et al. **Calibration of the multiple choice machine reading comprehension.** International Joint Conference on Neural Networks, IJCNN 2022, Padua, Italy, July 18-23, 2022. 2022: 1-8. [paper](https://ieeexplore.ieee.org/document/9892434)
- Kumar S. **Answer-level calibration for free-form multiple choice question answering.**  Proceedings of the 60th Annual Meeting of the Association for Computational Linguistics. 2022: 665-679. [paper](https://aclanthology.org/2022.acl-long.49/)
- Jiang Z, Araki J, Ding H, et al. **How can we know when language models know? on the calibration of language models for question answering.** Transactions of the Association for Computational Linguistics, 2021, 9: 962-977. [paper](https://aclanthology.org/2021.tacl-1.57/)

## Advancing Continual Learning in Machine Reading Comprehension
### Traditional  Continual Learning Methods
- French RM. **Catastrophic forgetting in connectionist networks.** Trends in Cognitive Sciences, 1999, 3(4): 128-135. [paper](https://www.sciencedirect.com/science/article/abs/pii/S1364661399012942)
- Yoon J, Yang E, Lee J, et al. **Lifelong learning with dynamically expandable networks.** The 6th International Conference on Learning Representations. 2018. [paper](https://openreview.net/forum?id=Sk7KsfW0-)
- Xu J, Zhu Z. **Reinforced continual learning.** Proceedings of the 32nd International Conference on Neural Information Processing Systems. 2018: 907-916. [paper](https://proceedings.neurips.cc/paper_files/paper/2018/file/cee631121c2ec9232f3a2f028ad5c89b-Paper.pdf)
- Kirkpatrick J, Pascanu R, Rabinowitz N, et al. **Overcoming catastrophic forgetting in neural networks.** Proceedings of the national academy of sciences, 2017, 114(13): 3521-3526. [paper](https://www.pnas.org/doi/10.1073/pnas.1611835114)
- Schwarz J, Czarnecki W, Luketina J, et al. **Progress & compress: A scalable framework for continual learning.** Proceedings of the 35th International Conference on Machine Learning. 2018: 4535-4544.  [paper](https://proceedings.mlr.press/v80/schwarz18a/schwarz18a.pdf)
- Lopez-Paz D, Ranzato M. **Gradient episodic memory for continual learning.** Proceedingsof the 31st International Conference on Neural Information Processing Systems. 2017: 6467-6476.  [paper](https://proceedings.neurips.cc/paper_files/paper/2017/file/f87522788a2be2d171666752f97ddebb-Paper.pdf)
- Chaudhry A, Ranzato M, Rohrbach M, et al. **Efficient lifelong learning with A-GEM.** The 7th International Conference on Learning Representations. 2019. [paper](https://openreview.net/forum?id=Hkf2_sC5FX)
- Riemer M, Cases I, Ajemian R, et al. **Learning to learn without forgetting by maximizing transfer and minimizing interference.** The 7th International Conference on Learning Representations. 2019. [paper](https://openreview.net/forum?id=B1gTShAct7)
- Wu C, Herranz L, Liu X, et al. **Memory replay gans: Learning to generate new categories without forgetting.** Proceedings of the 32nd International Conference on Neural Information Processing Systems. 2018: 5966-5976.  [paper](https://proceedings.neurips.cc/paper/2018/hash/a57e8915461b83adefb011530b711704-Abstract.html)
- Chaudhry A, Dokania PK, Ajanthan T,et al. **Riemannian walk for incremental learning: Understanding forgetting and intransigence.** Proceedings of the European Conference on Computer Vision. 2018: 556-572. [paper](https://openaccess.thecvf.com/content_ECCV_2018/papers/Arslan_Chaudhry__Riemannian_Walk_ECCV_2018_paper.pdf)
- Shim D, Mai Z, Jeong J, et al. **Online class-incremental continual learning with adversarial shapley value.** Thirty-Fifth AAAI Conference on Artificial Intelligence. 2021: 9630-9638.  [paper](https://ojs.aaai.org/index.php/AAAI/article/view/17159/16966)
- Buzzega P, Boschini M, Porrello A, et al. **Dark experience for general continual learning: a strong, simple baseline.** Proceedings of the 34th International Conference on Neural Information Processing Systems. 2020. [paper](https://proceedings.neurips.cc/paper/2020/file/b704ea2c39778f07c617f6b7ce480e9e-Paper.pdf)

### Methods in Machine Reading Comprehension
- Su L, Guo J, Zhang R, et al. **Continual domain adaptation for machine reading comprehension.** Proceedings of the 29th ACM International Conference on Information and Knowledge Management. 2020: 1395-1404.  [paper](https://dl.acm.org/doi/abs/10.1145/3340531.3412047)
- deMasson d’AutumeC, Ruder S, Kong L, et al. **Episodic memory in lifelong language learning.** Proceedings of the 33rd International Conference on Neural Information Processing Systems. 2019: 13122-13131.  [paper](https://proceedings.neurips.cc/paper_files/paper/2019/file/f8d2e80c1458ea2501f98a2cafadb397-Paper.pdf)
- Wang Z, Mehta SV,Póczos B,et al. **Efficient meta lifelong-learning with limited memory.**  Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing. 2020: 535-548. [paper](https://aclanthology.org/2020.emnlp-main.39/)
- Abujabal A, Roy R S, Yahya M, et al. **Never-ending learning for open-domain question answering over knowledge bases.** Proceedings of the 2018 World Wide Web Conference. 2018: 1053-1062. [paper](https://dl.acm.org/doi/10.1145/3178876.3186004)
- Echegoyen G, Rodrigo Á, Peñas A. **Study of a lifelong learning scenario for question answering.** Expert Systems with Applications, 2022, 209: 118271. [paper](https://www.sciencedirect.com/science/article/pii/S0957417422014117)
- Zhong W, Gao Y, Ding N, et al. **Proqa: Structural prompt-based pre-training for unified question answering.** Proceedings of the 2022 Conference of the North American Chapter of the Association for Computational Linguistics. 2022: 4230-4243. [paper](https://aclanthology.org/2022.naacl-main.313/)
- Zheng Y. **Continuous qa learning with structured prompts.** 2022: arXiv-2208. [paper](https://arxiv.org/abs/2208.14602)
