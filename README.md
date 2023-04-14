# Creating AMI on AWS

### What is AMI?

AMI stands for Amazon Machine Image and it is used to store EC2 instances.

### Creating an AMI

1. Make sure your instances is selected and click on the `Actions` button. Then select `Images and templates` followed by `create image`

![1. Actions and create AMI.png](img%2F1.%20Actions%20and%20create%20AMI.png)

2. Name your AMI. Also, would suggest putting a description to help you with what security group you will need as you can see below.

![2. Name and description.png](img%2F2.%20Name%20and%20description.png)

3. Click the link in the green bo to launch your AMI you just created.

![3. Click link to launch image.png](img%2F3.%20Click%20link%20to%20launch%20image.png)

### Launch Instance In AMI

1. Select the AMI you created and then click the orange button at the top labelled `Launch Instance from AMI`

![4. Launch Instance.png](img%2F4.%20Launch%20Instance.png)

2. Name your instance to what suits you best. The AMI should be selected for you because you created an instance from your AMI.

![5. Name instance.png](img%2F5.%20Name%20instance.png)

3. Select your instance type and search for your key pair. If you don't have one, you can create one.

![6. Instance type and key pair.png](img%2F6.%20Instance%20type%20and%20key%20pair.png)

4. Select the security group you have created beforehand. If you don't have one, you can create a new one.

![7. security group.png](img%2F7.%20security%20group.png)