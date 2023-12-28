# Projeto da disciplina UPX5, do curso de Análise e Desenvolvimento de Sistemas (Newton Paiva)

# Guia para Executar o Aplicativo Python

## Pré-requisitos
Antes de começar, certifique-se de que o ambiente de desenvolvimento tenha os seguintes pré-requisitos instalados:

1. **Python**: [Baixe e instale o Python](https://www.python.org/downloads/).

2. **Git**: [Instale o Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

## Clonando o Repositório
1. Abra um terminal ou prompt de comando.

2. Navegue até o diretório onde você deseja clonar o repositório usando o comando `cd`.

3. Execute o seguinte comando para clonar o repositório:
    ```bash
    git clone https://github.com/seu-usuario/seu-repositorio.git
    ```

## Configurando o Ambiente Virtual (Opcional, mas recomendado)
1. Navegue até o diretório do projeto:
    ```bash
    cd seu-repositorio
    ```

2. Crie um ambiente virtual:
    ```bash
    python -m venv venv
    ```

3. Ative o ambiente virtual:
    - No Windows:
        ```bash
        .\venv\Scripts\activate
        ```
    - No Linux/Mac:
        ```bash
        source venv/bin/activate
        ```

## Instalando Dependências
1. Certifique-se de estar no diretório do projeto.

2. Instale as dependências usando o seguinte comando:
    ```bash
    pip install -r requirements.txt
    ```

## Executando o Aplicativo
1. Certifique-se de estar no diretório do projeto.

2. Execute o aplicativo Python:
    ```bash
    python app.py
    ```

3. Abra o navegador e acesse `http://localhost:5000` para visualizar o aplicativo.

## Desativando o Ambiente Virtual (Opcional)
Quando terminar de usar o aplicativo, você pode desativar o ambiente virtual:
```bash
deactivate
