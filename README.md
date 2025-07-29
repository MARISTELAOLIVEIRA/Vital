# Vital

Sistema de Gerenciamento de Exames Médicos

![Logo Vital](static/geral/img/logo.png)

### Tela Inicial
![Tela Inicial](static/geral/img/tela1.png)

## Sobre o Projeto

O **Vital** é uma plataforma web para gerenciamento de exames médicos, permitindo que clínicas, laboratórios e pacientes possam solicitar, acompanhar e acessar resultados de exames de forma simples e segura.

## Funcionalidades

- Solicitação de exames por pacientes
- Upload e gerenciamento de resultados em PDF
- Controle de acesso por senha para exames sensíveis
- Geração de links de acesso temporário para médicos
- Visualização de exames por tipo (sangue, imagem, etc)
- Cadastro e autenticação de usuários
- Interface administrativa para gestão de clientes e exames

## Tecnologias Utilizadas

- Python 3
- Django
- SQLite3
- Bootstrap 5
- PDF.js (visualização de PDFs)
- HTML5, CSS3, JavaScript

## Estrutura do Projeto

```
empresarial/
exames/
usuarios/
vital/
templates/
static/
manage.py
db.sqlite3
```

## Como rodar o projeto

1. Clone o repositório:
    ```sh
    git clone https://github.com/seu-usuario/vital.git
    cd vital
    ```

2. Instale as dependências:
    ```sh
    pip install -r requirements.txt
    ```

3. Execute as migrações:
    ```sh
    python manage.py migrate
    ```

4. Inicie o servidor:
    ```sh
    python manage.py runserver
    ```

5. Acesse em [http://localhost:8000](http://localhost:8000)

## Telas do Sistema

> Adicione aqui prints das principais telas do sistema para ilustrar as funcionalidades.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

## Licença

Este projeto está sob a licença MIT.

---

Desenvolvido com 💙 por [Seu Nome ou Equipe]