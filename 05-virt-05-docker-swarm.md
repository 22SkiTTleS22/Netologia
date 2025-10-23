Задача 1
Создайте ваш первый Docker Swarm-кластер в Яндекс Облаке. Документация swarm: https://docs.docker.com/engine/reference/commandline/swarm_init/
1.Создайте 3 облачные виртуальные машины в одной сети.
<img width="1361" height="227" alt="image" src="https://github.com/user-attachments/assets/27f16d1b-9a45-44a9-a5bb-acd7e2acc74d" />
2.Установите docker на каждую ВМ.
3.Создайте swarm-кластер из 1 мастера и 2-х рабочих нод.
<img width="1045" height="237" alt="image" src="https://github.com/user-attachments/assets/2039e5ee-63fc-41ce-be46-284c020afaa6" />
<img width="2010" height="115" alt="image" src="https://github.com/user-attachments/assets/0f081b17-820b-451f-a197-d92371061415" />
<img width="1996" height="106" alt="image" src="https://github.com/user-attachments/assets/75d06bd3-3d62-4e9d-8912-445fb4ce12fa" />
4.Проверьте список нод командой:
  docker node ls
<img width="1267" height="129" alt="image" src="https://github.com/user-attachments/assets/5cecc098-60b3-46cb-9029-5ee1e402bb79" />
