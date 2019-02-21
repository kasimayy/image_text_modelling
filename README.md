# Structure of Notebook
1. Introduction to Automated Chest X-ray Report Generation
    - Introduction to the dataset, the model and training framework
2. Image Preprocessing
    - Precomputing of image representations using pre-trained GoogLeNet
3. RNN Training
    - Creating RNN model using Lasagne Deep Learning Framework
4. Caption Generation
    - Sampling trained network to generate image captions

Extras:
backups/
    - To save time, the various stages of preprocessing have been saved as well as a trained model
doc/
    - Relevant papers, one of which uses the same dataset, and another which uses a similar model on a different dataset

# Prerequisites
### Python packages:
python=2.7, numpy, jupyter, matplotlib, scikit-learn, scikit-image

### Theano and lasagne:
Please follow the [installation instructions](https://lasagne.readthedocs.io/en/latest/user/installation.html)
