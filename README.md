# Coding Assignment 3: Transfer Learning and Advanced CNN Applications

In the previous assignment, you built a Convolutional Neural Network from the ground up. Now, we will explore more advanced and powerful applications of CNNs. You will learn how to leverage massive, pre-trained models using transfer learning to achieve state-of-the-art performance with very little data. You will also see the versatility of CNNs by applying them to a non-image domain: finding patterns in biological sequence data.

By the end of this assignment, you will have practical experience with two of the most impactful techniques in modern deep learning.


## Learning Objectives

After completing this assignment, you will be able to:

* **Implement transfer learning** by fine-tuning a state-of-the-art, pre-trained model (VGG16) on a new dataset.

* **Apply CNNs to non-image data**, such as DNA sequences, demonstrating their versatility.

* **Understand the trade-offs** between training a model from scratch and fine-tuning a pre-trained one.

* **Adapt convolutional architectures** for one-dimensional sequence analysis.



</br>

## Assignment Structure

This assignment is broken down into five notebooks, each building upon the last.

1.  **`CA3.1_TransferLearning.ipynb`**
    
    Training large networks from scratch is computationally expensive. This notebook is a guided tutorial on transfer learning. 
    
    Refering to this, apply transfer learning using InceptionV3 or any other pre-trained models that are available to achieve 98% accuracy. For transfer learning, you need to decide how to add fine-tuning layers or unfreeze the pre-trained layers (hyper-parameter tuning). You can also experiment with different hyperparameters such as learning rates, batch sizes, epochs, and their learning curve in TensorBoard.


2.  **`CA3.2_CNNforDNA.ipynb`**
    
    CNNs aren't just for images! In this final notebook, you'll apply convolutional networks to sequence data. You will build a model to find specific patterns in DNA sequences and answer a series of questions as you go.


</br>

---

### Setup and Environment on Explorer HPC

The recommended platform for this assignment is the **Explorer HPC**, and the easiest way to use it is through the [Open OnDemand (OOD) web interface](ttps://ood.explorer.northeastern.edu/).

**Helpful Links:**
* **Access Explorer:** You can access the interactive dashboard from [here](https://ood.explorer.northeastern.edu/).
* **Getting started with Explorer:** Refer to this [document](https://docs.google.com/document/d/1nsP4YUBajdM6j3R0tA4gRnwo9qPdRv5gTtXHYdiXCz8/) to create environments, manage files, and start sessions in our HPC. 
* **Official Documentaion:** For more info on the HPC, refer to the [Official Documentation](https://rc-docs.northeastern.edu/en/latest/).


---

### Submission Instructions

1. Complete the primary tasks for both notebooks:

    * In `CA3.1`, achieve >=98% accuracy on the transfer learning task (using a different pre-trained model).

    * In `CA3.2`, answer all the in-line questions.

2. Zip both completed notebooks (`.ipynb` files), along with their PDF versions. Name the zip file `CA3-Your-Last-Name`.

3.  Submit the zip file as a direct **reply** to the [*coding assignment module of week 3*](https://northeastern.instructure.com/courses/226141/discussion_topics/2923188) on Canvas.

### Important Notes

* Please adhere to the collaboration policy outlined in the course syllabus.
* Make sure to credit any external resources, discussions, or AI assistance you used to complete the assignment.
* Start early! These notebooks comprehensively tries to translate the theoretical knowledge to practical application. Good luck!