# Adversaries

This document contains the weekly updates on the adversarial data generation project for the MIIS Capstone requirement.

## Work done since the final presentation in May
This document contains the weekly updates on the adversarial data generation project for the MIIS Capstone requirement.Exploration of the latest and archaic adversarial data generation techniques across domains - vision, audio, etc

# Week 09/05 to 09/12
* Shortlist the list of techniques for implementation 
* Set up the necessary configuration files for usage of the framework
* Basic implementation one of the rudimentary attacks (FGSM) in pytorch and identifying further requirements based on the implementation
* Set up models to be attacked on (Basic CNN models for MNIST recognition)

# Week 09/13 to 09/20
* Testing and debugging the attack
* Implement framework for adversarial training and report accuracy for test and adversarial data
* Implement other forms of attack like JSMA
* Explore current benchmarks for these attacks and verfiy whether these attacks conform to them 
In case the metrics vary by large amounts , investigate the cause for the difference

# Week 09/21 to 09/28
* Formalise jupyter notebook experiments to python modules for framework
* Implement black-box attack
* Gather prerequisites for Amazon oracle attack

# Week 09/29 to 11/05
* Trained attacks developed in Pytorch weren't able to fool the models as much as the Cleverhans tensorflow models. 
So investigation of the root cause must be executed
* Create test cases for the developed utilities
* 
