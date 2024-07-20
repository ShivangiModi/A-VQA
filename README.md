# A-VQA
Attention based Visual Question Answering System predicts the answer of a given question related to semantic present in the image.

Visual Question Answering (VQA) system is being used in various research disciplines for extracting meaningful data from images and communicating this meaningful data to humans. Thus, to implement VQA system, Computer vision and Natural Language Processing fields are combined. Existing VQA system contains many open research issues such as improper count of occluded object problem, single word answer, time specific answer problem and many more problems because of its wide assortment of utilizations and its more extensive region of research. In this paper, we present Attention
based Visual Question Answering (A-VQA) method for handling improper count of occluded object. A-VQA systems generate the textual answer by extracting image and textual features and applying multi-layer attention mechanism on these images and textual features. A-VQA system handle Object Recognition, Counting, Color and Activity
recognition types of visual questions. For training and evaluating A-VQA method, Visual
Genome dataset is used.

![image](https://github.com/user-attachments/assets/86cc6753-e3b9-4102-9c1d-2a55af2397ec)

There are four phases for implementing visual question answering system. 
In the first phase of VQA, the system is presented with real picture and question in textual format. Textual question is related to an image, and which is asked by a person to get the correct answer from image. 
At that point the subsequent stage is preparing on both picture and textual question and produces the image features and question encoding vector. 
In the third phase both these feature vectors are combined and generate the final combined feature matrix. 
In fourth phase applied dual attention mechanism to handle the improper count of occluded object problem. After applying attention mechanism, softmax classifier is used to generate the final actual answer.
