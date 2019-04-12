# Named-Entity-Recognition
This is my code to my submission to ARNEKT IECSIL competition for FIRE 2018 confrence.

An end to end Language Independent  Deep Learning model built using Keras to predict the Named Entity for Indian Languages. The model makes use of the different contextual information of the words along with the Word-Level and Character-Level features that are helpful in predicting the various Named Entity Classes. No domain-specific knowledge and no handcrafted rules of any sort to attain good results. We used 2CNN+LSTM model consisting of CNN as character-level encoder, CNN as word-level encoder and BiLSTM as the Tag Decoder.

### Working Notes
The link for the published Working Notes http://ceur-ws.org/Vol-2266/T3-3.pdf

### Tech Stack
- Python
- Keras

### How to Run
1. Install all the dependencies by 
```
pip install -r requirements.txt
```
2. The dataset is available in the datasetgt folder as compressed files, please extract the dataset
3. Go through the notebook for the codes of each language.



*Due to file size limit on github, I have not uploaded the trained model file.*
