1. Собрать образ командой:

docker build . --tag=myapp

2. Запустить контейнер командой:

docker run -it -p 8000:8000 -d myapp