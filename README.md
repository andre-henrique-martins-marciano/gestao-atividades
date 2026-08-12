## Sistema de Gestão de Aluguéis

Plataforma web desenvolvida com **Python**, **Django** e **Bootstrap** para tornar a gestão de aluguéis mais simples, organizada e eficiente.

O sistema auxilia no gerenciamento completo de locações, permitindo o controle de:

-  Imóveis
-  Contratos
-  Inquilinos
-  Pagamentos
-  Vencimentos

Com uma interface intuitiva e moderna, o projeto facilita a administração de imóveis e automatiza processos importantes do dia a dia.

Além disso, o sistema utiliza banco de dados para persistência das informações, garantindo segurança e organização dos dados.

---

# Índice

- [ Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [ Funcionalidades](#-funcionalidades)
- [ Instalação](-instalação)
- [ Uso](-uso)
- [ Estrutura do Projeto](#-estrutura-do-projeto)
- [ Contribuição](#-contribuição)
- [ Licença](#-licença)
- [ Contato](#-contato)

---

# Tecnologias Utilizadas

- Python
- Django
- Bootstrap
- HTML5
- CSS3
- JavaScript
- SQLite3 / PostgreSQL

---

#  Funcionalidades

 Cadastro de imóveis  
 Cadastro de inquilinos  
 Gerenciamento de contratos  
 Controle de pagamentos  
 Controle de vencimentos  
 Interface responsiva  
 Painel administrativo  
 Organização centralizada das locações  
 Persistência de dados com banco de dados  
 Interface intuitiva e moderna  

---

# Preview do Sistema

```bash
Em breve...
```

---

# Instalação

Siga os passos abaixo para executar o projeto localmente:

## Clone o repositório

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
```

## Acesse a pasta do projeto

```bash
cd seu-repositorio
```

## Crie um ambiente virtual

```bash
python -m venv venv
```

## Ative o ambiente virtual

### Windows

```bash
venv\Scripts\activate
```

### Linux / Mac

```bash
source venv/bin/activate
```

##  Instale as dependências

```bash
pip install -r requirements.txt
```

##  Execute as migrações

```bash
python manage.py migrate
```

##  Inicie o servidor

```bash
python manage.py runserver
```

---

# Uso

O sistema oferece uma interface simples e eficiente para gerenciar imóveis, contratos e pagamentos.

Com ele é possível:

- Cadastrar imóveis
- Registrar inquilinos
- Gerenciar contratos
- Controlar pagamentos
- Acompanhar vencimentos
- Administrar informações através do painel do Django

---

# Painel Administrativo

Crie um superusuário:

```bash
python manage.py createsuperuser
```

Acesse:

```bash
http://127.0.0.1:8000/admin
```

---

# Estrutura do Projeto

```bash
 sistema-aluguel
 ┣  app
 ┣  templates
 ┣  static
 ┣  media
 ┣  manage.py
 ┣  requirements.txt
 ┗  README.md
```

---

# Objetivo do Projeto

O objetivo deste sistema é facilitar o gerenciamento de locações, reduzindo processos manuais e melhorando a organização das informações relacionadas aos imóveis e contratos.

---

# Contribuição

Sinta-se à vontade para contribuir com este projeto.

## Como contribuir

1. Faça um fork do projeto
2. Crie uma branch:

```bash
git checkout -b minha-feature
```

3. Faça suas alterações e commit:

```bash
git commit -m "Minha nova feature"
```

4. Faça o push:

```bash
git push origin minha-feature
```

5. Abra um Pull Request

---

## Autor

**André Henrique Martins Marciano**

LinkedIn: [https://www.linkedin.com/in/andre-h-martins-marciano/](https://www.linkedin.com/in/andre-h-martins-marciano/)

---

## Licença

MIT License

---

