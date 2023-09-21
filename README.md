# Goodreads_Books_Review_Rating_Prediction 2022 - 2023

Reviews are a good way to judge the quality of any product, whether it's books, clothes, technology, or anything else. When you want to buy something online these days, the first thing that comes to mind is the reviews from past buyers and the overall rating the product has received.
Reader feedback, whether positive or negative, five stars or one star, will encourage the product owner to make improvements.
Reader connection and engagement will be encouraged by book reviews, whether they be left on Amazon, Goodreads, or social media. Readers must determine whether or not other readers are enjoying the book.

In this competition we work with a challenging dataset consisting reviews from the Goodreads book review website, and a variety of attributes describing the items. and we predict review rating which ranges from 0 to 5.

## Acknowledgements
The dataset of this competition is taken from UCSD Book Graph.
If you have any questions or find any bugs regarding these datasets, feel free to contact Mengting Wan (m5wan@ucsd.edu).

Dataset link: [Goodreads 2022-2023 dataset](https://www.kaggle.com/competitions/goodreads-books-reviews-290312/data)

## Citations
please cite the following papers:

Mengting Wan, Julian McAuley, "Item Recommendation on Monotonic Behavior Chains", in RecSys'18. [bibtex]
Mengting Wan, Rishabh Misra, Ndapa Nakashole, Julian McAuley, "Fine-Grained Spoiler Detection from Large-Scale Review Corpora", in ACL'19. [bibtex]

## Evaluation
The evaluation metric for this competition is [**Mean F1-Score**](https://en.wikipedia.org/wiki/F-score). The **F1 score**, commonly measures accuracy using the precision(p) and recall(r). Precision is the ratio of true positives(tp) to all predicted positives (tp + fp). Recall is the ratio of true positives (tp) to all actual positives (tp + fn).
The F1 metric weights recall and precision equally, and a good retrieval algorithm will maximize both precision and recall simultaneously. Thus, moderately good performance on both will be favored over extremely good performance on one and poor performance on the other.

## Citation
<pre>
@misc{goodreads-books-reviews-290312,
    author = {Mark McDonald, Paul Mooney, Phil Culliton, Yashvi Patel},
    title = {Goodreads Books Reviews},
    publisher = {Kaggle},
    year = {2022},
    url = {https://kaggle.com/competitions/goodreads-books-reviews-290312}
}</pre>
