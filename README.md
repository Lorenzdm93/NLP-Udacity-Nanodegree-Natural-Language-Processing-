# NLP-Udacity-Nanodegree-Natural-Language-Processing-
This repo contains notebooks and projects that I worked on during the NLP Nanodegree offered by Udacity

* In this Bayesian Inference notebook I have used the Naive Bayes algorithm to create a model that can classify SMS messages as spam or not spam, based on the training we give to the model

* In the HMM project, Part of speech tagging is the process of determining the syntactic category of a word from the words in its surrounding context. It is often used to help disambiguate natural language phrases because it can be done quickly with high accuracy. Tagging can be used for many NLP tasks like determining correct pronunciation during speech synthesis and for word sense disambiguation. Here I've use the Pomegranate library to build a hidden Markov model for part of speech tagging using a "universal" tagset. Hidden Markov models have been able to achieve >96% tag accuracy with larger tagsets on realistic text corpora. Hidden Markov models have also been used for speech recognition and speech generation, machine translation, gene recognition for bioinformatics, and human gesture recognition for computer vision, and more.

* The machine translation project I built a deep neural network that function as part of an end-to-end translation machine, accepting English input and generating a French translation output

* In the final project, VUI speech recogniser, I build a deep neural network that functions as part of an end-to-end automatic speech recognition (ASR) pipeline. The completed pipeline will accept raw audio as input and return a predicted transcription of the spoken language. The full pipeline is summarized below:
  * STEP 1 is a pre-processing step that converts raw audio to one of two feature representations that are commonly used for ASR.
  * STEP 2 is an acoustic model which accepts audio features as input and returns a probability distribution over all potential transcriptions. After learning about the basic types of neural networks that are often used for acoustic modeling, you will engage in your own investigations, to design your own acoustic model.
  * STEP 3 in the pipeline takes the output from the acoustic model and returns a predicted transcription.
