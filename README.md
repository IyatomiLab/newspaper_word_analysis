# newspaper_word_analysis

Web上の読売、朝日、毎日、産経新聞の記事をcharacter-level convolutional neural network (CLCNN) により解析。
CLCNNが得た各新聞社の特徴を表していると考えられる部位についてのヒートマップを作成。

![ヒートマップ例[^fig]](https://user-images.githubusercontent.com/20217092/35472436-794c7ea8-03b2-11e8-9e30-b04dd04afb80.png)

マスクすると予測値が大きく低下する _N_ 文字を[five_words.ipynb](https://github.com/IyatomiLab/newspaper_word_analysis/blob/master/five_words.ipynb)に、
ヒートマップの強く発火した文字群を[word_analysis.ipynb](https://github.com/IyatomiLab/newspaper_word_analysis/blob/master/word_analysis.ipynb)に示す。

## reference
- Daiki Shimada, Ryunosuke Kotani, and Hitoshi Iyatomi. Document classification through image-based character embedding and wildcard training. 2016 IEEE Inter- national Conference on Big Data, pp. 3922–3927, 2016.
- Joshua Saxe and Konstantin Berlin. A character-level convolutional neural network with embeddings for detecting malicious urls, file paths and registry keys. CoRR arXiv:1710.09435, 2017.
- Edwaed Roff, Jon Barker, Jared Sylvester, Robert Barndon, Bryan Catanzaro, and Charles Nicholas. Malware detection by eating a whole exe. CoRR arXiv:1702.08568, 2017.
- Matthew D Zeiler and Rob Fergus. Visualising and understanding convolutional net- works. CoRR arXiv:1311.2901, 2013.
