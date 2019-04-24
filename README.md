# Financial_TS_pred_Research_paper1
A deep learning framework for financial time series using stacked autoencoders and LSTM:research paper implementation

This is my personal implementation of a research paper by the name above. It was released in 2017 as an open access paper. Here's the link
to the paper: https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0180944#pone.0180944.ref004

The implementation is in the form of a jupyter notebook. I started step by step, since the paper itself is vague in a lot of areas when 
describing the architecture of the autoencoders or the LSTM, or when talking about the wavelet transformation part.

All the libraries I import in my notebook are pretty standard in a deep learning project. One interesting library I found was PyWt,
which helped me with the wavelet transformation part. 

If you have Keras,matplotlib, pandas, and pyWt installed in your local environment, you should be able to run the code pretty easily.
Remember to change the filepath in the data import section of the code! 

This was a fun and challenging project, and while the results were good, they were not good enough for me to use in production as an investment
strategy. Feel free to change the hyperparameters and anything else to see if you get better results! More importantly, please leave a comment
if you feel like I missed something in the paper or implemented something erroneously.

