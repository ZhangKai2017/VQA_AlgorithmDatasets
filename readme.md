

## Table Category
* [Collection of VQA papers](#papers)
* [Leaderboard](#vqa-challenge-leaderboard)
* [Tutorials](#Tutorials)
* [VQA Dataset](#Dataset)
* [VQA Algorithm](#Algorithm)
* [VQA Code Library](#CodeLibrary)

## :page_facing_up:Collection of Papers
  - VQA: https://github.com/jokieleung/awesome-visual-question-answering/blob/master/README.md#CVPR-2020
  - Text-VQA https://github.com/xinke-wang/Awesome-Text-VQA

  - Survey papers:
    - KB-VQA: https://github.com/astro-zihao/Awesome-KBQA
    - 2019, V+L dataset and methods: https://arxiv.org/pdf/1907.09358.pdf
    - 2017, VQA dataset and methods: https://www.sciencedirect.com/science/article/pii/S1077314217300772?casa_token=EX_Gt8Ib5rQAAAAA:NSFjlS4iVem0eC_iQCvHf6HPkg18fbQAQC-BqxW96u85bg2gMNw0yFFUFS4HvdiAuzr0D0FQ1Bc

## :green_book: Tutorials
  - Sigir2020: https://www.avishekanand.com/talk/sigir20-tute/
  - CVPR2020 (Recent Advances in Vision-and-Language Research): https://rohit497.github.io/Recent-Advances-in-Vision-and-Language-Research/
  - KDD 2020 (Scene Graph) https://suitclub.ischool.utexas.edu/IWKG_KDD2020/slides/Shih-Fu.pdf

## :chart_with_upwards_trend: Leaderboard
  - VQAv2 leaderboard: https://visualqa.org/roe.html
  
|  Algorithm | Accuracy  |
|  ----  | ----  |
|  GridFeat+MoVie | 76.36  |
| DL-61 (BGN)  | 76.08 |
| Renaissance@DamoNLP	|76.02|
| VILLA (adversarial training) based on UNITER|75.9|
| Ensemble LXMERT, VILBERT, VisualBERT |75.15|
| Pixel-BERT x152 |74.45|
|	Oscar 	|73.82|
|UNITER (+grid feature)	|73.82|
|	LXMERT	|72.54|
|	VLBERT	|72.22|
|	Pixel-BERT r50 |71.35|
|	MCAN		|70.93|
|	VisualBERT 	|71.00|
|	ViLBERT	|70.92|
|	BUTD		|65.67|
|	MUTAN		|60.17|

- VizWiz leaderboard: https://evalai.cloudcv.org/web/challenges/challenge-page/523/leaderboard/1459#leaderboardrank-1

|  Algorithm | Accuracy  |
|  ----  | ----  |
|  HSSLab | 56.33  |
|  LXMBERT | 55.4  |
|  Pythia | 54.72  |
|  Gridfeature+MCAN | 54.17  |

## :floppy_disk: Dataset
* VQA Dataset
     * General VQA
          - COCO
          - VQAv1, VQAv2
          - VQA Dialog

     * Text-VQA
          - TextVQA
          - Scene Text VQA
          - OCR-VQA (toy-sized dataset, containing book/poster cover)
     * Re-ask VQA 
          - Inverse Visual QA (iVQA)
          - VQA-Rehrasings
          - VQA-LOL
          - VQA- introspect
     * Re-image VQA
          - VQAv2
          - VQA-CP
     * Reasoning/External Knowledge tasks
          - VCR (11/2018)
          - Visual Entailment(2019)
          - GQA
          - OK-VQA
          - CLEVER
          - Referring Expression
          - NLVR2 (2018)

     * Explainable/Grounding Image Captioning/VQA
        - Grounding for image captioning (referring expression)
          - Flickr30K entities
          - Visual Genome
          - RefClef
          - RefCOCO 
          - CLEVER-Ref+
          - Google Referring expression
          - PhraseCut
        - grounding for VQA
          - Visual7W 
          - VQA-E
## :pencil2: Algorithm
   * Image Feature preparation
      - Show, Attend and Tell  (2015/5)
      - SAN (2015/11)
      - BUTD (2017/7)
      - Grid Feature (2020/1)
      - Pixel-BERT (2020/4)
   * Enhanced multimodal fusion
      - Bilinear pooling: how to fuse two vectors into one
        - MCB (2016/6)
        - MLB (2016/10)
        - MUTAN (2017/5)
        - MFB&MFH (2017/8)
        - BLOCK (2019/1)
      - FiLM: Feature-wise Linear Modulation		
        - FiLM
      - cross-modal attention
        - SAN (2015/11)
        - HierCoAttn (2016/5)
        - DAN (2016/11)
        - DCN (2018/4)
        - BAN (2018/5)
      - intra-modal attention(Relational Reasoning):
        - UNITER
        - ViLBERT
        - LXMERT	
        - B2T2
        - VisualBERT
        - Unicoder-VL
        - VL-BERT
      - graph attention/graph Convolutional Network
        - Graph-Structured, (2016/9)
        - Relation Network, (2017/6)
        - Graph Learner,(2018/6)
        - MuRel, (2019/2)
        - ReGAT, (2019/3)
        - LCGN (2019/5)
      - Cross-modal+intra-modal
        - MCAN, 2019: Deep Modular Co-Attention Network

      - Multi-step reasoning
        - MAC: Memory, Attention and Composition

      - Neural module networks
        - NMN, (2015/11)
        - N2NMN,(2017/4)
        - PG+EE,(2017/5)
        - TbD,(2018/3)
        - stackNMN,(2018/7)
        - NS-VQA,(2018/10)
        - Prob-NMN, (2019/2)
        - MMN (2019/10)

   * External Knowledge Algorithm
      - Mucko (1/2020)
