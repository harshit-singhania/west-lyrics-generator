# west-lyrics-generator

This project aims to try and generate rap lyrics by emulating Kanye West's music by using two seperate text generation models. The first model to be used is the Bigram Language Model, and the second language model to be used is the GPT 1.0 model outlined in the paper  [Attention Is All You Need](https://pastebin.com/qXMZ2bst) 

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

### Performance of the Bigram Model 

| Iter | Train Loss | Val Loss |
|------|------------|----------|
| 0    | 6.3149     | 6.3117   |
| 100  | 3.4847     | 3.5578   |
| 200  | 2.8361     | 2.9400   |
| 300  | 2.6957     | 2.8320   |
| 400  | 2.6363     | 2.7805   |
| 500  | 2.6113     | 2.7346   |
| 600  | 2.5880     | 2.7189   |
| 700  | 2.5673     | 2.7107   |
| 800  | 2.5620     | 2.6895   |
| 900  | 2.5522     | 2.6931   |
| 1000 | 2.5366     | 2.6783   |
| 1100 | 2.5438     | 2.6853   |
| 1200 | 2.5404     | 2.6715   |
| 1300 | 2.5177     | 2.6792   |
| 1400 | 2.5219     | 2.6518   |
| 1500 | 2.5269     | 2.6434   |
| 1600 | 2.5165     | 2.6520   |
| 1700 | 2.5190     | 2.6784   |
| 1800 | 2.5218     | 2.6634   |
| 1900 | 2.5165     | 2.6583   |
| 2000 | 2.5095     | 2.6502   |
| 2100 | 2.5125     | 2.6450   |
| 2200 | 2.5089     | 2.6657   |
| 2300 | 2.5067     | 2.6493   |
| 2400 | 2.5054     | 2.6666   |
| 2500 | 2.5066     | 2.6478   |
| 2600 | 2.5047     | 2.6982   |
| 2700 | 2.5056     | 2.6644   |
| 2800 | 2.4992     | 2.6601   |
| 2900 | 2.5063     | 2.6694   |
| 3000 | 2.4995     | 2.6424   |
| 3100 | 2.5087     | 2.6588   |
| 3200 | 2.5028     | 2.6564   |
| 3300 | 2.4987     | 2.6628   |
| 3400 | 2.5044     | 2.6513   |
| 3500 | 2.4961     | 2.6489   |
| 3600 | 2.5039     | 2.6343   |
| 3700 | 2.5009     | 2.6457   |
| 3800 | 2.5057     | 2.6676   |
| 3900 | 2.5018     | 2.6722   |
| 4000 | 2.4991     | 2.6631   |
| 4100 | 2.5013     | 2.6479   |
| 4200 | 2.5018     | 2.6693   |
| 4300 | 2.4882     | 2.6345   |
| 4400 | 2.4959     | 2.6427   |
| 4500 | 2.4976     | 2.6638   |
| 4600 | 2.4966     | 2.6450   |
| 4700 | 2.4919     | 2.6450   |
| 4800 | 2.4966     | 2.6372   |
| 4900 | 2.4998     | 2.6525   |
| 4999 | 2.4999     | 2.6693   |

Average Training Loss: 


