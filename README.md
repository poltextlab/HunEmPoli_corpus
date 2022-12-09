# General information

The HunEmPoli corpus was built using pre-agenda speeches from the 2014-2018 parliamentary term, and was created within the framework of the Hungarian Comparative Agendas Project (CAP) of the Institute of Political Science of the Centre for Social Science Research, and is freely accessible for research purposes upon registration (in case of any further questions, please contact: `ring.orsolya@tk.hu`)

# Annotation details

In the course of our research, we created an inductive emotion category system, the categories of which can later be mapped to Plutchik's emotion category system, which distinguishes eight classes and is also convertible to the positive-negative categories used in sentiment analysis. This extended system was necessary because, in our previous experience, sentences in political texts could not be classified into one of the most commonly used Plutchik's category systems for emotion analysis, or only with very low annotator agreement, whereas the extended system allowed the corpus to be annotated with high inter-annotator agreement.
In the final annotation guide, a total of 12 so-called emotion topics (ET) were defined, each of which was accompanied by at least three call words or phrases to facilitate the annotators' work.<br>

<table>
<thead>
<tr class="header">
<th style="text-align: left;"><strong>Related concepts</strong></th>
<th style="text-align: left;"><strong>Emotion topic</strong></th>
<th style="text-align: center;"><strong>In Plutchik's system</strong></th>
<th style="text-align: center;"><strong>Sentiment</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">fear, threat, intimidation, dread, anxiety</td>
<td style="text-align: left;"><strong>Fear</strong></td>
<td style="text-align: center;">Fear</td>
<td rowspan="8" style="text-align: center;">Negative</td>
</tr>
<tr class="even">
<td style="text-align: left;">suffering, deprivation, misery, poverty, torment, failure, negative change</td>
<td style="text-align: left;"><strong>Suffering</strong></td>
<td rowspan="3" style="text-align: center;">Sadness</td>
</tr>
<tr class="odd">
<td style="text-align: left;">sorrow, despair, hopelessness, melancholy</td>
<td style="text-align: left;"><strong>Sorrow</strong></td>
</tr>
<tr class="even">
<td style="text-align: left;">misfortune, catastrophe</td>
<td style="text-align: left;"><strong>Misfortune</strong></td>
</tr>
<tr class="odd">
<td style="text-align: left;">crime, terror, assassination, persecution, cruelty, organized crime, vandalism, intentional harm, violence</td>
<td style="text-align: left;"><strong>Crime</strong></td>
<td rowspan="2" style="text-align: center;">Anger</td>
</tr>
<tr class="even">
<td style="text-align: left;">anger, fury, hatred</td>
<td style="text-align: left;"><strong>Anger</strong></td>
</tr>
<tr class="odd">
<td style="text-align: left;">conflict, confusion, conflict of interest, revenge, punishment</td>
<td style="text-align: left;"><strong>Conflict</strong></td>
<td rowspan="2" style="text-align: center;">Disgust</td>
</tr>
<tr class="even">
<td style="text-align: left;">contempt, mockery</td>
<td style="text-align: left;"><strong>Contempt</strong></td>
</tr>
<tr class="odd">
<td style="text-align: left;">improvement, relief, development, success, positive change</td>
<td style="text-align: left;"><strong>Improvement</strong></td>
<td style="text-align: center;">Success</td>
<td rowspan="4" style="text-align: center;">Positive</td>
</tr>
<tr class="even">
<td style="text-align: left;">joy, enjoyment, merriment, serenity, love, acceptance, tolerance</td>
<td style="text-align: left;"><strong>Joy</strong></td>
<td style="text-align: center;">Joy</td>
</tr>
<tr class="odd">
<td style="text-align: left;">assistance, rescue, relief, healing, care, deliverance</td>
<td style="text-align: left;"><strong>Assistance</strong></td>
<td rowspan="2" style="text-align: center;">Trust</td>
</tr>
<tr class="even">
<td style="text-align: left;">justice, investigation</td>
<td style="text-align: left;"><strong>Justice</strong></td>
</tr>
</tbody>
</table>

# Quality Assurance

In order to ensure the quality of the corpus, the inter-annotator agreement (Cohen's Kappa) was calculated from time to time. Since annotators marked Emotion Topics at clause-level, we performed token-level evaluation, as we did not want to minor errors (e.g. in the marking of punctuation marks or hyphens) differences in punctuation marks or punctuation marks) would distort the results. <br>

<div id="7_tablazat">
<table style="width:90%;">
<caption>Emóciótopikok esetében mért egyetértés - <span
class="math inline"><em>κ</em></span> (1: Fear, 2: romlás, 3:
bűnözés, 4: javulás, 5: érdekellentét, 6: megvetés, 7: szomorúság, 8:
derű, 11: segítség, 12: igazságszolgáltatás).</caption>
<colgroup>
<col style="width: 10%" />
<col style="width: 8%" />
<col style="width: 8%" />
<col style="width: 8%" />
<col style="width: 8%" />
<col style="width: 8%" />
<col style="width: 8%" />
<col style="width: 8%" />
<col style="width: 8%" />
<col style="width: 8%" />
<col style="width: 8%" />
</colgroup>
<thead>
<tr class="header">
<th style="text-align: left;"><strong>ET</strong></th>
<th style="text-align: left;"><strong>1</strong></th>
<th style="text-align: left;"><strong>2</strong></th>
<th style="text-align: left;"><strong>3</strong></th>
<th style="text-align: left;"><strong>4</strong></th>
<th style="text-align: left;"><strong>5</strong></th>
<th style="text-align: left;"><strong>6</strong></th>
<th style="text-align: left;"><strong>7</strong></th>
<th style="text-align: left;"><strong>8</strong></th>
<th style="text-align: left;"><strong>11</strong></th>
<th style="text-align: left;"><strong>12</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;"><strong>Kappa</strong></td>
<td style="text-align: left;">0,564</td>
<td style="text-align: left;">0,885</td>
<td style="text-align: left;">0,971</td>
<td style="text-align: left;">0,930</td>
<td style="text-align: left;">0,615</td>
<td style="text-align: left;">0,846</td>
<td style="text-align: left;">0,5</td>
<td style="text-align: left;">1</td>
<td style="text-align: left;">0,264</td>
<td style="text-align: left;">1</td>
</tr>
</tbody>
</table>
</div>

# Citation

Please refer to the following publication:


@inproceedings{absa_2022, <br>
  author = {{\"U}veges, István and Vincze, Veronika and Ring, Orsolya and Guba, {\relax Cs}enge},<br>
  editor =       {Ines, Rehbein and Gabriella, Lapesa and Christopher, Klamm and Simone, Ponzetto},<br>
  title =        {{Aspect-based emotion analysis of Hungarian parliamentary speeches}},<br>
  booktitle =    {Proceedings of the 2nd Workshop on Computational Linguistics for Political Text Analysis (CPSS-2022) Potsdam, Germany},<br>
  publisher =    {University of Mannheim, University of Stuttgart},<br>
  year =         {2022}<br>
}<br>

