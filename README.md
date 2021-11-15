# DWDM21
DAta Warehouse &amp; Data Mining

Chuangchai Janmanee 623020519-5

Group Name:
1 นายชยากร จันทร์ลุน 623020517-9

2 นายช่วงชัย จันทร์มณี 623020519-5

3 อภิวัฒน์ เหลี่ยมสิงขร

4 นวลแพร พนาวัฒนวงค์

5 กิตติคุณ เกียรติศักดิ์ศิริ
บทที่ 1 Introduction

#สารบัญ
Lecture
(https://github.com/Thitichaya2000/DWDM21/blob/main/HW%20Chapter%201.pdf)
บทที่ 2 Getting to Know Your Data

Lecture
(https://github.com/Thitichaya2000/DWDM21/blob/main/Chapter%202.pdf)
(https://github.com/Thitichaya2000/DWDM21/blob/main/Chapter2.pdf)
Github
Basic python
(https://github.com/Thitichaya2000/DWDM21/blob/main/Data101(Chapter2).ipynb)
Variables
Data structure
Loop
Condition
Function
Data Exploration
(https://github.com/Thitichaya2000/DWDM21/blob/main/Data102(Chapter2).ipynb)
Boxplot
Times Series Plot
Data Visualization
(https://github.com/Thitichaya2000/DWDM21/blob/main/Data_Visualization.ipynb)
Scatter plot
Plot
Bar chart
Grouped Barchart
Stacked Barchart
Histogram
Distance Numpy
(https://github.com/Thitichaya2000/DWDM21/blob/main/Distance_Numpy.ipynb)
Numpy Array
สร้าง numpy array (matrix) จาก list
สร้าง matrix เริ่มต้น (zeros, ones)
สร้าง matrix random
matrix properties
Indexing & Slicing
Useful functions
Distance Matrix
Euclidean Distance (L2-norm)
Distance function
Manhattan Distance (L1-norm)
Distance of Binary Value
บทที่ 3 [Data Preprocessing]

lecture
(https://github.com/Thitichaya2000/DWDM21/blob/main/Chapter%203.Data%20Preprocessing.pdf)
Github
(https://github.com/Thitichaya2000/DWDM21/blob/main/Data_Preprocessing(Chapter_3).ipynb)
ชี้ข้อมูลในตาราง
ชี้แบบธรรมดาใช้ [ชื่อ column] [index]
ชี้แบบ .iloc (มองข้อมูลเป็น matrix)
Missing Values NAN NULL NA
Handling Missing Value 1 (ลบ missing)
Handling Missing Value 1.5 (ลบค่า Missing เฉพาะใน Column ที่เราสนใจ)
Handing Missing Value 2 (แทนด้วย class ใหม่ (unknown))
Handing Missing Value 3 (แทนด้วย class ใหม่ (ค่าที่เหมาะสม))
Handing Missing Value 4 (แทนด้วย ค่ากลาง)
Handing Missing Value 5 (แทนด้วย ค่ากลางของ Samples ใน Class เดียวกัน)
Select date by values [PD]
ต่อตารางแนวแกน Y [PD]
การเรียงข้อมูล [PD]
Outlier
การรวมตาราง Data Integration (ต่อตารางในแนวแกน x)
รวม 2 ตาราง (.merge())
เลือกเฉพาะ column ที่ต้องการมาแปะ (.map())
Group by (pandas)
[PD] save ตารางเอาไปใช้ที่อื่น
[PD] การสร้างตาราง
บทที่ 4 [Data Warehousing and On-line Analytical Processing]

lecture
(https://github.com/Thitichaya2000/DWDM21/blob/main/04OLAP.pdf)
What is a Data Warehouse?
From Tables and Spreadsheets to Data Cubes
Conceptual Modeling of Data Warehouses
Star Schema: An Example
Snowflake Schema: An Example
Fact Constellation: An Example
Typical OLAP Operations
Roll up (drill-up)
Drill down (roll down)
Slice and dice
Pivot (rotate)
Drill across
Drill through
บทที่ 5 Association Rules

lecture
(https://github.com/Thitichaya2000/DWDM21/blob/main/06FPBasic.pdf)
Basic Concepts
What Is Pattern Discovery?
k-Itemsets and Their Supports
Frequent Itemsets (Patterns)
From Frequent Itemsets to Association Rules
Mining Frequent Itemsets and Association Rules
Efficient Pattern Mining Methods
Apriori Algorithm
Apriori Pruning and Scalable Mining Methods
A Candidate Generation & Test Approach
The Apriori Algorithm
Github
(https://github.com/Thitichaya2000/DWDM21/blob/main/Chapter6_Association_Rules.ipynb)
เตรียม Data สำหรับ (Fequence Pattern) Association Rule
Apriori
บทที่ 6 [Classification]

Lecture
(https://github.com/Thitichaya2000/DWDM21/blob/main/08ClassBasic.pdf)
Basic Concepts
Supervised vs. Unsupervised Learning (1)
Supervised vs. Unsupervised Learning (2)
Prediction Problems: Classification vs. Numeric Prediction
Classification—Model Construction, Validation and Testing
Decision Tree Induction
An Example
Information Gain
Load Data
Train Model
import (เรียกใช้ algorithm algorithm ที่เราต้องการ)
define (กำหนด parameters ให้กับ model)
train (ฝึกสอนตัวแบบ)
Plot tree
Evalution
Random
Advanced Tree
TEST
(https://github.com/Thitichaya2000/DWDM21/blob/main/Lecture141064.pdf)
Bayes’ Theorem: Basics
Naïve Bayes
ClassifierCategorical vs. Continuous Valued Features
Training Dataset
Lazy Learner: Instance-Based Methods
The k-Nearest Neighbor Algorithm
(https://github.com/Thitichaya2000/DWDM21/blob/main/Lecture191064.pdf)
Model Evaluation and Selection
Classifier Evaluation Metrics
Confusion Matrix
Accuracy, Error Rate,Sensitivity and Specificity
Precision and Recall, and F-measures
Neural Network for Classification
Perceptron
Github
Decision Tree
(https://github.com/Thitichaya2000/DWDM21/blob/main/Chapter7_Classification(Decision_Tree).ipynb)
Load data
Train Model
Evaluation
Advanced Tree
Test
KNN
(https://github.com/Thitichaya2000/DWDM21/blob/main/Chap7_Classification_(KNN_NN).ipynb)
Load data
Split data
Train Model
Retrain & Evaluate
Neural Network
Evaluation
(https://github.com/Thitichaya2000/DWDM21/blob/main/Chap7_Classification_(Evaluation).ipynb)
Load data
Split data
สร้าง Model ทำนาย
import
define
train
evaluation
บทที่ 7 [Clustering]

Lecture
(https://github.com/Thitichaya2000/DWDM21/blob/main/10ClusBasic.pdf)
Github
(https://github.com/Thitichaya2000/DWDM21/blob/main/Chap_8_Clustering.ipynb)
K-means
Generate Data
Explore data
Clustering
Example Application (Color Quantization)
นับจำนวนสี
จัดกลุ่มสีให้เหลือ 16 สี
ใช้ centroid เป็นตัวแทนของสี
Hierachical Clustering
Clustering Evaluation
MiniExam

(https://github.com/Thitichaya2000/DWDM21/blob/main/MiniExam.ipynb)
Project

Powerpoint
(https://github.com/Thitichaya2000/DWDM21/blob/main/Final%20Project%20%E0%B8%81%E0%B8%A5%E0%B8%B8%E0%B9%88%E0%B8%A1%E0%B8%A5%E0%B8%B9%E0%B8%81%E0%B8%AB%E0%B8%A1%E0%B8%B5.pdf)
Github
(https://github.com/Thitichaya2000/DWDM21/blob/main/Project_lookmhee.ipynb)
