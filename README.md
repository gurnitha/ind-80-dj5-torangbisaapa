# ind-80-dj5-torangbisaapa
Membuat aplikasi untuk memamerkan hasil karya menggunakan Django versi 5


## 1. REMOTE REPOSITORI

#### 1. Membuat dan mengklon remote repositori


## 2. MENGKLON STARTER PROYEK HALO DUNIA

#### 1. Mengklon dan memodifikasi starter proyek

        new file:   .env.example
        modified:   README.md
        new file:   app/main/__init__.py
        new file:   app/main/admin.py
        new file:   app/main/apps.py
        new file:   app/main/migrations/__init__.py
        new file:   app/main/models.py
        new file:   app/main/tests.py
        new file:   app/main/views.py
        new file:   config/__init__.py
        new file:   config/asgi.py
        new file:   config/settings.py
        new file:   config/urls.py
        new file:   config/wsgi.py
        new file:   manage.py
        new file:   requirements.txt

#### 2. Membuat lingkungan virtual

	λ python -m venv venv312512
	λ ls
	src/  venv312512/

        modified:   README.md

#### 3. Menginstal requirements

        (venv312512) λ pip install -r requirements.txt

#### 4. Mensetup environ variable pada file .env

        DEBUG=True
        SECRET_KEY=django-insecure-%5hrvtl+3hx7&6@-bfgr^ry$z(%liuh6(tet8brhr7n)=3w75c
        DATABASE_NAME=ind_80_dj5_torangbisaapa
        DATABASE_USER=postgres
        DATABASE_PASSWORD=postgres
        DATABASE_HOST=localhost
        DATABASE_PORT=5432