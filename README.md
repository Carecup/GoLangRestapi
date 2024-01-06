# GoLangRestapi
Лабораторная работа 4 по сетевым технологиям

В лабораторной работе реализованы следующие методы RESTAPI:

router.HandleFunc("/user", createUser).Methods("POST") - добавление пользователя

![image](https://github.com/Carecup/GoLangRestapi/assets/25736912/b73cb2b6-80c9-4f62-80a6-d77f519c6720)

router.HandleFunc("/todo", createTask).Methods("POST") - добавление задачи

![image](https://github.com/Carecup/GoLangRestapi/assets/25736912/11bb65e4-72ae-4422-b5bc-323c291bf632)

router.HandleFunc("/todo", getTasks).Methods("GET") - получение задач по пользователю

![image](https://github.com/Carecup/GoLangRestapi/assets/25736912/96db35da-aebb-4e29-944f-5e4d34e5f86f)

router.HandleFunc("/todo/{id}", updateTask).Methods("PUT") - обновление задачи 

![image](https://github.com/Carecup/GoLangRestapi/assets/25736912/95beab50-8999-4983-a689-d33cdea4b5f5)

router.HandleFunc("/todo/{id}", deleteTask).Methods("DELETE") - удаление задачи

![image](https://github.com/Carecup/GoLangRestapi/assets/25736912/22a5981b-0cf7-4363-84e7-5d8cfc6629bf)
