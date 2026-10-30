# DL course for HSE KNAD

Репозиторий с материалами для курса Deep Learning / Глубинное Обучение на КНАД, 2026.

## Course Topics

1. Week 1: MLP, chain-rule. Intro to torch. Context: [lecture](/week01/lecture1_mlp.html), [seminar](/week01/sem01_pytorch_intro.ipynb)
2. Week 2: Функции потерь, Dropout, Batch Normalization. Полный training loop + введение трекера экспериментов (конфиги, seeds, воспроизводимость). Context: lecture, seminar
3. Week 3: Оптимизация нейронных сетей + практика обучения (schedulers, warmup, AMP, grad clipping / accumulation)
4. Week4: Операция свертки, виды сверток. Context: [lecture](/week04/lecture.html), [seminar](/week04/week01/sem01_pytorch_intro.ipynb)
5. Week5: Сверточные архитектуры (UNet, ResNet, AlexNet)
6. Week6: Задачи компьютерного зрения: сегментация, детекция, классификация
7. Week7: Последовательности I: RNN / LSTM / GRU: BPTT etc
8. Week8: Последовательности II: звук — спектрограммы, 1D-свертки vs RNN, CTC (ASR обзорно), связь с временными рядами (WaveNet / TCN)
9. Week9: Эмбеддинги и токенизация как общий принцип (текст, аудио-токены, категориальные признаки) + attention как идея
10. Week10: Архитектура трансформера (и работа с любыми последовательностями), немного про BERT
11. Week11: Vision Transformer + transfer learning 
12. Week12: GAN + соревновательные атаки
13. Week13: Разные модальности: мультимодальные модели и их обучение
14. Week 14: Индустриальный интенсив: узкие места пайплайна (data loading vs compute vs communication), карта distributed-подходов (DP → DDP → FSDP/ZeRO обзорно). + Мини-лекция: latency vs throughput, зачем отдельный inference-сервер и на чем вообще сервить.


## Assignments

Подробности по проекту и темы можно найти тут: [project.md](/project.md)

## Authors:

* [Gleb Panin](https://t.me/GotliebPt)
* [Daria Andreeva](https://t.me/Xufana)
* [Anastasia Izyumova](https://t.me/starminalush)
