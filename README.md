# Проект React с TypeScript, Vite и Docker

Этот проект представляет собой шаблон для быстрого старта разработки React-приложения с использованием TypeScript, Vite и Docker.

## Технологии

- [React](https://reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Vite](https://vitejs.dev/)
- [Docker](https://www.docker.com/) 


## Запуск проекта локально

1. Клонируйте репозиторий:

   ```bash
   git clone https://github.com/your-username/your-react-ts-vite-docker.git

2. Перейдите в каталог проекта:

    ```bash
    cd your-react-ts-vite-docker

3. Установите зависимости:

    ```bash
    npm i

4. Запустите приложение локально:

    ```bash
    npm run dev

## Запуск проекта с использованием Docker

1. Соберите Docker-образ:

    ```bash
    docker build -t react-ts-vite-docker .

2. Запустите контейнер:

    ```bash
    docker run -p 3000:3000 -d react-ts-vite-docker

### Приложение будет доступно по адресу http://localhost:3000.

