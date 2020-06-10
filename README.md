# NMT_EN_FR_ATTENTION
This repo is about the machine translation from French to English. <br>
<em><b>Dataset</b></em>: English dataset downloaded from Spacy, and French dataset is downloaded from Multi30K 2018 test set. Both of them are tokenized and transferred to lower cases and splited into train, validation and test dataset. <br>
Only words appear more than 3 times are kept and the model has 20,518,917 trainable parameters.<br>
<em><b>Encoder</b> </em>and <em><b>Decoder</b></em>: GRU, attention and masking are applied<br>
<em><b>BLEU score</b></em>: around 39<br>
<em><b>Visualization</b> </em>of the result:<br>
src is the input of French sentences and trg is the groud truth, and predicted_trg is the prediction. <br>
<img align='center' style="border-color:gray;border-width:2px;border-style:dashed"  src="example.png" width = "700px" height="550px" ></img>
