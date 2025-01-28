# Hyperlane Validator Setup

## 🛠 Установка зависимостей

1. Обновление системы и базовых пакетов, установка python:

sudo apt-get update -y && sudo apt upgrade -y && sudo apt-get install make screen build-essential unzip lz4 gcc git jq python3-pip -y

3. Установка Docker и Docker Compose:
   
curl -sSL https://raw.githubusercontent.com/web3nodes/Dependencies/main/docker.sh | bash
