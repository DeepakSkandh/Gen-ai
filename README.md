# Gen AI Course

Coursework and from-scratch implementations for a 12-week deep learning and generative AI course: ANNs, CNNs, RNNs/LSTMs, VAEs, GANs, diffusion models, and transformers/LLMs.

## Approach

Each topic is covered two ways:
- **from_scratch/**: core ideas implemented with minimal libraries (NumPy / plain PyTorch) to understand what's happening underneath
- **labs/**: practical work with TensorFlow/Keras, PyTorch, and Hugging Face

Theory notes and derivations live in **notes/**.

## Progress

| Week | Topic | Notes | From scratch | Lab | Status |
|------|-------|-------|--------------|-----|--------|
| 1 | Neural networks: neurons, activations, losses | | | | ⏳ |
| 2 | ANN practice (Keras) | | | | ⏳ |
| 3 | CNNs: convolution, pooling | | | | ⏳ |
| 4 | CNN image classification (MNIST, CIFAR-10) | | | | ⏳ |
| 5 | RNNs, LSTMs | | | | ⏳ |
| 6 | Sentiment, text generation, time series | | | | ⏳ |
| 7 | Autoencoders, VAEs, GANs | | | | ⏳ |
| 8 | Diffusion models | | | | ⏳ |
| 9 | GANs and pretrained diffusion in practice | | | | ⏳ |
| 10 | Transformers: embeddings, tokenization, attention | | | | ⏳ |
| 11 | BERT, decoders, fine-tuning (PEFT, LoRA) | | | | ⏳ |
| 12 | Prompting and prompt tuning | | | | ⏳ |

## Setup

    git clone https://github.com/<your-username>/gen-ai-course.git
    cd gen-ai-course
    pip install -r requirements.txt

## Repo structure

    notes/          theory notes per topic
    from_scratch/   minimal implementations
    labs/           weekly practice notebooks
    src/genai/      shared utilities (data, training, plotting)
    assets/         figures and generated samples
..
