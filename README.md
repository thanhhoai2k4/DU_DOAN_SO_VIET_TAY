# đây là dự án demo nhận dạng chử số viết bằng tay từ 0-9

# 3 load dữ liệu từ MNIST đây là tập dử liệu viết tay số
![image](https://user-images.githubusercontent.com/78804409/208310763-f4f616c5-ea2e-4db2-b7c1-d9b9f71dd3e8.png)
load dự chiều và chia dử liệu ra làm 3 phần 



exam : X_train[50000:60000,:] lấy từ hàng thứ 50 000 đến hàng thứ 60 000 và cột từ cột cuối cùng đến cột đầu

![image](https://user-images.githubusercontent.com/78804409/208310899-f8faa005-7243-4430-beb1-89c73c2d6c3c.png)
Dử liệu đầu vào của model là 1 ma trận (matric) có n dử liệu có 28x28x1 nên vì thế phải chuyển đổi dử liệu n chiều thứ tư có 28x28x1 chiều
