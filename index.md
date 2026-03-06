---
layout: single
title: "Kerol DJOUMESSI"
excerpt: "Data Scientist based in Tübingen (Germany). Looking for new career opportunities and collaborations."
author_profile: true
header:
  overlay_image: /assets/images/tuebingen.jpeg
  overlay_filter: 0.5 # same as adding an opacity of 0.5 to a black background
---
# About me
I am currently a postdoc researcher at the [Hertie Institute for AI in Brain Health](https://hertie.ai/data-science/about-us), where my work focuses on trustworthy AI for medical applications. My research interests center on building methods that can safely and reliably improve patient care and support user well-being.

I conducted my PhD on __Interpretable Machine Learning for Safe Medical Diagnostics__ in the Department of Data Science at the [Hertie Institute for Artificial Intelligence in Brain Health](https://hertie.ai/data-science/team/members/kerol-djoumessi) at the [University of Tübingen](https://uni-tuebingen.de/en/). During my PhD studies, I was also a scholar of the [International Max Planck Research School for Intelligent Systems (IMPRS-IS)](https://imprs.is.mpg.de/scholars).
 
## Bio
I hold a bachelor's degree in Computer Mathematics (BSc) and a master's degree (MSc) in Computer Science from the University of Dschang in Cameroon. I then completed a second Master's degree (MSc) in Applied Mathematics at the [African Institute for Mathematical Science (AIMS)](https://aims.ac.za/) in South Africa. 

Following this, I joined the [International Max Planck Research School for Intelligent Systems (IMPRS-IS)](https://imprs.is.mpg.de) where I pursued my PhD in __Machine Learning for Medical Image Analysis__ under the supervision of [Prof. Dr. Philipp Berens](https://hertie.ai/data-science).

## Research interests
My research focuses on __explainable deep learning for clinical diagnosis__, with emphasis on inherently interpretable models for medical image analysis. My current work includes applications in ophthalmology and radiology.

Beyond interpretability, I am also interested in __Vision Language Models (VLMs), clinical ethics, fairness in AI, resource-efficient deep learning models, the deployment of AI systems in clinical practice, and ensuring the robustness of models in real-world settings__. 

## Teaching Assistant (TA)
- [Machine Learning I](https://ovidius.uni-tuebingen.de/ilias3/goto.php?target=crs_4323713&client_id=pr02) (Winter semester 2023/2024)
- [Machine Learning for Medical Image Analysis](https://www.mlmia-unitue.de/teaching/ws22-ml-for-medical-image-analysis-ml4506/) (Winter semester 2022/2023)

## Student supervision
MSc students: 
- Frederik Spieß (Sep 2025 - March 2026) -- MSc Medical Informatics (University of Tübingen)
- Anna Schäfer (Oct 2025 - April 2026) -- (University of Tübingen)
- Olivier Kanamugire (2024) -- Msc in Mathematical Sciences (AIMS Rwanda)

## Latest News
- __February 2026__ - <span style="color:red"> New accepted paper</span> - Our paper [SoftCAM: Making black box models self-explainable for high-stakes decisions](https://openreview.net/forum?id=3v1rKkPvuU) has been accepted at [MIDL 2026](https://2026.midl.io/). In this work, we present __SoftCAM__, a simple yet effective method to transform black-box CNNs into inherently self-explainable models, with extensive validation on medical imaging datasets. Unlike post-hoc methods, Soft-CAM modifies the network architecture itself: we remove the global average pooling layer and replace the fully connected classifier with a spatially aware class-evidence layer—implemented via a convolutional layer. This design preserves spatial information and produces class-specific evidence maps that directly support the model’s predictions. We further enhance interpretability by applying an ElasticNet regularization on the evidence maps to refine the explanations. Quantitative comparisons show that Soft-CAM outperforms existing class activation map (CAM) methods, all without compromising classification performance.
- __Febuary 2026__ - <span style="color:red"> 
<a href="https://ircai.org/global-top-100/" style = "color: red">Top 100: IRCAI Global AI for SDGs Index</a> </span> - Our project on [interpretable DR screening](https://journals.plos.org/digitalhealth/article?id=10.1371/journal.pdig.0000831) recently published in PLoS Digital Health has been selected as one of the worldwide top 100 AI solutions for driving progress on the SDGs. The project description is available [here](https://ircai.org/top100/entry/interpretable-ai-for-safer-and-faster-diabetic-retinopathy-screening/).
- __January 2026__ - <span style="color:red"> MIDL Young Researcher Board</span> - I joined the [MIDL Young Researcher Board](https://www.midl.io/young-researchers-board) as a member and will serve in this role for the next two years.
- __August 2025__ - <span style="color:red"> New accepted paper</span> - Our paper entitled [A Hybrid Fully Convolutional CNN-Transformer Model for Inherently Interpretable Disease Detection from Retinal Fundus Images](https://link.springer.com/chapter/10.1007/978-3-032-17611-0_11) has been accepted at [the 8th IMIMIC Workshop on Interpretability in Medical Image Computing at MICCAI 2025](https://imimic-workshop.com/) for <span style="color:red"> oral presentation </span>. In this work, we introduced the first inherently self-explainable hybrid sequential CNN-Transformer model for medical image analysis. Our architecture integrates a CNN feature extractor with dual-resolution convolutional windowed self-attention to capture both low- and high-frequency features while preserving spatial information. A convolutional classification head produces class-specific evidence maps that directly support the model’s predictions. To enhance interpretability, we apply a Lasso penalty to these maps, encouraging sparsity and improving the clarity and faithfulness of the explanations.
- __Jun 2025__ - <span style="color:red"> New accepted paper</span> - Our paper entitled [Prototype-Guided and Lightweight Adapters for Inherent Interpretation and Generalisation in Federated Learning](https://arxiv.org/abs/2507.05852) has been accepted at [MICCAI 2025](https://conferences.miccai.org/2025/en/).
- __Jun 2025__ - <span style="color:red"> New preprint alert</span> - [Clinically Interpretable Deep Learning via Sparse BagNets for Epiretinal Membrane and Related Pathology Detection](https://www.medrxiv.org/content/10.1101/2025.06.05.25329045v1). In this work, we trained the [sparse BagNet model](https://openreview.net/forum?id=us8BFTsWOq), an inherently interpretable deep learning model, to detect ERM in OCT images, showing that it performed on par with a comparable black-box model and generalised well to external data. Through a clinical user study with ophthalmologists, we showed that the visual explanations readily provided by the sparse BagNet model for its decisions are well-aligned with clinical expertise. This study proposes potential directions for clinical implementation of the __sparse BagNet model__ to guide clinical decisions in practice.
- __May 2025__ - <span style="color:red"> New journal paper</span> - [An Inherently Interpretable AI model improves Screening Speed and Accuracy for Early Diabetic Retinopathy](https://journals.plos.org/digitalhealth/article?id=10.1371/journal.pdig.0000831) was published at __Plos Digital Health__. In this work, we evaluate our self-explainable model, [sparseBagNet](https://proceedings.mlr.press/v227/donteu24a/donteu24a.pdf), on a benchmark of 10 retinal fundus datasets for early detection of diabetic retinopathy. Despite being inherently interpretable, sparseBagNet performs comparably to traditional black-box models while improving ophthalmologists' diagnostic accuracy by ~20% and reducing decision time by ~ 25% for challenging cases.
- __November 2024__ - <span style="color:red"> 7th place in the MIDRC XAI challenge</span> - Our inherently interpretable [Dense BagNet model](https://openreview.net/forum?id=us8BFTsWOq) achieved [seventh place](https://www.midrc.org/xai-challenge-2024) in the [MIDRC XAI Challenge](https://qtim-challenges.southcentralus.cloudapp.azure.com/competitions/36/), a MICCAI-endorsed competition titled [“XAI: Decoding AI Decisions for Pneumonia on Chest Radiographs.”](https://qtim-challenges.southcentralus.cloudapp.azure.com/competitions/36/) 
- __October 2024__ - <span style="color:red"> 2 papers accepted at MICCAI 2024</span> -. We presented our accepted  papers [This actually looks like that: Proto-BagNets for local and global interpretability-by-design](https://link.springer.com/chapter/10.1007/978-3-031-72117-5_67) and [Interpretable-by-design Deep Survival Analysis for Disease Progression Modeling](https://link.springer.com/chapter/10.1007/978-3-031-72117-5_47) at MICCAI 2024
- __September 2024__ - I joined the [Africa Science Entrepreneurship Program](https://www.sarao.ac.za/news/africa-science-entrepreneurship-program-2024-call-for-technical-mentors/) for a year as a Mentor
- __July 2024__ - Participation at the [UCL Medical Image Computing Summer School (MedICSS)](https://www.ucl.ac.uk/medical-image-computing/ucl-medical-image-computing-summer-school-medicss) hosted at UCL (London) 
- __Jun 2024__ - Speakers at [IndabaX Cameroon 2024]([https://www.indabaxcameroon.org/speakers](https://deeplearningindaba.com/2024/indabax/cameroon/))
- __Jun 2024__ - Two papers accepted at MICCAI 2024
    - _This actually looks like that: Proto-BagNets for local and global interpretability-by-design_
    - _Interpretable-by-design Deep Survival Analysis for Disease Progression Modeling_
- __March 2024__ - Tutor during the [Foundational Methods in Data Science Training School](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://qla.aimsric.org/%3Fevents%3Dfoundational-methods-in-data-science-training-school-2&ved=2ahUKEwjG6OO3xdmFAxUkhP0HHZ4iD_8QFnoECBMQAQ&usg=AOvVaw2DpuHiMg8Qoa8mse70vxwo) in Kigali organized by the AIMS Research and Innovation Center (AIMS-RIC). I gave a talk on __"Trustworthy ML for medical image diagnosis"__.
- __August 2023__ - Invitation to the TV show [“Ladies of Another View”](https://www.bek.news/ladiesofanotherview/2023-08-08/) to talk about the challenges of Artificial Intelligence: [watch](https://www.bek.news/ladiesofanotherview/2023-08-08/)
- __July 2023__ - <span style="color:red"> Oral presentation at the Medical Imaging with Deep Learning (MIDL-23) conference</span> - I presented our paper on trustworthy AI for image analysis titled [Sparse Activations for Interpretable Disease Grading](https://openreview.net/forum?id=us8BFTsWOq): [presentation](https://www.youtube.com/watch?v=6T5TCBJaYl4) \| [slide](https://drive.google.com/file/d/1-hFD1RZmaPQqI5I80nfRZw6mguuvJ-Qo/view) \| [conference webpage](https://2023.midl.io/program)
- __March 2023__ - Participation with an oral presentation at the [Bern Interpretable AI Symposium (BIAS)](https://www.caim.unibe.ch/about_us/news_and_events/events_2022/bias_symposium/index_eng.html) in Medical Image Analysis. I presented the result of our paper [Sparse Activations for Interpretable Disease Grading](https://openreview.net/forum?id=us8BFTsWOq) accepted at MIDL 2023: [presentation](https://drive.google.com/file/d/1Q7UN_kMoggfK9HKLHMCGLPo7x7Nmpa7k/view) \| [slide](https://drive.google.com/file/d/1EoOElk0CIvV70o1ZCCyZoyJ2elYRoBrf/view)
- __April 2023__ - Participation with an oral presentation at the [From Theory to Practice (T2P) workshop in Data Science](https://qla.aimsric.org/?events=theory-to-practice-t2p-2022) organized by Quantum Leap Africa (QLA). I gave a presentation on interpretable AI models for medical image diagnosis: [slide](https://drive.google.com/file/d/1ucH40izWpzQuHvS5R2lGWTmvwvpe2_oL/view)
- __October 2022__ - Volunteer trainer at the ["Collaborative Science Symposium with clinical data for healthcare professionals"](https://biortc.com/biortc-summer-school-2023-advancing-bioimaging-and-open-hardware-training-in-africa/) in Yobe
State (Nigeria) organized by the Biomedical Science Research and Training Centre (BioRTC) Yobe State University

## Reviewing
- [MICCAI](https://miccai.org/) (4+4+4): 2024, 2025, 2025
- [MIDL](https://www.midl.io/) (1+4): 2025, 2026
- [FIAMI-MICCAI Workshop](https://faimi-workshop.github.io/) (3): 2025
- [IMIMIC-MICCAI Workshop](https://imimic-workshop.com/) (3): 2025
- [Plos Digital Health](https://journals.plos.org/digitalhealth/) (1)
