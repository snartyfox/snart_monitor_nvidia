# snart_monitor_nvidia
Monitor designed to prevent overheating in mining rigs with nvidia GPU cards with telegram

- AMD GPUS will be avaliable soon...
- Web page in pogregss..
- Update settings via telegram will be avaliable soon...

How it works:
- Download and Extract the monitor
- 
![Screenshot_1](https://user-images.githubusercontent.com/89432902/130544349-65aa82e8-090b-4066-9390-629edf481e2a.png)

- Open the recent JSON file "config_json.json"
- 
- ![imagen](https://user-images.githubusercontent.com/89432902/130544516-268ba585-57ce-40b0-86c8-5961b17311ac.png)
- 
-Open Telegram an search for "@snart_bot" and type /start

![imagen](https://user-images.githubusercontent.com/89432902/130544628-4e79bbdc-a125-4dc0-971e-60fb271894ac.png)

![imagen](https://user-images.githubusercontent.com/89432902/130544955-dd44b1fc-c505-46b7-b827-4042c208b914.png)

- Copy the chat_id to "config_json.json" 
- 
![imagen](https://user-images.githubusercontent.com/89432902/130545049-91506546-7326-4d45-b9d4-e07678c79612.png)

![imagen](https://user-images.githubusercontent.com/89432902/130545108-18faaa62-df07-4235-a471-a34aa5b19092.png)

- Configure all your alert settings on °C:
- 
-   "lower_temp_alert": 30 (Helps to detect when GPUs are not Mining)
    "higher_temp_alert": 75 (Send an alert when temperature is Hot)
    "critical_temp_alert": 82 (Send an alert amd sutdown or reboot the miner)
    
 ![imagen](https://user-images.githubusercontent.com/89432902/130545296-88515c26-b2d1-4efe-baef-01d1396e574d.png)
 
- Save the json file and open the monitor
- 
![imagen](https://user-images.githubusercontent.com/89432902/130545502-9ba3c6ae-185d-4676-9488-ea7c2c81a026.png)

- New message will be sent on Telegram
- 
-  ![imagen](https://user-images.githubusercontent.com/89432902/130545558-20d52840-0791-4941-b674-e8996aca8598.png)
-  
-You can monitor as much cards as you want

![imagen](https://user-images.githubusercontent.com/89432902/130545687-a87cce15-08da-4610-a608-fcaa32832184.png)

-If critical temperature rises over your parameter, the miner will try to shutdown or reboot and send a message to your telegram

![imagen](https://user-images.githubusercontent.com/89432902/130546067-5d26d379-aff6-43fe-a454-f922fae9c0c1.png)

![imagen](https://user-images.githubusercontent.com/89432902/130546096-cd4b959c-8454-479c-905b-91df6888363f.png)

Enjoy!
