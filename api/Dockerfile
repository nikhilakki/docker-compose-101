FROM python:3.8-alpine
COPY api /app
# gcc for libuv used by uvicorn server
RUN apk add gcc 
WORKDIR /app
RUN pip install fastapi uvicorn
