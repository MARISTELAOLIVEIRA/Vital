# Vital

Sistema de Gerenciamento de Exames Médicos

### Tela Inicial
![Captura](https://raw.githubusercontent.com/MARISTELAOLIVEIRA/Vital/main/templates/static/img/Captura.png)

## Sobre o Projeto

O **Vital** é uma plataforma web para gerenciamento de exames médicos, permitindo que clínicas, laboratórios e pacientes possam solicitar, acompanhar e acessar resultados de exames de forma simples e segura.

## Funcionalidades

- ✅ Solicitação de exames por pacientes
- ✅ Upload e gerenciamento de resultados em PDF
- ✅ Controle de acesso por senha para exames sensíveis
- ✅ Geração de links de acesso temporário para médicos
- ✅ Visualização de exames por tipo (sangue, imagem, etc)
- ✅ Cadastro e autenticação de usuários
- ✅ Interface administrativa para gestão de clientes e exames

## Tecnologias Utilizadas
- ![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
- ![Django](https://img.shields.io/badge/Django-4.x-green?logo=django&logoColor=white)
- ![SQLite3](https://img.shields.io/badge/SQLite3-3.x-lightgrey?logo=sqlite&logoColor=blue)
- ![Bootstrap](https://img.shields.io/badge/Bootstrap-5.x-purple?logo=bootstrap&logoColor=white)
- ![PDF.js](https://img.shields.io/badge/PDF.js-2.x-orange?logo=adobeacrobatreader&logoColor=white) (visualização de PDFs)
- ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
- ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
- ![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow?logo=javascript&logoColor=white)

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
![Captura2](https://raw.githubusercontent.com/MARISTELAOLIVEIRA/Vital/main/templates/static/img/Captura2.png)
![Captura3](https://raw.githubusercontent.com/MARISTELAOLIVEIRA/Vital/main/templates/static/img/Captura3.png)
![Captura4](https://raw.githubusercontent.com/MARISTELAOLIVEIRA/Vital/main/templates/static/img/Captura4.png)
![Captura5](https://raw.githubusercontent.com/MARISTELAOLIVEIRA/Vital/main/templates/static/img/Captura5.png)
![Captura6](https://raw.githubusercontent.com/MARISTELAOLIVEIRA/Vital/main/templates/static/img/Captura6.png)
![Captura7](https://raw.githubusercontent.com/MARISTELAOLIVEIRA/Vital/main/templates/static/img/Captura7.png)
![Captura8](https://raw.githubusercontent.com/MARISTELAOLIVEIRA/Vital/main/templates/static/img/Captura8.png)


## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

## Licença

Este projeto está sob a licença MIT.

---

Desenvolvido com 💙 por Maristela
