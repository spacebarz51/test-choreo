FROM ubuntu:20.04  # Switch to an older but stable version
WORKDIR /app
COPY . .
RUN apt update && apt install -y php-cli
CMD ["php", "-S", "0.0.0.0:8000", "index.php"]
