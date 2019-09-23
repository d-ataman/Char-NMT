# Character-level Neural Machine Translation based on the OpenNMT-py Toolkit


This software implements the Neural Machine Translation based on Hierarchical Character-to-Word Level Representations and Hierchical Character-based Decoding.

## Options

### Compositional Encoder based on Character Input

  To activate the character-level encoder composing source word representations from a character trigram vocabulary, select 
  
  ```-src_data_type text-trigram``` in the settings of preprocess.py and translate.py

  and
 
  ```-encoder_type trigramrnn``` in train.py 
  

### Hiearchical Decoder with Compositional Word Embeddings and Character Output 

  To activate the character-level decoder, select

  ```-tgt_data_type characters``` in the settings of preprocess.py and translate.py 

  and

  ```-decoder_type charrnn``` in train.py



## Further information

For information about how to install and use OpenNMT-py:
[Full Documentation](http://opennmt.net/OpenNMT-py/)


## Contact

For further questions you can contact ataman@fbk.eu

## Citation

If you use this software, please cite:

Ataman, D., Firat, O., Di Gangi, M., Federico, M. and Birch, A. (2019) On the Importance of Word Boundaries in Character-level Neural Machine Translation. (To appear at the WNGT Workshop at EMNLP).
