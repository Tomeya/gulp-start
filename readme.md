

# Домашнее задание по Gulp

Данный стартовый шаблон имеет gulp задачи для компиляции less и jade файлов.

### Как выполнять ДЗ

1. Сделайте fork данного проекта
2. Клонируйте свой форк к себе локально, сделайте изменения, и сделайте git push в свой репозиторий (у себя в аккаунте), откуда вы его клонировали
3. На github сайте сделайте New pull request (кнопка на странице с вашим репозиторием) и отправьте свои изменения.

### Что необходимо сделать

Вам необходимо создать gulp задачу для компиляции SASS файлов в CSS.

1. Создайте задачу с именем scss которая будет компилировать scss файлы в css.
2. Закомментируйте задачу связанную с LESS в месте где она вызывается в dulp defult таске, и пропишите туда scss задачу которую вы создали.
3. Проследите чтобы добавить watcher который будет следить за scss файлами, и при их изменении запускать задачу scss.
