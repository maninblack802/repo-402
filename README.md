# Домашнее задание к занятию «Защита хоста»
---
### Задание 1
`Установите eCryptfs, добавьте пользователя cryptouser, зашифруйте домашний каталог пользователя с помощью eCryptfs`

Добавляем пользователя:
![image1](https://github.com/maninblack802/repo-402/blob/main/img1.png)

Делаем шифрованную копию домашней папки пользователя и в дальнейшем пользуемся ей:
![image2](https://github.com/maninblack802/repo-402/blob/main/img2.png)

Монтируем шифрованную папку пользователя:
![image3](https://github.com/maninblack802/repo-402/blob/main/img3.png)

Создаем файл, смотрим его и отмонтируем папку пользователя. После этого ничего не видим.
![image4](https://github.com/maninblack802/repo-402/blob/main/img4.png)

---

### Задание 2
`Установите поддержку LUKS, создайте небольшой раздел, зашифруйте созданный раздел с помощью LUKS`

Создаем и форматируем раздел на пустом диске:
![image5](https://github.com/maninblack802/repo-402/blob/main/img5.png)

Подключаемся к разделу с помощью пароля, созданного на предыдущем шаге:
![image6](https://github.com/maninblack802/repo-402/blob/main/img6.png)

Монтируем шифрованный диск в разделе:
![image7](https://github.com/maninblack802/repo-402/blob/main/img7.png)

Отмонтируем диск и больше его не видим:
![image8](https://github.com/maninblack802/repo-402/blob/main/img8.png)
