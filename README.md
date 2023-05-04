# Notes App Queue Consumer

The Notes App Queue Consumer is a practice project for the [Belajar Fundamental Aplikasi Back-End](https://www.dicoding.com/academies/271) class in [Dicoding Indonesia](https://www.dicoding.com). It is a message broker project that consumes messages from the RabbitMQ queue.

This project is designed to complement the [Notes App Back-End](https://github.com/satriows25/dicoding-notes-app-backend) project, which uses RabbitMQ as a message broker for exporting notes. The Notes App Queue Consumer project consumes messages from the RabbitMQ queue and performs the necessary actions based on the message content.

Through this project, students in the [Belajar Fundamental Aplikasi Back-End](https://www.dicoding.com/academies/271) class can practice their skills in message broker development, particularly in consuming messages from queues and performing the necessary actions based on the message content.

## Configuring the Environment

`.env` file (development):

```
# node-postgres configuration
PGUSER=
PGHOST=localhost
PGPASSWORD=
PGDATABASE=notesapp
PGPORT=5432

# nodemailer SMTP authentication
SMTP_HOST=smtp.mailtrap.io
SMTP_PORT=2525
SMTP_USER=
SMTP_PASSWORD=

# Message broker
RABBITMQ_SERVER=amqp://localhost
```

## Running Locally

```bash
$ git clone https://github.com/satriows25/dicoding-notes-app-queue-consumer.git
$ cd dicoding-notes-app-queue-consumer
$ npm install
$ npm run start-dev
```
