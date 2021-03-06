# Task 3: Learning with both COVID-19 and non-COVID-19 CT scans


## 3D U-Net baselines for lung segmentation
<table>
<tr>
    <th rowspan="3" colspan="2"><center>Subtask<br/>
    <th colspan="4"><center>Validation Set</td>
    <th colspan="4"><center>Testing Set</td>
</tr>
<tr>
    <th colspan="2"><center>Left Lung</td>
    <th colspan="2"><center>Right Lung</td>
    <th colspan="2"><center>Left Lung</td>
    <th colspan="2"><center>Right Lung</td>
</tr>
<tr>
    <th><center>DSC</td>
    <th><center>NSD</td>
    <th><center>DSC</td>
    <th><center>NSD</td>
    <th><center>DSC</td>
    <th><center>NSD</td>
    <th><center>DSC</td>
    <th><center>NSD</td>
</tr>
<tr>
    <th rowspan="6"><center>StructSeg<br/>
    <th><center>Fold0</td>
    <td><center>0.9632±0.01222</td>
    <td><center>0.7392±0.08513</td>
    <td><center>0.9718±0.003526</td>
    <td><center>0.7393±0.07017</td>
    <td><center>0.9737±0.01928</td>
    <td><center>0.9033±0.05893</td>
    <td><center>0.9760±0.02040</td>
    <td><center>0.9082±0.06067</td>
</tr>
<tr>
    <th><center>Fold1</td>
    <td><center>0.9629±0.01212</td>
    <td><center>0.7370±0.08380</td>
    <td><center>0.9714±0.003654</td>
    <td><center>0.7342±0.07034</td>
    <td><center>0.9768±0.01287</td>
    <td><center>0.9103±0.05301</td>
    <td><center>0.9799±0.01138</td>
    <td><center>0.9178±0.04883</td>
</tr>
<tr>
    <th><center>Fold2</td>
    <td><center>0.9635±0.01254</td>
    <td><center>0.7426±0.08482</td>
    <td><center>0.9719±0.003474</td>
    <td><center>0.7399±0.06888</td>
    <td><center>0.9681±0.03147</td>
    <td><center>0.8937±0.08818</td>
    <td><center>0.9761±0.02844</td>
    <td><center>0.9094±0.07768</td>
</tr>
<tr>
    <th><center>Fold3</td>
    <td><center>0.9631±0.01206</td>
    <td><center>0.7388±0.08532</td>
    <td><center>0.9719±0.003377</td>
    <td><center>0.7394±0.06996</td>
    <td><center>0.9693±0.02504</td>
    <td><center>0.9066±0.05615</td>
    <td><center>0.9725±0.02522</td>
    <td><center>0.9128±0.06349</td>
</tr>
<tr>
    <th><center>Fold4</td>
    <td><center>0.9628±0.01294</td>
    <td><center>0.7382±0.08891</td>
    <td><center>0.9717±0.003885</td>
    <td><center>0.7383±0.07256</td>
    <td><center>0.9777±0.01294</td>
    <td><center>0.9159±0.05313</td>
    <td><center>0.9804±0.01332</td>
    <td><center>0.9199±0.05670</td>
</tr> 
<tr>
    <th><center>Avg</td>
    <td><center>0.9631±0.01187</td>
    <td><center>0.7392±0.08207</td>
    <td><center>0.9717±0.003443</td>
    <td><center>0.7382±0.06749</td>
    <td><center>0.9731±0.02136</td>
    <td><center>0.9060±0.06212</td>
    <td><center>0.9770±0.02050</td>
    <td><center>0.9136±0.06078</td>
</tr>   
<tr>
    <th rowspan="6"><center>StructSeg<br/>
    <th><center>Fold0</td>
    <td><center>0.9574±0.04580</td>
    <td><center>0.8120±0.07485</td>
    <td><center>0.9547±0.1087</td>
    <td><center>0.8097±0.1089</td>
    <td><center>0.9272±0.06327</td>
    <td><center>0.7535±0.1448</td>
    <td><center>0.9297±0.06976</td>
    <td><center>0.8526±0.1603</td>
</tr>
<tr>
    <th><center>Fold1</td>
    <td><center>0.9536±0.05027</td>
    <td><center>0.8053±0.08703</td>
    <td><center>0.9516±0.1108</td>
    <td><center>0.8047±0.1141</td>
    <td><center>0.9223±0.07158</td>
    <td><center>0.7357±0.1749</td>
    <td><center>0.9427±0.03816</td>
    <td><center>0.7668±0.1431</td>
</tr>
<tr>
    <th><center>Fold2</td>
    <td><center>0.9535±0.04857</td>
    <td><center>0.7971±0.08188</td>
    <td><center>0.9523±0.1088</td>
    <td><center>0.7998±0.1125</td>
    <td><center>0.9409±0.04120</td>
    <td><center>0.7739±0.1199</td>
    <td><center>0.9379±0.05813</td>
    <td><center>0.7555±0.1623</td>
</tr>
<tr>
    <th><center>Fold3</td>
    <td><center>0.9537±0.04944</td>
    <td><center>0.7975±0.07700</td>
    <td><center>0.9484±0.1115</td>
    <td><center>0.7950±0.1163</td>
    <td><center>0.9357±0.05080</td>
    <td><center>0.7786±0.1162</td>
    <td><center>0.9358±0.05910</td>
    <td><center>0.7820±0.1325</td>
</tr>
<tr>
    <th><center>Fold4</td>
    <td><center>0.9569±0.04607</td>
    <td><center>0.8114±0.07851</td>
    <td><center>0.9550±0.1086</td>
    <td><center>0.8091±0.1095</td>
    <td><center>0.9476±0.03763</td>
    <td><center>0.8053±0.1049</td>
    <td><center>0.9512±0.03294</td>
    <td><center>0.8052±0.1113</td>
</tr> 
<tr>
    <th><center>Avg</td>
    <td><center>0.9550±0.04785</td>
    <td><center>0.8047±0.07983</td>
    <td><center>0.9524±0.1092</td>
    <td><center>0.8036±0.1117</td>
    <td><center>0.9347±0.0538</td>
    <td><center>0.7694±0.1332</td>
    <td><center>0.9395±0.05260</td>
    <td><center>0.7724±0.1408</td>
</tr>  
</table>
