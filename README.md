### How to run the project:

Clone the repository and open it in the command-line interface:

```
git clone https://github.com/yandex-praktikum/kittygram_backend.git
```

```
cd kittygram_backend
```

Create and activate a virtual environment:

```
python3 -m venv env
```

* If Linux/macOS

    ```
    source env/bin/activate
    ```

* If Windows

    ```
    source env/scripts/activate
    ```

```
python3 -m pip install --upgrade pip
```

Install the dependencies from the requirements.txt file

```
pip install -r requirements.txt
```

Run migrations:

```
python3 manage.py migrate
```

Run the project:

```
python3 manage.py runserver
```
