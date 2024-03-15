**The LOG created for GOEM 99 week  7&8**

Start time:06/03/2024 3:30 pm
End time:3:55 pm 
Total time: 25 mins  
Title: **CREATING A RUNNING VM**
Description: 
Creating a VM through Google cloud with the credits from Google
STEPS:
1.	Create a new project in the google cloud console based on the credits

![image](https://github.com/pphilip-resume/Geom99log/assets/146376119/fab4346e-8c90-4b99-9754-99ca1aae1ba8)

2.	Create a VM in google cloud console platform
   
![image](https://github.com/pphilip-resume/Geom99log/assets/146376119/139bebf3-60dd-4caf-bad4-e25356f07aa8)

3.	Specify the VM name and other details 
4.	Store the password
5.	Create firewall rules, the ports and IP address that will be allowed (full 0  for IP is any computer, specific ones for fleming,Port 444)
![image](https://github.com/pphilip-resume/Geom99log/assets/146376119/062f9ef2-45ac-429f-b425-332c0c0fa026)

6.	Allowing 6442,6080 to enter
   ![image](https://github.com/pphilip-resume/Geom99log/assets/146376119/229cd7b4-c418-4d3b-aef5-bfd9988386c8)
7.	The ports are allowed 
8.	Create the Vm and start running(credit is being used)
![image](https://github.com/pphilip-resume/Geom99log/assets/146376119/3654fd9d-94e3-4a4e-89d9-f121a0b6068e)
9. The instance starts and the cridts are collected.(Remote Desktop with password and username)
    
![image](https://github.com/pphilip-resume/Geom99log/assets/146376119/442238c0-10bd-4a10-9ed1-205b6d5b197b)

10.	Starting and stopping a Vm
![image](https://github.com/pphilip-resume/Geom99log/assets/146376119/c10d8c36-0415-44e4-9103-73e24b18f986)

11.	Sign out/ x does not stop the VM. It should be SHUT DOWN or STOPPED the Vm google cloud console window


Start time:06/03/2024 19:15 pm

End time:06/03/2024 20:00pm

Total time: 65 mins

Title: **Publishing the ArcGis pro map Through the  vm Created**

Description: Publish a map through arcgis from a remote server using the IP address and specifying the port

Steps: VM IS RUNNING THROUGHOUT

1.	Start the VM 
2.	On the local computer start the Remote Desktop connection 
3.	Enter the External IP(will be different every time, add:444 port)
![image](https://github.com/pphilip-resume/Geom99log/assets/146376119/c0284883-2741-4aa2-a3e2-efd088042d18)
4. Add the credentials
![image](https://github.com/pphilip-resume/Geom99log/assets/146376119/d72247f5-7535-4dbb-b17a-655a13d79b45)
5. Accept the certificate
![image](https://github.com/pphilip-resume/Geom99log/assets/146376119/a5ae126d-6883-4fdf-ac2f-148540843196)
7.	This will initiate the VM.
8.	Place the required shapefile in the path specified (extracted)
![image](https://github.com/pphilip-resume/Geom99log/assets/146376119/52b56c1d-e5d3-49e9-88d6-b33b817e1e2f)

8.This makes sure that the folder path is correct.

The following steps to be completed in the local computer

10.	Create a new map in the arcPro and add the required shapefile
![image](https://github.com/pphilip-resume/Geom99log/assets/146376119/ad0c6abe-5705-4995-b5a9-ea05ae530097)

11.	Add the server connection
![image](https://github.com/pphilip-resume/Geom99log/assets/146376119/151c7b02-829c-4896-9215-4c4198590ed0)

12.	The link would be the external IP of the running VM :6443/arcgis
![image](https://github.com/pphilip-resume/Geom99log/assets/146376119/fe106938-a48a-43df-8485-3f8a9aa85c0c)
![image](https://github.com/pphilip-resume/Geom99log/assets/146376119/ced93379-307f-4af5-8109-7db265adb78c)

13. Username and password to be entered
14.	Change the map name and publish
15.	Add the reference site root 

![image](https://github.com/pphilip-resume/Geom99log/assets/146376119/5e5f4d84-3eba-4834-8452-b41e1dec145d)

![image](https://github.com/pphilip-resume/Geom99log/assets/146376119/27708899-7742-42bc-8808-823106b00ae3)

15.Analyse the service (add ids sequentially, register folder)

![image](https://github.com/pphilip-resume/Geom99log/assets/146376119/3588c9b6-9686-48c0-8f9c-9f958c42d5df)

![image](https://github.com/pphilip-resume/Geom99log/assets/146376119/8b0e796c-83d8-41bd-8444-bd4cb1029b61)

16.	Open the map published from the sever(check if layer is there)
17.	Publish the map in AGOL as a new item from the URL but without :6443
19.	Check manager to find if the map is present in manager using 6443 port
![image](https://github.com/pphilip-resume/Geom99log/assets/146376119/0c211ebe-33cd-41e3-a134-73d40dc4128f)
![image](https://github.com/pphilip-resume/Geom99log/assets/146376119/e71d2d35-6237-46e5-b945-bac80cf8b6b9)
![image](https://github.com/pphilip-resume/Geom99log/assets/146376119/96cc54db-722b-4b83-8f49-2ec7c95a9f97)
![image](https://github.com/pphilip-resume/Geom99log/assets/146376119/7bcaeefc-df8b-4eb4-8595-09fcc7c24327)

20. the service that is already presenting the server

![image](https://github.com/pphilip-resume/Geom99log/assets/146376119/a351a55a-2fca-4997-adc1-be0dd9dcc53b)

![image](https://github.com/pphilip-resume/Geom99log/assets/146376119/51fd37fb-e2b4-4f16-bb98-54b70af74cf8)

20.Adding the map through URL
![image](https://github.com/pphilip-resume/Geom99log/assets/146376119/4f58a632-b195-429c-a630-7770d0c22062)

![image](https://github.com/pphilip-resume/Geom99log/assets/146376119/1f466228-a721-4ce0-9f37-8ab07d94bcd8)

21. publishing the canada map
![image](https://github.com/pphilip-resume/Geom99log/assets/146376119/057c6a46-9a66-44c9-b533-a861495f6ef7)
![image](https://github.com/pphilip-resume/Geom99log/assets/146376119/2bb9efb7-a612-4192-b672-6f32c9b082ca)

21. Saving the map as a layer
![image](https://github.com/pphilip-resume/Geom99log/assets/146376119/9f231b7f-ff4b-458f-82df-16c46924fdfd)
![image](https://github.com/pphilip-resume/Geom99log/assets/146376119/79e4b81b-81da-429d-8a22-395a4e23d7fe)

22. server contains
![image](https://github.com/pphilip-resume/Geom99log/assets/146376119/2b77c149-7657-4ad3-9541-37efc1795e46)

23. shutting down the VM
![image](https://github.com/pphilip-resume/Geom99log/assets/146376119/b384139b-5fc7-43b8-a2b8-b28de9e0cb66)














   











