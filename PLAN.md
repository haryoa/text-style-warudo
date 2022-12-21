## Composable Plan

### Data

Currently, we focus on Unsupervised Style Transfer with **n** style data. For example, we want to train a style transfer for negative and positive sentences style. 

User need to give these data. We will provide the dataloader here.

### Model

Usually,the model consists of encoder -> decoder (except if you use decoder-like model like GPT). We will add flexibility on how to include the model. But, user should provide the code to do the forward pass with the model.

### Training Process
 
There are several process to train a style transfer model. We will add this feature.

### Evaluation

We will collect several automatic style transfer metric here.

