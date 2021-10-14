# Quiz

**The main task of the project**: to provide the user with the opportunity to check
your knowledge in different fields.

## Features

- При старте приложения пользователь вводит логин и пароль для входа.
Если пользователь не зарегистрирован, он должен пройти процесс регистрации.
- При регистрации нужно указать:
	- логин (нельзя зарегистрировать уже существующий логин);
	- пароль;
	- дату рождения.
- После входа в систему пользователь может:
	- стартовать новую викторину;
	- посмотреть результаты своих прошлых викторин;
	- посмотреть Топ-20 по конкретной викторине;
	- изменить настройки. Можно менять пароль и дату рождения;
	- выход
- Для старта новой викторины пользователь должен выбрать раздел знаний
викторины. Например: «История», “География», «Биология» и т. д. Также
нужно предусмотреть смешанную викторину, когда вопросы будут выбираться из разных викторин по случайному принципу.
- Конкретная викторина состоит из двадцати вопросов. У каждого вопроса
может быть один или несколько правильных вариантов ответа. Если вопрос предполагает несколько правильных ответов, а пользователь указал
не все, вопрос не засчитывается.
- По завершении викторины пользователь получает количество правильно
отвеченных вопросов, а также свое место в таблице результатов игроков
викторины.
- Необходимо также разработать утилиту для создания и редактирования
викторин и их вопросов. Это приложение должно предусматривать вход по логину и паролю. 

## JSON structure of quiz file

```js
Quiz-root
	Quiz1
		Section1
			Question1
				Answer1 + attribute IsTrue = true
				Answer2 + attribute IsTrue = false
			Question2
		Section2
```

