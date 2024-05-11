# CSC730: Anomaly Detection
## Assignments

### Assignment 1: Introduction to Anomaly Detection
Jacob James, Kris Jensen
The first assignment of this course tasked us with an-
alyzing a set of skewed data from the MNIST dataset.
This skewed dataset contained eight classes from a
total set of ten classes. Also, each class was not rep-
resented with equivalent frequency. The dataset con-
tains 12244 records of data. Each record contains a
784-element list that represents a 28x28 image of a
handwriting sample.
This report will detail the steps taken by our team
to generate an anomaly score for each image and com-
pare our results for accuracy.
We used two primary toolsets to perform the analy-
sis. One toolset was python executed on VS code and
the other was python executed on Google Colab.

![fft_7](https://github.com/krisrjensen/csc730/assets/7505620/8da2c6c5-cc68-4d31-ad84-82395e924c41)

### Assignment 2: Fuzzy C-Means
Jacob James, John Nelson, Kris Jensen
The second assignment of this course tasked us with
implementing a Fuzzy C-Means (FCM) clustering al-
gorithm ‘from scratch’ on a set of skewed data from
the MNIST dataset. This skewed dataset contained
eight classes from a total set of ten classes. Also, each
class was not represented with equivalent frequency.
The dataset contains 12244 records of data.
Each
record contains a 784-element list that represents a
28x28 image of a handwriting sample.
This report will detail the steps taken by our team
to implement the FCM algorithm ‘from scratch’ and
determine the accuracy using the Rand Index Metric.
All code was executed in python on VS code.

![pca_cluster_means](https://github.com/krisrjensen/csc730/assets/7505620/fecaadc7-338b-41df-9b2c-96179a2256f8)

### Assignment 3: Analyzing Optigrid
Carson Price, Kris Jensen
Our task with assignment three is to describe the
OptiGrid algorithm, analyze the Optigrid code avail-
able on Github [1], in great detail. After analyzing
the algorithm and the code, we will modify the demo
example to accept a 2D dataset of 30000 points and
create visualizations of the data points and cutting
planes. If time permits, we can earn extra credit by
extending the modifications and visualization to a 3D
dataset of 30000 points.



![2d_img1](https://github.com/krisrjensen/csc730/assets/7505620/6d31cd86-94aa-4585-8b9a-fed670508366)
![3d_img_yz](https://github.com/krisrjensen/csc730/assets/7505620/b3324f36-71e4-4588-9aa2-21aaed3408c6)

### Assignment 4: Semi-supervised learning, wrapper methods
Kris Jensen
The fourth assignment of this course is meant
to introduce semi-supervised classification methods.
Semi-supervised learning is a type of machine learn-
ing that uses a small amount of labeled data and a
large amount of unlabeled data to train models. This
is in contrast to supervised learning, which only uses
labeled data, and unsupervised learning, which only
uses unlabeled data. Semi-supervised learning is par-
ticularly useful when labeled data is scarce, as is often
the case in practice [1].
The assignment is divided into three parts. The
first part of the assignment is to select a supervised
learning method then train the model on the full data
set. The second part is to train the model on a small
subset of the data, and the third part is to train the
model on a small subset of data then use a wrapper
method to implement semi-supervised learning.


![img3](https://github.com/krisrjensen/csc730/assets/7505620/70e2bcca-f87b-4b79-8525-fb5f6db4ec12)
![img12](https://github.com/krisrjensen/csc730/assets/7505620/558e846b-31fb-477e-9c36-34993d6720e6)

### Assignment 5: DBench – Installing and taking it for a test drive
Kris Jensen
For assignment 5 we are tasked to learn about ADBench, a
so-called anomaly detection toolset. This toolset is a compila-
tion of 57 datasets and 30 anomaly detection algorithms. These
algorithms can be classified as supervised, semi-supervised,
and unsupervised. ADBench was presented in a paper by
Han et al. in 2022 and at the 36th Conference on Neural
Information Processing Systems (NeurIPS 2022). The paper
is titled ”AD-Bench: A Benchmark for Anomaly Detection in
High-Dimensional Data” [1].
The assignement objectives are listed in the next section.
One of the common themes of this assignment is the re-
utilization of the ’skewed MNIST‘ dataset. In this report
we will discuss the installation of ADBench, the application
of two algorithms to the ‘skewed MNIST‘ dataset, and the
characterization of the results.


### Assignment 6: Measuring Performance – ROC and PR Curves
Kris Jensen
In this assignment, we generate Receiver Operating Char-
acteristic (ROC) and Precision-Recall (PR) curves using the
MNIST and MNIST-C data on a probability density-based
anomaly detection method of our choice. The MNIST-C
dataset is a corrupted version of the original MNIST dataset,
which contains images of handwritten digits. The MNIST-C
dataset introduces various types of corruption to these images,
such as blurring, noise, and pixelation, making it a challenging
dataset for standard MNIST recognition algorithms. Our goal
is to generate a composite datset of normal and anomalous
images, train a model on this dataset using a label set derived
from the source location, and evaluate its performance using
ROC and PR curves.

![Precision_recall_knn_canny_edges_dotted_line_stripe](https://github.com/krisrjensen/csc730/assets/7505620/c46fee3f-3ca8-423c-ab52-a2b73b976c09)
![roc_curve_knn_canny_edges_dotted_line_stripe](https://github.com/krisrjensen/csc730/assets/7505620/92f2ef40-aae9-4911-af8e-2a21c6ed4ca5)

#### Assignment 7: Isolation Forests - Anomaly Detection by Isolating Anomalies
Kris Jensen
Anomaly detection is a crucial task in various domains,
from fraud detection in financial transactions to identifying
rare diseases in medical diagnosis. Traditional anomaly detec-
tion methods often focus on profiling normal instances and
identifying instances that deviate from this normal profile.
However, a novel approach called Isolation Forest (iForest)
takes a fundamentally different approach by explicitly isolating
anomalies instead of profiling normal points [1].
The requirements for this assignment are as follows[2].
1) Get the provided dataset from D2L.
2) Write your own version of isolation forest code.
3) Run your code on the dataset to obtain anomalousness
scores for each point for your chosen parameter settings.
4) Sort the points by anomalousness scores and generate a
precision-recall curve.
5) Generate the equivalent of the following figure from
your forest.
In this assignment, we implement the Isolation Forest algo-
rithm from scratch and evaluate its performance on a dataset
provided by the instructor. The dataset contains normal and
anomalous instances, and our goal is to assess the effectiveness
of the Isolation Forest algorithm in detecting anomalies.


![itree_tsne_graph](https://github.com/krisrjensen/csc730/assets/7505620/d6f9764d-8cf5-432b-8adf-9a491c0c8fc3)
![itree_tsne_graph](https://github.com/krisrjensen/csc730/assets/7505620/98aa60b2-48ab-40c8-aa61-6a5ba52ace25)

### Assignment 8: Active Learning - How many labels do we really need, anyway?
Kris Jensen
Anomaly detection is a crucial task in various domains,
from fraud detection in financial transactions to identifying
rare diseases in medical diagnosis [1]. Some times the data is
not labeled, and it is expensive or difficult to label the data.
In those instances active learning can be used to reduce the
amount of labeled data required to train a model.
The requirements for this assignment are as follows [2].
1) Get the MNIST dataset (the original, balanced – not
MNIST-C).
2) Write your own version of an active learning classifier.
This should follow the basic outline shown in the figure
above. Assume that the algorithm will start by querying
1 point at random. You may choose whatever utility
function and classifier model you like. You do NOT need
to write the actual classifier model itself from scratch.
3) Run your code on the dataset and determine accuracy
and a confusion matrix.
4) Do this sequentially over a number of iterations suf-
ficiently large to see performance flatten out, and plot
accuracy vs. number of iterations. Show the confusion
matrices at some selected points along the way.
Active learning is a machine learning paradigm that aims to
reduce the amount of labeled data required to train a model [3].
In active learning, the model is allowed to query the user for
labels of instances that it is uncertain about. This allows the
model to focus on the most informative instances, reducing
the need for large amounts of labeled data. In this assignment,
we implement an active learning algorithm from scratch and
evaluate its performance on the full MNIST dataset.

![active_learning_SVC_random_strategy_average](https://github.com/krisrjensen/csc730/assets/7505620/195b22ad-3641-4e5d-ba92-40bae8441f82)
![active_learning_SVC_lowest_vote_strategy_average](https://github.com/krisrjensen/csc730/assets/7505620/e8ae7e3d-e7d8-4cd7-b7e3-ba4c1cf9e059)

### Assignment 9: Active Learning Based Rare Class Discovery
Kris Jensen
The goal of this assignment is to discover all the classes
in the provided datasets with as few queries to the oracle as
possible, using the information gained along the way to inform
the choice of which point to query next. This is in contrast
to the previous assignment [1], where the goal was to build a
classifier with high accuracy.
Active learning is a machine learning paradigm that aims to
reduce the amount of labeled data required to train a model.
In active learning, the model is allowed to query the user for
labels of instances that it is uncertain about. This allows the
model to focus on the most informative instances, reducing
the need for large amounts of labeled data [2].
Rare class discovery is the task of identifying all the classes
in a dataset, even if some of the classes are represented by
only a few instances. This is particularly challenging when
the dataset is imbalanced, with some classes being much rarer
than others [3].
The datasets used in this assignment were provided by
the instructor. They include the MNIST-C derived dataset
and the MNIST-skewed dataset. The MNIST-C dataset is
a corrupted version of the original MNIST dataset, while
the MNIST-skewed dataset has a skewed distribution of the
classes. Importantly, the non-corrupted MNIST dataset used
in this assignment has a balanced number of entries for each
class.

![classes_discovered_tsne_2d](https://github.com/krisrjensen/csc730/assets/7505620/c6e98468-5a83-440e-b61e-3865074f9622)
![tsne_2d](https://github.com/krisrjensen/csc730/assets/7505620/6ff7d734-0cfc-4f35-afa4-045b14b4dee3)
![rev2_classes_discovered_raw_data](https://github.com/krisrjensen/csc730/assets/7505620/82a9978e-0d83-4f86-8a8c-b1d8476d539b)



