# Smart Library

**[Updating Repo . . . . .]**



# Table of Contents

1. [Motivation](#motivation)  
2. [Introduction](#introduction)
3. [Methodology](#methodology)
4. [Configuration](#configuration)

 
# Motivation
Physical library collections are valuable and long-standing resources for knowledge and learning. However, managing and finding books are often tedious. It is specifically designed for our text recognition model using rich supervision to accelerate training and achieve the same using our own datasets. The proposed system has the potential to greatly reduce the amount of manual labor required for managing book inventories.

# Introduction
The method that is used here is the OCR (Optical Character Recognition) which simply means the conversion of handwritten text images electrically into a format that can be editable and searchable. OCR is implemented in various fields like Banking, Healthcare, and other industrial applications. Some of the methods to implement this OCR is using ANN (Artificial Neural Networks), CNN, KNN clustering and so on. In our case, we make use of ANN-BPA (Back Propagation Algorithm) method.
The specific objective is as follows:
-	To scan the given hand-written documents.
-	To apply OCR on the hand-written image.
-	Use BPA and get the desired list of books in text form.



# Methodology

## 1. Data acquisition

A dataset was created by writing english alphabets (Capital A-Z) and digits (0-9) multiple times using a ball point pen. They are then scanned and the images are stored in the computer.

## 2. Preprocessing 

The scanned images are converted to B/W and several filters were used to remove noice and deblur the images. 
Each alphabet is then cropped and stored is separate sub folders. 

# Configuration




