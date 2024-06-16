# Проект команды Сера несанкционированная

## Установка на сервер

[1] Склонировать репозиторий и в папку с репозиторием скачать файл с нашей моделью по ссылке на [гугл диске](https://drive.google.com/file/d/1JmCZXjWZN7BEIytnFTzzmGsh0q9QTyeb/view?usp=sharing) , a также склонировать в эту же папку ComfyUI командой ```git clone https://github.com/comfyanonymous/ComfyUI.git```

[2] В папке репозитория выполнить ```cp ./gazprom_AK.ckpt ./ComfyUI/models/checkpoints/```

[3] Если не установлена cuda, ```sudo apt-get install nvidia-driver-535 nvidia-cuda-toolkit python3-venv```

[4] Создайте venv c помощью python (версия должна быть >= 10) ```python -m venv sera_env```

[5] ```source ./sera_env/bin/activate```

[6] ```pip install -r ./requirements_sera.txt```

[7] Можно запускать сервер: ```python ./ComfyUI/main.py --listen```


