# rg_text_to_sound
**Research Group - Text to Sound**  
  
This README has two sections:
* Main Resources: the "primary"/"most used" resouces, with an in-depth explanation
* Other Resources: the resources that are implemented in this repository but are secondary, with a brief description and links to more in-depth READMEs


# Main Resources
## TTS Pipeline
Currently located at: [playground/mirco_nani/tts_pipeline/](playground/mirco_nani/tts_pipeline/)  
This repository defines the skeleton of the pipelines used at inference time, a first design of the pipeline can be found [here](https://docs.google.com/presentation/d/1Cx96uZUxc3dx-PRyFl2v2R7lmjZ05UeixxwqPsBeEBQ/edit#slide=id.gbf06894dcc_0_30).  
For informations on how to use TTS Pipeline, please read its [README.md](playground/mirco_nani/tts_pipeline/README.md)  
## TTS WebsocketServer
Currently located at: [playground/mirco_nani/tts_websocketserver/](playground/mirco_nani/tts_websocketserver/)  
This repository holds the implementation of a websocket server that exposes TTS Pipeline's prediction functionalities for the Production Team.  
For more informations on TTS WebsocketServer, please read its [README.md](playground/mirco_nani/tts_websocketserver/README.md)  


# Other resources
## Git Tutorial
Currently located at: [playground/beat_toedtli/](playground/beat_toedtli/)  
A simple guideline on the structure and usage of this repository.
More details can be found in its own [README.md](playground/beat_toedtli/README.md)  

## words embeddings
Currently located at: [playground/beat_toedtli/word_embeddings](playground/beat_toedtli/word_embeddings)  
Word embeddings explorative implementations, benchmarked with [benchmarking_tools](playground/mirco_nani/embeddings_pipelines/benchmarking_tools)
More details can be found in its own [README.md](playground/beat_toedtli/word_embeddings/README.md)  

## Command Patterns Dataset
Currently located at: [playground/mirco_nani/embeddings_pipelines/commands_patterns_dataset](playground/mirco_nani/embeddings_pipelines/commands_patterns_dataset)  
A simple sentences generator to augment our dataset. It takes sentence patterns with blank tokens and replaces these tokens with given keywords. The final output consists of all the possible sentences obtainable from all the combinations of patterns and keywords.  
More details can be found in its own [README.md](playground/mirco_nani/embeddings_pipelines/commands_patterns_dataset/README.md)  

## Benchmarking Tools
Currently located at: [playground/mirco_nani/embeddings_pipelines/benchmarking_tools](playground/mirco_nani/embeddings_pipelines/benchmarking_tools)  
These tools are made to benchmark embedding models (such as BERT or sent2vec) in order to produce performances comparisons.
More details can be found in its own [README.md](playground/mirco_nani/embeddings_pipelines/benchmarking_tools/README.md)  

## Embeddings Pipelines
Currently located at: [playground/mirco_nani/embeddings_pipelines/](playground/mirco_nani/embeddings_pipelines/)   
First implementation of TTS Pipeline  
More details can be found in its own [README.md](playground/mirco_nani/embeddings_pipelines/embeddings_pipelines/README.md)  