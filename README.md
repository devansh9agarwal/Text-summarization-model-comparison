# Text summarization model comparison using Topsis
**Kaggle Notebook:** https://www.kaggle.com/devanshagarwal9/text-summarization-model-comparison-using-topsis <br>
This project compares various text-summarization models available on Hugging Face. <br>
These models are:
<ul>
  <li>facebook/bart-large-cnn</li>
  <li>philschmid/bart-large-cnn-samsum</li>
  <li>google/pegasus-cnn_dailymail</li>
  <li>google/pegasus-large</li>
</ul>
<br>
I have used technique for order performance by similarity to ideal solution (TOPSIS) for the comparison of the listed models on the basis of following parameters:
<br>
<ul>
  <li>Redundancy score</li>
  <li>BLEU score</li>
  <li>BERT score</li>
  <li>Rouge-1 score</li>
  <li>Rouge-2 score</li>
  <li>Named Entity Precision</li>
  <li>Named Entity Recall</li> 
</ul>

**Result**
![image](https://github.com/devansh9agarwal/Text-summarization-model-comparison/assets/110768484/6adb03f9-9ba1-4c18-9aa1-85b244932428)
