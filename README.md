
1. Выполняем установку:

sudo apt upgrade

sudo apt-get install adduser libfontconfig1 musl dpkg

wget https://dl.grafana.com/oss/release/grafana_10.4.5_amd64.deb

sudo dpkg -i grafana_10.4.5_amd64.deb

2. Запускаем, добавляем в автозагрузку, проверяем работоспособность

systemctl start grafana-server.service

systemctl enable grafana-server.service

systemctl status grafana-server.service

3. Заходим на веб интерфейс grafana

http://ip_grafana:3000/

Дефолтный логин/пароль:

admin/admin

4. Добавляем новую базу данных prometheus в grafana 
![image](https://github.com/user-attachments/assets/5f3c303b-1236-4747-83c6-c41162df7745)
![image](https://github.com/user-attachments/assets/60daf77f-c116-4686-9e14-a41552dee351)
![image](https://github.com/user-attachments/assets/77bc10b3-948a-41f7-804b-397a5a90556a)
![image](https://github.com/user-attachments/assets/e799e97e-ce01-4e87-9dc3-01351b5f3137)
