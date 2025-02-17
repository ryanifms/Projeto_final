# Projeto_final

**financiaAi** é um projeto para facilitar o acesso a informações financeiras e ajudar os usuários a gerenciar suas finanças pessoais.

## Índice

- [Descrição](#descrição)
- [Instalação](#instalação)
- [Uso](#uso)
- [Contribuição](#contribuição)
- [Licença](#licença)
- [Contato](#contato)

## Descrição

O **financiaAi** é uma ferramenta que permite aos usuários:
- Gerenciar seus gastos diários.
- Planejar orçamentos.
- Monitorar investimentos.
- Analisar relatórios financeiros detalhados.

## Instalação

1. Clone o repositório:
    ```bash
    git clone https://github.com/ryanifms/Projeto_final.git
    ```

2. Entre no diretório do projeto:
    ```bash
    cd Projeto_final
    ```

3. Instale as dependências do Composer:
    ```bash
    composer install
    ```
4. Faca a copia das variveis de ambiente:
    ```bash
    copy .env.example .env
    ```


4. Configure o banco de dados no arquivo `.env`:
    ```plaintext
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=financiaai
    DB_USERNAME=seu_usuario
    DB_PASSWORD=sua_senha
    ```

5. Execute as migrações do banco de dados:
    ```bash
    php php artisan key:generate
    php artisan key:generate
    
    ```

## Uso

Para iniciar a aplicação, execute:
```bash
php artisar serve 
