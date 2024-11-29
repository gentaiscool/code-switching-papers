# Code-switching Research Resources
This is the list of tutorials, workshops, papers, and resources on computational linguistic approaches to code-switching research. 
The list will be updated over the time. You are welcome to send a pull request for updating the list and be one of the contributors! 

📌 I plan to collect theses and books on code-switching and list them here. If you have one, don't hesitate to contact me or create a pull request! 

## Table of Contents

- [🚀 Highlights](#-highlights)
- [🏫 Workshops](#-workshops)
- [📑 Research Papers](#-research-papers)
  - [Survey Paper](#survey-paper)
  - [Large Language Models](#large-language-models)
  - [Language Identification and POS Tagging](#language-identification-and-pos-tagging)
  - [Corpus](#corpus)
  - [Language Modeling and Speech Recognition](#language-modeling-and-speech-recognition)
  - [Discourse](#discourse)
  - [Generation](#generation)
  - [Speech Synthesis](#speech-synthesis)
  - [Metric](#metric)
  - [Representation Learning](#representation-learning)
  - [Machine Translation](#machine-translation)
  - [Speech Translation](#speech-translation)
  - [Natural Language Understanding](#natural-language-understanding)
  - [Named Entity Recognition](#named-entity-recognition)
  - [Linguistics](#linguistics)
  - [Affective Computing](#affective-computing)
  - [Dialog and Conversational System](#dialog-and-conversational-system)
  - [Discourse](#discourse)
  - [Syntax](#syntax)
  - [Adversarial Attack](#adversarial-attack)
  - [Social Linguistics](#social-linguistics)
  - [Benchmark](#benchmark)
  - [Social Media](#social-media)
  - [Text Normalization](#text-normalization)
  - [Toolkit](#toolkit)
- [Books](#books)
- [Theses](#theses)

## 🚀 Highlights
- If you are new on code-switching or looking for a new research direction, we have written a comprehensive survey paper on code-switching: <b>The Decades Progress on Code-Switching Research in NLP: A Systematic Survey on Trends and Challenges</b> <a href="https://arxiv.org/pdf/2212.09660.pdf">[Paper]</a>. Feel free to read and let us know if you have any suggestions! Thanks to Alham Fikri Aji, Zheng-Xin Yong, and Thamar Solorio to make this possible 😊
- We organized the code-switching workshop at EMNLP 2023! <a href="https://code-switching.github.io/2023">[Website]</a>
- We (I, Marina Zhukova, and Sudipta Kar) organized a bird-of-a-feather session at EMNLP 2022 in Abu Dhabi. We have around 30 people joining (in-person and online). Thanks for coming!
- 📔 There was a comprehensive tutorial about code-mixing by Microsoft Research (Monojit Choudhury, Kalika Bali, Anirudh Srinivasan, and Sandipan Dandapat) at EMNLP 2019, you can check the following <a href="https://genius1237.github.io/emnlp19_tut/">link</a>.

## 🏫 Workshops
This is the list of the code-switching workshop series:
- First Workshop on Computational Approaches to Code-switching, EMNLP 2014 <a href="http://emnlp2014.org/workshops/CodeSwitch/call.html">[Website]</a>
- Second Workshop on Computational Approaches to Code-switching, EMNLP 2016
- Third Workshop on Computational Approaches to Linguistic Code-switching, ACL 2018 <a href="https://code-switching.github.io/2018/">[Website]</a>
- Fourth Workshop on Computational Approaches to Linguistic Code-switching, LREC 2020 <a href="https://code-switching.github.io/2020/">[Website]</a>
- First Workshop on Speech Technologies for Code-switching in Multilingual Communities, Interspeech 2020 <a href="https://www.microsoft.com/en-us/research/event/workshop-on-speech-technologies-for-code-switching-2020/">[Website]</a>
- Fifth Workshop on Computational Approaches to Linguistic Code-switching, NAACL 2021 <a href="https://code-switching.github.io/2021">[Website]</a>
- Sixth Workshop on Computational Approaches to Linguistic Code-switching, EMNLP 2023 <a href="https://code-switching.github.io/2023">[Website]</a>
- Seventh Workshop on Computational Approaches to Linguistic Code-switching, NAACL 2025 <a href="https://code-switching.github.io/2025">[Website (will open soon)]</a>

## 📑 Research Papers

### Survey Paper
- <b>Winata, et al. (2023)</b> <i>The Decades Progress on Code-Switching Research in NLP: A Systematic Survey on Trends and Challenges</i>. ACL Findings <a href="https://arxiv.org/pdf/2212.09660.pdf">[Paper]</a>
- <b>Doğruöz, et al (2021)</b> <i>A Survey of Code-switching: Linguistic and Social Perspectives for Language Technologies</i>. ACL <a href="https://aclanthology.org/2021.acl-long.131.pdf">[Paper]</a>
- <b>Jose, et al. (2020)</b> <i>A Survey of Current Datasets for Code-Switching Research</i>. International Conference on Advanced Computing and Communication Systems (ICACCS) <a href="https://ieeexplore.ieee.org/document/9074205">[Paper]</a>
- <b>Sitaram, et al. (2019)</b> <i>A Survey of Code-switched Speech and Language Processing</i>. Arxiv <a href="https://arxiv.org/pdf/1904.00784.pdf">[Paper]</a>

### Large Language Models
- <b>Winata, et al. (2024)</b> <i>MINERS: Multilingual Language Models as Semantic Retrievers</i>. Arxiv <a href="https://arxiv.org/pdf/2406.07424">[Paper]</a> <a href="https://github.com/gentaiscool/miners">[Code]</a>
- <b>Leon, et al., (2024)</b> <i>Code-Mixed Probes Show How Pre-Trained Models Generalise On Code-Switched Text</i>. LREC <a href="https://aclanthology.org/2024.lrec-main.307.pdf">[Paper]</a> <a href="https://github.com/francesita/code-mixed-probes">[Code]</a>
- <b>Huzaifah, et al. (2024)</b> <i>Evaluating Code-Switching Translation with Large Language
Models</i>. LREC-COLING <a href="https://aclanthology.org/2024.lrec-main.565.pdf">[Paper]</a>
- <b>Yong, et al. (2023)</b> <i>Prompting Large Language Models to Generate Code-Mixed Texts: The Case of South East Asian Languages</i>. CALCS, EMNLP <a href="https://aclanthology.org/2023.calcs-1.5.pdf">[Paper]</a>

### Language Identification and POS Tagging
- <b>Igor Sterner and Simone Teufel (2023)</b> <i>TongueSwitcher: Fine-Grained Identification of German-English Code-Switching</i>. CALCS, EMNLP <a href="https://aclanthology.org/2023.calcs-1.1.pdf">[Paper]</a>
- <b>Ostapenko, et al. (2022)</b> <i>Speaker Information Can Guide Models to Better Inductive Biases: A Case Study On Predicting Code-Switching</i>. ACL <a href="https://aclanthology.org/2022.acl-long.267.pdf">[Paper]</a>
- <b>Nguyen, et al. (2021)</b> <i>Automatic Language Identification in Code-Switched Hindi-English Social Media Text</i>. Journal of Open Humanities Data <a href="https://openhumanitiesdata.metajnl.com/article/10.5334/johd.44/">[Paper]</a>
- <b>Tarunesh, et al. (2021)</b> <i>From Machine Translation to Code-Switching: Generating High-Quality Code-Switched Text</i>. ACL <a href="https://aclanthology.org/2021.acl-long.245.pdf">[Paper]</a>
- <b>Gustavo Aguilar and Thamar Solorio. (2020)</b> <i>From English to Code-Switching: Transfer Learning with Strong Morphological Clues</i>. ACL <a href="https://arxiv.org/pdf/1909.05158.pdf">[Paper]</a> <a href="https://github.com/gaguilar/cs_elmo">[Code]</a>
- <b>Mager, et al. (2019)</b> <i>Subword-Level Language Identification for Intra-Word Code-Switching</i>. NAACL <a href="https://arxiv.org/abs/1904.01989">[Paper]</a>
- <b>Zhang, et al. (2018)</b> <i>A Fast, Compact, Accurate Model for Language Identification of Codemixed Text</i>. EMNLP <a href="https://aclanthology.org/D18-1030.pdf">[Paper]</a>
- <b>Kelsey Ball and Dan Garrette. (2018)</b> <i>Part-of-Speech Tagging for Code-Switched, Transliterated Texts without Explicit Language Identification</i>. EMNLP <a href="http://aclweb.org/anthology/D18-1347">[Paper]</a>
- <b>Zeynep Yirmibesoglu and Gulsen Eryigit. (2018)</b> <i>Detecting Code-Switching between Turkish-English Language Pair</i>. Workshop W-NUT, EMNLP <a href="http://www.aclweb.org/anthology/W18-6115">[Paper]</a>
- <b>Mavem, et al. (2018)</b> <i>Language Identification and Analysis of Code-Switched Social Media Text</i>. 3rd Workshop of Computational Approaches to Linguistic Code-switching, ACL <a href="http://www.aclweb.org/anthology/W18-3206">[Paper]</a>
- <b>Victor Soto and Julia Hirschberg. (2018)</b> <i>Joint Part-of-Speech and Language ID Tagging for Code-Switched Data</i>. 3rd Workshop of Computational Approaches to Linguistic Code-switching, ACL <a href="http://aclweb.org/anthology/W18-3201">[Paper]</a> 
- <b>Bullock, et al. (2018)</b> <i>Predicting the presence of a Matrix Language in code-switching</i>. 3rd Workshop of Computational Approaches to Linguistic Code-switching, ACL <a href="http://www.aclweb.org/anthology/W18-3208">[Paper]</a>
- <b>Soto, et al. (2018)</b> <i>The Role of Cognate Words, POS Tags, and Entrainment in Code-Switching</i>. Interspeech <a href="http://www.cs.columbia.edu/speech/PaperFiles/2018/soto_is18.pdf">[Paper]</a> 
- <b>Barman, et al. (2016)</b> <i>Part-of-speech Tagging of Code-mixed Social Media Content: Pipeline,Stacking and Joint Modelling</i>. 2nd Workshop on Computational Approaches to Code-Switching, ACL <a href="https://aclweb.org/anthology/W16-5804">[Paper]</a> 
- <b>Vyas, et al. (2014)</b> <i>POS Tagging of English-Hindi Code-Mixed Social Media Content</i>. EMNLP <a href="https://www.aclweb.org/anthology/D14-1105.pdf">[Paper]</a>
- <b>Heba Elfardy and Mona Diab. (2012)</b> <i>Token Level Identification of Linguistic Code Switching</i>. COLING <a href="https://www.aclweb.org/anthology/C12-2029.pdf">[Paper]</a>
- <b>Thamar Solorio and Yang Liu. (2008)</b> <i>Learning to Predict Code-Switching Points</i>. EMNLP <a href="http://www.aclweb.org/anthology/D08-1102">[Paper]</a>
- <b>Dau-Cheng Lyu and Ren-Yuan Lyu. (2008)</b> <i>Language Identification on Code-Switching Utterances Using Multiple Cues</i>. Interspeech <a href="https://pdfs.semanticscholar.org/67b5/b05a9669202fe63cf5165a5b2286ddd1b6f2.pdf">[Paper]</a>

### Corpus
- <b>Kuwanto, et al. (2024)</b> <i>Linguistics Theory Meets LLM: Code-Switched Text Generation via Equivalence Constrained Large Language Models</i>. Arxiv <a href="">[Paper]</a> <a href="https://github.com/gkuwanto/ezswitch">[Code]</a> <a href="https://huggingface.co/datasets/garrykuwanto/cspref">[Dataset]</a>
- <b>Ruochen Zhang and Carsten Eickhoff (2024)</b> <i>CroCosum: A Benchmark Dataset for Cross-Lingual Code-switched Summarization</i>. LREC <a href="https://aclanthology.org/2024.lrec-main.367.pdf">[Paper]</a> <a href="https://github.com/RosenZhang/CroCoSum">[Dataset]</a>
- <b>Whitehouse, et al. (2022)</b> <i>EntityCS: Improving Zero-Shot Cross-lingual Transfer with Entity-Centric Code Switching</i>. EMNLP <a href="https://arxiv.org/pdf/2210.12540.pdf">[Paper]</a> <a href="https://github.com/huawei-noah/noah-research/tree/master/NLP">[Code]</a>
- <b>Lovenia, et al. (2022)</b> <i>ASCEND: A Spontaneous Chinese-English Dataset for Code-switching in Multi-turn Conversation</i>. LREC <a href="https://arxiv.org/pdf/2112.06223.pdf">[Paper]</a> <a href="https://huggingface.co/datasets/CAiRE/ASCEND">[Dataset]</a>
- <b>Nguyen, et al. (2020)</b> <i>CanVEC-the Canberra Vietnamese-English Code-switching Natural Speech Corpus</i>. LREC <a href="https://aclanthology.org/2020.lrec-1.507.pdf">[Paper]</a>
- <b>Umapathy, et al. (2020)</b> <i>Investigating Modelling Techniques for Natural Language Inference on Code-Switched Dialogues in Bollywood Movies</i>. First Workshop on Speech Technologies for Code-switching in Multilingual Communities, Interspeech 2020 <a href="https://aka.ms/CodeMixedNLI">[Dataset]</a>
- <b>Xiang, et al. (2020)</b> <i>Sina Mandarin Alphabetical Words:A Web-driven Code-mixing Lexical Resource</i>. AACL-IJCNLP <a href="">[TBC]</a>
- <b>Chakravarthi, et al. (2020)</b> <i>Corpus Creation for Sentiment Analysis in Code-Mixed Tamil-English Text</i>. Spoken Language Technologies for Under-resourced languages) and CCURL (Collaboration and Computing for Under-Resourced Languages Workshop, LREC <a href="https://arxiv.org/pdf/2006.00206.pdf">[Paper]</a>
- <b>Khanuja, et al. (2020)</b> <i>A New Dataset for Natural Language Inference from Code-mixed Conversations</i>. 4th Workshop of Computational Approaches to Linguistic Code-switching, LREC <a href="https://arxiv.org/abs/2004.05051">[Paper]</a>
- <b>Barik, et al. (2019)</b> <i>Normalization of Indonesian-English Code-Mixed Twitter Data</i>. W-NUT, EMNLP <a href="https://www.aclweb.org/anthology/D19-5554.pdf">[Paper]</a> <a href="https://github.com/seelenbrecher/code-mixed-normalization">[Dataset]</a>
- <b>Singh, et al. (2018)</b> <i>A Twitter Corpus for Hindi-English Code Mixed POS Tagging</i>. Sixth International Workshop on Natural Language Processing for Social Media, ACL <a href="http://aclweb.org/anthology/W18-3503">[Paper]</a>
- <b>Li, et al. (2012)</b> <i>A Mandarin-English Code-Switching Corpus</i>. LREC <a href="http://www.lrec-conf.org/proceedings/lrec2012/pdf/964_Paper.pdf">[Paper]</a>
- <b>Lyu, et al. (2010)</b> <i>SEAME: A Mandarin-English Code-Switching Speech Corpus in South-East Asia</i>. Interspeech <a href="https://pdfs.semanticscholar.org/de83/7c40f54125ce9c612c143ebc6c9ca5e84b13.pdf">[Paper]</a>
- <b>Lyu, et al. (2010)</b> <i>An Analysis of a Mandarin-English Code-switching Speech Corpus: SEAME</i>. Age <a href="https://www.researchgate.net/profile/Tien_Ping_Tan/publication/266890986_An_Analysis_of_a_Mandarin-English_Code-switching_Speech_Corpus_SEAME/links/54cb12f80cf2517b7560ffbb.pdf">[Paper]</a>


### Language Modeling and Speech Recognition
- <b>Yu, et al. (2023)</b> <i>Code-switching text generation and injection in mandarin-english asr</i>. ICASSP <a href="https://arxiv.org/pdf/2303.10949">[Paper]</a>
- <b>Tolúlopé, et al. (2023)</b> <i>Multilingual self-supervised speech representations improve the speech recognition of low-resource African languages with codeswitching</i>. Sixth Workshop on Computational Approaches to Linguistic Code-Switching. <a href="https://openreview.net/forum?id=mtrmzEoSRk">[Paper]</a>
- <b>Kumar, et al. (2020)</b> <i>Machine Learning based Language Modelling of Code Switched Data</i>. International Conference on Electronics and Sustainable Communication Systems (ICESC) <a href="https://ieeexplore.ieee.org/abstract/document/9155695">[Paper]</a>
- <b>Madhumani, et al. (2020)</b> <i>Learning not to Discriminate: Task Agnostic Learning for Improving Monolingual and Code-switched Speech Recognition</i>. Arxiv <a href="https://arxiv.org/pdf/2006.05257.pdf">[Paper]</a>
- <b>Shah, et al. (2020)</b> <i>Learning to Recognize Code-switched Speech Without Forgetting Monolingual Speech Recognition</i>. Arxiv <a href="https://arxiv.org/pdf/2006.00782.pdf">[Paper]</a>
- <b>Winata, et al. (2020)</b> <i>Meta-Transfer Learning for Code-Switched Speech Recognition</i>. ACL <a href="https://arxiv.org/pdf/2004.14228.pdf">[Paper]</a> <a href="https://github.com/audioku/meta-transfer-learning">[Code]</a>
- <b>Chandu, et al. (2020)</b> <i>Style Variation as a Vantage Point for Code-Switching</i>. Arxiv <a href="https://arxiv.org/pdf/2005.00458.pdf">[Paper]</a>
- <b>Ganji Sreeram and Rohit Sinha (2020)</b> <i>Exploration of End-to-End Framework for Code-Switching Speech Recognition Task: Challenges and Enhancements</i>. IEEE Access <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9058687">[Paper]</a>
- <b>Winata, et al. (2019)</b> <i>Code-Switched Language Models Using Neural Based Synthetic Data from Parallel Sentences</i>. CoNLL <a href="https://www.aclweb.org/anthology/K19-1026.pdf">[Paper]</a>
- <b>Hila Gonen and Yoav Goldberg (2019)</b> <i>Language Modeling for Code-Switching:Evaluation, Integration of Monolingual Data, and Discriminative Training</i>. EMNLP <a href="https://www.aclweb.org/anthology/D19-1427.pdf">[Paper]</a>
- <b>Lee, et al. (2019)</b> <i>Linguistically Motivated Parallel Data Augmentation for Code-switch Language Modeling</i>. Interspeech <a href="https://www.isca-speech.org/archive/Interspeech_2019/pdfs/1382.pdf">[Paper]</a>
- <b>Victor Soto and Julia Hirschberg (2019)</b> <i>Improving Code-Switched Language Modeling Performance Using Cognate Features</i>. Interspeech <a href="https://www.isca-speech.org/archive/Interspeech_2019/pdfs/2681.pdf">[Paper]</a>
- <b>Chang, et al. (2019)</b> <i>Code-switching Sentence Generation by Generative Adversarial Networks and its Application to Data Augmentation</i>. Interspeech <a href="https://www.isca-speech.org/archive/Interspeech_2019/pdfs/3214.pdf">[Paper]</a>
- <b>Zeng, et al. (2019)</b> <i>On the End-to-End Solution to Mandarin-English Code-switching Speech Recognition</i>. Interspeech <a href="https://www.isca-speech.org/archive/Interspeech_2019/pdfs/1429.pdf">[Paper]</a>
- <b>Taneja, et al. (2019)</b> <i>Exploiting Monolingual Speech Corpora for Code-mixed Speech Recognition</i>. Interspeech <a href="https://www.isca-speech.org/archive/Interspeech_2019/pdfs/1959.pdf">[Paper]</a>
- <b>Shan, et al. (2019)</b> <i>Investigating End-to-end Speech Recognition for Mandarin-english Code-switching</i>. IEEE International Conference on Acoustics, Speech, and Signal Processing (ICASSP) <a href="http://lxie.nwpu-aslp.org/papers/2019ICASSP-ChanghaoShan-CS.pdf">[Paper]</a>
- <b>Grandee Lee, Haizhou Li. (2019)</b> <i>Word and Class Common Space Embedding for Code-switch Language Modelling</i>. IEEE International Conference on Acoustics, Speech, and Signal Processing (ICASSP) <a href="https://www.researchgate.net/profile/Grandee_Lee/publication/331122308_Word_and_Class_Common_Space_Embedding_for_Code-switch_Language_Modelling/links/5c66b31a45851582c3eadf09/Word-and-Class-Common-Space-Embedding-for-Code-switch-Language-Modelling.pdf">[Paper]</a>
- <b>Hamed, et al. (2019)</b> <i>Code-Switching Language Modeling with Bilingual Word Embeddings: A Case Study for Egyptian Arabic-English</i>. International Conference on Speech and Computer <a href="https://link.springer.com/chapter/10.1007/978-3-030-26061-3_17">[Paper]</a>
- <b>Winata, et al. (2018)</b> <i>Learn to Code-Switch: Data Augmentation using Copy Mechanism on Language Modeling</i>. Arxiv <a href="https://arxiv.org/pdf/1810.10254.pdf">[Paper]</a>
- <b>Winata, et al. (2018)</b> <i>Towards End-to-end Automatic Code-Switching Speech Recognition</i>. Arxiv <a href="https://arxiv.org/pdf/1810.12620.pdf">[Paper]</a>
- <b>Nakayama, et al. (2018)</b> <i>Speech Chain for Semi-Supervised Learning of Japanese-English Code-Switching ASR and TTS</i>. IEEE Spoken Language Technology Workshop (SLT) <a href="https://ieeexplore.ieee.org/iel7/8632666/8639030/08639674.pdf">[Paper]</a>
- <b>Jesse Emond, Bhuwana Ramabhadran, Brian Roark, Pedro Moreno, and Min Ma. (2018)</b> <i>Transliteration Based Approaches to Improve Code-Switched Speech Recognition Performance</i>, IEEE Spoken Language Technology Workshop (SLT) <a href="https://ieeexplore.ieee.org/iel7/8632666/8639030/08639699.pdf">[Paper]</a>
- <b>Ganji Sreeram and Rohit Sinha. (2018)</b> <i>Exploiting Parts-of-Speech for Improved Textual Modeling of Code-Switching Data</i>. 2018 Twenty Fourth National Conference on Communications (NCC) <a href="https://ieeexplore.ieee.org/abstract/document/8600097">[Paper]</a>
- <b>Garg, et al. (2018)</b> <i>Code-switched Language Models Using Dual RNNs and Same-Source Pretraining</i>. EMNLP <a href="http://aclweb.org/anthology/D18-1346">[Paper]</a>
- <b>Ewald van der Westhuizen and Thomas R. Niesler. (2018)</b> <i>Synthesised bigrams using word embeddings for code-switched
ASR of four South African language pairs</i>. Computer Speech and Language <a href="https://www.sciencedirect.com/science/article/pii/S0885230818301815">[Paper]</a>
- <b>Biswal, et al. (2018)</b> <i>Multilingual Neural Network Acoustic Modelling for ASR of Under-Resourced
English-isiZulu Code-Switched Speech</i>. Interspeech <a href="https://www.researchgate.net/profile/Emre_Yilmaz33/publication/325571050_Multilingual_Neural_Network_Acoustic_Modelling_for_ASR_of_Under-Resourced_English-isiZulu_Code-Switched_Speech/links/5b2cdac40f7e9b0df5baf271/Multilingual-Neural-Network-Acoustic-Modelling-for-ASR-of-Under-Resourced-English-isiZulu-Code-Switched-Speech.pdf">[Paper]</a>
- <b>Winata, et al. (2018)</b> <i>Code-Switching Language Modeling using Syntax-Aware Multi-Task Learning</i>. 3rd Workshop of Computational Approaches to Linguistic Code-switching, ACL <a href="http://aclweb.org/anthology/W18-3207">[Paper]</a> <a href="https://github.com/gentaiscool/multi-task-cs-lm">[Code]</a>
- <b>Chandu, et al. (2018)</b> <i>Language Informed Modeling of Code-Switched Text</i>. 3rd Workshop of Computational Approaches to Linguistic Code-switching, ACL <a href="http://www.aclweb.org/anthology/W18-3211">[Paper]</a>
- <b>Pratapa, et al. (2018)</b> <i>Language Modeling for Code-Mixing: The Role of Linguistic Theory based Synthetic Data</i>. ACL <a href="https://www.microsoft.com/en-us/research/uploads/prod/2018/05/language_modeling_cm.pdf">[Paper]</a> 
- <b>Sivasankaran, et al. (2018)</b> <i>Phone Merging For Code-Switched Speech Recognition</i>. 3rd Workshop of Computational Approaches to Linguistic Code-switching, ACL <a href="http://aclweb.org/anthology/W18-3202">[Paper]</a> 
- <b>Garg, et al. (2018)</b> <i>Dual Language Models for Code Switched Speech Recognition</i>. Interspeech <a href="https://arxiv.org/abs/1711.01048">[Paper]</a>
- <b>Baheti, et al. (2017)</b> <i>Curriculum Design for Code-switching: Experiments with Language
Identification and Language Modeling with Deep Neural Networks</i>. ICON <a href="https://www.microsoft.com/en-us/research/uploads/prod/2018/04/icon-2017-curriculum.pdf">[Paper]</a>
- <b>Adel, et al. (2015)</b> <i>Syntactic and Semantic Features For Code-Switching Factored Language Models</i>. IEEE Transactions on Audio, Speech, and Language Processing <a href="https://arxiv.org/pdf/1710.01809.pdf">[Paper]</a>
- <b>Ying Li and Pascale Fung. (2014)</b> <i>Code switch language modeling with Functional Head Constraint</i>. ICASSP <a href="https://www.semanticscholar.org/paper/Code-switch-language-modeling-with-Functional-Head-Li-Fung/46996cb0e1b6ff7c4bf88b6b200327a1a19cd946">[Paper]</a>
- <b>Ying Li and Pascale Fung. (2014)</b> <i>Language Modeling with Functional Head Constraint for Code Switching Speech Recognition</i>. EMNLP <a href="http://www.aclweb.org/anthology/D14-1098">[Paper]</a>
- <b>Adel, et al. (2013)</b> <i>Combination of Recurrent Neural Networks and Factored Language
Models for Code-Switching Language Modeling</i>. ACL <a href="http://www.aclweb.org/anthology/P13-2037">[Paper]</a>
- <b>Adel, et al. (2013)</b> <i>Recurrent neural network language modeling for code switching conversational speech</i>. ICASSP <a href="https://ieeexplore.ieee.org/document/6639306/">[Paper]</a>
- <b>Vu, et al. (2012)</b> <i>A First Speech Recognition System for Mandarin-English Code-Switch Conversational Speech</i>. ICASSP <a href="https://www.csl.uni-bremen.de/cms/images/documents/publications/ICASSP2012-Vu_CodeSwitch.pdf">[Paper]</a>
- <b>Ying Li and Pascale Fung. (2012)</b> <i>Code-switch Language Model with Inversion Constraints for Mixed Language Speech Recognition</i>. COLING <a href="http://www.aclweb.org/anthology/C12-1102">[Paper]</a>
- <b>Li, et al. (2011)</b> <i>Asymmetric acoustic modeling of mixed language speech</i>. ICASSP <a href="https://pdfs.semanticscholar.org/1b57/5dbb14901b0cfa668f21a3b188beee4c9582.pdf">[Paper]</a>

### Discourse
- <b>Sravani, et al. (2021)</b> <i>Political Discourse Analysis: A Case Study of Code Mixing and Code Switching in Political Speeches</i>. Proceedings of the 5th Workshop on Computational Approaches to Code Switching (CALCS), NAACL <a href="https://www.aclweb.org/anthology/2021.calcs-1.1.pdf">[Paper]</a>

### Generation
- <b>Gupta, et al. (2020)</b> <i>A Semi-supervised Approach to Generate the Code-Mixed Text using Pre-trained Encoder and Transfer Learning</i>. Findings of EMNLP <a href="https://www.aclweb.org/anthology/2020.findings-emnlp.206.pdf">[Paper]</a>
- <b>Bryan Gregorius and Takeshi Okadome (2022)</b> <i>Generating Code-Switched Text from Monolingual Text with Dependency Tree</i>. The 20th Annual Workshop of the Australasian Language Technology Association <a href="https://aclanthology.org/2022.alta-1.12/">[Paper]</a> <a href="https://github.com/Selubi/CSify">[Code]</a>

### Speech Synthesis
- <b>Sai Krishna Rallabandi and Alan W Black (2019)</b> <i>Variational Attention using Articulatory Priors for generating Code Mixed Speech using Monolingual Corpora</i>. Interspeech <a href="https://pdfs.semanticscholar.org/5e74/c4c5688a24248a9bd04aa0474c28bc267ba5.pdf">[Paper]</a>
- <b>Sai Krishna Rallabandi and Alan W Black (2017)</b> <i>On Building Mixed Lingual Speech Synthesis Systems.</i> Interspeech <a href="https://pdfs.semanticscholar.org/02a2/0ed2182475b40a4e7744aa6555607adffa62.pdf">[Paper]</a>
- <b>Chandu, et al. (2017)</b> <i>Speech Synthesis for Mixed-Language Navigation Instructions.</i> Interspeech <a href="https://pdfs.semanticscholar.org/99f0/7e194197a55fd017657d4cd1a8d9c349de05.pdf?_ga=2.136822064.183444372.1582035562-2106241630.1557729576">[Paper]</a>

### Metric
- <b>Guzman, et al. (2017)</b> <i>Metrics for modeling code-switching across corpora</i>. Interspeech <a href="https://pdfs.semanticscholar.org/25a5/cf5c7dc2269cf67d98b2fb46317a4d16b581.pdf">[Paper]</a>

### Representation Learning
- <b>Adilazuarda, et al. (2023)</b> <i>IndoRobusta: Towards Robustness Against Diverse Code-Mixed Indonesian Local Languages</i>. Proceedings of the First Workshop on Scaling Up Multilingual Evaluation, AACL <a href="https://aclanthology.org/2022.sumeval-1.5.pdf">[Paper]</a> <a href="https://github.com/faridlazuarda/indorobusta">[Code]</a>
- <b>Prasad, et al. (2021)</b> <i>The Effectiveness of Intermediate-Task Training for Code-Switched Natural Language Understanding</i>. Proceedings of the 1st Workshop on Multilingual Representation Learning, EMNLP <a href="https://aclanthology.org/2021.mrl-1.16.pdf">[Paper]</a>
- <b>Winata, et al. (2021)</b> <i>Are Multilingual Models Effective in Code-Switching?</i>. Proceedings of the 5th Workshop on Computational Approaches to Code Switching (CALCS), NAACL <a href="https://www.aclweb.org/anthology/2021.calcs-1.20.pdf">[Paper]</a>
- <b>Rizal, et al. (2020)</b> <i>Evaluating Word Embeddings for Indonesian–English Code-Mixed Text Based on Synthetic Data</i>. Proceedings of the 4th Workshop on Computational Approaches to Code Switching (CALCS), LREC <a href="https://www.aclweb.org/anthology/2020.calcs-1.4/">[Paper]</a>
- <b>Winata, et al. (2019)</b> <i>Hierarchical Meta-Embeddings for Code-Switching Named Entity Recognition</i>. EMNLP <a href="https://arxiv.org/abs/1909.08504">[Paper]</a> <a href="https://github.com/gentaiscool/meta-emb">[Code]</a>
- <b>Pratapa, et al. (2018)</b> <i>Word Embeddings for Code-Mixed Language Processing</i>. EMNLP <a href="http://www.aclweb.org/anthology/D18-1344">[Paper]</a>

### Machine Translation
- <b>Pengpun, et al. (2024)</b> <i>On Creating an English-Thai Code-switched Machine Translation in Medical Domain.</i> EMNLP <a href="https://arxiv.org/abs/2410.16221">[Paper]</a>
- <b>Gaser, et al. (2023)</b> <i>Exploring Segmentation Approaches for Neural Machine Translation of Code-Switched Egyptian Arabic-English Text</i>. EACL <a href="https://aclanthology.org/2023.eacl-main.256.pdf">[Paper]</a>
- <b>Kuwanto, et al. (2021)</b> <i>Low-Resource Machine Translation Training Curriculum Fit for Low-Resource Languages</i>. Arxiv <a href="https://arxiv.org/pdf/2103.13272">[Paper]</a>
- <b>Vivek Srivastava and Mayank Singh (2020)</b> <i>PHINC: A Parallel Hinglish Social Media Code-Mixed Corpus for Machine Translation</i>. W-NUT, EMNLP <a href="http://noisy-text.github.io/2020/pdf/2020.d200-1.7.pdf">[Paper]</a> <a href="https://zenodo.org/record/3605597#.X5rwWXgzZQI">[Dataset]</a>
- <b>Thoudam Doren Singh and Thamar Solorio. (2017)</b> <i>Towards Translating Mixed-Code Comments from Social Media</i>. CICLing <a href="https://link.springer.com/chapter/10.1007/978-3-319-77116-8_34">[Paper]</a>

### Speech Translation
- <b>Alastruey, et al. (2023)</b> <i>Towards Real-World Streaming Speech Translation for Code-Switched Speech</i>. CALCS, EMNLP <a href="https://aclanthology.org/2023.calcs-1.2.pdf">[Paper]</a>

### Natural Language Understanding
- <b>Krishnan, et al. (2021)</b> <i>Multilingual Code-Switching for Zero-Shot Cross-Lingual Intent Prediction and Slot Filling</i>. MRL, EMNLP <a href="https://aclanthology.org/2021.mrl-1.18.pdf">[Paper]</a>

### Named Entity Recognition
- <b>Priyadharshini, et al. (2020)</b> <i>Named Entity Recognition for Code-Mixed Indian Corpus using Meta Embedding</i>. 6th International Conference on Advanced Computing and Communication Systems (ICACCS) <a href="https://ieeexplore.ieee.org/abstract/document/9074379">[Paper]</a>
- <b>Winata, et al. (2019)</b> <i>Learning Multilingual Meta-Embeddings for Code-Switching Named Entity Recognition</i>. RepL4NLP, ACL <a href="https://www.aclweb.org/anthology/W19-4320">[Paper]</a> <a href="https://github.com/gentaiscool/meta-emb">[Code]</a>
- <b>Aguilar, et al. (2018)</b> <i>Named Entity Recognition on Code-Switched Data: Overview of the CALCS 2018 Shared Task</i>. 3rd Workshop of Computational Approaches to Linguistic Code-switching, ACL <a href="http://www.aclweb.org/anthology/W18-3219">[Paper]</a>
- <b>Wang, et al. (2018)</b> <i>Code-Switched  Named  Entity  Recognition
with Embedding Attention</i>. 3rd Workshop of Computational Approaches to Linguistic Code-switching, ACL <a href="http://www.aclweb.org/anthology/W18-3221">[Paper]</a>
- <b>Winata, et al. (2018)</b> <i>Bilingual Character Representation for Efficiently Addressing Out-of-Vocabulary Words in Code-Switching Named Entity Recognition</i>. 3rd Workshop of Computational Approaches to Linguistic Code-switching, ACL <a href="http://aclweb.org/anthology/W18-3214">[Paper]</a>
- <b>Aguilar, et al. (2017)</b> <i>A Multi-task Approach for Named Entity Recognition in Social Media Data</i>. 3rd Workshop on Noisy User-generated Text, EMNLP <a href="http://www.aclweb.org/anthology/W17-4419">[Paper]</a>

### Linguistics
- <b>Li Nyuyen. (2018)</b> <i>Borrowing or Code-switching? Traces of community norms in Vietnamese-English speech.</i> Australian Journal of Linguistics 38.4 (2018): 443-466. <a href="https://www.tandfonline.com/doi/abs/10.1080/07268602.2018.1510727">[Paper]</a>
- <b>Fairchild, Sarah, and Janet G. Van Hell. (2017)</b> <i>Determiner-noun code-switching in Spanish heritage speakers.</i> Bilingualism: Language and Cognition 20.1 (2017): 150-161. <a href="https://www.researchgate.net/profile/Janet_Van_Hell/publication/282895015_Determiner-noun_code-switching_in_Spanish_heritage_speakers/links/5891e94ba6fdcc1b41469634/Determiner-noun-code-switching-in-Spanish-heritage-speakers.pdf">[Paper]</a>
- <b>Bhatt, Rakesh M., and Agnes Bolonyai. (2011)</b> <i>Code-switching and the optimal grammar of bilingual language use.</i> Bilingualism: Language and Cognition 14.4 (2011): 522-546. <a href="https://s3.amazonaws.com/academia.edu.documents/38571919/BLC-Bhatt-Bolonyai.pdf?AWSAccessKeyId=AKIAIWOWYYGZ2Y53UL3A&Expires=1540209279&Signature=srQ%2B9cKb1LdK4qgUtuGJ1zG3Wa4%3D&response-content-disposition=inline%3B%20filename%3DCode-switching_and_the_optimal_grammar_o.pdf">[Paper]</a>
- <b>Lipski (2005)</b> <i>Code-switching or Borrowing? No sé so no puedo decir, you know.</i> Second Workshop on Spanish Sociolinguistics <a href="http://commonweb.unifr.ch/artsdean/pub/gestens/f/as/files/4740/21370_065330.pdf">[Paper]</a>
- <b>Roberto R. Heredia and Jeanette Altarriba (2001)</b> <i>Bilingual Language Mixing: Why Do Bilinguals Code-Switch?</i> SAGE Publications <a href="https://journals.sagepub.com/doi/pdf/10.1111/1467-8721.00140">[Paper]</a>
- <b>Belazi, et al. (1994)</b> <i>Code switching and X-bar theory: The functional head constraint</i>. Linguistic inquiry Vol 25 No.2 Spring <a href="https://www.jstor.org/stable/4178859">[Paper]</a>
- <b>Shana Poplack (1980)</b> <i>Sometimes i’ll start a sentence in spanish y termino en espanol: toward a typology of code-switching1</i>. Linguistics 18(7-8) <a href="https://yorkspace.library.yorku.ca/xmlui/bitstream/handle/10315/2506/CRLC00161.pdf?sequence=1&isAllowed=y">[Paper]</a>
- <b>Pfaff, Carol W. (1979)</b> <i>Constraints on language mixing: intrasentential code-switching and borrowing in Spanish/English.</i> Language: 291-318. <a href="https://www.jstor.org/stable/pdf/412586.pdf?casa_token=_ghSnFiA7q4AAAAA:TR2oFkeipuhqYca38iK-55yaQ2vMiJG47mdMkDHw3QMdOq1TN935OkaeI5i06KgXnGg8tPjQwXnOLlA8sMdL2VC6kGSrsE2bX2tONqcwhWI2aWcs8kBg">[Paper]</a>
- <b>Shana Poplack (1978)</b> <i>Syntactic structure and social function of code-switching</i>. Vol. 2. Centro de Estudios Puertorriqueños, City University of New York <a href="https://www.researchgate.net/publication/317039669_Syntactic_structure_and_social_function_of_code-switching">[Paper]</a>
- <b>Gumperz, J. J., & Hernandez, E. (1969)</b> <i>Cognitive aspects of bilingual communication</i>. Institute of International Studies, University of California <a href="https://files.eric.ed.gov/fulltext/ED138103.pdf">[Paper]</a>

### Affective Computing
- <b>Chakravarthi, et al. (2021)</b> <i>DravidianCodeMix: Sentiment Analysis and Offensive Language Identification Dataset for Dravidian Languages in Code-Mixed Text</i>. Arxiv <a href="https://arxiv.org/pdf/2106.09460.pdf">[Paper]</a> <a href="https://github.com/bharathichezhiyan/DravidianCodeMix-Dataset">[Code and Dataset]</a>
- <b>Siddharth Yadav (2020)</b> <i>Unsupervised Sentiment Analysis for Code-mixed Data</i>. Arxiv<a href="https://arxiv.org/pdf/2001.11384.pdf">[Paper]</a> <a href="https://github.com/sedflix/unsacmt">[Code]</a>
- <b>Wang, et al. (2017)</b> <i>Emotion Analysis in Code-Switching Text With Joint Factor Graph Model</i>. IEEE/ACM Transactions on Audio, Speech, and Language Processing <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7776833">[Paper]</a>
- <b>Wang, et al. (2016)</b> <i>A Bilingual Attention Network for Code-switched Emotion Prediction</i>. COLING <a href="https://www.aclweb.org/anthology/C16-1153.pdf">[Paper]</a>
- <b>Sophia Lee and Zhongqing Wang (2015)</b> <i>Emotion in Code-switching Texts: Corpus Construction and Analysis</i>. Proceedings of the Eighth SIGHAN Workshop on Chinese Language Processing <a href="https://www.aclweb.org/anthology/W15-3116.pdf">[Paper]</a>
- <b>Wang, et al. (2015)</b> <i>Emotion Detection in Code-switching Texts via Bilingual and Sentimental Information</i>. ACL <a href="https://www.aclweb.org/anthology/P15-2125.pdf">[Paper]</a>
  
### Dialog and Conversational System
- <b>Gupta, et al. (2018)</b> <i>Uncovering Code-Mixed Challenges: A Framework for Linguistically Driven Question Generation and Neural based Question Answering</i>. CoNLL <a href="http://www.aclweb.org/anthology/K18-1012">[Paper]</a>

### Discourse
- <b>Sravani, et al. (2021)</b> <i>Political Discourse Analysis: A Case Study of Code Mixing and Code Switching in Political Speeches</i>. CALCS Proceedings of the 5th Workshop on Computational Approaches to Code Switching (CALCS), NAACL <a href="https://www.aclweb.org/anthology/2021.calcs-1.1.pdf">[Paper]</a>

### Syntax
- <b>Kodali, et al. (2022)</b> <i>SyMCoM - Syntactic Measure of Code Mixing A Study Of English-Hindi Code-Mixing</i>. Findings of ACL <a href="https://aclanthology.org/2022.findings-acl.40.pdf">[Paper]</a>
- <b>Özlem Çetinoglu and Çagrı Çöltekin (2019)</b> <i>Challenges of Annotating a Code-Switching Treebank</i>. SyntaxFest <a href="https://syntaxfest.github.io/syntaxfest19/proceedings/papers/paper_83.pdf">[Paper]</a>

### Adversarial Attack
- <b>Samson Tan and Shafiq Joty (2021)</b> <i>Code-Mixing on Sesame Street: Dawn of the Adversarial Polyglots</i>. NAACL <a href="https://arxiv.org/pdf/2103.09593.pdf">[Paper]</a>

### Social Linguistics
- <b>Bolock, et al. (2020)</b> <i>Who, When and Why: The 3 Ws of Code-Switching</i>. International Conference on Practical Applications of Agents and Multi-Agent Systems <a href="https://www.researchgate.net/profile/Alia_El_Bolock/publication/342705747_Who_When_and_Why_The_3_Ws_of_Code-Switching/links/5f0a659892851c52d62cfd13/Who-When-and-Why-The-3-Ws-of-Code-Switching.pdf">[Paper]</a>
- <b>Yoder, et al. (2017)</b> <i>Code-Switching as a Social Act:The Case of Arabic Wikipedia Talk Pages</i>. Proceedings of the Second Workshop on Natural Language Processing and Computational Social Science, ACL <a href="https://www.aclweb.org/anthology/W17-2911">[Paper]</a>
- <b>Agrawal, et al. (2017)</b> <i>Agarwal, Prabhat, et al. I may talk in English but gaali toh Hindi mein hi denge: A study of English-Hindi code-switching and swearing pattern on social networks</i>. International Conference on Communication Systems and Networks (COMSNETS) <a href="https://ieeexplore.ieee.org/abstract/document/7945452">[Paper]</a>

### Benchmark
- <b>Khanuja, et al. (2020)</b> <i>GLUECoS : An Evaluation Benchmark for Code-Switched NLP</i>. ACL <a href="https://arxiv.org/pdf/2004.12376.pdf">[Paper]</a>
- <b>Aguilar, et al. (2020)</b> <i>LinCE: A Centralized Benchmark for Linguistic Code-switching Evaluation</i>. LREC <a href="https://www.aclweb.org/anthology/2020.lrec-1.223.pdf">[Paper]</a>

### Social Media
- <b>Bali, et al. (2014)</b> <i>“I am borrowing ya mixing ?” An Analysis of English-Hindi Code Mixing in Facebook</i>. Proceedings of The First Workshop on Computational Approaches to Code Switching <a href="https://www.aclweb.org/anthology/W14-3914.pdf">[Paper]</a>

### Text Normalization
- <b>Dwija Parikh and Thamar Solorio (2021)</b> <i>Normalization and Back-Transliteration for Code­Switched Data</i>. CALCS Proceedings of the 5th Workshop on Computational Approaches to Code Switching (CALCS), NAACL <a href="https://www.aclweb.org/anthology/2021.calcs-1.15.pdf">[Paper]</a>

### Toolkit
#### Synthetic Data Generation Toolkit
- <b>Jayanthi, et al. (2021)</b> <i>CodemixedNLP: An Extensible and Open NLP Toolkit for Code-Mixing</i>. CALCS Proceedings of the 5th Workshop on Computational Approaches to Code Switching (CALCS), NAACL <a href="https://www.aclweb.org/anthology/2021.calcs-1.14.pdf">[Paper]</a> <a href="https://github.com/murali1996/CodemixedNLP">[Code]</a>
- <b>Rizvi, et al. (2021)</b> <i>GCM: A Toolkit for Generating Synthetic Code-mixed Text</i>. EACL (System Demonstrations) <a href="https://www.aclweb.org/anthology/2021.eacl-demos.24.pdf">[Paper]</a> <a href="https://github.com/microsoft/CodeMixed-Text-Generator">[Code]</a>

#### Annotation Toolkit
- <b>Shah, et al. (2019)</b> <i>CoSSAT: Code-Switched Speech Annotation Tool</i>. Proceedings of the First Workshop on Aggregating and Analysing Crowdsourced Annotations for NLP <a href="https://www.aclweb.org/anthology/D19-5907.pdf">[Paper]</a>

#### Summarization
- <b>Mehnaz, et al. (2021)</b> <i>GupShup: Summarizing Open-Domain Code-Switched Conversations</i>. EMNLP <a href="https://aclanthology.org/2021.emnlp-main.499.pdf"></a>

#### Question Answering
- <b>Gupta, et al. (2020)</b> <i>A Unified Framework for Multilingual and Code-Mixed Visual Question Answering</i>. AACL-IJCNLP <a href="">[TBA]</a>

#### Dialog and Conversational System
- <b>Bawa, et al. (2020)</b> <i>Do Multilingual Users Prefer Chat-bots that Code-mix? Let's Nudge and Find Out!</i>. ACM on Human-Computer Interaction <a href="https://dl.acm.org/doi/pdf/10.1145/3392846">[Paper]</a>
- <b>Banerjee, et al. (2018)</b> <i>A Dataset for Building Code-Mixed Goal Oriented Conversation Systems</i>. COLING <a href="https://arxiv.org/pdf/1806.05997.pdf">[Paper]</a>

### Position Paper
- <b>Nguyen, et al. (2022)</b> <i>Building Educational Technologies for Code-Switching: Current Practices, Difficulties and Future Directions</i>. Languages <a href="https://www.mdpi.com/2226-471X/7/3/220/pdf?version=1660898944">[Paper]</a>

## Books
- <b>Caciullos and Travis (2018)</b> <i>Bilingualism in the Community</i>. Cambridge University Press

## Theses
- <b>Genta Indra Winata (2021)</b> <i>Multilingual Transfer Learning for Code-Switched Language and Speech Neural Modeling</i>. <a href="https://arxiv.org/pdf/2104.06268.pdf">[Thesis]</a>
- <b>Gustavo Aguilar (2020)</b> <i>Neural Sequence Labeling on Social Media Text</i>. <a href="https://uh-ir.tdl.org/bitstream/handle/10657/7726/AGUILAR-DISSERTATION-2020.pdf?sequence=1&isAllowed=y">[Thesis]</a>
- <b>Victor Soto Martinez (2020)</b> <i>Identifying and Modeling Code-Switched Language</i>. <a href="http://www.cs.columbia.edu/speech/ThesisFiles/victor_soto.pdf">[Thesis]</a>
