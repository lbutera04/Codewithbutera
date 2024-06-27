# Welcome to the DRGP!

** This is a WIP of Mine **

### Introduction

The DRGP (Dynamic Random Generation Project) is a thought experiment and subsequent project of mine that aims to solve one very specific problem that 
I frequently come across in the Data Science industry: Generating a 'practice' data frame for testing code. This has a pretty specific use case, but any
Data Scientist or Data-adjacent person knows the pain of trying to create example data to test our own code, test others' code, or to include in a Github file
so that others can try out our code. 

### Abstract

I came up with the idea for this project when working for a job that required me to test a lot of code, and I became very frustrated with having to constantly try
to write example data frames to fit hyper-specific use cases. I decided that in the true spirit of coding, this process could be abstracted and semi-automated. The 
current iteration of this project is the 'alpha' version, mainly designed to see if it works. The process depends on user input statements and essentially asks a series
of questions to define parameters of the data it will output, which it subsequently will utilize to generate fake data through various random processes, including
several available probability distributions, markov chains, and Natural Language libraries. 

### Future Additions

I have several plans to bring this project out of its 'alpha' stage. Features will include:
- _Input path saving_: I will make it such that input paths can be stored, saved, and dropped into the program, so that different users can pass data frames between each other.
- _Correlation Feature Generation_: I intend to include a feature that allows for a correlation or classification parameter on certain data types, so that data frames can be designed
  for specific use cases, i.e. testing out case-specific classifiers or regressions.
- _Python Library formatting_: I want to eventually make this into an importable python library, so that users can use it in their own code.

### Known Issues

Right now I have not found any issues. Please inform me if you find any.

### Safety and Security

All user inputs in this code are verified. This code should not be structurally compromising at all.