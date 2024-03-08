# Fastapi_helloworld

use master branch

## use this startup command in azure app service
gunicorn -w 1 -k uvicorn.workers.UvicornWorker -b 0.0.0.0:8000 app:app
