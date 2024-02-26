# Copilot Chat

Convert GitHub Copilot to ChatGPT using:
- [copilot-gpt4-service](https://github.com/aaamoon/copilot-gpt4-service)
- [NextChat](https://github.com/ChatGPTNextWeb/ChatGPT-Next-Web)
- [OAuth2 Proxy](https://github.com/oauth2-proxy/oauth2-proxy)

## Usage

1. Clone this repo
    ```sh
    git clone --recursive git@github.com:storyn26383/copilot-chat.git
    ```

2. Create and modify .env file
    ```sh
    cp .env.example .env
    ```

3. Set authenticated emails
    ```sh
    echo 'authenticated@example.com' > authenticated-emails.txt
    ```

4. Run service
    ```sh
    docker compose up
    ```
