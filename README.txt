Установка:
1. (рекомендуется) создать отдельное виртуальное окружение
2. pip3 install torch==1.8.2+cu111 torchvision==0.9.2+cu111 torchaudio==0.8.2 -f https://download.pytorch.org/whl/lts/1.8/torch_lts.html
3. python -m pip install detectron2 -f   https://dl.fbaipublicfiles.com/detectron2/wheels/cu111/torch1.8/index.html
4. pip install -r requirements.txt
5. В папке проекта создайте папку detectron_output. Можно положить туда готовые веса для модели - тогда ее можно будет не обучать с нуля: https://drive.google.com/file/d/1kcUSylC1AzQ5fx6wk2Fpb_d_Pz8qkPe1/view?usp=sharing