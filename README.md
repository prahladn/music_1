# music_1
I'm using this current repo to for work on a music genre classifier based on lyrics using Natural Language Processing.
The dataset I've used is from metrolyrics, and while I couldn't find the original on kaggle as its been taken down I did find the same dataset, although it was lacking line structure from user hiteshyalamanchili.
I used two models here. One of them is a LSTM network where I used attention on it to improve accuracy, and it comes surprisingly close to my final answer. 
I experimented with a hierarchial attention network, but it wasn't useful as the dataset lacked line structure. 
The second one I used was BERT. I saw immediate changes to accuracy here and rather than using the embeddings, I fine tuned the pre existing model, based on the imdb movie review classifier. 
After using the "cased" weights I recieved a final evaluation accuracy of 62%. 
