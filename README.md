# A Machine Learning Approach to Precise Renal Cancer Subtyping using RNA-seq Gene Expression Data

## Objective 

Cancer remains a significant global health challenge, with early detection and accurate classification being critical for effective treatment. In this repository, we develop an approach to detect the three most common subtypes of renal cancer — chromophobe renal cell carcinoma, clear cell renal cell carcinoma, and papillary renal cell carcinoma – by leveraging machine learning algorithms applied to RNA-seq gene expression data. 


## Results
The overall predictive performance of the machine learning methods based on ANOVA feature selection.
| Model | Accuracy | Precision | Recall | Specificity | F1 Score | AUC |
| :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: |
| Logistic Regression | 94.81 | 93.70 | 82.53 | 94.63 | 86.58 | 97.78 |
| Naive Bayes | 95.56 | 87.69 | 90.27 | 95.89 | 88.83 | 98.06 |
| Support Vector Machine | 97.04 | 96.74 | 85.63 | 96.69 | 89.64 | 98.23 |
| Decision Tree | 95.56 | 86.81 | 93.21 | 96.44 | 89.51 | 96.82 |
| Extra Trees Classifier | 96.30 | 87.88 | 92.20 | 97.38 | 89.84 | 98.49 |
| Multilayer Perceptron | 96.67 | 89.21 | 94.42 | 97.40 | 91.50 | 98.90 |


<h2>Results per class</h2>
The predictive performance of the machine learning methods per-class based on ANOVA feature selection.
<br>
<br>
<i>Note: KICH stands for chromophobe renal cell carcinoma, KIRC stands for clear cell renal cell carcinoma, and KIRP stands for papillary renal cell carcinoma.</i>
<br>
<br>
<table>
  <thead>
    <tr>
      <th rowspan="2">Classifier</th>
      <th colspan="6">Performance Metrics</th>
    </tr>
    <tr>
        <th>Class</th>
      <th>Accuracy</th>
      <th>Precision</th>
      <th>Recall</th>
      <th>Specificity</th>
      <th>F1 Score</th>
    </tr>
  </thead>
  <tbody>
    <!-- Replace the placeholder values with your actual data -->
    <tr>
      <td rowspan="3">Logistic Regression</td>
      <td>KICH</td>
      <td>97.22</td>
      <td>100.00</td>
      <td>61.54</td>
      <td>100.00</td>
      <td>76.19</td>
    </tr>
    <tr>
      <td>KIRC</td>
      <td>94.44</td>
      <td>94.07</td>
      <td>97.37</td>
      <td>89.39</td>
      <td>95.69</td>
    </tr>
    <tr>
      <td>KIRP</td>
      <td>92.78</td>
      <td>87.04</td>
      <td>88.68</td>
      <td>94.49</td>
      <td>87.85</td>
    </tr>
  </tbody>
    <tbody>
    <!-- Replace the placeholder values with your actual data -->
    <tr>
      <td rowspan="3">Naive Bayes</td>
      <td>KICH</td>
      <td>96.67</td>
      <td>73.33</td>
      <td>84.62</td>
      <td>97.60</td>
      <td>78.57</td>
    </tr>
    <tr>
      <td>KIRC</td>
      <td>94.44</td>
      <td>95.61</td>
      <td>95.61</td>
      <td>92.42</td>
      <td>95.61</td>
    </tr>
    <tr>
      <td>KIRP</td>
      <td>95.56</td>
      <td>94.12</td>
      <td>90.57</td>
      <td>97.64</td>
      <td>92.31</td>
    </tr>
  </tbody>
    <tbody>
    <!-- Replace the placeholder values with your actual data -->
    <tr>
      <td rowspan="3">Support Vector Machine</td>
      <td>KICH</td>
      <td>97.22</td>
      <td>100.00</td>
      <td>61.54</td>
      <td>100.00</td>
      <td>76.19</td>
    </tr>
    <tr>
      <td>KIRC</td>
      <td>96.67</td>
      <td>95.76</td>
      <td>99.12</td>
      <td>92.42</td>
      <td>97.41</td>
    </tr>
    <tr>
      <td>KIRP</td>
      <td>97.22</td>
      <td>94.44</td>
      <td>96.23</td>
      <td>97.64</td>
      <td>95.33</td>
    </tr>
  </tbody>
    <tbody>
    <!-- Replace the placeholder values with your actual data -->
    <tr>
      <td rowspan="3">Decision Tree Classifier</td>
      <td>KICH</td>
      <td>96.67</td>
      <td>70.59</td>
      <td>92.31</td>
      <td>97.01</td>
      <td>80.00</td>
    </tr>
    <tr>
      <td>KIRC</td>
      <td>93.89</td>
      <td>97.25</td>
      <td>92.98</td>
      <td>95.45</td>
      <td>95.07</td>
    </tr>
    <tr>
      <td>KIRP</td>
      <td>96.11</td>
      <td>92.59</td>
      <td>94.34</td>
      <td>96.85</td>
      <td>93.46</td>
    </tr>
  </tbody>
    <tbody>
    <!-- Replace the placeholder values with your actual data -->
    <tr>
      <td rowspan="3">Extra Trees Classifier</td>
      <td>KICH</td>
      <td>96.67</td>
      <td>73.33</td>
      <td>84.62</td>
      <td>97.60</td>
      <td>78.57</td>
    </tr>
    <tr>
      <td>KIRC</td>
      <td>95.56</td>
      <td>99.07</td>
      <td>93.86</td>
      <td>98.48</td>
      <td>96.40</td>
    </tr>
    <tr>
      <td>KIRP</td>
      <td>96.67</td>
      <td>91.23</td>
      <td>98.11</td>
      <td>96.06</td>
      <td>94.55</td>
    </tr>
  </tbody>
    <tbody>
    <!-- Replace the placeholder values with your actual data -->
    <tr>
      <td rowspan="3">Multilayer Perceptron</td>
      <td>KICH</td>
      <td>97.22</td>
      <td>75.00</td>
      <td>92.31</td>
      <td>97.60</td>
      <td>82.76</td>
    </tr>
    <tr>
      <td>KIRC</td>
      <td>95.56</td>
      <td>98.18</td>
      <td>94.74</td>
      <td>96.97</td>
      <td>96.43</td>
    </tr>
    <tr>
      <td>KIRP</td>
      <td>97.22</td>
      <td>94.44</td>
      <td>96.23</td>
      <td>97.64</td>
      <td>95.33</td>
    </tr>
  </tbody>
</table>


