# Notes App Queue Consumer

Proyek latihan message broker kelas [Belajar Fundamental Aplikasi Back-End](https://www.dicoding.com/academies/271) di [Dicoding Indonesia](https://www.dicoding.com).

## Mengonfigurasi Environment

File `.env` (development):

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

## Menjalankan di local

```bash
$ git clone https://github.com/satriows25/dicoding-notes-app-queue-consumer.git
$ cd dicoding-notes-app-queue-consumer
$ npm install
$ npm run start-dev
```
