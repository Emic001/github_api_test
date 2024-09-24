1. Клонируйте репозиторий -
   bash
   git clone <URL_REPOSITORY>
cd github_api_test
2. Установите зависимости
   bash
   pip install -r requirements.txt
3.Создайте файл `.env` в корне проекта и добавьте в него ваши данные:
   GITHUB_USERNAME=свое имя
   GITHUB_TOKEN= свой токен
   REPO_NAME=test-repo
4. Установите зависимости с помощью `pip install -r requirements.txt
5. Запустите тест с помощью команды `python test_api.py`
