install:
	@echo "Installing dependencies..."
	pip install --upgrade pip &&\
		pip install -r requirements.txt
format:
	@echo "Formatting code..."
	black *.py mylib/*.py
lint:
	@echo "Linting..."
	#pylint --disable=R,C *.py mylib/*.py
test:
	@echo "Running tests..."
	#python -m pytest -vv --cov=mylib --cov=main test_*.py
