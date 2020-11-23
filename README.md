# University_OOP_LB1
LB1

Лабораторная работа №1 по ООП 
КНТЕУ ФИТ 
КИБЕРБЕЗОПАСНОСТЬ 
2020

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Задание:
1 Створити проект у Visual Studio та зареєструватись на github.com

2. Створити публічний репозиторій та зайти у термінал
Windows+R  > cmd

3. Відкрити корневий каталог

4. Перевіряемо наявність репозиторію за допомогою git status

5. Якщо репозиторію не має пишемо 
git init
в іншому випадку одразу пишемо
git config --global user.name Name
git config --global user.email Email

6. Перевіряємо збереження конфігурацій
git config -e –global

7. Додаємо 
git remote add origin адреса репозиторію
git remote add upstream адреса репозиторію

8. Після цього в цьому корневому каталозі пишемо (для збереження коміту локально)
git add .
git commit -m “first commit”

9. Після цього нам необхідно передати коміт на remote
git push origin master

10. Вносимо зміни до проекту у Visual Studio

11. Додаємо змінені файли до коміту 
// «.» ставимо аби не обирати окремий файл, а система просканує і додасть усі змінені файли
git add .
git commit -m “second commit”
git push origin master

12. Далі створюємо .gitignore файл (самостійно знаходимо файли, які мають бути в .gitignore для проекту у Visual Studio).

13. Створюємо README.md файл (файл для опису репозиторію), у якому додаємо опис репозиторію, використоруючи маркдаун розмітку.

14. Що таке маркдаун розмітка виклристоуємо Google Search

15. Знову додаємо зміни до коміту.

16. Шукаємо як створити ще одну гілку (branch) develop із гілки master і перейти на неї (за допомогою однієї команди).

17. Робимо зміни та зберігаємо у origin develop.

18. Потім об’єднуємо гілку develop із  гілкою master у master. (git merge).

