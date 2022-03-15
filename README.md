# Seq2Seq-Double-Translation
Training Seq2Seq model to translate senteces ENG-RUS-ENG or RUS-ENG-RUS


Hello, my friend.

I introduce you my double-translator. In this work, two Seq2Seq LSTM model were traind as English-Russian translator and Russian-English translator. Then I combined these models into English-Russia-English translator and Russian-English-Russian translator. I did it just for fun.

The dataset of 100k pairs of sentences for both languages was used. The architecture is the same LSTM Seq2Seq model. Opimizer is Adam and Loss is sparse categorical crossentropy. The final models can translate some phrases, but they still have problems with another phrases.

It is worth to emphasise that Russian-English translator was easier traind and achieved better results tnan English-Russian translator. I guess, it's because English are easier.

Enjoy yourself!
Dmitrii Utev.
