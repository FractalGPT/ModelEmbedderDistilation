# ModelEmbedderDistillation

## О проекте
`ModelEmbedderDistillation` - это проект, направленный на дистилляцию сложных моделей встраивания (например, Sbert, E5) для упрощения и повышения эффективности их использования в различных приложениях машинного обучения.

## Особенности

- **Дистилляция Sbert**: Процесс упрощения модели Sbert для оптимизации производительности без значительной потери точности.
- **Дистилляция Sbert с Декомпозицией Слоев**: Расширенный метод дистилляции, который включает в себя декомпозицию слоев модели для более глубокой оптимизации.
- **C# Версия на Базе AI Framework**: Реализация вышеупомянутых методов дистилляции в C#, с использованием AI Framework для легкой интеграции в .NET проекты.

## Начало работы

Для начала работы с `ModelEmbedderDistillation`, клонируйте репозиторий и следуйте инструкциям в разделе установки.



## Дорожная карта (SBert)

| Этап                                         | Задачи                           | Статус                |
| -------------------------------------------- | -------------------------------- | --------------------- |
| **Дистилляция Sbert**                        | Исследование методов дистилляции | 🟢 Завершена          |
| **Дистилляция с Декомпозицией Слоев**        | Разработка метода декомпозиции   | 🟢 Завершена       |
| **C# Версия на базе [AI Framework](https://github.com/AIFramework/AIFrameworkOpen)**           | Перенос алгоритмов в C#          | 🟢 Завершена         |
|                                              | Интеграция с AI Framework        | 🟢 Завершена         |
| **Оптимизация и Расширение**                 | Оптимизация производительности   | 🟡 В процессе          |
|                                              | Поддержка дополнительных моделей | 🟡 В процессе          |
| **Документация и Примеры**                   | Разработка документации          | 🟡 В процессе          |
|                                              | Создание примеров использования  | 🟡 В процессе          |


## Модели

* Дистиллированный SBERT [FractalGPT/SberDistil](https://huggingface.co/FractalGPT/SberDistil)
  * Запустить пример на Colab: <a target="_blank" href="https://colab.research.google.com/drive/1m3fyh632htPs9UiEu4_AkQfrUtjDqIQq?usp=sharing"> <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
  
* Дистиллированный SBERT с применением SVD разложения: [FractalGPT/SbertSVDDistil](https://huggingface.co/FractalGPT/SbertSVDDistil)
  * Запустить пример на Colab: <a target="_blank" href="https://colab.research.google.com/drive/1R9hHbEpyGEYO5Nw3p5VWTc-bny3PqiZs?hl"> <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
  
* Портированная модель для использования на C# [FractalGPT/SbertDistilAIFr](https://huggingface.co/FractalGPT/SbertDistilAIFr)

## Лицензия

* Этот проект распространяется под лицензией [Apache 2.0](https://github.com/FractalGPT/ModelEmbedderDistilation/blob/main/LICENSE). Подробности смотрите в файле LICENSE.
