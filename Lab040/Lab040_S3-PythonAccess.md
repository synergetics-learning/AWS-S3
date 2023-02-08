# AWS Simple Storage Service: Working with S3 using Python SDK
This lab covers following topics
<ol>
    <li>Create Access and Secret Access Keys for a file</li>
    <li> Understand SDK using Python040_S3010.ipynb</li>
</ol>


### 1) Create a bucket and upload a CSV file 'LoanData_Raw.csv'.
* #### Object Ownership: Keep it default as disabled.
* #### Block public access settings: Uncheck it.
* #### Bucket Versioning: Enable/Disable
* #### Encryption: Keep default
* #### Upload a CSV file LoadData_Raw.csv

    ![BucketsAndObject](Images040/S3_010_010BucketObject.jpg)

### 2) Create Policy, User Group, User and Access Keys.
* #### Visit IAM from the AWS Services.
    ![IAM Home010](Images040/S3_020_010IAM_Home.jpg)

* #### Creating a Policy:
    ![Creating Policy020](Images040/S3_020_020IAM_Policy.jpg)

* #### Submitting actions:
    ![Creating Policy030](Images040/S3_020_030IAM_Policy.jpg)

* #### Setting Resource Privileges:
    ![Creating Policy040](Images040/S3_020_040IAM_Policy.jpg)

    ![Creating Policy050](Images040/S3_020_050IAM_Policy.jpg)

    ![Creating Policy060](Images040/S3_020_060IAM_Policy.jpg)

    ![Creating Policy070](Images040/S3_020_070IAM_Policy.jpg)

### 3) Create User Group.
* #### Creating a User Group:
    ![Creating Policy070](Images040/S3_030_010IAM_UserGroup.jpg)

* #### Alloting a policy to user group:
    ![Creating Policy070](Images040/S3_030_020IAM_UserGroup.jpg)

### 4) Create User and Access Key.
* #### Creating a User:
    ![Creating Policy070](Images040/S3_040_010IAM_User.jpg)

* ##### User Name: ChandraS3User
* ##### Enable Console Access: Check
* ##### Custom Password: Submit what you can remember.
* ##### User Must create a new password: Uncheck
    ![Creating Policy070](Images040/S3_040_020IAM_User.jpg)

* #### Create a User:
    ![Creating Policy070](Images040/S3_040_030IAM_User.jpg)

    ![Creating Policy070](Images040/S3_040_040IAM_User.jpg)

* #### Click on the user to observe following page:
    ![Creating Policy070](Images040/S3_040_050IAM_AccessKey.jpg)

* #### Go to Security Credential tab
* #### Scroll down to find button for 'Create Access Key'
    ![Creating Policy070](Images040/S3_040_060IAM_AccessKey.jpg)

* #### Set access key for application running outside AWS.
    ![Creating Policy070](Images040/S3_040_070IAM_AccessKey.jpg)

* #### Set description as for 'Python Code accessing S3'.
* #### Create access keys and copy from...
    ![Creating Policy070](Images040/S3_040_080IAM_AccessKey.jpg)

* #### Note:
* ##### Access key begins with words AKIA
* ##### Place access key for Client and Resource
* ##### Place Secret Access Key for Client and Resource.
* ##### Run the code.

    




