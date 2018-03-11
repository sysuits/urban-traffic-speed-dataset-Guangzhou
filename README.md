# Urban Traffic Speed Dataset of Guangzhou, China
## 1. Data Description
This is an urban traffic speed dataset which consists of 214 anonymous road segments within two months (i.e., from August 1, 2016 to September 30, 2016) at 10-minute interval, and the speed observations were collected from Guangzhou, China.
## 2. File Description
### **speeddata.csv** - the traffic speed dataset (contains **1,855,589** speed observations). Note that, for the convenience, **speeddata.csv** is separated into two files (i.e., **speeddata_Aug.csv** & **speeddata_Sep.csv**) where **speeddata_Aug.csv** covers the total observations during August, 2016 and **speeddata_Sep.csv** covers the total observations during September, 2016, respectively.

(1) *road_id*: a unique anonymous identifier for each road segment. As an example, 1 indicates the first road segment;

(2) *day_id*: a unique code indicating the date. In this column, 1 represents Aug. 1, 2016, 2 represents Aug. 2, 2016, as such, 61 represents Sep. 30, 2016;

(3) *time_id*: a unique code indicating the time windows. For example, 1 represents 00:00:00-00:10:00, 2 represents 00:10:00-00:20:00;

(4) *speed*: the speed values with unit km/h.

### **tensor.csv** - the third-order tensor in Matlab and it can be directly loaded. In detail, we have

(1) the length of its first dimension corresponding to road semgent is 214;

(2) the length of second dimension corresponding to day is 61;

(3) the length of third dimension corresponding to time window is 144;

(4) the tensor entries is valued by traffic speed where 0 indicates the unobserved.

## 3. Publication
Xinyu Chen, Zhaocheng He, Jiawei  Wang, 2018. **Spatial-temporal traffic speed patterns discovery and incomplete data recovery via SVD-combined tensor decomposition**. *Transportation Research Part C: Emerging Technologies*, 86, 59-77. [Download PDF](https://www.sciencedirect.com/science/article/pii/S0968090X17302966)
