# Demucs
This repository has a TensorFlow 2.x implementation of [Music Source Separation in the Waveform Domain](https://arxiv.org/abs/1911.13254)

`demucs_Model.ipynb` file has a model configuration, `demucs_CustomTraining.ipynb` file contains `gen_ds` which generates a `tf.data.Dataset` from the `stem` files from https://sigsep.github.io/datasets/musdb.html#musdb18-compressed-stems

Finally, `demucs_main.ipynb` file trains the Model, Demucs.
