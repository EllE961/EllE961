<div align="center">

# Yahya Al Salmi

**I build things from the bottom up so I can measure them.**

<a href="mailto:yahyaalsalmi961@gmail.com"><img src="https://img.shields.io/badge/email-yahyaalsalmi961%40gmail.com-1f1d1b?style=flat-square&labelColor=0d0c0b" alt="email: yahyaalsalmi961@gmail.com"></a>
<img src="https://img.shields.io/badge/mostly-python%20%C2%B7%20pytorch-d95926?style=flat-square&labelColor=0d0c0b" alt="mostly Python and PyTorch">
<img src="https://img.shields.io/badge/also-typescript%20%C2%B7%20c%23%20%C2%B7%20rust-3987e5?style=flat-square&labelColor=0d0c0b" alt="also TypeScript, C# and Rust">

</div>

The bigger projects here are a Llama-style language model written without `transformers`, a RAG engine with its own
HNSW index, and an IDE that draws a repository as a honeycomb. On the smaller ones I care about the same thing: an
honest evaluation against a simple baseline. A few READMEs here say the baseline won, and that's on purpose.

Outside of machine learning I play CTFs (mostly reversing and pwn) and build the tools I want while doing it.

---

## Featured

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/EllE961/Hexis"><img src="https://raw.githubusercontent.com/EllE961/Hexis/main/docs/assets/hero.png" alt="Hexis showing a repository as a honeycomb of hex cells grouped into coloured folder territories"></a>
      <h3><a href="https://github.com/EllE961/Hexis">Hexis</a></h3>
      An IDE that draws your repository as a honeycomb. Files are hex cells and folders are territories, next to an editor, a git panel, a terminal and Claude agents that plan, code and review on the same grid.
      <br><br><sub>React · Express · Tauri · CodeMirror · Claude Agent SDK</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/EllE961/forge-llm"><img src="https://raw.githubusercontent.com/EllE961/forge-llm/main/docs/assets/generate.png" alt="Forge playground: generated text coloured by token surprisal with the top-5 alternatives for a token"></a>
      <h3><a href="https://github.com/EllE961/forge-llm">forge-llm</a></h3>
      A 26.7M-parameter Llama-style model built from scratch: BPE tokenizer, pretraining, a KV-cached decoder captured as a CUDA graph (590 tok/s), speculative decoding and LoRA, plus a playground for looking inside it.
      <br><br><sub>PyTorch · CUDA graphs · FastAPI</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/EllE961/sift-rag"><img src="https://raw.githubusercontent.com/EllE961/sift-rag/main/docs/assets/ui-ask.png" alt="Sift answering a SciFact claim with citation chips and highlighted source spans"></a>
      <h3><a href="https://github.com/EllE961/sift-rag">sift-rag</a></h3>
      Hybrid-search RAG from first principles: BM25, a numba HNSW index, rank fusion and reranking, with citations that point at exact character spans. 0.736 nDCG@10 on SciFact, evaluated on BEIR.
      <br><br><sub>Python · numba · Claude citations · BEIR</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/EllE961/CarDetection"><img src="https://raw.githubusercontent.com/EllE961/CarDetection/main/docs/assets/demo.gif" alt="YOLOv8 tracking vehicles on a motorway with drawn In and Out zones"></a>
      <h3><a href="https://github.com/EllE961/CarDetection">CarDetection</a></h3>
      Vehicle tracking with YOLOv8 and BoT-SORT that counts how traffic moves between zones you draw on the video. It matched 23 of the 24 transitions I counted by hand on a motorway clip.
      <br><br><sub>YOLOv8 · OpenCV · BoT-SORT</sub>
    </td>
  </tr>
</table>

---

## Machine learning

