# ICASSP 2019 Tutorial: Detection and Classification of Acoustic Scenes and Events / Code examples

Author: **Toni Heittola**, *Tampere University* 
[Email](mailto:toni.heittola@tuni.fi), 
[Homepage](http://www.cs.tut.fi/~heittolt/), 
[GitHub](https://github.com/toni-heittola)

This repository contains code examples for the tutorial presented in ICASSP 2019 conference by *Tuomas Virtanen, Annamaria Mesaros, and Toni Heittola*.

Slides for the tutorial can be found [here](http://www.cs.tut.fi/~heittolt/pubs/ICASSP2019_DCASE_tutorial.pdf).

## Code examples

1. **Sound classification** using acoustic scene classification as example application, system is based convolutional neural networks (CNN) architecture (`code_examples/sound_classification_example.ipynb`)
2. **Sound event detection** system based on convolutional recurrent neural networks (CRNN) architecture (`code_examples/sound_event_detection_example.ipynb`)

Example systems are implemented in Python (version 3.x) with Keras (Tensorflow backend) and published as Jupyter notebooks. Jupyter notebooks allow either just viewing or interactive code execution through web browser based interface. 

- To view notebooks just click them above.      
- For interactive code execution: 

    1. Clone or download the repository
    2. Make sure Jupyter is installed (`pip install jupyter`), e.g. Anaconda Python has it pre-installed
    3. Make sure pre-requisites are installed, e.g. by running command `pip install -r requirements.txt` inside `code_examples` directory 
    4. Start notebook from command prompt with command `jupyter notebook` (inside the `code_examples` directory), this opens browser interface.
    5. Open notebook file (*.ipynb) from the list
    6. Notebook is constructed from code and text cells, start from the top and execute cell by cell starting from first cell with `shift+enter`

**Note** : Training of these systems is computationally rather heavy, and GPU accelerated training is advisable. (Make sure to install GPU enabled Tensorflow version). Directory `code_examples/data/` contains pre-trained models (along with training history), and system outputs for the test set to allow only partial code execution.

## Changelog

#### 1.0.0 / 2019-05-12

* First public release

## License

This software is released under the terms of the [MIT License](https://github.com/toni-heittola/icassp2019-tutorial/blob/master/LICENSE).
