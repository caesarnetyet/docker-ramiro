#Docker image
#Para construir la imagen seria docker build -t mongoramiro .

FROM mongo:latest

# Install ping
RUN apt-get update && apt-get install -y \
  iputils-ping \
  && rm -rf /var/lib/apt/lists/*

ENV MONGO_INITDB_ROOT_USERNAME=root
ENV MONGO_INITDB_ROOT_PASSWORD=orimar