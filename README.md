# Arabic Dialect Identification

Trying to predict the dialect given the text using the QADI dataset; an automatically collected dataset of tweets belonging to a wide range of
country-level Arabic dialects -covering 18 different countries in the Middle East and North
Africa region.

## Approaches

* Linear SVM with simple tf-idf tokenization.
* Bert base transformer pre trained on arabic tweets fine tuned to QADI dataset.

<h2><b>Results</b></h1>

<table style="width:100%">
  <tr>
    <th>Model</th>
    <th>Macro Precision</th>
    <th>Macro Recall</th>
    <th>Macro F1-score</th>
    <th>Accuracy</th>
  </tr>
  
  <tr>
    <td>LinearSVC</td> <td>60%</td>  <td>56%</td>  <td>57%</td>  <td>60%</td>
  </tr>
 
 <tr>
    <td>AraBERTv0.2-Twitter</td> <td>60%</td>  <td>56%</td>  <td>57%</td>  <td>60%</td>
  </tr>  
</table>
