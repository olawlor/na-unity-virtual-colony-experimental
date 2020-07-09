all: lint server

server:
	google-chrome http://0.0.0.0:8000/
	python3 -m http.server 


lint:
	find . -name "*.json" -print -exec jsonlint -q '{}' ';'

lint-setup:
	npm install -g jsonlint



