# About

# How to run
First create a virtual environment. I am using python3.12:
```shell
python -m venv venv
```
After activating it, install the dependencies:
```shell
pip install -r requirements.txt
```

To run the application do:
```shell
uvicorn main:app --reload
```
> NOTE: It can handle hot reloading of new code

Now you can open two browser tabs with http://localhost:8000 and start playing with the both chats.
