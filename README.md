# Real-Time Face Mask Detection

![](face-mask-detection.gif)

## Info

Hello, COVID 👋 😷

It is necessary to attribute the image received at the input to one of the classes — to determine the presence of a mask on the face or its absence.

The classifier will be considered successful if at least 90% of the variants are correctly classified.

An additional task was the work of the classifier in real time. In this case, detection and classification through the laptop camera.

## Metrics

|             |                                                                                                                                                                                               |
|:-----------:|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|  Accuracy   |                           <div style="background-color:white; padding:10px">![](https://latex.codecogs.com/svg.latex?\Large&space;\frac{TP+TN}{TP+TN+FP+FN}) </div>                           |
|    Loss     |         <div style="background-color:white; padding:10px">![](https://latex.codecogs.com/svg.latex?\Large&space;-\frac{1}{l}\sum_{i=1}^{l}(y_i*\log(y_i)+(1-y_i)*\log(1-y_i))) </div>         |
|  Precision  |                               <div style="background-color:white; padding:10px">![](https://latex.codecogs.com/svg.latex?\Large&space;\frac{TP}{TP+FP}) </div>                                |
|   Recall    |                               <div style="background-color:white; padding:10px">![](https://latex.codecogs.com/svg.latex?\Large&space;\frac{TP}{TP+FN}) </div>                                |
|   F-score   |         <div style="background-color:white; padding:10px">![](https://latex.codecogs.com/svg.latex?\Large&space;\frac{(1+\beta^2)*Precision*Recall}{\beta^2*Precision*Recall}) </div>         |

## Sample data

![](src/sample_data.png)

## Score model

![](src/final_metrics.png)

![](src/final_metrics_2.png)

## Prediction

![](src/score_model.png)

![](src/score_model_2.png)

![](src/score_model_3.png)
