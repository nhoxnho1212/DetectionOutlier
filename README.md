# outlier detection

# 1.Boxplot using IQR score , Z-score

> powerful method to get rid of outliers in data if you are dealing with **parametric distributions** in a **low dimensional** feature space

![stdn](https://github.com/nhoxnho1212/DetectionOutlier/blob/master/The_Normal_Distribution.svg.png)

>https://towardsdatascience.com/ways-to-detect-and-remove-the-outliers-404d16608dba
## 1. IQR score
![img](https://github.com/nhoxnho1212/DetectionOutlier/blob/master/boxplot.jpg)
> [source Khan academy](https://www.khanacademy.org/math/ap-statistics/summarizing-quantitative-data-ap/stats-box-whisker-plots/v/judging-outliers-in-a-dataset)

>**IQR**=Q3-Q1

>**threshole** := Z

>  Q1 - Z\*IQR > **outlier** > Q3 - Z\*IQR

## 2. Z-score
![z-score](https://github.com/nhoxnho1212/DetectionOutlier/blob/master/Zscore.jpg)

**outlier**:

![z-score](https://github.com/nhoxnho1212/DetectionOutlier/blob/master/z-score1.jpg)

