## Learning Natural Language Understanding
This repo tries to provide an overview of NLU models and techniques used in NLP tasks such as conversational agents (both task-oriented and open-domain). The materials discussed here are from different sources which you can check in ```References``` sections.

NLU is a general topic in NLP which tries to understand the human language on semantic level. As you might've noticed, this is challenging task and a robust NLU system needs to extract both **semantic** and **linguistic** features from the language in order to understand it well.

## NLU Components
You might have used NLU services like [Microsoft's LUIS](https://www.luis.ai/), [Amazon's Lex](https://aws.amazon.com/lex/), [Google's Diagflow (former API.ai)](https://dialogflow.com/), or [IBM Watson NLU](https://www.ibm.com/watson/services/natural-language-understanding/). All of these services try to extract sematic and linguistic information from text so that it can be used for other NLP tasks. Applications of NLU are numerous and almost all industries have a use case in which NLU plays an important role! 

In this repo, we will discuss different components of a typical NLU system and provide papers, code (our implementatio) and third-party libs which can help you learn and use these components. The components that we will cover are:
* Intent Classification
* Entity Extraction or Named Entity Recognition (NER)
* Relation Extraction
* Sentiment Analysis
* Semantic Role Labeling (SRL)

## Running Experiments
We will use a lot of packages and libraries for different components of the NLU. To save you from headache, we've provided some dockerfiles (with different backends) in the ```docker``` folder which you can use to run the experiments. Alternatively, you can use ```pip``` or ```conda``` to install the requirements and start having fun!


## References
* [Stanford Natual Language Understanding course (cs244U)](http://web.stanford.edu/class/cs224u/)
* [Rasa NLU](https://github.com/RasaHQ/rasa_nlu)
* [SLING](https://github.com/google/sling)