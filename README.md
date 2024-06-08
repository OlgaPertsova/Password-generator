# Password Generator

Учебное приложение с функцией генерации паролей разной сложности: от 6 до 12 символов, с использованием цифр, специальных символов и заглавных букв.

## Quickstart

Run the following commands to bootstrap your environment:

    sudo apt-get install -y git python-venv python-pip
    git clone https://github.com/OlgaPertsova/Password-generator.git
    cd password-generator

    python -m venv venv
    source venv/bin/activate
    pip install -r requirements.txt

    cp .env

Run the app locally:
    
    python manage.py runserver

Run the app docker:

    git clone https://github.com/OlgaPertsova/Password-generator.git
    cd password-generator
    docker build . --tag docker-pass-generator
    docker run image_id/image_tag
