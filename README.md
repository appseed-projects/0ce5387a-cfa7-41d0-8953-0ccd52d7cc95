# Flask/jinja Material Kit 

`Open-Source` seed project generated by AppSeed in **Flask** Framework on top of **[Material Kit](https://appseed.us/generator/material-kit/)** design. Designed for those who like bold elements and beautiful websites, **Material Kit 2** is ready to help you create stunning websites and web apps. `Material Kit 2` is built with over 60 frontend individual elements, like buttons, inputs, navbars, nav tabs, cards, or alerts, giving you the freedom of choosing and combining.

<br />

> Context:

- Built with [Material Kit Generator](https://appseed.us/generator/material-kit/)
- Timestamp: `2022-05-18 21:52`
- Build ID: `0ce5387a-cfa7-41d0-8953-0ccd52d7cc95`
- **Free [Support](https://appseed.us/support/)** (registered users) via `Email` and `Discord`

<br />

> Features

- `Up-to-date dependencies`
- Render Engine: Flask / [Jinja2](https://jinja.palletsprojects.com/)

<br />

![Material Kit - Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/167396765-c88b7a95-155f-4236-8691-7b80fa2d9cd9.png)

<br />


## ✨ Start the app in Docker

> **Step 1** - Download the code from the GH repository (using `GIT`) 

```bash
$ # Get the code
$ git clone https://github.com/appseed-projects/<YOUR_BUILD_ID>.git
$ cd <YOUR_BUILD_ID>
```

> **Step 2** - Edit `.env` and set `DEBUG=True`. This will activate the `SQLite` persistance. 

```txt
DEBUG=True
```

<br />

> **Step 3** - Start the APP in `Docker`

```bash
$ docker-compose up --build 
```

Visit `http://localhost:85` in your browser. The app should be up & running.

<br />


## ✨ How to use it

> Download the code 

```bash
$ # Get the code
$ git clone https://github.com/appseed-projects/0ce5387a-cfa7-41d0-8953-0ccd52d7cc95.git
$ cd 0ce5387a-cfa7-41d0-8953-0ccd52d7cc95
```

<br />

### 👉 Set Up for `Unix`, `MacOS` 

> Install modules via `VENV`  

```bash
$ virtualenv env
$ source env/bin/activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Flask Environment

```bash
$ export FLASK_APP=run.py
$ export FLASK_ENV=development
```

<br />

> Start the app

```bash
$ flask run
```

At this point, the app runs at `http://127.0.0.1:5000/`. 

<br />

### 👉 Set Up for `Windows` 

> Install modules via `VENV` (windows) 

```
$ virtualenv env
$ .\env\Scripts\activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Flask Environment

```bash
$ # CMD 
$ set FLASK_APP=run.py
$ set FLASK_ENV=development
$
$ # Powershell
$ $env:FLASK_APP = ".\run.py"
$ $env:FLASK_ENV = "development"
```

<br />

> Start the app

```bash
$ flask run
```

At this point, the app runs at `http://127.0.0.1:5000/`. 

<br />

## ✨ Code-base structure

The project has a simple, intuitive structure presented bellow:

```bash
< PROJECT ROOT >
   |
   |-- apps/__init__.py
   |-- apps/
   |    |-- static/
   |    |    |-- <css, JS, images>         # CSS files, Javascripts files
   |    |
   |    |-- templates/
   |         |
   |         |-- includes/                 # Page chunks, components
   |         |    |
   |         |    |-- navigation.html      # Top bar
   |         |    |-- sidebar.html         # Left sidebar
   |         |    |-- scripts.html         # JS scripts common to all pages
   |         |    |-- footer.html          # The common footer
   |         |
   |         |-- layouts/                  # App Layouts (the master pages)
   |         |    |
   |         |    |-- base.html            # Used by common pages like index, UI
   |         |    |-- base-fullscreen.html # Used by auth pages (login, register)
   |         |
   |      index.html                       # The default page
   |      page-404.html                    # Error 404 page (page not found)
   |      page-500.html                    # Error 500 page (server error)
   |         *.html                        # All other pages provided by the UI Kit
   |
   |-- requirements.txt
   |
   |-- run.py
   |
   |-- ************************************************************************
```

<br />

## ✨ PRO Version

> For more components, pages and priority on support, feel free to take a look at this amazing starter:

**Material Kit 2** is a premium design crafted by the `Creative-Tim` agency on top of Bootstrap 5 Framework. Designed for those who like bold elements and beautiful websites, Material Kit 2 is made of hundreds of elements, designed blocks, and fully coded pages built with an impressive level of quality.

- 👉 [Flask Material Kit2 PRO](https://appseed.us/product/material-kit2-pro/flask/) - product page
- 👉 [Flask Material Kit2 PRO](https://flask-material-kit2-pro.appseed-srv1.com/) - LIVE Demo

<br >

![Mk2 PRO - Premium Seed project by AppSeed.](https://user-images.githubusercontent.com/51070104/168224733-b054bb46-d454-4aea-bb94-2d01bf4760d2.png)

<br />

---
Flask/Jinja Material Kit - Open-source starter generated by **[AppSeed Generator](https://appseed.us/generator/)**.
