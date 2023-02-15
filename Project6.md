## Web Solution With WordPress

Additional Volumes Created 

![image](https://user-images.githubusercontent.com/124367888/219038685-3ee1cfd7-061d-468e-9cbc-c1363dcf4c58.png)

Volumes Added to Ec2 Instance

![image](https://user-images.githubusercontent.com/124367888/219048583-dd695241-e9b0-4447-b50b-121704583862.png)

Creating Parttions on the attached Storage

![image](https://user-images.githubusercontent.com/124367888/219050121-a30ff3e3-f167-452b-bc5e-ee7e1c335f2a.png)

![image](https://user-images.githubusercontent.com/124367888/219050532-6e087c48-870d-4029-ae5c-03d94887a06f.png)

New Partition was not created initially as in above . A key prcess of the gdisk is the "n" prompt

![image](https://user-images.githubusercontent.com/124367888/219057898-5ccc7ff8-0ec3-43f2-b7d9-d18ca2238f15.png)

![image](https://user-images.githubusercontent.com/124367888/219058531-b1ea1937-4d40-48ed-bd24-e84dd69ee632.png)

Creation of Physical Volume

![image](https://user-images.githubusercontent.com/124367888/219058936-fd851b7a-b911-4bd0-8eeb-6fbe4216a5c2.png)

Logical Volume for Apps and Logs Created

![image](https://user-images.githubusercontent.com/124367888/219060024-4b7f4efa-6b3c-48ad-b72f-5854c192c92e.png)

Mounting of Web Folder in Another Location

![image](https://user-images.githubusercontent.com/124367888/219060845-8d91d694-97bb-4eee-b8a5-c2bf7e2d93ab.png)


verifying the setup 

![image](https://user-images.githubusercontent.com/124367888/219107071-87e69f86-6d2b-45dd-bc9d-33119327e195.png)

Setting the UUID within /etc folder

![image](https://user-images.githubusercontent.com/124367888/219121225-6de994d9-cf79-4414-8eea-3be3d830c14c.png)

testing my config

![image](https://user-images.githubusercontent.com/124367888/219121423-e38ad5db-ae06-42d1-80bc-f1e844e5c572.png)


Installation of Wordpress 
1. Install Httpd Apcahe

Default test page loads
![image](https://user-images.githubusercontent.com/124367888/219124700-00f5931f-de7e-4ba3-8fd5-36b40f32cbe4.png)

2. install phgp 

![image](https://user-images.githubusercontent.com/124367888/219125362-de153cd0-db71-483b-a5dd-880153bbf55c.png)

3. Download wordpress and set permissions

![image](https://user-images.githubusercontent.com/124367888/219126507-70d9a3ad-1040-4f67-aa2a-252b2320afb3.png)

4. Setting Database permissions

![image](https://user-images.githubusercontent.com/124367888/219129017-40363239-d655-47ee-adde-37f5aba607db.png)

5. Created a new user "admin " for connectivity 

![image](https://user-images.githubusercontent.com/124367888/219131800-f734a35b-b203-40a3-8833-7bfe85502cc0.png)

6. There was need to configure the Wordpress Config file. This resulted into Connection Error 
7. ![image](https://user-images.githubusercontent.com/124367888/219141339-c5f8b1d5-7502-4c20-bf70-43e911389cbc.png)

completed

![image](https://user-images.githubusercontent.com/124367888/219141417-34615d9e-f8a0-4c50-ae54-9485981bb67a.png)



