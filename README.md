# AAE6102-Assignment-1
## Satellite Communication and Navigation (2024/25 Semester 2) - YANG Xiaoyu(24145927r)

## Task 1: Acquisition
The GPS signal acquisition process is structured into three distinct phases: initialization, initial acquisition, and precision refinement.


The result figures are shown as follows,

| Open Sky | Urban |
|:--------:|:-----:|
| <img src="sky/S-fig-101.png" alt="左图" width="350"> <br> Fig1: Open Sky Acquisition Result| <img src="urban/U-fig2.png" alt="右图" width="350"> <br> Fig2: Urban Acquisition Result|
| <img src="sky/Sky PDOP.png" alt="左图" width="350"> <br> Fig3: In open sky dataset, satellite 16,22,26,27,31 can be acquired| <img src="urban/Urban PDOP.png" alt="右图" width="350"> <br> Fig4: In urban dataset, satellite 1,3,11,18 can be acquired|




## Task 2: Tracking


## Task 3: Navigation Data Decoding



## Task 4: Position and velocity estimation
### Open Sky
<p align="center">
    <img src="sky/WSL-sky-enu.png" alt="示例图片" width="600">
    <br>  
    <strong>Fig. WSL-sky-enu.png</strong>
</p>

|  |  |
|:--------:|:-----:|
| <img src="sky/WSL-sky-positions.png" alt="左图" width="350"> <br> Fig1: Open Sky Acquisition Result| <img src="sky/WSL-sky-gt.png" alt="右图" width="500"> <br> Fig2: Urban Acquisition Result|


### Urban
<p align="center">
    <img src="urban/WSL-urban-enu.png" alt="示例图片" width="600">
    <br>  
    <strong>Fig. WSL-urban-enu</strong>
</p>

|  |  |
|:--------:|:-----:|
| <img src="urban/WSL-urban-positions.png" alt="左图" width="350"> <br> Fig1: Open Sky Acquisition Result| <img src="urban/WSL-urban-gt.png" alt="右图" width="500"> <br> Fig2: Urban Acquisition Result|




## Task 5: Kalman-filter based positioning and velociy
### Open Sky
<p align="center">
    <img src="sky/EKF-sky-enu.png" alt="示例图片" width="600">
    <br>  
    <strong>Fig. EKF-sky-enu</strong>
</p>

|  |  |
|:--------:|:-----:|
| <img src="sky/EKF-sky-positions.png" alt="左图" width="350"> <br> Fig1: Open Sky Acquisition Result| <img src="sky/EKF-sky-gt.png" alt="右图" width="500"> <br> Fig2: Urban Acquisition Result|



### Urban
<p align="center">
    <img src="urban/EKF-urban-enu.png" alt="示例图片" width="600">
    <br>  
    <strong>Fig. EKF-urban-enu</strong>
</p>

|  |  |
|:--------:|:-----:|
| <img src="urban/EKF-urban-positions.png" alt="左图" width="350"> <br> Fig1: Open Sky Acquisition Result| <img src="urban/EKF-urban-gt.png" alt="右图" width="500"> <br> Fig2: Urban Acquisition Result|
