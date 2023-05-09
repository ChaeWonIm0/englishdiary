# ai26

## 테스트

##### 2023-04-14 일기쓰기, 공지사항, 공개일기장, 로그인/회원가입 기능이 포함된 flask 파일 넣음 (채원)
##### 2023-05-04 Amazon Lightsail로 서버 공개를 위한 repository 생성


#### 2023-05-04 실험
amazon lightsail : ubuntu 무료버전 라이트세일 고정 IP 주소 : 43.200.159.39
flask를 받아들이질 못함
### "killed"
![image](https://user-images.githubusercontent.com/114221089/236110364-b4756e50-4b26-488d-a248-d4748725e582.png)

### cpu가 2배 큰 ubuntu를 구매해도 20분간 중지됨
![image](https://user-images.githubusercontent.com/114221089/236158068-80e9da2e-8a43-4339-a07a-6c825343c69e.png)


AWS EC2 : t2.micro(무료버전)(ubuntu) 
CPU 가용률 99% 이상으로 flask를 받아들이질 못함
> torch, transformer, torch library
### "killed" 
![image](https://user-images.githubusercontent.com/114221089/236109639-3d24b224-3437-4658-bfea-b623245e248e.png)

#### 2023-05-08 실험A
lightsail 2GB 서버로 실행

![image](https://user-images.githubusercontent.com/114221089/236973858-109dfba9-6287-4bfb-912e-9a9261e74c93.png)
pytorch_model.bin 100% 이후로 진행 불가

#### 2023-05-09 실험B
lightsail 4GB(20$ 버전)으로 사용 시도
![image](https://user-images.githubusercontent.com/114221089/236977560-41173804-5911-49e8-b117-a5ad437fe02f.png)
killed

- 현재 실행중인 Gunicorn 프로세스에서 계속해서 "CRITICAL WORKER TIMEOUT" 메시지와 함께 Worker 프로세스가 종료되었다는 메시지가 출력되고 있습니다. 이러한 메시지는 Worker 프로세스가 응답하지 않거나 일정 시간 내에 작업을 완료하지 못했을 때 발생할 수 있습니다.

- 일반적으로 이러한 문제는 웹 애플리케이션의 처리 시간이 너무 오래 걸려서 발생할 수 있습니다. 이 경우에는 코드를 최적화하거나, 처리 시간이 오래 걸리는 작업을 백그라운드 작업으로 분리하는 등의 방법을 사용하여 문제를 해결할 수 있습니다. 또는 Gunicorn 설정을 조정하여 Worker 프로세스의 개수를 늘리거나 요청 대기 시간(timeout)을 조정할 수도 있습니다.

- 따라서 이 경우에는 Gunicorn 설정을 조정하거나 애플리케이션 코드를 분석하여 원인을 파악하고 해결해야 합니다


#### 2023-05-09 수정
- navbar, sidebar의 제목 순서 변경 : 공지사항, 사용설명서, 공개일기장, 일기쓰기
