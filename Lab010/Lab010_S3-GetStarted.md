# AWS Simple Storage Service: Get Started
## An Object Storage Service storing Data Objects in buckets.  
* ### An `object` is a file and metadata describing a file.  
* ### A `bucket` is like a folder as container of objects.
* ### Offers an industry level `Scalability, Availability, Security and Performance`
* ### Can store and protect `any amount of data`

### 1) Home Page
![Home page for AWS S3 Service](Images010/S3_010HomePage.jpg)

### 2) Create Bucket
* #### Bucket Name: Follow naming practices to name a bucket.
* #### Region: Asia Pacific Mumbai
* #### Copy setting for existing bucket: Default.

![Creating a bucket-01](Images010/S3_020_010BucketCreation.jpg)

* #### Object ownership: Default.
* #### Block public access: Allow all users to access a bucket.  Uncheck all boxes here.
![Creating a bucket02](Images010/S3_020_020BucketCreation.jpg)

* #### Bucket Versioning: Lets disable it for a while.
* #### Tags: Lets bypass it for a while
![Creating a bucket03](Images010/S3_020_030BucketCreation.jpg)

* #### Encryption: It applies server side encryption by default.  Apply Amazone S3 managed key (SSE-S3).
* #### Bucket key: Disable.
![Creating a bucket04](Images010/S3_020_040BucketCreation.jpg)

* #### Advanced Settings: It refers to configuring `Object Lock`. Lets leave it disabled.

* #### Click on 'Create Bucket'. Observe the page showing creation status.
![Creating a bucket05](Images010/S3_020_050BucketCreation.jpg)

### 3) View objects in bucket.
* #### Click on bucket name. Observe the page showing bucket details.
![Viewing a bucket01](Images010/S3_030_020ViewBucket.jpg)

* #### Its now bucket properties and list of objects.
* #### Objects: List all objects in a bucket.
* #### Properties: View properties of bucket.
* #### Permissions, Metrix, Management: Lets visit them later.
* #### Create a folder and upload a file.
![Viewing a bucket02](Images010/S3_030_020ViewBucket.jpg)

### 4) Upload files.
* #### Find the upload button.
![Upload objects01](Images010/S3_040_010UploadObjects.jpg)

* #### Create a folder and upload a file by clicking on 'Add Files' button.
* #### Brows to the file in local machine and click on `Upload`.
![Upload objects02](Images010/S3_040_020UploadObjects.jpg)

### 5) Observe object properties.
* #### Click on uploaded object name.
* #### Observe the properties like Region, URLs, Permissions etc.
* #### Copy Object URL and try to access an image in browser. Access has been denied.
![ObjectProperties01](Images010/S3_050_010ObjectProperties.jpg)

### 6) Configure the public access.
* #### Open properties for Bucket. Bucket -> Permission
![ConfigurePublicAccess01](Images010/S3_060_010PublicAccess.jpg)
* #### Configure bucket for Object Ownership to enable ACL.
* #### Keep Object ownership as `Bucket Owner Preferred`.
* #### Save changes.
![ConfigurePublicAccess02](Images010/S3_060_020PublicAccess.jpg)

* #### Observe that, ACL Edit has been enabled.  Click on `Edit`.
* #### For `Everyone (Public Access)`, check the `List' and `Read` for Object and Bucket ACL.
* #### Save changes.
![ConfigurePublicAccess03](Images010/S3_060_030PublicAccess.jpg)
* #### Go to the properties of object and select `Permissions`. Observe, permissions have been enabled for object.  Now, object is publically accessible.
![ConfigurePublicAccess04](Images010/S3_060_040PublicAccess.jpg)

### 7) Download the object
* #### Find the button of Download.  Click it to download an object in the local machine.
![DownloadObject01](Images010/S3_070_010Download-EmptyBucket.jpg)
* #### Empty Bucket and Delete Permanently.
* #### Go to the list of the buckets.  Select a bucket to empty.
![EmptyBucket](Images010/S3_070_020Download-EmptyBucket.jpg)
* #### Delete a bucket.
* #### Go back to the list of buckets.  Select a bucket to delete and click the `Delete` button.
![DeleteBucket](Images010/S3_070_030Download-EmptyBucket.jpg)

## Thats all in this lab.









