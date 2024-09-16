# CARDAPIO_ON_WHATS

## Descrição

O projeto **CARDAPIO_ON_WHATS** é uma aplicação que permite a criação e gestão de cardápios que podem ser acessados e consultados através do WhatsApp. O sistema integra funcionalidades de envio e recepção de mensagens para fornecer uma experiência interativa de visualização de cardápios via WhatsApp.

## Funcionalidades

- **Gerenciamento de Cardápios**: Criação, edição e remoção de itens de cardápio.
- **Integração com WhatsApp**: Envio e recebimento de mensagens para interagir com os usuários.
- **Interface de Usuário**: Interface simples e intuitiva para consultar e visualizar o cardápio.

## Requisitos

Para executar o projeto, você precisará de:

- Python 3.7 ou superior
- Bibliotecas Python necessárias (verifique o arquivo `requirements.txt`)
- Conta no Twilio para enviar mensagens via WhatsApp (ou outra API de sua escolha)

## Instalação

1. Clone o repositório:
    ```bash
    git clone https://github.com/Paulovinicius212/CARDAPIO_ON_WHATS.git
    ```
2. Navegue até o diretório do projeto:
    ```bash
    cd CARDAPIO_ON_WHATS
    ```
3. Instale as dependências:
    ```bash
    pip install -r requirements.txt
    ```

4. Configure as variáveis de ambiente necessárias para a integração com a API do WhatsApp (por exemplo, Twilio). Crie um arquivo `.env` com as seguintes variáveis:
    ```dotenv
    TWILIO_ACCOUNT_SID=your_twilio_account_sid
    TWILIO_AUTH_TOKEN=your_twilio_auth_token
    TWILIO_PHONE_NUMBER=your_twilio_phone_number
    ```

## Uso

Para iniciar a aplicação, execute o script principal:

```bash
python main.py
