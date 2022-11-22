# labirint.py

![image](https://user-images.githubusercontent.com/81209823/203325760-413efad2-ce7d-451f-9a07-b0f9d86eb352.png)

Для создания игры, я использовал pygame.
Я создал переменные для персонажей.
![image](https://user-images.githubusercontent.com/81209823/203325989-557489d5-3221-4056-bb7d-4980fb1bb459.png)

Я выбрал шрифт с помощью font.init().
![image](https://user-images.githubusercontent.com/81209823/203326201-c2e70493-c914-492e-b524-a28cfeb81bf2.png)

Я создал класс GameSprite для того чтобы мои герои вывелись на экран.
![image](https://user-images.githubusercontent.com/81209823/203326318-e2bf39ec-c39b-4881-974d-aa990e3d8276.png)

Для того чтобы персонаж передвигался и я мог им управлять, я создал класс Player(GameSprite)
И внес клавиши управления.
![image](https://user-images.githubusercontent.com/81209823/203326567-792c67ef-7ed5-4e78-b60e-990bf22263f8.png)

Я создал класс для вражеского персонажа и их будет несколько. И в этом классе я настроил их передвижение по экрану.
![image](https://user-images.githubusercontent.com/81209823/203326736-1fd18559-cfb2-4576-a409-2ec022b20550.png)

Я создал стены лабиринта. И использовал Surface для отрисовывания стен на экране.
![image](https://user-images.githubusercontent.com/81209823/203326983-638ffa49-b51c-4c5a-802a-a0906f08ef3d.png)

Класс bullet для пуль, которыми будет стрелять гравный герой.
![image](https://user-images.githubusercontent.com/81209823/203327085-2ea6d92c-f58a-4367-8b0a-42537905a21e.png)

Создал окно игры размером в ширину 500 и в высоту 700.
![image](https://user-images.githubusercontent.com/81209823/203327235-26236c1c-5b80-48e6-830f-5c55d396e971.png)

Отдельные переменные для персонажей.
![image](https://user-images.githubusercontent.com/81209823/203327313-505bfbf8-fa10-4e0b-8a67-1bd3f945a641.png)

Настоил стены по высоте, ширине.
![image](https://user-images.githubusercontent.com/81209823/203327369-b44aad6c-6056-4327-a885-01774ee6c808.png)

Группы спрайтов.
![image](https://user-images.githubusercontent.com/81209823/203327406-a9157e13-fb9e-4e66-a8d8-8df61493bc66.png)

И добавил спрайты в группу.
![image](https://user-images.githubusercontent.com/81209823/203327448-3764d229-68cc-4444-b349-b5f467080ef7.png)

Это счетчик очков.
![image](https://user-images.githubusercontent.com/81209823/203327528-63084dfc-0a5e-497d-924e-e8bf133ca0a5.png)

Игровой цикл.