| Project | What it is |
|---|---|
| [zero-four](https://github.com/EllE961/zero-four) | AlphaZero for Connect Four, trained only by self-play and graded against a perfect solver: Elo 1621, optimal moves on 98.1% of benchmark positions. |
| [compass-recsys](https://github.com/EllE961/compass-recsys) | Two-stage film recommender on MovieLens-1M: SASRec and a two-tower retriever feeding a LambdaRank ranker, 0.179 NDCG@10 over all 3,706 films. |
| [Parkinson's voice classifier](https://github.com/EllE961/Parkinson-s-Disease-Kaggle) | Shows that random splits inflate accuracy from 0.78 to 0.90 when the same speakers sit in train and test. |
| [Amazon Fine Food Reviews](https://github.com/EllE961/Amazon-Fine-Food-Reviews) | Sentiment model on all 568k reviews, 0.899 accuracy, with an analysis of 3-star reviews and duplicates. |
| [Fake News Detection](https://github.com/EllE961/Fake-News-Detection) | Fake news classifier that measures how much of its 0.990 accuracy comes from the Reuters byline. |
| [news-detector-app](https://github.com/EllE961/news-detector-app) | The same model in a PyQt5 desktop app that labels a pasted article Fake or Real. |
| [Spam Detection](https://github.com/EllE961/Spam-Email-Detection) | SMS spam filter with TF-IDF and Naive Bayes, 0.961 accuracy and no false positives. |
| [Novel genre classification](https://github.com/EllE961/Automated-Multi-Genre-Classification-of-Novels) | Group project tagging 762 Project Gutenberg books with ten genres, 0.49 macro F1. |
| [Movie recommender](https://github.com/EllE961/Movie-Recommendation-System) | MovieLens SVD compared against bias and k-NN baselines, with learned movie similarities. |
| [Customer segmentation](https://github.com/EllE961/Mall-Customer-Segmentation-Data-KMeans) | KMeans with k chosen by silhouette and checked for stability across 20 seeds. |
| [Titanic](https://github.com/EllE961/Titanic-Survival-Prediction) · [Iris](https://github.com/EllE961/Iris-Flower-Classification) · [Loan](https://github.com/EllE961/Loan-Prediction) | Classic tabular problems, each cross-validated against the simplest rule that could beat it. |
| [chess-ai](https://github.com/EllE961/chess-ai) | Experimental AlphaZero-style agent: policy/value net, MCTS self-play, screen board detection and mouse automation. |
| [Coin collector RL](https://github.com/EllE961/RLAgent-curriculum-) | Unity ML-Agents arena where 12 PPO agents learn to collect coins and avoid obstacles. |
| [TextProcessor](https://github.com/EllE961/TextProcessor-EllE) | Tkinter app that paraphrases and summarizes text with two T5 models. |
| [100 DS/ML projects](https://github.com/EllE961/DataScience-ML-Projects) | My checklist of 100 project ideas with datasets, linked to the ones I've finished. |

## Computer vision

| Project | What it is |
|---|---|
| [CarDetection](https://github.com/EllE961/CarDetection) | YOLOv8 vehicle tracking with zone-to-zone traffic counts. |
| [Digit Recognizer](https://github.com/EllE961/Digit-Recognizer-Application) | Tkinter drawing pad that reads handwritten digits with a Keras CNN, 99.01% on the MNIST test set. |
| [Color Detection](https://github.com/EllE961/Color-Detection) | PyQt5 webcam app that boxes and names 44 colors from hand-written HSV ranges in OpenCV. |
| [Face Mask Detection](https://github.com/EllE961/Face-Mask-Detection) | Faster R-CNN that finds faces and classifies them as masked or unmasked. |
| [Face recognition](https://github.com/EllE961/real-time-face-recognition-system) | PyQt5 app for registering faces and recognizing them in real time. |

## Security and CTFs

| Project | What it is |
|---|---|
| [ghidra-decompile-all](https://github.com/EllE961/ghidra-decompile-all) | Ghidra script that dumps every decompiled function in a program to one C-style text file. |
| [pwnelle](https://github.com/EllE961/pwnelle) | Static ELF triage for pwn: protections, interesting functions, ROP gadgets and ranked exploit paths. |
| [SmartHunter](https://github.com/EllE961/smarthunter) | Scans a file for hidden strings and flags across 11 encodings, ranked by confidence. |
| [CTF Task Tracker](https://github.com/EllE961/CTF-Task-Tracker-bot) | Discord bot that tracks a team's CTF challenges and scaffolds a matching GitHub repo. |
| [LA CTF 2025: McFlagChecker](https://github.com/EllE961/LA-CTF-McFlagChecker) | Reversing a Minecraft datapack flag checker by inverting a GF(251) matrix and discrete logs. |
| [DamCTF 2025](https://github.com/EllE961/damctf2025-writeup) · [UMDCTF 2025](https://github.com/EllE961/UMDCTF2025Writeup) | Write-ups across pwn, rev, crypto, misc and OSINT, each with a solver. |

## Tools, apps and games

| Project | What it is |
|---|---|
| [GitEllE](https://github.com/EllE961/GitEllE) | Git reimplemented in Python to learn its internals: SHA-1 zlib object store, staging index and refs. |
| [ArcadeHub](https://github.com/EllE961/ArcadeHub) | WinForms arcade launcher in C# with a Snake game written from scratch on a timer loop and GDI+. |
| [Quick-Cash](https://github.com/EllE961/Quick-Cash) | Android job board from a university group project, on Firebase with Google Maps and PayPal. |
| [reactplayground](https://github.com/EllE961/reactplayground) | Expo app with a live Flexbox playground and stack, tab and drawer navigator demos. |
| [prodmanager](https://github.com/EllE961/prodmanager) | React and Bootstrap product manager UI (its first scaffold is [product-management-app](https://github.com/EllE961/product-management-app)). |

<details>
<summary><b>Coursework</b></summary>
<br>

| Project | What it is |
|---|---|
| [A3-CSCI4177](https://github.com/EllE961/A3-CSCI4177) | Load tests, OWASP ZAP scans and monitoring for a Next.js and Express microservice store. |
| [CSCI4177L3](https://github.com/EllE961/CSCI4177L3) | React and Redux product catalogue on an Express and PostgreSQL API with JWT roles. |
| [lab7csci3172](https://github.com/EllE961/lab7csci3172) | React portfolio with persistent dark mode and data from Netlify Functions. |
| [lab5csci3172](https://github.com/EllE961/lab5csci3172) | Meme generator with canvas pixel effects and Unsplash search through a Netlify Function. |
| [STAT2430-Assignment-1](https://github.com/EllE961/STAT2430-Assignment-1) | ggplot2 study of the Palmer penguins in R Markdown. |

</details>
