## Client/Server Architecture Using A MySQ

For this demonstration wil be using my existing LAMP and LEMP stack 

![image](https://user-images.githubusercontent.com/124367888/218390200-b11a9358-814d-49a8-acb8-c4d1cbefeffe.png)

Server A = Mysql Server =  172.31.51.148
Server B = Mysql Client =  172.31.49.204

Next I tested connectivity 

![image](https://user-images.githubusercontent.com/124367888/218393365-84c1b569-e43a-45d5-a91b-9cd89e72d14f.png)

Changed the ind Address

![image](https://user-images.githubusercontent.com/124367888/218395663-2cf544b2-495e-4a3a-84df-8f5cebeffc87.png)

Permission Error . Fixed by creating additional User, and granting all IP access via "%" and restarting teh mysql service

![image](https://user-images.githubusercontent.com/124367888/218415035-3748e3da-51cd-4c93-a358-1588e30f62ce.png)

Successful Connection 
![image](https://user-images.githubusercontent.com/124367888/218415378-b393541d-4ddd-4d0e-ba51-fae8bdef8005.png)

