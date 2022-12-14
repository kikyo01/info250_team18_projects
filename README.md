# INFO 250 Informations Visualization

#### 📈info250 Information Visualization Course Code Warehouse

*This code werehouse is made by Team 18 for  Info 250(Fall, 2022) .*

## Team members
- Chi Song 宋池 
  - student_id : 320200945881
  - email : songch20@lzu.edu.cn
  - class number : 3
  
- Yiwei Han 韩祎伟 
  - student_id : 320200930921
  - email : hanyw20@lzu.edu.cn
  - class number : 3
  
 - Xurui Zhang 张栩瑞
   - student_id : 320200931601
   - email : xrzhang20@lzu.edu.cn
   - class number : 4
   
 - Yu Gui 桂昱 
    - student_id : 320200930891
    - email : guiy2020@lzu.edu.cn
    - class number : 4
    
    
    
    
    
## Project 1

##### About The project

At the beginning of the project, the team members have a brief discussion, confirm the general idea, and start to realize when the project is proposed. The code part is mainly in charge of Song Chi and Han Yiwei, and Zhang Xurui and Gui Yu modified the specific requirements to make the project complete and in line with the requirements. The code part is not very useful. The main thing is that we spent a lot of time in the two-factor analysis of task3, understanding the requirements and asking the teaching assistants. When encountering problems, we will discuss with each other, help each other, and learn from each other's strengths. The realization of the project is inseparable from everyone's efforts.

##### Preparatory Work

In this part, we define a number of functions so that we can use them later.

##### Task 1

In this part, we choose SVM for visualization. Finally we chose a bar dot plot to show the content. The visualization shows the distribution of the data.

##### Task 2

To  show how affects energy consumption, we grouped by experiment_id, because when `RQ=2.2`, each feature number corresponds to one experiment_id, and each experiment is performed 30 times. The `xy_egy()` function is grouped by experiment_id, averaged, and then called `plot_bar()` for visualization.

##### Task 3

To finish this task, we print the algorithms at first. Then we use `xy_egy()` to determine the number of features or samples of each algorithm and transfer it to x and y, and set the number of decimal places of y to 3 Bit (convenient for illustration) and then call the functions plot_bar1 (for `RQ=2.1`) and plot_bar2 to draw `(for RQ=2.2)`。 In addition, the drawing function calls the muti_axes function, and when the mode is equal to 1 or 2, it will be in a different subgraph.

##### Task 4

We defined a function named `plot_barh()`. In `plot_barh()` We made a division of every no_features values with egy and no_datapoints values with egy. Then we get a average of egy cost rate of every althirom into one horizontal bar chart.

##### Task 5

We use a scatter plot to show the relationship between 'recall' and 'f1'. By the result of the scatter plot,we can find there would be a positive-relevant relationship between recall and f1.



## Project 2
##### About The project

This project is mainly devided in to two parts. The code part and the report part. The works are in the "\project2" directory. In the directory named "\previous" there stores eliminated documents. The directory named "\images" is visualizations used.

##### Works

The two main documents are listed:

    This is the report part:  Info250-Project2-T18.md 
    This is the code part:    project2.ipynb
    (This is a Pdf version that was converted from the markdown file) : Info250-Project2-T18.pdf

