# Сборка веб проекта

> Здесь вы можете прочесть инструкцию по сборке веб проекта.

1. Для сборки вам сначала нужно установить Node.js вместе с npm. Также может потребоваться установка python 2.7.
2. Чтоб упрстить работу я написал наборы часто используемых команд и сохранил их в файлы с расширением .cmd .
Но вы и сами можете их запускать, только перед этим перейдите в папку проекта командой pushd.
3. И так, если вы первый раз собираете подобный проект на этом компьютере, то запустите 
``` 
setup.cmd
```
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
Эта команда компилятор c++ 2005 (нужен для некоторых компонентов), vue cli, http server.
4. Теперь вам нужно восстановить модули node.js. Запустите
```
restore_moduls.cmd
```
5. На єтом шаге вы можете начать разработку. Весь код находится в папках src и static, 
однако я рекомендую вам изменять только static\global_conf.js .
6. Для удобной отладки в режиме hotreload запустите 
```
dev.cmd
```
7. Сборка. Чтоб ссбрать веб проект запустите файл
```
build.cmd
```
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
или пропишите в командной это, чтоб увидеть результат.
```
pushd <путь в папку WebBase>
npm run build
```
8. Чтоб открыть собранный проект на другом устройстве из вашей сети - запустите сервер
```
run_httpserver.cmd
```
9. Собранный проект находится в папке dist. 

