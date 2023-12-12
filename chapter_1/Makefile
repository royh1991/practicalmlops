install:
	pip install --upgrade pip &&\
	pip install -r requirements.txt
lint:
	pylint --disable=R,C hello.py
test:
	python -m pytest --cov=hello hello_test.py