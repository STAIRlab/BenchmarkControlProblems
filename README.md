# BenchmarkControlProblems

This is OpenSees implementation of Ohtori et al Nonlinear Benchmark Control Problem (https://ascelibrary.org/doi/10.1061/%28ASCE%290733-9399%282004%29130%3A4%28366%29). The model has been checked and found to have a similar eigenvalues number with Ohtori simulation (and previous simulation). However, it must be noted that the OpenSees model may have little bit smaller stifness due to the usage of Fiber Section.

Ohtori Nonlinear Benchmark Control Problem are based on SAC Phase II Building Design.

## 3 Story Building Eigenvalues
From Ohtori Paper, the first 3 Natural Period is : 0.99, 3.06, and 5.83 Hz

OpenSees Eigenvalues:
| Mode | Period (s) | Frequency (Hz) |
|------| -------|-----------|
|1     |1.0097077067198548 | 0.9903856267955097|
|2     |0.32667497129029194 | 3.0611466683542576|
|3     | 0.17080331473344545| 5.854687314239736  |
|4     | 0.14030860249371874| 7.1271467481458775 |
|5     | 0.09941529284564488 | 10.058814608660155 |
|6     | 0.09053790203823787 | 11.045097991973117|


## 9 Story Building Eigenvalues
From Ohtori Paper, the first 6 Natural Period is 0.443, 1.18, 2.05, 3.09, and 4.27 Hz.

OpenSees Eigenvalues:
| Mode | Period (s) | Frequency (Hz) |
|------| -------|-----------|
|1     |2.308495285624674 |  0.433182604368803|
|2     |0.8663962990169478 | 1.154206223104421|
|3     | 0.5003944305086168s| 1.9984235215878967  |
|4     | 0.33122636480423545s| 3.1271467481458775 |
|5     | 0.238455860283037s | 4.058814608660155 |
|6     | 0.21310192365457478s | 4.692590206838954|
|7     | 0.208440378354854s | 4.7975349492869155|
|8     | 0.20047370144783241s | 4.988185446659305|
|9     | 0.1921842060521685s | 5.20334121383809|


## 20 Story Building Eigenvalues

| Mode | Period (s) | Frequency (Hz) |
|------| -------|-----------|
|1     |3.760731682904276 |  0.26590570248493156|
|2     |1.312985451850604 | 0.761623061847744|
|3     | 0.7599609135879114| 1.3158571475456824  |
|4     | 0.5398783375579737| 1.8522691696119704 |
|5     | 0.4101396081818257 | 2.4381941662085804 |
|6     | 0.390398422766829 | 2.561485758351192|
|7     | 0.32997567778392145 | 3.030526391265818|
|8     | 0.3269631749829076 | 3.0584484018797387|
|9     | 0.2698124823956028 | 3.706277749351072|
|10     | 0.26438009130509105 | 3.782433068479478|
|11    | 0.22420690266397214 | 4.460165981146174|
|12    | 0.22095274813268914 | 4.525854547866806|

