# MAD_practical-6_21012021011
pr 6

Service introduction : 

Services in Android are a special component that facilitates an application to run in the background in order to perform long-running operation tasks. The prime aim of a service is to ensure that the application remains active in the background so that the user can operate multiple applications at the same time. A user-interface is not desirable for android services as it is designed to operate long-running processes without any user intervention. A service can run continuously in the background even if the application is closed or the user switches to another application. Further, application components can bind itself to service to carry out inter-process communication(IPC). There is a major difference between android services and threads, one must not be confused between the two. Thread is a feature provided by the Operating system to allow the user to perform operations in the background. While service is an android component that performs a long-running operation about which the user might not be aware of as it does not have UI.


Type of service : 

1. Foreground Services:

Services that notify the user about its ongoing operations are termed as Foreground Services. Users can interact with the service by the notifications provided about the ongoing task. Such as in downloading a file, the user can keep track of the progress in downloading and can also pause and resume the process.

2. Background Services:

Background services do not require any user intervention. These services do not notify the user about ongoing background tasks and users also cannot access them. The process like schedule syncing of data or storing of data fall under this service.

3. Bound Services:

This type of android service allows the components of the application like activity to bound themselves with it. Bound services perform their task as long as any application component is bound to it. More than one component is allowed to bind themselves with a service at a time. In order to bind an application component with a service bindService() method is used. 


**AIM**: What is Service? Write down types of Service. Create an MP3 player application by using service by following below instructions.

![image](https://github.com/Sagar20042004/MAD_practical-6_21012021011/assets/98373145/6f7839e9-00c9-459b-a6ab-aaa03e20da32)

![image](https://github.com/Sagar20042004/MAD_practical-6_21012021011/assets/98373145/83188574-49b4-423e-b495-825fdd99b1a8)

