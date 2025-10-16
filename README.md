# Nenets Language Processing

A collection of Jupyter notebooks for Nenets language processing: creating a word frequency dictionary, training GPT-2 on Nenets, developing a simple verb lemmatization algorithm, and building a neural machine translation model using Keras.

## 📂 Repository Structure
- `notebooks/frequency_dictionary.ipynb` — Parsing data from various sources in the Forest Nenets language and creating a word frequency dictionary
- `notebooks/Implementation of GPT-2 & Training Language Model in Nenets Language.ipynb` — Fine-tuning GPT-2 on Nenets language
- `notebooks/lemmatization_algorithm.ipynb` — Developing a simple verb lemmatization algorithm for Nenets
- `notebooks/parsing_nvinder.ipynb` — Parsing data from the *Nyaryana Vynder* newspaper
- `notebooks/multilingual_dataset_extension.ipynb` — Multilingual dataset extension for English, French, Finnish, and Hungarian languages
- `notebooks/neural_translation_model.ipynb` — Neural machine translation model using Keras
- `notebooks/data/input/` — Raw datasets
- `notebooks/data/output/` — Processed datasets
- `requirements.txt` — Dependencies

## 📊 Data Sources
- Newspaper [*Nyaryana Vynder*](https://nvinder.ru/)
- Collection of Nenets fairy tales *Ненецие” лаханако”* (N.M. Yangasova)
- [Community](https://vk.com/nn.yanao) of the socio-political national newspaper of the Yamalo-Nenets Autonomous Okrug *Nyaryana Ngerm* on the social network VKontakte
- [Community](https://vk.com/club173849556) of the socio-political national newspaper of the Yamalo-Nenets Autonomous Okrug *Nyaryana Ngerm* for speakers of the Forest Nenets dialect on the social network VKontakte
- [Page](http://www.yamalexpedition.ru/nen/blog-nen) of diary entries in the Forest Nenets language on the website of the ethnographic expedition *Real People*
- [Page](http://www.yamalexpedition.ru/nen/education-for-nomads-nen) about nomadic education on the website of the ethnographic expedition *Real People*

## 🛠 Technologies Used
- Python (pandas, NumPy, scikit-learn)
- TensorFlow
- Hugging Face Transformers

## 📜 License
MIT License

# Обработка ненецкого языка

Сборник Jupyter-ноутбуков для обработки ненецкого языка: составление 
частотного словаря слов, обучение GPT-2 на ненецком языке, разработка простого 
алгоритма лемматизации глаголов и создание модели нейронного машинного перевода с использованием Keras.

## 📂 Структура репозитория
- `notebooks/frequency_dictionary.ipynb` — Парсинг данных из различных 
  источников на лесном ненецком языке и составление частотного словаря слов
- `notebooks/Implementation of GPT-2 & Training Language Model in Nenets Language.ipynb` — Тонкая настройка GPT-2 на ненецком языке
- `notebooks/lemmatization_algorithm.ipynb` — Разработка простого алгоритма 
  лемматизации ненецких глаголов
- `notebooks/parsing_nvinder.ipynb` — Парсинг данных из газеты *Nyaryana 
  Vynder*
- `notebooks/multilingual_dataset_extension.ipynb` — Мультиязычное расширение 
  датасета на английский, французский, финский и венгерский языки
- `notebooks/neural_translation_model.ipynb` — Модель нейронного машинного перевода с использованием Keras
- `notebooks/data/input/` — Исходные датасеты
- `notebooks/data/output/` — Обработанные датасеты
- `requirements.txt` — Зависимости

## 📊 Источники данных
- Газета [*Nyaryana Vynder*](https://nvinder.ru/)
- Сборник ненецких сказок *Ненецие” лаханако”* (Н.М. Янгасова)
- [Сообщество](https://vk.com/nn.yanao) общественно-политической 
  национальной газеты Ямало-Ненецкого автономного округа *Няръяна Нгэрм* в 
  социальной сети ВКонтакте
- [Сообщество](https://vk.com/club173849556) общественно-политической 
  национальной газеты Ямало-Ненецкого автономного округа *Няръяна Нгэрм* для носителей лесного диалекта ненецкого языка в социальной сети ВКонтакте
- [Страница](http://www.yamalexpedition.ru/nen/blog-nen) дневниковых 
  записей на лесном ненецком языке на сайте этнографической экспедиции 
  *Настоящие люди*
- [Страница](http://www.yamalexpedition.ru/nen/education-for-nomads-nen) на тему кочевого образования на сайте этнографической экспедиции *Настоящие люди*

## 🛠 Используемые технологии
- Python (pandas, NumPy, scikit-learn)
- TensorFlow
- Hugging Face Transformers

## 📜 Лицензия
MIT License

## 📚 Citation

If you use this repository in your research or publications, please cite it as follows:

```bibtex
@software{pavel_shnyakov_2025_17369083,
  author       = {Pavel Shnyakov},
  title        = {shnyakov/nenets: Initial Release – Nenets Language Processing},
  month        = oct,
  year         = 2025,
  publisher    = {Zenodo},
  version      = {v1.0.0},
  doi          = {10.5281/zenodo.17369083},
  url          = {https://doi.org/10.5281/zenodo.17369083}
}
