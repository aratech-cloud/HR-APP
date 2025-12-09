# Human Resource Application

With Laravel, MySQL & Mazer Admin Template

## 🚀 Cara Menjalankan di localhost

```bash
git https://github.com/aratech-cloud/point-of-sales.git
cd point-of-sales
cp .env.example .env
composer install && npm install
php artisan key:generate
php artisan migrate --seed
npm run dev
php artisan serve
```

## 🚀 Deploy to Cloudpanel

### 1. Download source code

Download source code ini dan upload file `.zip` nya ke site Cloudpanel:

### 2. SSH ke server

Buka cmd atau powershell dan jalankan perintah berikut:

```bash
ssh user-site@ip_server
```

### 3. Install Dependencies

```bash
composer install
```

### 4. Setup Environment

```bash
php artisan key:generate
```

### 5. Jalankan Migration dan Seeder

```bash
php artisan migrate
php artisan db:seed
```

### 6. Install Node js

```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.2/install.sh | bash
source ~/.bashrc
nvm install 20
nvm use 20
node -v
```

### 7. Install packages dan build

```bash
npm install
npm run build
```
