# Large Language Model:
I gained a deep understanding of LLM and its construction from the book "Building a LLM from scratch"- by Sebastian Raschka.

This repository contains code for building a LLM from scratch.
Code contains every detailed steps mentioned in the book.

A LLM is divide into three stages :

  ![llm](https://github.com/user-attachments/assets/48fdd0d5-f4d3-49dd-ae64-9f9f156f0c8d)


## Stage 1: Building an LLM
### Data preparation and sampling:
1. Creating Tokens
2. Creating token IDS
3. Adding special context tokens
4. Byte Pair Encoding (BPE)
5. Creating Input- Target pairs
6. Implementing a Data loader
7. Creating token embeddings
8. Positional Embeddings

### Attention Mechanism:

  ![image](https://github.com/user-attachments/assets/f25bfff9-f136-4eee-98b5-c65a2a468a05)


1. Simplified Attention mechanism
2. Implementing self attention with trainable weights
3. Compact self attention
4. Casual attention
5. Multi head attention

## Stage 2: Foundation model
1. Training Loop
2. Model Evaluation
3. Load Pre-trained weights

## Stage 3: Finetuning 
### Finetuning for classification
1. Downloading dataset
2. Creating dataloaders
3. Initializing model with pretrained weights
4. Adding classification head
5. Calculating loss and accuracy
6. Finetuning model on supervised data

### Finetuning for Instruction 
&emsp; 1.Preparing dataset<br/>
  &emsp; &emsp; a. Converting instructions to ALPACA Format<br/> 
  &emsp; &emsp; b. Splitting dataset into train-test-validation <br/>
&emsp; 2. Organizing data into training batches<br/>
  &emsp; &emsp; a. Creating target token ids for training<br/>
  &emsp; &emsp; b. Masking target token ids<br/>
&emsp; 3. Creating Dataloaders<br/>
&emsp; 4. Loading a pretrained LLM<br/>
&emsp; 5. Finetuning LLM on instruction dataset<br/>
&emsp; 6. Extracting and saving response<br/>
&emsp; 7. Evaluating finetuned LLM<br/>
  


