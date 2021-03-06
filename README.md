# DWDM21
DAta Warehouse &amp; Data Mining

ช่วงชัย จันทร์มณี 623020519-5

# Group Name:
#### 1 นายชยากร จันทร์ลุน 623020517-9
#### 2 นายช่วงชัย จันทร์มณี 623020519-5
#### 3 อภิวัฒน์ เหลี่ยมสิงขร
#### 4 นวลแพร พนาวัฒนวงค์
#### 5 กิตติคุณ เกียรติศักดิ์ศิริ

# DWDM21
### Data Warehouse & Data Mining 2021

# สารบัญ
* บทที่ 1: Introduction
  * [Introduction](https://github.com/chuangchai49097/DWDM21/blob/main/Chapter%201) (บรรยาย)
    * Data Warehouse & Data Mining
 
* บทที่ 2: Getting to Know Your Data
  * [มิติของ Data](https://github.com/chuangchai49097/DWDM21/blob/main/Hw2) (บรรยาย)
  * [Basic Python](https://github.com/chuangchai49097/DWDM21/blob/main/Data102(Chapter2).ipynb).ipynb)
    * Varibles
    * Casting
    * Data Structure (list)
     * วิธีสร้าง list ว่าง
     * เติมค่าลงใน list (.append())
     * การชี้ค่าใน list (indexing)
     * list slicing
     * format string
     * Nested loop
   * Function
     * normal
     * ไม่มี input
     * ไม่มี output
     * ไม่มีทั้ง input และ output
     * ลักษณะของ input (parameter)
  * [Pandas]
   * Read Data
  * .head() & .tail() (ดูหัวตาราง ท้ายตาราง)
   * Boxplot
   * Time Series plot
  * [Visualization]
    * Scatter plot
     * Normal
     * กำหนดขนาดจุด
     * กำหนดสี
     * เปลี่ยนลักษณะของจุดเป็นอย่างอื่น
    * Plot (เป็นการพล็อตกราฟที่เชื่อมกัน)
    * Bar Chart
      * Grouped Barchart (พล็อตเทียบด้านข้าง)
      * Stacked Barchart (พล็อตเทียบในแท่งเดียวกัน)
    * Histogram
  * [Distance Numpy]
    * Numpy Array
      * สร้าง numpy array (matrix)
      * matrix transpose
      * สร้าง matrix เริ่มต้น (zeros,ones)
      * สร้าง matrix random
      * matrix properties
      * matrix properties
      * Useful functions
      * เขียน function วนลูปหา sum, mean, max, min
    * Distance Matrix
      * Euclidean Distance (L2-norm)
      * Distance function
      * Manhattan Distance (L1-norm)
      * Distance of Binary Value
      
* บทที่ 3: Data Preprocessig
  * [Data Preprocessig](https://github.com/chuangchai49097/DWDM21/blob/main/Data_Preprocessing_(Chapter_3).ipynb)
    * การชี้ข้อมูลในตาราง
      * ชี้แบบธรรมดา [ชื่อคอลัมน์][index]
      * ชี้แบบ .iloc[] (มองข้อมูลเป็น matrix)
    * Missing Values
      * Handling Missing value 1 (ลบค่า missing)
      * เขียน function หาว่าการทำ dropna() ทำให้ข้อมูลหายไปกี่ %
      * Handling Missing Value 1.5 (ลบค่า missing เฉพาะใน column ที่เราสนใจ)
      * Handling Missing Value 2 (แทนด้วย class ใหม่ (unknown))
      * Handling Missing Value 3 (แทนด้วย class ใหม่ (ค่าที่เหมาะสม))
      * Handling Missing Value 4 (แทนด้วย ค่ากลาง)
      * Handling Missing Value 5 (แทนด้วย ค่ากลางของ samples ใน class เดียวกัน)
    * Select data by values [PD]
      * สร้าง list ของ boolean
      * นำ list ของ boolean มาเลือกค่าในตาราง
    * ต่อตางแนวแกน Y [PD]
      * Handling Missing Value 5 (แทนด้วย ค่ากลางของ sample ใน class เดียวกัน) ต่อ
      * การเรียงข้อมูล [PD]
    * หา Outlier
      * เขียนฟังค์ชั่น คำนวณ หา Q1,Q2,Q3,IQR,vmin,vmax โดยรับ input เป็น output ขอบ boxplot
      * เขียน function box_vals ให้สามารถรับ input ที่ box plot วาดแบบแนวนอนได้ (vert = False)
      * Panda's looping (.ilerrows)
    * การรวมตาราง (ต่อตารางในแนวแกน x)
      * รวม 2 ตาราง (.merge())
      * เลือกมาเฉพาะ column ที่ต้องการมาแปะ (.map())
    * Group by (pandas)
    * [PD] save ตารางเอาไปใช้ที่อื่น
    * [PD] การสร้างตาราง
  
* บทที่ 4: Data Warehousing and On-line Analytical Processing

* บทที่ 5: Association Rules
  * [Mining Frequent Patterns, Association and Correlations](https://github.com/chuangchai49097/DWDM21/blob/main/%E0%B8%9A%E0%B8%97%E0%B8%97%E0%B8%B5%E0%B9%88%205.pdf) (บรรยาย)
    * What Is Pattern Discovery
    * Basic Concepts
    * Apriori
  * [Data 'reduced_marketbasket' Case]
    * HW
  
* บทที่ 6: Classification
  * [Classification: Basic Concepts](https://github.com/chuangchai49097/DWDM21/blob/main/Chapter6_Association_Rules.ipynb) (บรรยาย)
    * Supervised vs Unsupervised Learning
    * Clssification vs Numeric Prediction
    * Classification-Model Construction, Validation and Testing
    * Decision Tree Induction
    * Information Gain
  * [Decision Tree คำนวนมือ](https://github.com/chuangchai49097/DWDM21/blob/main/41%20(1).pdf) (บรรยาย การบ้าน)
  * [Decision Tree](https://github.com/chuangchai49097/DWDM21/blob/main/Chapter7_Classification_(Decision_Tree).ipynb)
    * Load Data
    * Train Model
      * import (เรียกใช้ algorithm ที่เราต้องการ)
      * Define (กำหนด parameters ให้กับ model)
      * train (ฝึกสอนตัวแบบ)
    * plot tree
    * Advanced Tree
      * ใช้ค่า Default
        * import
        * Define
        * Train
        * Evaluate
      * ต้นไม้ที่ใช้เกณฑ์ Entropy มีความสูงไม่เกิน 4 ชั้น
      * ต้นไม้ที่ใช้เกณฑ์ Gini มีใบไม่เกิน 25 ใบ
      * ต้นไม้ที่ใช้เกณฑ์ Entropy และใช้การ split แบบ random
      * ต้นไม้ที่ใช้เกณฑ์ Entropy และ ใช้การ split แบบ random และ ข้อมูลที่อยู่ในใบขั้นต่ำ = 2 และ เริ่ม random ที่จุดที่ 6
  * [K-Nearest Neighbor & Neural Network](https://github.com/chuangchai49097/DWDM21/blob/main/Chapter7_Classification_(KNN_NN).ipynb)
    * Load data
    * Split Data
    * K-Nearest Neighbor (KNN)
    * Retrain & Evaluate
    * Neural Network

  * [Evaluation](https://github.com/chuangchai49097/DWDM21/blob/main/Chap7_Classification_(Evaluation).ipynb)
    * Load data
    * แบ่ง Data
    * สร้าง Model ทำนาย
    * Evaluation (classification_report, confusion_matrix, accuracy_score)

* บทที่ 7: Clustering
  * [Clustering](https://github.com/chuangchai49097/DWDM21/blob/main/Chapter8_Clustering.ipynb)
    * K-means
      
    * Clustering
     
    * Example application (Color Quantization) (ลดจำนวนสีของภาพ)
     
* MiniExam
  * [Data flights and airports Case](https://github.com/chuangchai49097/DWDM21/blob/main/MiniExam.ipynb)
    * หารัฐที่มีจำนวนเครื่องบินขาออกมากที่สุดและน้อยที่สุด
    * สายการบินอะไรมีความล่าช้ามากที่สุดและน้อยที่สุด
    * โจทย์กำหนดเอง - วันจันทร์-ศุกร์ มีเครื่องบินขาออกของรัฐไหนมากที่สุด
 
* Project Group
  * [Project Group](https://github.com/chuangchai49097/DWDM21/blob/main/Project_Final2.ipynb)
    * Data and Preprocessing
    
  * [Slide นำเสนอ](https://github.com/chuangchai49097/DWDM21/blob/main/Project.pdf)
