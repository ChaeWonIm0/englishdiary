# English diary with NLP




##### 2023-04-26 + Added public diary sorting feature

##### 2023-04-27 (for all to share) Member information modification feature completed

##### 2023-04-28 Paraphrases feature error fixed (+ close button)
##### 2023-05-04 Experiment
Amazon Lightsail: Ubuntu free version Lightsail fixed IP address: 43.200.159.39
Unable to accept Flask


### "killed"
![image](https://user-images.githubusercontent.com/114221089/236110364-b4756e50-4b26-488d-a248-d4748725e582.png)

### Even with an Ubuntu that has twice the CPU, it stops for 20 minutes
![image](https://user-images.githubusercontent.com/114221089/236158068-80e9da2e-8a43-4339-a07a-6c825343c69e.png)


AWS EC2: t2.micro (free version) (Ubuntu)
CPU usage rate over 99% and unable to accept Flask
> I think may be torch, transformer, torch library
### "killed" 
![image](https://user-images.githubusercontent.com/114221089/236109639-3d24b224-3437-4658-bfea-b623245e248e.png)

#### 2023-05-08 Experiment A
Attempt to use Lightsail 2GB 

### stop
![image](https://user-images.githubusercontent.com/114221089/236973858-109dfba9-6287-4bfb-912e-9a9261e74c93.png)
Unable to proceed after 100% of pytorch_model.bin

#### 2023-05-09 Experiment B
Attempt to use Lightsail 4GB ($20 version)
![image](https://user-images.githubusercontent.com/114221089/236977560-41173804-5911-49e8-b117-a5ad437fe02f.png)
### "killed"

- The Gunicorn process that is currently running continues to display a message that the Worker process has been terminated along with the "CRITICAL WORKER TIMEOUT" message. These messages can occur when the Worker process does not respond or cannot complete the task within a certain time.

- Typically, this problem can occur when the processing time of the web application is too long. In this case, the problem can be solved by optimizing the code, separating tasks that take a long time to process into background tasks, or adjusting the Gunicorn settings to increase the number of Worker processes or adjust the request wait time (timeout).

- Therefore, in this case, you need to adjust the Gunicorn settings or analyze the application code to identify the cause and solve it.


#### Modifications on 2023-05-09
- Changed the order of the titles in the navbar and sidebar: Notice, User Manual, Public Diary, Diary Writing

### Move to Docker
![image](https://user-images.githubusercontent.com/114221089/237052505-e6fbf005-6c52-4ef0-a4b2-ee53518ca937.png)

### Successfully opened the homepage in Docker
![image](https://user-images.githubusercontent.com/114221089/237060539-8d0a2950-b9b4-4373-ada6-b68ca426f9a3.png)


### 230511 Docker test

### Unable to access from unknown sources
#### ex) 502 bad gateway, 504 gateway timeout broadcast

![image](https://github.com/ChaeWonIm0/englishdiary/assets/114221089/07addaf1-fc1e-48be-a8c4-c4557a4ded43)

### 230512 Docker record

![image](https://github.com/ChaeWonIm0/englishdiary/assets/114221089/8d4ff3bc-9763-4983-ab46-6695aec70af2)

### Change : config.py to config directory
### __init__.py code modify
#### EWS_diary initial version server environment available
