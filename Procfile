install:
	# Install requirements 
	pip install --upgrade pip &&\
		pip install -r requirements.txt
dev:
	# Start server
	fastapi dev ./app/main.py   
web: uvicorn main:app --host=0.0.0.0 --port=${PORT:-5000}
