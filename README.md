# outlier detection

# 1.phân phối chuẩn (standard normal distribution)

> dữ liệu có mật độ xác suất có **dạng hình chuông ( bell curve)** và có **chiều dữ liệu thấp** có thể biểu diễn dưới dạng 1 hàm phân phối chuẩn rồi xóa các dữ liệu nhiễu

>các dữ liệu nhiễu là các dữ liệu có mật dộ xuất hiện thấp, nằm ngoài rìa của hàm phân phối

![stdn](https://github.com/nhoxnho1212/DetectionOutlier/blob/master/StandardScore/The_Normal_Distribution.svg.png)

>https://towardsdatascience.com/ways-to-detect-and-remove-the-outliers-404d16608dba

## 1. phân phối chuẩn 

> là một phân phối (phân phối Gauss) có **hàm mật dộ xác suất** có dạng **hình chuông**

> là hàm biểu diễn cách xuất hiện của các điểm dữ liệu **xung quanh** giá trị **trung bình** của tập dữ liệu

> có **hàm mật độ đối xứng** qua **giá trị trung bình**

> tích phân hàm phân phối là xác suất dữ liệu nằm trong độ lệch chuẩn của giá trị trung bình

> tổng diện tích dưới dường cong = 1

> giá trị trung bình (mean), trung vị (median), yếu vị (mode) đều bằng nhau

![img](https://github.com/nhoxnho1212/DetectionOutlier/blob/master/StandardScore/PDF.jpg)

> phân phối chuẩn tắc là phân phối có trung bình = 0 và độ lệch chuẩn = 1

(https://towardsdatascience.com/understanding-the-68-95-99-7-rule-for-a-normal-distribution-b7b7cbf760c2)


## 2. IQR score
![img](https://github.com/nhoxnho1212/DetectionOutlier/blob/master/StandardScore/boxplot.jpg)
> [source Khan academy](https://www.khanacademy.org/math/ap-statistics/summarizing-quantitative-data-ap/stats-box-whisker-plots/v/judging-outliers-in-a-dataset)

>**IQR**=Q3-Q1

>**threshole** := Z

>  Q1 - Z\*IQR > **outlier** > Q3 - Z\*IQR

## 3. Z-score
![z-score](https://github.com/nhoxnho1212/DetectionOutlier/blob/master/StandardScore/Zscore.jpg)

**outlier**:

![z-score](https://github.com/nhoxnho1212/DetectionOutlier/blob/master/StandardScore/z-score1.jpg)

