# YouTube Video Views Prediction Using Linear Regression
🎯 Objective

Video ki features dekh kar predict karna ke usay kitne views mil sakte hain.

🎯Input Features
Video Length (minutes)
Likes
Comments
Shares
Subscribers
🎯Output (Target)
Views
Step 1: Dataset
| Length_Min | Likes | Comments | Shares | Subscribers | Views |
| ---------- | ----- | -------- | ------ | ----------- | ----- |
| 5          | 120   | 15       | 10     | 1000        | 2500  |
| 8          | 200   | 30       | 15     | 1500        | 4200  |
| 6          | 150   | 20       | 12     | 1200        | 3100  |
| 10         | 300   | 45       | 25     | 2500        | 6200  |
| 4          | 90    | 10       | 5      | 800         | 1800  |
| 7          | 180   | 25       | 14     | 1400        | 3800  |
| 12         | 350   | 50       | 30     | 3000        | 7200  |
| 9          | 250   | 35       | 20     | 2000        | 5200  |
| 3          | 70    | 8        | 4      | 700         | 1500  |
| 15         | 500   | 80       | 40     | 5000        | 10500 |
| 6          | 160   | 22       | 13     | 1300        | 3300  |
| 8          | 210   | 28       | 16     | 1700        | 4500  |
| 11         | 320   | 48       | 28     | 2800        | 6800  |
| 5          | 110   | 14       | 8      | 900         | 2300  |
| 14         | 450   | 70       | 35     | 4200        | 9500  |
| 7          | 170   | 24       | 12     | 1450        | 3700  |
| 13         | 400   | 60       | 32     | 3500        | 8400  |
| 4          | 85    | 9        | 5      | 750         | 1700  |
| 10         | 290   | 40       | 22     | 2400        | 5900  |
| 6          | 140   | 18       | 10     | 1100        | 2900  |
Step 2: Import Libraries
Step 3: Load Dataset
Step 4: Check Dataset
Step 5: Define Features and Target
X (Input)
Length_Min
Likes
Comments
Shares
Subscribers
y (Output)
Views
Step 6: Split Dataset
Step 7: Train Linear Regression Model
Step 8: Prediction
Step 9: Accuracy Check
MAE
MSE
R² Score
Step 10: Predict New Video
