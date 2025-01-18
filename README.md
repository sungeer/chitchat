# pulasan
This project is built on the Quart framework and can be considered a comprehensive backend project template. The main advantage is that it can be conveniently used directly for other new projects.


# Pulasan

*A async backend scaffold based on Quart.*

> When it comes to the choice of an asynchronous framework, I would highly recommend Starlette. You might want to take a look at the scaffolding, which encompasses the best practices for Python asynchronous back-end development: *[viper](https://github.com/sungeer/pulasan)*.

## Installation

clone:
```
$ git clone https://github.com/sungeer/pulasan.git
$ cd pulasan
```
create & activate virtual env then install dependency:

with venv + pip:
```
$ python -m venv venv
$ source venv/bin/activate  # use `venv\Scripts\activate` on Windows
$ pip install -r requirements.txt
```

run:
```
$ uvicorn pulasan:app
* Running on http://127.0.0.1:8000/
```

## License

This project is licensed under the MIT License (see the
[LICENSE](LICENSE) file for details).
