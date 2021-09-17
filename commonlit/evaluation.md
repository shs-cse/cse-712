Submissions are scored on the root mean squared error. RMSE is defined as:


<img src="https://render.githubusercontent.com/render/math?math=\mathrm{RMSE} = \sqrt{\frac{1}{n}\sum_{i=1}^{n}{(y_i - \hat{y_i})^2}}">

**Submission File**
For each row in the test set, you must predict the value of the target as described on the data tab, each on a separate row in the submission file. The file should contain a header and have the following format:

```
id,target
eaf8e7355,0.0
60ecc9777,0.5
c0f722661,-2.0
etc.
```
