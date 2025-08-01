# Notes App API Queue Consumer

Queue consumer for Notes App API V3. The message producer can be found [here](https://github.com/Realitaa/notes-app-back-end).

## Prerequisite

1. Modern NodeJS (Personally using v23.4).
2. RabbitMQ.
3. SMTP server such as `Mailtrap`.

## Installation

1. Install Dependencies

    ```sh
    npm install
    ```

2. Copy and paste `.env.example` to `.env`

    ```sh
    cp .env.example .env
    ```

3. Change _environtment variable_ for your local in `.env`.

4. Run consumer

    ```sh
    npm run start
    ```

    Running in *development* mode using `dev` suffix.

    ```sh
    npm run start:dev
    ```

5. Cosumer is running:

    ```sh
    Consumer is running, waiting for messages in the "${queueName}" queue...
    ```