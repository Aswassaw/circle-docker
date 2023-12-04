# Tentang Repositori

Repositori ini berisi config docker khusus aplikasi web Circle untuk development.

## Development

- Clone repositori ini.
- Masuk ke direktori development.
- Jalankan command `docker compose create` di terminal atau cmd.
- **PostgreSQL** dapat diakses melalui port `5444`, dengan USER=postgres dan PASSWORD=aswassaw ( ubah pada file docker-compose.yaml ).
- **Redis** dapat diakses melalui port `6555`.
- **RabbitMQ** dapat diakses melalui port `7666`, dan port `14444` untuk mengakses **RabbitMQ Management** di browser.
- Sesuaikan .env project dengan semua informasi di atas dan jalankan dengan lancar.
