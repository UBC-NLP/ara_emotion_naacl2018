# Arabic_Emotion_Datasets
* Paper Title: Enabling Deep Learning of Emotion With First-Person Seed Expressions

* Authors: Hassan Alhuzali, Muhammad Abdul-Mageed & Lyle Ungar.

* Email: muhammad.mageeed@ubc.ca

</br>

# Datasets description
## Lama-dataset (Gold):
	
* Each line contains 3 comma separated fields (CVS), with the header: **"tweet_id","emotion_relevance","emotion_category"**.
* **"tweet_id":** The Twitter id of the tweet
* **"emotion_relevance:"** Whether the tweet carries emotion or not (relevant to the task or not; binary "YES"/"NO")
* **"emotion_category":** The category of emotion the tweet carries.
* Note: Tweets that have **"emotion_relevance"=NO** are not considered for the **"emotion_category"** classification task. As such, the label under **"emotion_category"** is the suspected label if the  **"emotion_relevance"** were to be equal to **YES**.
* Filename: "Lama_dataset.csv".

</br>

## Lama-Dist (Distant Supervision):
* Each line contains 2 fields corresponding to the following tweet_id, and emotion_label.
* Each field is separated by comma and double quotes.
* For example, here is the header of the file: **"tweet_id","label"**.
* Filename: "Lama_dist_dataset.csv".

</br>

# License & co
* The dataset is only meant for **research purposes**.
* Please cite the [paper](http://aclweb.org/anthology/W18-1104) if you use our data.

```
@article{Alhuzali2018,
  title = {{Enabling Deep Learning of Emotion With First-Person Seed Expressions}},
  author = {Alhuzali, Hassan and Abdul-Mageed, Muhammad and Ungar, Lyle},
  pages = {25--35},
  url = {https://peopleswksh.github.io/pdf/PEOPLES04.pdf},
  year = {2018}
}
```
