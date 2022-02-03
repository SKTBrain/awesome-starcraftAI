
# Awesome StarCraft AI

A curated list of resources dedicated to StarCraft AI.

We are looking for more contributors and maintainers!

## Table of Contents
 - [API/Codes](#apicodes)
 - [Replays](#replays)
 - [Research Papers](#research-papers)
   - [Surveys](#surveys)
   - [Benchmark](#benchmark)
   - [Thesis](#thesis)
   - [Dataset](#dataset)
   - [Bayesian Approach](#bayesian-approach)
   - [Satisfaction and Optimization](#satisfaction-and-optimization)
   - [Planning](#planning)
   - [Prediction](#prediction)
   - [Control](#control)
   - [Full Game Play](#full-game-play)
   - [Learning from Demonstration](#learning-from-demonstration)
   - [Miscellaneous](#miscellaneous)
 - [Reports](#reports)
 - [Competitions](#competitions)
 - [Others](#others)

<div>
<img align="center" src="https://github.com/SKTBrain/awesome-starcraftAI/blob/master/images/3.png?raw=true" width="99.5%">
<div align="center">Photo Credit: Google DeepMind <a href="https://deepmind.com/blog/deepmind-and-blizzard-release-starcraft-ii-ai-research-environment/">[Link]</a></div>
<br>
</div>
<div>
<img align="center" src="https://github.com/SKTBrain/awesome-starcraftAI/blob/master/images/1.png?raw=true" width="45.5%"><img align="center" src="https://github.com/SKTBrain/awesome-starcraftAI/blob/master/images/2.jpg?raw=true" width="53.5%">
<div align="center">Photo Credit: Gabriel Synnaeve <a href="http://emotion.inrialpes.fr/people/synnaeve/phdthesis/phdthesis.html">[Link]</a></div>
</div>
<br>


## API/Codes
- The Brood War API (BWAPI). [[GitHub]](https://github.com/bwapi/bwapi)
- StarCraft II API - Technical Design, Blizzard. [[Link]](http://us.battle.net/forums/en/sc2/topic/20751114921)
- SparCraft, a combat simulator for StarCraft. [[GitHub]](https://github.com/davechurchill/ualbertabot)
- BWTA, A terrain analyzer for BWAPI. [[Link]](https://code.google.com/archive/p/bwta/)
- BroodWar Replay Scrapper in Python, Gavriel Synnaeve. [[GitHub]](https://github.com/syhw/Broodwar_replays_scrappers)

## Replays
- StarCraft Brood War Data Mining (replays, analyzer, datasets), Alberto Uriarte. [[Link]](http://nova.wolfwork.com/dataMining.html)
- GosuGamers, 8K replays as of April 2013. [[Link]](http://www.gosugamers.net/starcraft/replays-archive)
- TeamLiquid, professional community with tournament match replays. [[Link]](http://www.teamliquid.net/replay/index.php)
- ICCUP, International Cyber Cup, professional community with tournament match replays. [[Link]](http://iccup.com/en/starcraft/replays.html)
- BWReplays, a compilation of replays including previous resources. [[Link]](http://bwreplays.com/)
- StarData, a collection of 65646 StarCraft: Brood War replay dataset [[GitHub]](https://github.com/TorchCraft/StarData) [[UnitType Data]](https://docs.google.com/spreadsheets/d/1jlYDkXW2pQey1oGJlQRBiGjdMs0kfrdHAwzVI2zAjrU/edit#gid=0) [[WeaponType Data]](https://docs.google.com/spreadsheets/d/1YWFzY0_MEE4fOy9HrvZCYSpRqjgSBdCeRYVxB6zmJpQ/edit#gid=0) [[TechType Data]](https://docs.google.com/spreadsheets/d/1FpB8e7VJYubaqTtMLoc457a319Wu8yT8jTM6hPq6pT8/edit#gid=0)

## Research Papers
### Surveys
- S. Ontañón, G. Synnaeve, A. Uriarte, F. Richoux, D. Churchill, M. Preuss, A survey of real-time strategy game ai research and competition in starcraft, IEEE TCIAIG, 2013. [[Survey]](https://hal.inria.fr/file/index/docid/871001/filename/survey.pdf)
- S. Ontañón, G. Synnaeve, A. Uriarte, F. Richoux, D. Churchill, M. Preuss, RTA AI Problems and Techniques, Springer Encyclopedia of Computer Graphics and Games, 2015. [[Survey]](http://richoux.fr/publications/ecgg15_chapter-rts_ai.pdf)
- D. Churchill, M. Preuss, F. Richoux, G. Synnaeve, A. Uriarte, S. Ontañón, M. Certický, StarCraft Bots and Competitions, Springer Encyclopedia of Computer Graphics and Games, 2016. [[Survey]](http://richoux.fr/publications/ecgg16_chapter-sc_competitions.pdf)
- R. Lara-Cabrera, C. Cotta, A. Fernandez-Leiva, A review of computational intelligence in RTS games, IEEE FOCI, 2013. [[Survery]](http://www.lcc.uma.es/~ccottap/papers/lara13review.pdf)

### Benchmark
- A. Uriarte, S. Ontãñón, A Benchmark for StarCraft Intelligent Agents, AAAI AIIDE, 2015. [[Paper]](https://pdfs.semanticscholar.org/bbe4/2896225a4202754a95cca76252313413a342.pdf)

### Thesis
- G. Synnaeve, Bayesian programming and learning for multi-player video games: application to RTS AI, Ph.D. Thesis, INPG, 2012. [[Thesis]](https://tel.archives-ouvertes.fr/tel-00780635/document)
- J. Hagelback, Multi-Agent Potential Field Based Architectures for Real-Time Strategy Game Bots, Ph.D. Thesis, BIT, 2012. [[Thesis]](http://www.bth.se/tek/jhg.nsf/bilagor/jhg_phd_thesis_cr_pdf/$file/jhg.phd.thesis.cr.pdf)
- D. Churchill, Heuristic Search Techniques for Real-Time Strategy Games, Ph.D. Thesis, U. Alberta, 2016. [[Thesis]](http://www.cs.mun.ca/~dchurchill/pdf/DavidChurchill_phd_thesis.pdf)

### Dataset
- G. Synnaeve, P. Bessiere, A Dataset for StarCraft AI & an Example of Armies Clustering, arXiv, 2012. [[Paper]](https://arxiv.org/pdf/1211.4552.pdf)
- G. Robertson, I. Watson, An Improved Dataset and Extraction Process for Starcraft AI, FLAIRS, 2014. [[Paper]](https://pdfs.semanticscholar.org/1bb9/3ae33a6367ef12c9a4b7a025710495167046.pdf)
- Z. Lin, J. Gehring, V. Khalidov, G. Synnaeve, STARDATA: A StarCraft AI Research Dataset, arXiv, 2017. [[Paper]](https://arxiv.org/abs/1708.02139)

### Bayesian Approach
- G. Synnaeve, P. Bessiere, A bayesian model for opening prediction in rts games with application to starcraft, IEEE CIG, 2011. [[Paper]](https://hal.archives-ouvertes.fr/hal-00607277/file/OpeningPrediction.pdf)
- G. Synnaeve, P. Bessiere, A Bayesian model for RTS units control applied to StarCraft, IEEE CIG, 2011. [[Paper]](https://hal.archives-ouvertes.fr/file/index/docid/607281/filename/BayesianUnit.pdf)
- G. Synnaeve, P. Bessiere, Special tactics: A bayesian approach to tactical decision-making, IEEE CIG, 2012. [[Paper]](https://hal.archives-ouvertes.fr/hal-00752841/file/SpecialTactics.pdf)

### Satisfaction and Optimization
- M. Certický, Implementing a Wall-In Building Placement in StarCraft with Declarative Programming, arXiv, 2013. [[Paper]](https://arxiv.org/pdf/1306.4460.pdf)
- J. Fradin, F. Richoux,  Robustness and Flexibility of GHOST, AIIDE Third Workshop on Artificial Intelligence in Adversarial Real-Time Games, 2015. [[Paper]](http://richoux.fr/publications/aiide15.pdf)
- F. Richoux, A. Uriarte, J.-F. Baffier, GHOST: A Combinatorial Optimization Framework for Real-Time Problems, IEEE TCIAIG, 2016. [[Paper]](http://richoux.fr/publications/tciaig16.pdf)
- F. Richoux, A. Uriarte, S. Ontañón, Walling in Strategy Games via Constraint Optimization, AAAI AIIDE, 2014. [[Paper]](http://richoux.fr/publications/aiide14.pdf)

### Planning
- B. Weber. M. Mateas, Case-Based Reasoning for Build Order in Real-Time Strategy Games, AAAI AIIDE, 2009. [[Paper]](https://games.soe.ucsc.edu/sites/default/files/bweber_aiide_09.pdf)
- B. Weber, M. Mateas, A. Jhala, Applying Goal-Driven Autonomy to StarCraft, AAAI AIIDE, 2010. [[Paper]](http://alumni.soe.ucsc.edu/~bweber/pubs/gda_aiide2010.pdf)
- D. Churchill, M. Buro, Build Order Optimization in StarCraft, AAAI AIIDE, 2011. [[Paper]](https://pdfs.semanticscholar.org/dfd9/1e739bd979c08485a75fd11c501a6ec05118.pdf)
- D. Churchill, M. Buro, Incorporating Search Algorithms into RTS Game Agents, AAAI AIIDE Workshop, 2012. [[Paper]](http://musicweb.ucsd.edu/~sdubnov/Mu270d/AIIDE12/03/WS12-15-005.pdf)
- M. Stanescu, N. Barriga, M. Buro, Hierarchical Adversarial Search Applied to Real-Time Strategy Games, AAAI AIIDE, 2014. [[Paper]](https://pdfs.semanticscholar.org/1ea1/20c8ad129f4984a4bee95096efa4115e8f62.pdf)
- N. Justesen, S. Risi, Continual Online Evolutionary Planning for In-Game Build Order Adaptation in StarCraft, ACM GECCO, 2017. [[Paper]](https://njustesen.files.wordpress.com/2017/04/njustesen-gecco-2017-continual-online-evolutionary.pdf)

### Prediction
- B. Weber, M. Mateas, A Data mining approach to strategy prediction, IEEE CIG, 2009. [[Paper]](http://alumni.soe.ucsc.edu/~bweber/pubs/cig_2009.pdf)
- H. Park, H. Cho, K. Lee, K. Kim, Prediction of Early Stage Opponents Strategy for StarCraft AI using Scouting and Machine Learning, Workshop at SIGGRAPH Asia, 2012. [[Paper]](https://pdfs.semanticscholar.org/0805/94e9ae896d1b1df508575e8dc8546c26e938.pdf)
- H. Cho, K. Kim, S. Cho, Replay-based Strategy Prediction and Build Order Adaptation for StarCraft AI Bots, IEEE CIG, 2013. [[Paper]](http://cilab.sejong.ac.kr/home/lib/exe/fetch.php?media=public:paper:cig_2013.pdf)
- M. Stanescu, S. Hernandez, G. Erickson, R. Greiner, M. Buro, Predicting Army Combat Outcomes in StarCraft, AAAI AIIDE, 2013. [[Paper]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.696.7272&rep=rep1&type=pdf)
- Y. N. Ravari, S. Bakkes, P. Spronck, StarCraft Winner Prediction, AAAI AIIDE, 2016. [[Paper]](https://pure.uvt.nl/portal/files/13692982/NorouzzadehRavari.pdf)

### Control
- B. Weber, M. Mateas, A. Jhala, A Particle Model for State Estimation in Real-Time Strategy Games, AAAI AIIDE, 2011. [[Paper]](http://alumni.soe.ucsc.edu/~bweber/pubs/weber_aiide11.pdf)
- A. Shantia, E. Begue, M. Wiering, Connectionist Reinforcement Learning for Intelligent Unit Micro Management in StarCraft, IJCNN, 2011. [[Paper]](http://www.ai.rug.nl/~mwiering/GROUP/ARTICLES/StarCraft.pdf)
- D. Churchill, A. Saffidine, M. Buro, Fast Heuristic Search for RTS Game Combat Scenarios, AAAI AIIDE, 2012. [[Paper]](http://musicweb.ucsd.edu/~sdubnov/Mu270d/AIIDE12/01/AIIDE12-027.pdf)
- D. Churchill, M. Buro, Incorporating Search Algorithms into RTS Game Agents, AAAI AIIDE Workshop, 2012. [[Paper]](http://musicweb.ucsd.edu/~sdubnov/Mu270d/AIIDE12/03/WS12-15-005.pdf)
- S. Wender, I. Watson, Applying Reinforcement Learning to Small Scale Combat in the Real-Time Strategy Game StarCraft: Broodwar, IEEE CIG, 2012. [[Paper]](https://pdfs.semanticscholar.org/1308/c8326203caec91a7c44ffd1dfe86dd227c7f.pdf)
- D. Churchill, M. Buro, Portfolio Greedy Search and Simulation for Large-Scale Combat in StarCraft, IEEE CIG, 2013. [[Paper]](https://pdfs.semanticscholar.org/9fcc/5d4c04db820a7ca5197285cded68fed29f65.pdf)
- K. Nguyen, Z. Wang, R. Thawonmas, Potential Flows for Controlling Scout Units in StarCraft, IEEE CIG, 2013. [[Paper]](http://eldar.mathstat.uoguelph.ca/dashlock/CIG2013/papers/paper_87.pdf)
- N. Justesen, S. Risi, Script-and Cluster-Based UCT for StarCraft, IEEE CIG, 2014. [[Paper]](https://njustesen.files.wordpress.com/2017/02/njustesen2014script.pdf)
- N. Usunier, G. Synnaeve, Z. Lin, S. Chintala, Episodic Exploration for Deep Deterministic Policies: an Application to StarCraft Micromanagement Tasks, arXiv, 2016. [[arXiv]](https://arxiv.org/pdf/1609.02993v3.pdf) [[ICLR 2017 Submission]](https://openreview.net/pdf?id=r1LXit5ee)

### Full Game Play
- B. Weber, M. Mateas, A. Jhala, Building Human-Level AI for Real-Time Strategy Games, AAAI ACS 2011. [[Paper]](https://games.soe.ucsc.edu/sites/default/files/weber-acs2011.pdf)
- J. Young, F. Smith, C. Atkinson, K. Poyner, T. Chothia, SCAIL: An integrated Starcrat AI system, IEEE CIG, 2012. [[Paper]](http://geneura.ugr.es/cig2012/papers/paper103.pdf)

### Learning from Demonstration
- B. Weber, S. Ontañón, Using Automated Replay Annotation for Case-Based Planning in Games, ICCBR-Games Workshop, 2010. [[Paper]](https://games.soe.ucsc.edu/sites/default/files/iccbr-cg.pdf)
- B. Weber, M. Mateas, A. Jhala, Learning from Demonstration for Goal-Driven Autonomy, AAAI, 2012. [[Paper]](http://alumni.soe.ucsc.edu/~bweber/pubs/Weber-AAAI-2012.pdf)
- J. Young, N. Hawes, Learning Micro-Management Skills in RTS Games by Imitating Experts, AAAI AIIDE, 2014. [[Paper]](https://pdfs.semanticscholar.org/0a51/c01c7a3ff9c73c0e518e6eef51f30f71f4ba.pdf)
- N. Justesen, S. Risi, Learning Macromanagement in StarCraft from Replays using Deep Learning, IEEE CIG, 2017. [[Paper]](Learning Macromanagement in StarCraft from Replays using Deep Learning)

### Miscellaneous 
- W. Gong, E. Lim, P. Achananuparp, F. Zhu, D. Lo, F. Chua, In-Game Action List Segmentation and Labeling in Real-Time Strategy Games, IEEE CIG, 2012. [[Paper]](http://www.mysmu.edu/faculty/fdzhu/paper/CIG'12.pdf)
- H. Alburg, F. Brynfors, F. Minges, B. Mattson, J. Svensson, Making and Acting on Predictions in StarCraft: Brood War, Bachelors Thesis, University of Gothenburg, 2014. [[Theis]](http://publications.lib.chalmers.se/records/fulltext/203120/203120.pdf)
- M. Leece, A. Jhala, Sequential Pattern Mining in StarCraft: Brood War for Short and Long-Term Goals, AAAI AIIDE Workshop, 2014. [[Paper]](http://www.aaai.org/ocs/index.php/AIIDE/AIIDE14/paper/viewFile/9082/9011)
- G. Erickson, M. Buro, Global State Evaluation in StarCraft, AAAI AIIDE, 2014. [[Paper]](https://www.skatgame.net/mburo/ps/GlobalStateEval-AIIDE-2014.pdf)

## Reports
- J. Lewis, P. Trinh, D. Kirsh, A Corpus Analysis of Strategy Video Game Play in Starcraft: Brood War, COGSCI, 2011. [[Paper]](http://mindmodeling.org/cogsci2011/papers/0138/paper0138.pdf)
- M. Buro, D. Churchill, Real-Time Strategy Game Competitions, AI Magazine, 2012. [[Report]](https://pdfs.semanticscholar.org/9acf/46f89bc944dea9fd44ffb2722aef2b34688a.pdf)
- G. Robertson, I. Watson, A Review of Real-time Strategy Game AI, AI Magazine, 2014. [[Report]](http://www.aaai.org/ojs/index.php/aimagazine/article/view/2478/2457)
- M. Kim, S. Kim, K. Kim, A. Dey, Evaluation of StarCraft Artificial Intelligence Competition Bots by Experienced Human Players, CHI, 2016. [[Report]](http://www.cs.cmu.edu/~sjunikim/publications/CHI2016_LBW_Starcraft.pdf)


## Competitions
- AAAI AIIDE StarCraft AI Competition, 2016. [[Link]](http://www.cs.mun.ca/~dchurchill/starcraftaicomp/)
- IEEE CIG StarCraft AI Competition, 2016. [[Link]](https://sites.google.com/site/starcraftaic/)
   - Highlights Video. [[Link]](https://www.facebook.com/cjdahrl/videos/1155031857896481/)
- SSCAIT, Student StarCraft AI Tournament [[Link]](http://sscaitournament.com/)


## Others
- The Berkeley Overmind Project [[Project]](http://overmind.cs.berkeley.edu/)
- StarCraft AI, Resource for Custom AIs. [[Link]](http://www.starcraftai.com/wiki/Main_Page)
- StarCraft AI Blog, by Jay Scott. [[Blog]](http://satirist.org/ai/starcraft/blog/)
- StarCraft II AI Blog, by Matt Fisher. [[Blog]](https://graphics.stanford.edu/~mdfisher/GameAIs.html)
- Game AI 101, SK T-Brain. [[Link]](https://www.facebook.com/SKTBrain/photos/pcb.316808125356675/316807855356702/?type=3&theater)
- Ongoing survey on StarCraft research, by Vitaly Kurin [[Blog]](https://yobibyte.github.io/starcraft-research.html)

<br>
<div align="center">Maintainer: <a href="https://github.com/hshyunsookim">Hyunsoo Kim</a></div>
