---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        ZLST Lab
      image:
        filename: background2.jpg
      text: |
        <br>
        
        The **ZLST** lab ~~has been a center of excellence for Artificial Intelligence research, teaching, and practice since its founding in 2016~~ waiting for more content...
  
  # - block: collection
  #   content:
  #     title: Latest News
  #     subtitle:
  #     text:
  #     count: 5
  #     filters:
  #       author: ''
  #       category: ''
  #       exclude_featured: false
  #       publication_type: ''
  #       tag: ''
  #     offset: 0
  #     order: desc
  #     page_type: post
  #   design:
  #     view: card
  #     columns: '1'
  - block: markdown
    content:
      title:
      subtitle: ''
      text: |
        # Recommendation systems
        Recommendation systems (RS) are technologies that utilize user behavior and content characteristics to predict user preferences and provide personalized recommendations, which are widely used in fields such as e-commerce and social media.

        We are committed to researching trustworthy RS, the theory of RS, and large language models (LLMs) for RS. Our work has been published in numerous top conferences and journals, including NeurIPS, AAAI, KDD, WWW, SIGIR, WSDM, CIKM, Recsys, and TOIS.

        <!-- # 亮点工作
        ## Trustworthy Recommendation System
        - How Do Recommendation Models Amplify Popularity Bias? An Analysis from the Spectral Perspective (WSDM'2025 Best Paper!)
        - Alleviating matthew effect of offline reinforcement learning in interactive recommendation (SIGIR'2023 Best Paper Nomination!)
        - Bias and debias in recommender system: A survey and future directions (TOIS'2023)
        - Distributionally Robust Graph-based Recommendation System (WWW'2024 Oral)
        - CDR: Conservative Doubly Robust Learning for Debiased Recommendation (CIKM'2023)

        ## The Theory of Recommendation System
        - Advancing Loss Functions in Recommender Systems: A Comparative Study with a Rényi Divergence-Based Solution (AAAI'2025)
        - PSL: Rethinking and Improving Softmax Loss from Pairwise Perspective for Recommendation (NeurIPS'2024)

        ## Large Language Models for Recommendation System
        - Distillation matters: empowering sequential recommenders to match the performance of large language models (Recsys'2024 Oral) -->

        # Highlights
        ## Trustworthy Recommendation System
        - [ReSN](https://arxiv.org/abs/2404.12008) (WSDM'2025 Best Paper!)
        - [DORL](https://arxiv.org/abs/2307.04571) (SIGIR'2023 Best Paper Nomination!)
        - [Survey on Bias and Debias]() (TOIS'2023)
        - [DR-GNN](https://arxiv.org/abs/2402.12994) (WWW'2024 Oral)

        ## The Theory of Recommendation System
        - [DrRL]() (AAAI'2025)
        - [PSL](https://arxiv.org/abs/2411.00163) (NeurIPS'2024)

        ## Large Language Models for Recommendation System
        - [DLLM2Rec](https://arxiv.org/abs/2405.00338) (Recsys'2024 Oral)
    design:
      columns: '1'
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: markdown
    content:
      title:
      subtitle: ''
      text: |
        # Diffusion Models
        Diffusion Models are a class of generative models that have gained significant attention in recent years, particularly in the fields of computer vision and natural language processing. By establishing a mapping from noise distribution to data distribution, Diffusion Models can generate high-quality data such as images, videos, audios and text.

        We are devoted to provide a deeper understanding of the generaion dynamics of Diffusion Models and the acceleration of their sampling processes. Our works have been published in top conferences such as CVPR, ICML and NeurIPS.

        # Highlights
        ## Accelerated Sampling of Diffusion Models
        - [AMED-Solver](https://arxiv.org/abs/2312.00094) (CVPR'2024 Highlight)
        - [SFD](https://arxiv.org/abs/2409.19681) (NeurIPS'2024)
        - [GITS](https://arxiv.org/abs/2405.11326) (ICML'2024)


    design:
      columns: '1'
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: background2.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'paper-conference'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
