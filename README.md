# west-lyrics-generator

This project aims to try and generate rap lyrics by emulating Kanye West's music by using two seperate text generation models. The first model to be used is the [Bigram Language Model](https://pastebin.com/vxGwbqiH) , and the second language model to be used is the GPT 1.0 model outlined in the paper  [Attention Is All You Need](https://pastebin.com/qXMZ2bst)

The data being used is obtained from [HuggingFace](https://huggingface.co/datasets/huggingartists/kanye-west)

### conceptual comparison of both the models 

| Aspect                   | Bigram Language Model                         | GPT-1 (Generative Pre-trained Transformer 1)       |
|--------------------------|------------------------------------------------|----------------------------------------------------|
| Approach                 | Statistical                                   | Deep Learning                                     |
| Architecture             | Simple                                        | Transformer                                      |
| Context Awareness        | Limited (Considers only preceding word)       | Extensive (Captures long-range dependencies)     |
| Training Data            | Counting of word pairs (bigrams)              | Vast amounts of text data                        |
| Capabilities             | Simple tasks (e.g., text generation, spell checking) | Various NLP tasks (e.g., translation, text completion) |
| Complexity               | Low                                           | High                                             |
| Performance              | Limited by context window                     | Captures complex language patterns effectively   |
| Computational Resources  | Lightweight                                   | Resource-intensive                               |

#### Performance of the Bigram Model 

1. Average train loss: 2.6209058823529405
2. Average val loss: 2.7638784313725493





