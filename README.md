Сервис для посчёта слов Python на Web странице, использующий Flask, Celery, Redis, NSQD, PostgreSQL.

Шаги, необходимые для запуска:
1. Скопировать проект: git clone https://github.com/daftgrey/skillfactory-E8.git;
2. Перейти в папку с проектом: cd skillfactory-E8;
3. Собрать контейнеры: docker-compose build;
4. Сначало запустить контейнер Posgresql: docker-compose up postgres;
5. Все остальные: docker-compose up.

Сервис будет доступен по адресу http://0.0.0.0:5000
