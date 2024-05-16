# DESAFIO JEITTO - FastAPI  ![image](https://github.com/patyb783/PROJETO_PYTHON_JEITTO/assets/113445914/45cb641b-a615-4b94-900c-ba701db4b256)
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/patyb783/PROJETO_PYTHON_JEITTO/blob/Desafio_Jeitto/LICENSE) 

# Proposta do projeto Jeitto FastAPI

O Jeitto é um desafio que faz parte de um processo seletivo no qual foi solicitado 3 desafios para testar o conhecimento na linguagem Python. A proposta do projeto foi criar uma aplicação simples para gerenciar informações de clientes.
O projeto basea-se na criação de uma FastApi CRUD que roda com o Banco de Dados Sqlite3 e possui apenas uma tabela com as seguintes colunas:
 
* ID
* NOME
* EMAIL
* TELEFONE




## Funcionalidades

- Criação, edição e exclusão de clientes
- Testes Unitários com cobertura documentado [.venv\app\testes\.pytest_cache\README.md]
  
## Instalação

Para usar o pojeto Jeitto FastAPI, siga estas etapas:

1. Clone este repositório para o seu computador:

```bash
git clone https://github.com/seu-usuario/jeitto.git
```

2. Ative o ambiente virtual e Instale as dependências do projeto:

Sistemas Windows utilize o comando

```bash
.env\Scripts\activate
```

Sistemas Unix/Linux/macOS  utilize o comando

```bash
source .env/bin/activate
```
- DEPENDÊNCIAS

Instalando as dependências usando o arquivo

```bash
pip install -r requirements.txt
```

```bash
pip install fastapi
```

```bash
pip install uvicorn
```

```bash
pip install sqlalchemy
```

3. Inicie o aplicativo:

    - Para subir a aplicação navegue até a pasta que está o app e digite o comando abaixo
```bash
   uvicorn main:app --reload
```

4. Acesse o aplicativo no seu navegador em `http://localhost:8000`.
5. Documentação Swagger e funcionalidades da API - http://127.0.0.1:8000/docs#/
6. Testes executados com Postman

![image](https://github.com/patyb783/PROJETO_PYTHON_JEITTO/assets/113445914/856d6d68-29ad-4d6e-88e1-474fc302be6e)



## Contribuições

Contribuições são bem-vindas! Se você quiser contribuir para o projeto, por favor siga estas etapas:

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`)
3. Faça commit de suas mudanças (`git commit -am 'Adicionando uma nova feature'`)
4. Faça push para a branch (`git push origin feature/nova-feature`)
5. Crie um novo Pull Request

## Licença

Este projeto está licenciado sob a [![NPM](https://img.shields.io/npm/l/react)](https://github.com/patyb783/PROJETO_PYTHON_JEITTO/blob/Desafio_Jeitto/LICENSE) .
