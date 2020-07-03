# NMT_EN_FR_ATTENTION
This repo is about the machine translation from French to English. <br>
<em><b>Dataset</b></em>: Multi30K 2018 test set, 
29k pairs of sentences, 377-400k words<br>
<em><b>Training / Validation split </b> </em>: 0.9 for training and 0.1 for validating
<em><b>Encoder</b> </em>and <em><b>Decoder</b></em>: GRU, attention and masking are applied<br>
<em><b>Batch size</b> </em>:256<br>
<em><b>Best Epoch</b> </em>: 19 with total 50 epochs<br>
<em><b>Loss</b> </em>: nn.crossentropy<br>
<em><b>Novelty</b> </em>:<br>
modified the original model of German-English translation to French-English translation<br> 
Increase batch size <br>
decerease hidden layers with dropout<br>
<em><b>BLEU score</b></em>: around 39 <br>
<em><b>Visualization</b> </em>of the result:<br>
src is the input of French sentences and trg is the groud truth, and predicted_trg is the prediction. <br>
<img align='center' style="border-color:gray;border-width:2px;border-style:dashed"  src="example.png" width = "850px" height="550px" ></img>
