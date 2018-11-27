#### Reading and plotting data

![image](https://user-images.githubusercontent.com/28304175/48983989-fd3f5f80-f11b-11e8-937a-c8e538260113.png)

#### TODO: Implementing the basic functions
Here is your turn to shine. Implement the following formulas, as explained in the text.

- Sigmoid activation function
𝜎(𝑥)=11+𝑒−𝑥
- Output (prediction) formula
𝑦̂ =𝜎(𝑤1𝑥1+𝑤2𝑥2+𝑏)
- Error function
𝐸𝑟𝑟𝑜𝑟(𝑦,𝑦̂ )=−𝑦log(𝑦̂ )−(1−𝑦)log(1−𝑦̂ )
- The function that updates the weights
𝑤𝑖⟶𝑤𝑖+𝛼(𝑦−𝑦̂ )𝑥𝑖
𝑏⟶𝑏+𝛼(𝑦−𝑦̂ 

## Time to train the algorithm!
When we run the function, we'll obtain the following:
- 10 updates with the current training loss and accuracy
- A plot of the data and some of the boundary lines obtained. The final one is in black. Notice how the lines get closer and closer to the best fit, as we go through more epochs.
- A plot of the error function. Notice how it decreases as we go through more epochs.

### OUTPUT AFTER TRAINING THE ALGORITHM
========== Epoch 0 ==========
Train loss:  0.713584519538
Accuracy:  0.4

========== Epoch 10 ==========
Train loss:  0.622583521045
Accuracy:  0.59

========== Epoch 20 ==========
Train loss:  0.554874408367
Accuracy:  0.74

========== Epoch 30 ==========
Train loss:  0.501606141872
Accuracy:  0.84

========== Epoch 40 ==========
Train loss:  0.459333464186
Accuracy:  0.86

========== Epoch 50 ==========
Train loss:  0.425255434335
Accuracy:  0.93

========== Epoch 60 ==========
Train loss:  0.397346157167
Accuracy:  0.93

========== Epoch 70 ==========
Train loss:  0.374146976524
Accuracy:  0.93

========== Epoch 80 ==========
Train loss:  0.354599733682
Accuracy:  0.94

========== Epoch 90 ==========
Train loss:  0.337927365888
Accuracy:  0.94

![image](https://user-images.githubusercontent.com/28304175/48984029-70e16c80-f11c-11e8-8d5a-e6b8fbdebe42.png)

![image](https://user-images.githubusercontent.com/28304175/48984041-98383980-f11c-11e8-89ed-975d4c0c8eb4.png)
