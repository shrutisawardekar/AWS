**STEPS TO ATTACH IAM ROLES TO EC-2**

- *Step 1*
-> Select/type  IAM service from the serices option.
![1](https://user-images.githubusercontent.com/44541800/81148902-c7520c00-8f9a-11ea-8314-c713016cf6ac.png)



- *Step 2*
-> Select roles from dashboard then select Ec-2 from roles and click on create role.
![2](https://user-images.githubusercontent.com/44541800/81148242-89081d00-8f99-11ea-9320-ef41ca6b130b.png)



- *Step 3*
-> Select Ec-2 and click on permissions.
![3](https://user-images.githubusercontent.com/44541800/81149323-a0480a00-8f9b-11ea-84b6-3b61c9d36e14.png)



- *Step 4*
-> Select Amazon S3 Full Access 
![4](https://user-images.githubusercontent.com/44541800/81150533-a63eea80-8f9d-11ea-96a5-4dc44f5e738a.png)



- *Step 5*
-> Assign a role name and select create role.
![5](https://user-images.githubusercontent.com/44541800/81152728-d7b8b580-8f9f-11ea-8650-ef177d11f927.png)



- *Step 6*
-> The specified role is created.
![6](https://user-images.githubusercontent.com/44541800/81153042-26fee600-8fa0-11ea-8727-22dd6b6655a6.png)





**STEPS TO ATTACH IAM ROLES TO EC-2**
- *Step 1*
->Select ec-2 from services.

- *Step 2*
->Select the instance.

- *Step 3*
->Select actions ->Instance settings -> Attach/Replace IAM Role.

![7](https://user-images.githubusercontent.com/44541800/81154707-cc668980-8fa1-11ea-94d1-0d888f1ca5df.png)

- *Step 4*
->Select the specified IAM role and click on apply.
![8](https://user-images.githubusercontent.com/44541800/81155183-4d258580-8fa2-11ea-820f-46b394a30222.png)

**MobaXterm Commands**


- *aws s3 ls* -> Displays bucket name.

![1](https://user-images.githubusercontent.com/44541800/81180894-46f6cf80-8fc9-11ea-80b2-d3269315cf33.png)



- *ls -r* -> Displays folders inside a bucket.

![2](https://user-images.githubusercontent.com/44541800/81184810-7956fb80-8fce-11ea-8549-deb91870762b.png)


- *aws s3 ls --recursive*

![3](https://user-images.githubusercontent.com/44541800/81184818-7c51ec00-8fce-11ea-8ba8-1d21ff96a32b.png)


- *mv source destination* -> Sends file from source to destination and deletes it at source.

![4](https://user-images.githubusercontent.com/44541800/81184826-7eb44600-8fce-11ea-8fd9-4ca8f3b1abe5.png)


-*ls -a * -> Displays all files including hidden(starting with .)

![5](https://user-images.githubusercontent.com/44541800/81184837-84119080-8fce-11ea-903c-3b3b16949f28.png)


- *ls -l* -> Displays detailed information of files.

![6](https://user-images.githubusercontent.com/44541800/81184859-8a077180-8fce-11ea-8e60-ca6963eec7f2.png)


- *history* -> Displays all the commands being used till now.

![7](https://user-images.githubusercontent.com/44541800/81184868-8c69cb80-8fce-11ea-83a6-5d96b6343157.png)


- *Ctrl+R* -> Searches any command by initials.

![8](https://user-images.githubusercontent.com/44541800/81184881-8f64bc00-8fce-11ea-8bc8-010592016113.png)

- **

