# Deep-Learning-Helper
Helper notes from Dr. Rowel Atienza's <a href="https://github.com/roatienza/Deep-Learning-Experiments">Deep Learning Lessons</a>.

For any questions, please reach us through the following email addresses:
  - izza.jalandoni@eee.upd.edu.ph
  - mark.vincent.ty@eee.upd.edu.ph

---

### Notes
**1. Setting up *Anaconda* on Ubuntu/Linux** [[PDF](Notes/Setting-up%20Anaconda%20for%20Ubuntu_Linux.pdf)]


**2. Working with *Jupyter Notebook***

Notebook is a creative way of presenting your project outputs as it allows users to create documents (notebook) that contains codes, equations, and other visualizations all in one place.

  - Activate your working environment
  - Install ipykernel: `pip install ipykernel`
  - Adding virtual environment to jupyter: `python -m ipykernel install --user --name=<env_name>`
  - Run notebook: `jupyter notebook`

**3. Creating your *Hugging Face Space*** [[PDF](Notes/HuggingFace_Spaces.pdf)]

**4. Using *Google Colab***

All python scripts should be on your Google Drive where your Notebooks are mounted.

  - Using colab to execute a python script: [Colab Notebook](https://colab.research.google.com/drive/1NNtgPH_FETz9pX8tZ3DfMjTtZdMCUZBJ?usp=sharing)
  - Using colab on your main project: [Colab Notebook](https://colab.research.google.com/drive/1Dx1LxDX-_wvBcw_VVcr368PfOrzJJzai?usp=sharing)

---

### Experiments / Demos

Below is a list of experiments / demos regarding specific topics, done on Jupyter Notebook.

|   <b>Toolkits</b>     |                                          |    |
|:----------------------|:----------------------------------------:|:--:|
| Numpy                 | [Jupyter](Toolkits/numpy_demo.ipynb)     |    |
| Einsum                | [Jupyter](Toolkits/einsum_demo.ipynb)    |    |
| Einops                | [Jupyter](Toolkits/einops_demo.ipynb)    |    |
| Timm                  | [Jupyter](Toolkits/timm_demo.ipynb)      |    |
| HuggingFace           | [Model](Toolkits/huggingface_demo.ipynb) |    |
|                       | [Dataset](Datasets/dataset_demo.ipynb)   |    |
| HF Space/Gradio       | [Spaces sample](https://huggingface.co/spaces/izzajalandoni/dialogpt-tagalog) | [Notes](Notes/HuggingFace_Spaces.pdf) |
| Wandb                 | [Jupyter](Toolkits/wandb_demo.ipynb)     |    |
| <b>Dataloader</b>     | [Jupyter](Datasets/dataset_demo.ipynb)   |    |
| <b>Supervised Learning</b>|                                      |    |
| Pytorch Lightning     | [Jupyter](SupervisedLearning/mlp_lightning_demo.ipynb)|    |
| Loss Functions        | [Jupyter](SupervisedLearning/lossfunctions.ipynb)     |    |
| Object Detection      | [Jupyter](SupervisedLearning/object_detection.ipynb)  |    |
| <b>Building Blocks</b>|                                          |    |
| MLP                   | [Jupyter](BuildingBlocks/mlp_demo.ipynb) | [Notes](Notes/MultiLayer_Perceptron(MLP).pdf)    |
| CNN                   | [Jupyter](BuildingBlocks/cnn_demo.ipynb) | [Notes](Notes/NN%20IO%20Shape%20Calculation.pdf) |
| RNN/LSTM              | [Jupyter](BuildingBlocks/rnn_demo.ipynb) |    |
| Transformers          | Soon                                     |    |

---

### Useful YouTube Tutorial Links

- Stanford's CS231n Computer Vision Basics: <a href="https://www.youtube.com/playlist?list=PL3FW7Lu3i5JvHM8ljYj-zLfQRF3EO8sYv">YouTube Playlist</a>
