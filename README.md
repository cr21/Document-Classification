# Document-Classification
## Document Classification Using Tensorflow


The dataset is called **“Twenty Newsgroups”.**

The 20 Newsgroups data set is a collection of approximately 20,000 newsgroup documents, partitioned (nearly) evenly across **20 different newsgroups.** The 20 newsgroups collection has become a popular data set for experiments in text applications of machine learning techniques, such as text classification and text clustering.

In this notebook we will Explore how Conv1D can be used to learn a pattern from Text features.

We will build neural network classification Model using Tensorflow.

### Types of News
* comp.graphics
*   comp.os.ms-windows.misc
*   comp.sys.ibm.pc.hardware
*   comp.sys.mac.hardware
*   comp.windows.x	
*   rec.autos
*   rec.motorcycles
*   rec.sport.baseball
*   rec.sport.hockey	
*   sci.crypt
*   sci.electronics
*   sci.med
*   sci.space
*   misc.forsale	
*   talk.politics.misc
*   talk.politics.guns
*   talk.politics.mideast	
*   talk.religion.misc
*   alt.atheism
*   soc.religion.christian

### Training The models to Classify: 

<pre>
1. Combine "preprocessed_text", "preprocessed_subject", "preprocessed_emails" into one column. use that column to model. 

2. Split test train data using stratify split.

3. Analyze text data and pad the sequnce if required.  Sequnce length is not restricted, We will play with this hyper parameter.

4. Do Tokenizer i.e convert text into numbers.

5. code the model's ( Model-1, Model-2 ) as discribed below  and try to optimize that models.  

6. For every model use predefined **Glove vectors.**


7. Use **"categorical_crossentropy"** as Loss. 

8. Use **Accuracy and Micro Avgeraged F1 score** as your as Key metrics to evaluate your model. 

 


9. For Every model, we will save model to image ( Plot the model) with shapes and inlcude those images in the notebook markdown cell, 
upload those imgages to Classroom. You can use "plot_model" 
please refer <a href='https://www.tensorflow.org/api_docs/python/tf/keras/utils/plot_model'>this</a> 
</pre>
