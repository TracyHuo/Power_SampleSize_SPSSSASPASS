# 一. 原始数据
&ensp;&ensp;&ensp;&ensp;想研究性别和受教育程度两个因素对政治兴趣的影响，收集到了一份数据，内含72位受试者的性别、受教育程度、政治兴趣信息。性别gender包含female, male两个水平；受教育程度education包含middleschool, highschool, college 三个水平；因变量政治兴趣political_interest是连续数值变量。共6个水平组合，每个水平组合12个样本，为平衡数据。  
&ensp;&ensp;&ensp;&ensp;原始数据：  
**gender**&ensp;&ensp;&ensp;&ensp;**education**&ensp;&ensp;&ensp;&ensp;**political_interest**  
male&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;middleschool&ensp;&ensp;5.24\
male&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;middleschool&ensp;&ensp;5.08\
male&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;middleschool&ensp;&ensp;4.68\
male&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;middleschool&ensp;&ensp;5.36\
male&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;middleschool&ensp;&ensp;4.96\
male&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;middleschool&ensp;&ensp;4.83\
male&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;middleschool&ensp;&ensp;4.5\
male&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;middleschool&ensp;&ensp;5.33\
male&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;middleschool&ensp;&ensp;4.98\
male&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;middleschool&ensp;&ensp;4.85\
male&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;middleschool&ensp;&ensp;4.84\
male&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;middleschool&ensp;&ensp;4.49\
male&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;highschool&ensp;&ensp;&ensp;&ensp;4.61\
male&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;highschool&ensp;&ensp;&ensp;&ensp;4.16\
male&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;highschool&ensp;&ensp;&ensp;&ensp;4.23\
male&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;highschool&ensp;&ensp;&ensp;&ensp;4.86\
male&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;highschool&ensp;&ensp;&ensp;&ensp;4.96\
male&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;highschool&ensp;&ensp;&ensp;&ensp;4.58\
male&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;highschool&ensp;&ensp;&ensp;&ensp;5.86\
male&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;highschool&ensp;&ensp;&ensp;&ensp;6.26\
male&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;highschool&ensp;&ensp;&ensp;&ensp;5.77\
male&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;highschool&ensp;&ensp;&ensp;&ensp;5.97\
male&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;highschool&ensp;&ensp;&ensp;&ensp;5.35\
male&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;highschool&ensp;&ensp;&ensp;&ensp;5.44\
male&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;college&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;5.54\
male&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;college&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;5.78\
male&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;college&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;	5.93\
male&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;college&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;	5.47\
male&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;college&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;	6.37\
male&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;college&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;	5.64\
male&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;college&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;	5.27\
male&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;college&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;	5.78\
male&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;college&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;	5.72\
male&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;college&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;	5.35\
male&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;college&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;	5.97\
male&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;college&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;	5.6\
female&ensp;&ensp;&ensp;&ensp;	middleschool&ensp;&ensp;	4.63\
female&ensp;&ensp;&ensp;&ensp;	middleschool&ensp;&ensp;	5.24\
female&ensp;&ensp;&ensp;&ensp;	middleschool&ensp;&ensp;	5.01\
female&ensp;&ensp;&ensp;&ensp;	middleschool&ensp;&ensp;	4.81\
female&ensp;&ensp;&ensp;&ensp;	middleschool&ensp;&ensp;	5.05\
female&ensp;&ensp;&ensp;&ensp;	middleschool&ensp;&ensp;	5.26\
female&ensp;&ensp;&ensp;&ensp;	middleschool&ensp;&ensp;	4.73\
female&ensp;&ensp;&ensp;&ensp;	middleschool&ensp;&ensp;	4.31\
female&ensp;&ensp;&ensp;&ensp;	middleschool&ensp;&ensp;	4.63\
female&ensp;&ensp;&ensp;&ensp;	middleschool&ensp;&ensp;	5.04\
female&ensp;&ensp;&ensp;&ensp;	middleschool&ensp;&ensp;	4.65\
female&ensp;&ensp;&ensp;&ensp;	middleschool&ensp;&ensp;	4.34\
female&ensp;&ensp;&ensp;&ensp;	highschool&ensp;&ensp;&ensp;&ensp;	4.61\
female&ensp;&ensp;&ensp;&ensp;	highschool&ensp;&ensp;&ensp;&ensp;	4.82\
female&ensp;&ensp;&ensp;&ensp;	highschool&ensp;&ensp;&ensp;&ensp;	4.37\
female&ensp;&ensp;&ensp;&ensp;	highschool&ensp;&ensp;&ensp;&ensp;	4.6\
female&ensp;&ensp;&ensp;&ensp;	highschool&ensp;&ensp;&ensp;&ensp;	4.88\
female&ensp;&ensp;&ensp;&ensp;	highschool&ensp;&ensp;&ensp;&ensp;	4.68\
female&ensp;&ensp;&ensp;&ensp;	highschool&ensp;&ensp;&ensp;&ensp;	5.43\
female&ensp;&ensp;&ensp;&ensp;	highschool&ensp;&ensp;&ensp;&ensp;	5.51\
female&ensp;&ensp;&ensp;&ensp;	highschool&ensp;&ensp;&ensp;&ensp;	4.57\
female&ensp;&ensp;&ensp;&ensp;	highschool&ensp;&ensp;&ensp;&ensp;	5.24\
female&ensp;&ensp;&ensp;&ensp;	highschool&ensp;&ensp;&ensp;&ensp;	5.42\
female&ensp;&ensp;&ensp;&ensp;	highschool&ensp;&ensp;&ensp;&ensp;	5.39\
female&ensp;&ensp;&ensp;&ensp;	college&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;	5.61\
female&ensp;&ensp;&ensp;&ensp;	college&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;	4.88\
female&ensp;&ensp;&ensp;&ensp;	college&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;	5.3\
female&ensp;&ensp;&ensp;&ensp;	college	&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;5.44\
female&ensp;&ensp;&ensp;&ensp;	college&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;	5.47\
female&ensp;&ensp;&ensp;&ensp;	college&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;	5.77\
female&ensp;&ensp;&ensp;&ensp;	college&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;	5\
female&ensp;&ensp;&ensp;&ensp;	college&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;	5.52\
female&ensp;&ensp;&ensp;&ensp;	college&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;	5.42\
female&ensp;&ensp;&ensp;&ensp;	college&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;	5.36\
female&ensp;&ensp;&ensp;&ensp;	college&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;	5.81\
female&ensp;&ensp;&ensp;&ensp;	college&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;	5.31\
&ensp;&ensp;&ensp;&ensp;  
&ensp;&ensp;&ensp;&ensp;此为两因素析因设计。析因设计可以用来同时考察各个因素的主效应 和 因素间的各级交互效应的大小。以此两因素析因设计为例，可以考察：gender因素对因变量的影响；education因素对因变量的影响；gender，education的交互作用对因变量的影响。  
&ensp;&ensp;&ensp;&ensp;   
&ensp;&ensp;&ensp;&ensp;   
# 二. SPSS操作过程与结果  
* **操作**：Analyze -- General Linear Model -- Univariate  
* **结果**：  
![image](https://github.com/TracyHuo/Power_SampleSize_SPSSSASPASS/blob/master/Image/SPSS1.PNG)  
![image](https://github.com/TracyHuo/Power_SampleSize_SPSSSASPASS/blob/master/Image/SPSS2.PNG)  
* **解释**：  
&ensp;&ensp;&ensp;&ensp;可见，gender和education因素对因变量都有显著影响，但两者的交互作用较弱。“观测幂”就是检验的效能，可见，对education因素的主效应的检验的效能较高。对gender的检验的效能低于0.75。  
&ensp;&ensp;&ensp;&ensp;   
&ensp;&ensp;&ensp;&ensp;   
# 三. SAS操作过程与结果  
## 1. 录入原始数据  
* **代码**：   
DATA temp;  
input gender $ education $ political_interest;  
datalines;  
male	middleschool	5.24\
male	middleschool	5.08\
male	middleschool	4.68\
male	middleschool	5.36\
male	middleschool	4.96\
male	middleschool	4.83\
male	middleschool	4.5\
male	middleschool	5.33\
male	middleschool	4.98\
male	middleschool	4.85\
male	middleschool	4.84\
male	middleschool	4.49\
male	highschool	4.61\
male	highschool	4.16\
male	highschool	4.23\
male	highschool	4.86\
male	highschool	4.96\
male	highschool	4.58\
male	highschool	5.86\
male	highschool	6.26\
male	highschool	5.77\
male	highschool	5.97\
male	highschool	5.35\
male	highschool	5.44\
male	college	5.54\
male	college	5.78\
male	college	5.93\
male	college	5.47\
male	college	6.37\
male	college	5.64\
male	college	5.27\
male	college	5.78\
male	college	5.72\
male	college	5.35\
male	college	5.97\
male	college	5.6\
female	middleschool	4.63\
female	middleschool	5.24\
female	middleschool	5.01\
female	middleschool	4.81\
female	middleschool	5.05\
female	middleschool	5.26\
female	middleschool	4.73\
female	middleschool	4.31\
female	middleschool	4.63\
female	middleschool	5.04\
female	middleschool	4.65\
female	middleschool	4.34\
female	highschool	4.61\
female	highschool	4.82\
female	highschool	4.37\
female	highschool	4.6\
female	highschool	4.88\
female	highschool	4.68\
female	highschool	5.43\
female	highschool	5.51\
female	highschool	4.57\
female	highschool	5.24\
female	highschool	5.42\
female	highschool	5.39\
female	college	5.61\
female	college	4.88\
female	college	5.3\
female	college	5.44\
female	college	5.47\
female	college	5.77\
female	college	5\
female	college	5.52\
female	college	5.42\
female	college	5.36\
female	college	5.81\
female	college	5.31\
；  
&ensp;&ensp;&ensp;&ensp;   
## 2. 两因素方差分析 GLM  
* **一般线性模型**：  
Yijk = υ + αi + βj + (αβ)ij + εijk  
&ensp;&ensp;&ensp;&ensp;其中，Yijk是每个样本的因变量值，υ是总平均效应，αi是因素A的第i水平的效应，βj是因素B的第j水平的效应，(αβ)ij是αi和βj之间的交互作用的效应，εijk是随机误差分量。  
&ensp;&ensp;&ensp;&ensp;   
* **方差分解模型**：  
SST = SSA + SSB + SSAB + SSE    
&ensp;&ensp;&ensp;&ensp;     
* **代码**：  
PROC glm data = temp;  
class gender education ;  
model political_interest = gender education gender\*education ;  
run;   
&ensp;&ensp;&ensp;&ensp;     
* **结果**：  
![image](https://github.com/TracyHuo/Power_SampleSize_SPSSSASPASS/blob/master/Image/SAS1.PNG)  
&ensp;&ensp;&ensp;&ensp;     
![image](https://github.com/TracyHuo/Power_SampleSize_SPSSSASPASS/blob/master/Image/SAS2.PNG)  
&ensp;&ensp;&ensp;&ensp;     
![image](https://github.com/TracyHuo/Power_SampleSize_SPSSSASPASS/blob/master/Image/SAS3.PNG)  
* **解释**：   
&ensp;&ensp;&ensp;&ensp;方差分析表里包含了对各因素主效应及交互效应的检验结果，与SPSS结果一致。（I类平方和与模型中变量的进入顺序有关，III类平方和与此顺序无关）  
&ensp;&ensp;&ensp;&ensp;交互作用图明显看到三条线基本平行，代表两因素的交互作用较弱。  
## 3. 检验效能计算  
* **计算每个水平组合的均值和标准差**：  
**代码**：    
PROC means mean std;  
var political_interest ;  
class gender education;  
run;  
**结果**：  
![image](https://github.com/TracyHuo/Power_SampleSize_SPSSSASPASS/blob/master/Image/SAS4.PNG)  
&ensp;&ensp;&ensp;&ensp;    
* **录入均值数据**：  
DATA temp2;  
do gender = "female","male";  
do education = "college","highschool","middleschool";  
input mean @@ ;  
output;  
end; end;  
cards;  
5.4075 4.9600 4.8083 5.7017 5.1708 4.9283  
run;  
* **计算检验效能**：  
**代码**：  
PROC glmpower data = temp2;  
class gender education;  
model mean = gender education gender\*education;  
power  
stddev = 0.2730 0.7055  
ntotal = 72  
power =.;  
run;quit;   
**结果**：  
![image](https://github.com/TracyHuo/Power_SampleSize_SPSSSASPASS/blob/master/Image/SAS5.PNG)  
&ensp;&ensp;&ensp;&ensp;    
**解释**：  
&ensp;&ensp;&ensp;&ensp;首先计算了每个水平组合的样本均值和标准差。然后，使用GLMPOWER计算检验效能。stddev = 0.2730 0.7055 取的是现有数据的每个水平组合的标准差的最小和最大值，所以计算出的各检验的效能处在一个范围里。与SPSS的结果基本一致。  
&ensp;&ensp;&ensp;&ensp;    
## 4. 样本量估算  














