# KUIS AI Projects

A list of all ongoing and completed open-source projects under KUIS AI Lab.

## Deep Learning 

1. **[Knet](https://github.com/denizyuret/Knet.jl)**: (pronounced "kay-net") is the [Koç
University](http://www.ku.edu.tr/en) deep learning framework implemented in
[Julia](http://docs.julialang.org) by [Deniz Yuret](http://www.denizyuret.com) and
collaborators.  It supports GPU operation and automatic differentiation using dynamic
computational graphs for models defined in plain Julia.

2. **[AutoGrad.jl](https://github.com/denizyuret/AutoGrad.jl)**: An automatic differentiation package for Julia. It started as a port of the
popular Python [autograd](https://github.com/HIPS/autograd) package and forms the foundation
of the [Knet](https://github.com/denizyuret/Knet.jl) Julia deep learning framework.
AutoGrad can differentiate regular Julia code that includes loops, conditionals, helper
functions, closures etc. It uses reverse mode differentiation
(a.k.a. backpropagation) so it can efficiently handle functions with large array inputs and
scalar outputs.

## Computer Vision

1. **[MS-CornerNet](https://github.com/egeonat/MS-CornerNet)**: This is a pytorch implementation of MS-CornerNet, an extension of the [CornerNet paper](https://arxiv.org/abs/1808.01244) to work on RGB+T inputs, specifically the kaist dataset.

## Human-Computer Interaction

1. **[Kart-ON](https://karton.ku.edu.tr)**: The programming environment, Kart-ON, is designed as an affordable means to increase collaboration among students and decrease dependency on screen-based interfaces. Kart-ON is a tangible programming language that uses everyday objects such as paper, pen, fabrics as programming objects and employs a mobile phone as the compiler. 
2. **[Budgie](https://budgi.es)**: We developed an afford-able and accessible tangible music platform for visually im-paired children that aims to teach the basics of programmingthrough music creation. By ordering the tangible blocks in analgorithmic structure, the children can create a melody.


## Natural Language Processing

1. **[Arabic-BERT](https://github.com/alisafaya/ArabicBERT)**: Set of publicly shared Pretrained BERT language models for Arabic language.
2. **[SHA-RNN.jl](https://github.com/alisafaya/SHA-RNN.jl)**: Implementation of Single Headed Attention - Recurrent Neural Networks in Julia and Knet.
3. **[OffensEval2020](https://github.com/alisafaya/OffensEval2020)**: An approach to utilize pre-trained BERT models with Convolutional Neural Networks for Offensive Speech Detection 
4. **[Morse.jl](https://github.com/ai-ku/Morse.jl)**: Morse, is a recurrent encoder-decoder model that produces morphological analyses of each word in a sentence.
5. **[Turkish Morphology Datasets](https://github.com/ai-ku/TrMor2018)**: Various Turkish datasets for morphological tasks
6. **[child](https://github.com/ai-ku/childes-pos)**: Learning grammatical categories using paradigmatic representations: Substitute words for language acquisition. A paradigmatic representation of word context which uses probable substitutes instead of frames.
