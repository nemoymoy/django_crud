##Создать образ командой:
```commandline
docker image build . --tag=[IMAGE_NAME]
```

##Запуска контейнера из образа:
```commandline
docker run -d -p 8000:8000 [IMAGE_NAME]
```

