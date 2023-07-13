# Toxic Comments Detection using Deep Learning
##  KERAS Sequential Model using Python

![Image](https://imgur.com/SzC5WSF.jpg)

### Description:

This GitHub repository showcases a deep learning approach for toxic comment detection, with the objective of identifying and addressing toxic comments in online platforms. The original training dataset consists of approximately 160,000 rows, characterized by highly imbalanced data. To address this issue, the dataset has been carefully processed, reducing the number of rows and achieving a balanced distribution.

Data source : ( https://www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge/data )

### Data Pre-processing:
- [Stopwords]  punctuation, and case sensitivity have been eliminated to enhance the quality of the text data.
![Image](https://imgur.com/DRIfwvw.jpg)
- [Word stemming] techniques have been employed to normalize the words within the comments. Stemming reduces words to their base or root form, allowing for better generalization and reducing the vocabulary size.
- Comprehensive data cleaning techniques have been implemented, ensuring the identification and rectification of null or empty values.
- Measures have been taken to detect and handle duplicate data instances effectively.
![Image](https://imgur.com/e7zyqex.jpg)
**Data Correlation:**
Before the data pre-processing :
![Image](https://imgur.com/6uTffic.jpg)
After the data pre- processing :
![Image](https://imgur.com/SqdDsnS.jpg)

**Relationship between Categories label at 1 glance:** 
![Image](https://imgur.com/B38TfmU.jpg)
![Image](https://imgur.com/Ucj58Bk.jpg)
![Image](https://imgur.com/GkQPrnG.jpg)
![Image](https://imgur.com/5nbaik5.jpg)

### Data Characteristics:

The dataset presents several challenges, featuring a single column containing comments in text format. The comments are classified into five distinct toxic comment types: 'toxic', 'severely-toxic', 'obscene', 'threat', 'insult', and 'identity_hate'. These labels are represented in binary form.
![Image](https://imgur.com/b5o52Gs.jpg)

Original Data size :
![Image](https://imgur.com/uXBFYQZ.jpg)

Data size after Balancing done :
![Image](https://imgur.com/azxW74w.jpg)

Comment text lenght:
![Image](https://imgur.com/7Wyhapi.jpg)
Sample of Dataframe before cleaning :
![Image](https://imgur.com/jKVCmZK.jpg)

Sample of Dataframe after cleaning:
![Image](https://imgur.com/MEzK91j.jpg)


### Data Preparation:

- [Vectorization] process: To represent the textual data numerically, vectorization techniques have been applied. This process involves converting the tokens or words into numerical vectors that capture their semantic meaning. Common approaches include one-hot encoding and word embeddings.
![Image](https://imgur.com/8QnJdYj.jpg)
- [Sequential Model]: The deep learning model implemented in this project follows a sequential architecture. A sequential model consists of a linear stack of layers, where each layer communicates directly with the adjacent layers. This architecture allows for the capture of complex patterns and dependencies within the text data.
- ![Image](https://imgur.com/z246rEI.jpg)

### Model Architecture:
A sequential deep learning model has been developed to address the problem of toxic comment detection. The model demonstrates exceptional performance, achieving over 90% accuracy on the training data. The choice of a deep learning approach enables the model to capture complex patterns and dependencies within the text data.

**Data Pipeline :**
![Image](https://imgur.com/IqsWoFT.jpg)
![Image](https://imgur.com/ccg2xTB.jpg)
![Image](https://imgur.com/iiAwtS7.jpg)

**Visualization of the Training result:**
![Image](https://imgur.com/K1D8SUq.jpg)

### Testing the Model with new input:
![Image](https://imgur.com/Z7ZPpgd.jpg)
![Image](https://imgur.com/ggtpHhU.jpg)
![Image](https://imgur.com/LhFArGa.jpg)
![Image](

### Importance and Objectives:
The primary objective of creating this model is to combat toxic comments in online platforms. Toxic comments can lead to harmful effects such as cyberbullying, harassment, and the spread of hate speech. By developing an accurate toxic comment detection model, online platforms can better protect their users by identifying and removing toxic content promptly.

#### The importance of creating such models lies in several aspects:
1. **User Safety:** Toxic comment detection models contribute to creating a safer and more inclusive online environment, ensuring users can engage without fear of harassment or harm.
2. **Content Moderation:** Online platforms can utilize these models to automate content moderation, saving time and resources by swiftly identifying and flagging toxic comments.
3. **Community Building:** By actively monitoring and managing toxic comments, online communities can foster a more positive and constructive atmosphere, encouraging healthy discussions and interactions.
4. **Protecting Vulnerable Individuals:** Toxic comment detection models play a crucial role in safeguarding vulnerable individuals, reducing the potential impact of cyberbullying and hate speech
