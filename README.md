

# nanoGPT Text Generation

This repository contains an implementation of a small, efficient variant of the GPT architecture called nanoGPT. It is trained on a subset of the OpenWebText corpus and can generate text one character at a time.

The code was created following the Neural Networks: Zero to Hero lecture series by Andrej Karpathy. It is published here so that people can easily modify and learn from it. [nanoGPT model.py](https://github.com/karpathy/nanoGPT/blob/master/model.py) 


## Usage

To train the model:

```python
python train.py
```

To generate text:

```python
python generate.py
```

## License

MIT