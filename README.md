# Final-Project-Digital-Skola

# Final Project: Cloud Full-Stack Deployment

## Deskripsi
Repositori ini berisi implementasi pipeline CI/CD dan deployment aplikasi portofolio ke Google Cloud Platform.

## Arsitektur & Teknologi
* Frontend: Node.js/Next.js
* Container: Docker
* CI/CD: GitHub Actions
* Deployment: GCP Cloud Run
* Monitoring: Google Cloud Operations (Monitoring & Logging)

## Tautan Penting
* Aplikasi Live: https://hello-minipro-2-587984343301.asia-southeast2.run.app
* CI/CD Pipeline: https://github.com/bayusp28/Final-Project-Digital-Skola/blob/main/.github/deploy.yml

## Fitur Proyek
1. CI/CD Otomatis: Pipeline berjalan saat ada *push* ke branch main.
2. Keamanan: Kredensial GCP diamankan dengan GitHub Secrets.
3. Scaling: Layanan mampu melakukan *autoscaling* melalui Cloud Run.
4. Monitoring: Log dan metrik tervisualisasi dalam dashboard khusus GCP.
