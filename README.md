# Large Language Model for Graph Representation Learning (LLM4Graph)

## Motivation
Large Language Model (LLM) has revolutionized lots of areas and is now making its way into conventional graph representation learning. Some empirical evidence already shows that, with the powerful LLM, graph neural network doesn't seem to be irreplaceable and this trend is inevitable and unstoppable. So we will try to embrace it and keep track of its development. In this repository, we collect papers focusing on **LLM for graph learning tasks at node, edge and graph levels**. If you find that we miss any related work or we need to update information (publication, code, blog, etc. ) of the following papers, feel free to let us know by email (sitao.luan@mail.mcgill.ca, luansito@mila.quebec, jiaqi.zhu@mail.mcgill.ca).

## Paper List
**🔥Sitao's Recommendation**
**👑Reported results surpass SOTA GNNs' results on node classification tasks**

### Published Paper
- (*ICLR 2023*) Learning on Large-scale Text-attributed Graphs via Variational Inference [[paper](https://arxiv.org/abs/2210.14709)][[code](https://github.com/andyjzhao/glem)]
- (*KDD 2023*) Graph-Aware Language Model Pre-Training on a Large Graph Corpus Can Help Multiple Graph Applications [[paper](https://arxiv.org/abs/2306.02592)]
- (*KDD 2023*) GPPT: Graph Pre-training and Prompt Tuning to Generalize Graph Neural Networks [[paper](https://dl.acm.org/doi/abs/10.1145/3534678.3539249?casa_token=aP31ZFjvE9UAAAAA%3AD5NJiws3M0RFdDfv2MTevEN6SeHbXolI_RJx_2S6erqKQ-qn1TM8_F9aQPTu6nFjlHndoMyxqDI)][[code](https://github.com/MingChen-Sun/GPPT)]
- (*KDD 2023*) All in One: Multi-task Prompting for Graph Neural Networks [[paper](https://arxiv.org/abs/2307.01504)][[code](https://github.com/sheldonresearch/ProG)]
- (*KDD 2023*) Virtual Node Tuning for Few-shot Node Classification [[paper](https://arxiv.org/abs/2306.06063)]
- (*WWW 2023*) GraphPrompt: Unifying Pre-Training and Downstream Tasks for Graph Neural Networks [[paper](https://dl.acm.org/doi/10.1145/3543507.3583386)][[code](https://github.com/Starlien95/GraphPrompt)][[blog in Chinese](https://zhuanlan.zhihu.com/p/618189777)]
- (*SIGIR 2023*) Augmenting Low-Resource Text Classification with Graph-Grounded Pre-training and Prompting [[paper](https://arxiv.org/abs/2305.03324)][[code](https://github.com/WenZhihao666/G2P2)]
- (*NeurIPS 2023*) GIMLET: A Unified Graph-Text Model for Instruction-Based Molecule Zero-Shot Learning [[paper](https://arxiv.org/abs/2306.13089)] [[code](https://github.com/zhao-ht/GIMLET)]
- (*NeurIPS 2023*) WalkLM: A Uniform Language Model Fine-tuning Framework for Attributed Graph Embedding [[paper](https://openreview.net/forum?id=ZrG8kTbt70)]
- (*NeurIPS 2023*) Universal Prompt Tuning for Graph Neural Networks [[paper](https://arxiv.org/pdf/2209.15240.pdf)] [[Code](https://github.com/LuckyTiger123/GPF)]
- (*NeurIPS'23*) Can Language Models Solve Graph Problems in Natural Language? [[paper](https://arxiv.org/abs/2305.10037)][[code](https://github.com/Arthur-Heng/NLGraph)]

### Preprint
- (*arXiv 2023.02*) SGL-PT: A Strong Graph Learner with Graph Prompt Tuning [[paper](https://arxiv.org/abs/2302.12449)] [[blog in Chinese](https://zhuanlan.zhihu.com/p/618781703)]
- 🔥(*arXiv 2023.05*) Explanations as Features: LLM-Based Features for Text-Attributed Graphs [[paper](https://arxiv.org/abs/2305.19523)][[code](https://github.com/XiaoxinHe/TAPE)]
- (*openreview*) Pretrained Language Models to Solve Graph Tasks in Natural Language [[paper](https://openreview.net/forum?id=LfCzmmnH4L)]
- (*arXiv 2023.07*) Exploring the Potential of Large Language Models (LLMs) in Learning on Graphs [[paper](https://arxiv.org/abs/2307.03393)] [[code](https://github.com/CurryTang/Graph-LLM)][[blog in Chinese](https://zhuanlan.zhihu.com/p/648366848)]
- (*arXiv 2023.07*) Can Large Language Models Empower Molecular Property Prediction? [[paper](https://arxiv.org/abs/2307.07443)] [[code](https://github.com/ChnQ/LLM4Mol)]
- (*arXiv 2023.07*) Prompt Tuning on Graph-augmented Low-resource Text Classification [[paper](https://arxiv.org/abs/2307.10230)] [[code](https://github.com/wenzhihao666/g2p2-conditional)]
- (*arXiv 2023.07*) Prompt-Based Zero- and Few-Shot Node Classification: A Multimodal Approach [[paper](https://arxiv.org/abs/2307.11572)]
- 🔥👑(*arXiv 2023.08*) Natural Language is All a Graph Needs [[paper](https://arxiv.org/abs/2308.07134)] [[code](https://github.com/agiresearch/InstructGLM)]
- (*arXiv 2023.08*) SimTeG: A Frustratingly Simple Approach Improves Textual Graph Learning [[paper](https://arxiv.org/abs/2308.02565)] [[code](https://github.com/vermouthdky/simteg)]
- (*arXiv 2023.09*) Unleashing the Power of Graph Learning through LLM-based Autonomous Agents [[paper](https://arxiv.org/abs/2309.04565)]
- 🔥(*arXiv 2023.09*) Can LLMs Effectively Leverage Structural Information for Graph Learning: When and Why [[paper](https://arxiv.org/pdf/2309.16595)] [[code](https://github.com/TRAIS-Lab/LLM-Structured-Data)]
- (*arXiv 2023.09*) One for All: Towards Training One Graph Model for All Classification Tasks [[paper](https://arxiv.org/abs/2310.00149)] [[code](https://github.com/lechengkong/oneforall)]
- (*arXiv 2023.09*) Prompt-based Node Feature Extractor for Few-shot Learning on Text-Attributed Graphs [[paper](https://arxiv.org/abs/2309.02848)]
- (*arXiv 2023.09*) TouchUp-G: Improving Feature Representation through Graph-Centric Finetuning [[paper](https://arxiv.org/abs/2309.13885)]
- 🔥(*arXiv 2023.10*) GraphText: Graph Reasoning in Text Space [[paper](https://arxiv.org/abs/2310.01089)] [[code](https://github.com/AndyJZhao/GraphText)]
- (*arXiv 2023.10*) Label-free Node Classification on Graphs with Large Language Models (LLMS) [[paper](https://arxiv.org/abs/2310.04668)]  [[code](https://github.com/CurryTang/LLMGNN)]
- (*arXiv 2023.10*) GraphLLM: Boosting Graph Reasoning Ability of Large Language Model [[paper](https://arxiv.org/abs/2310.05845)][[code](https://github.com/mistyreed63849/Graph-LLM)]
- (*arXiv 2023.10*) Talk Like a Graph: Encoding Graphs for Large Language Models [[paper](https://arxiv.org/abs/2310.04560)]
- (*arXiv 2023.10*) Beyond Text: A Deep Dive into Large Language Models' Ability on Understanding Graph Data [[paper](https://arxiv.org/abs/2310.04944)]
- (*arXiv 2023.10*) Empower Text-Attributed Graphs Learning with Large Language Models (LLMs) [[paper](https://arxiv.org/abs/2310.09872)]
- (*openreview*) Efficient Large Language Models Fine-Tuning on Graphs [[paper](https://openreview.net/forum?id=DVA0NDUdCQ)]
- (*openreview*) Spatio-Temporal Graph Learning with Large Language Model [[paper](https://openreview.net/forum?id=QUkcfqa6GX)]
- (*openreview*) Simple Yet Effective Spatio-Temporal Prompt Learning [[paper](https://openreview.net/forum?id=YUNnVFlpjp)]
- (*openreview*) GraphGPT: Graph Learning with Generative Pre-trained Transformers [[paper](https://openreview.net/forum?id=070DFUdNh7)]
- (*openreview*) GraphAgent: Exploiting Large Language Models for Interpretable Learning on Text-attributed Graphs [[paper](https://openreview.net/forum?id=L3jATpVEGv)]
- (*arXiv 2023.10*) Thought Propagation: An Analogical Approach to Complex Reasoning with Large Language Models [[paper](https://arxiv.org/abs/2310.03965)]
- 🔥👑(*arXiv 2023.10*) GraphGPT: Graph Instruction Tuning for Large Language Models [[paper](https://arxiv.org/abs/2310.13023)][[code](https://github.com/HKUDS/GraphGPT)][[project page](https://graphgpt.github.io/)][[blog in Chinese](https://mp.weixin.qq.com/s/rvKTFdCk719Q6hT09Caglw)]
- 👑(*arXiv 2023.10*) Graph Agent: Explicit Reasoning Agent for Graphs [[paper](https://arxiv.org/abs/2310.16421)]
- (*arXiv 2023.10*) LLM4DyG: Can Large Language Models Solve Problems on Dynamic Graphs? [[paper](https://arxiv.org/abs/2310.17110)]
- (*arXiv 2023.10*) Disentangled Representation Learning with Large Language Models for Text-Attributed Graphs [[paper](https://arxiv.org/abs/2310.18152)]
- (*arXiv 2023.10*) HetGPT: Harnessing the Power of Prompt Tuning in Pre-Trained Heterogeneous Graph Neural Networks [[paper](https://arxiv.org/abs/2310.15318)]
- (*arXiv 2023.10*) Enhancing Graph Neural Networks with Structure-Based Prompt [[paper](https://arxiv.org/abs/2310.17394)]
- (*arXiv 2023.10*) ULTRA-DP: Unifying Graph Pre-training with Multi-task Graph Dual Prompt [[paper](https://arxiv.org/abs/2310.14845)]
- (*arXiv 2023.10*) Learning Multiplex Embeddings on Text-rich Networks with One Text Encoder [[paper](https://arxiv.org/abs/2310.06684)][[code](https://github.com/PeterGriffinJin/METERN-submit)]
- (*arXiv 2023.11*) Which Modality should I use -- Text, Motif, or Image? : Understanding Graphs with Large Language Models [[paper](https://arxiv.org/abs/2311.09862)]
- (*arXiv 2023.11*) Large Language Models as Topological Structure Enhancers for Text-Attributed Graphs [[paper](https://arxiv.org/abs/2311.14324)]


## Survey
- (*arXiv 2023.10*) Towards Graph Foundation Models: A Survey and Beyond [[paper](https://arxiv.org/abs/2310.11829)]
- (*IEEE Intelligent Systems 2023*) Integrating Graphs with Large Language Models: Methods and Prospects [[paper](https://arxiv.org/abs/2310.05499)]
- (*NeurIPS GLFrontiers 2023*) Integrating Graphs with Large Language Models: Methods and Prospects [[paper](https://arxiv.org/abs/2308.14522)]
- (*arXiv 2023.11*) A Survey of Graph Meets Large Language Model: Progress and Future Directions [[paper](https://arxiv.org/abs/2311.12399)]
- (*arXiv 2023.12*) Large Language Models on Graphs: A Comprehensive Survey [[paper](https://arxiv.org/abs/2312.02783)]

## Related Repository

- [Awesome-Graph-LLM](https://github.com/XiaoxinHe/Awesome-Graph-LLM)
- [awesome-large-graph-model](https://github.com/THUMNLab/awesome-large-graph-model)
- [Awesome-Language-Model-on-Graphs](https://github.com/petergriffinjin/awesome-language-model-on-graphs)
- [Awesome-LLMs-in-Graph-tasks](https://github.com/yhLeeee/Awesome-LLMs-in-Graph-tasks)
- [Awesome-LLM-KG](https://github.com/RManLuo/Awesome-LLM-KG)
- [KG-LLM-Papers](https://github.com/zjukg/KG-LLM-Papers)
- [Awesome-Graph-Prompt](https://github.com/WxxShirley/Awesome-Graph-Prompt)

