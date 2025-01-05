# Atualização de Bilheterias com Base na Inflação

Este projeto foi desenvolvido para obter dados de bilheterias por meio de uma API, realizar uma raspagem de dados para coletar informações sobre a inflação e, em seguida, atualizar os valores das bilheterias ajustando-os de acordo com a inflação.  

## Funcionalidades

- Requisição de dados de bilheterias por meio de uma API.
- Raspagem de dados para obter valores de inflação.
- Atualização dos valores de bilheterias considerando a inflação.
- Uso de bibliotecas e ferramentas populares como **Pandas**, **Requests** e **Selenium**.

## Tecnologias Utilizadas

- **Python 3.9+**
- **Pandas**: Para manipulação e análise dos dados.
- **Requests**: Para realizar requisições HTTP e acessar os dados da API.
- **Selenium**: Para automação de navegação na web e raspagem de dados.
- **Modulo_Senha**: Para gerenciar senhas de acesso às APIs ou sites protegidos.

## Pré-requisitos

Antes de executar o projeto, certifique-se de ter os seguintes requisitos instalados:

1. **Python** (versão 3.9 ou superior)
2. **Bibliotecas necessárias**: Instale as dependências utilizando o comando:
   ```bash
   pip install pandas requests selenium
   ```
3. **Driver Web do Selenium**: Baixe e configure o driver correspondente ao navegador utilizado (como ChromeDriver para o Google Chrome).

## Como Executar

1. Clone este repositório em sua máquina local:
   ```bash
   git clone https://github.com/EvertonSFTeixeira/API.git
   cd API.git
   ```

2. Execute o script principal:
   ```bash
   python main.py
   ```

3. O script irá:
   - Fazer a requisição à API para obter os dados de bilheterias.
   - Navegar em um site de inflação usando Selenium e coletar os dados necessários.
   - Ajustar os valores das bilheterias com base nos índices de inflação obtidos.

## Estrutura do Projeto

- `main.py`: Script principal que orquestra o fluxo do projeto.
- `Modulo_Senha.py`: Gerencia as senhas e credenciais para acessar a API ou sites protegidos.
- `requirements.txt`: Lista de dependências do projeto.


## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

Se precisar de ajustes ou preferir outro estilo, é só avisar! 😊
