# 🔥 TikTok Cookie Checker & Extractor 🕷️

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python)
![Status](https://img.shields.io/badge/Status-Working-brightgreen?style=for-the-badge)
![Dev](https://img.shields.io/badge/Developer-@hansYT-red?style=for-the-badge)

> **A ferramenta definitiva para validação em massa e extração de dados de contas TikTok.**

Este script automatiza o processo de verificação de cookies (formato Netscape), valida se a sessão está ativa (**LIVE**) ou expirada (**DIE**) e extrai informações detalhadas da conta, organizando tudo em pastas separadas.

## 🚀 Funcionalidades

* ✅ **Verificação Precisa:** Valida se o cookie está ativo via API interna.
* 📊 **Extração de Dados:** Coleta Seguidores, Likes, Vídeos, E-mail (se visível), Celular e Bio.
* 📂 **Auto-Organização:** Move cookies válidos para a pasta `lives` e cria subpastas por usuário (`@usuario`).
* 🛡️ **Bypasser:** Headers otimizados para simular um navegador real e evitar detecção básica.
* 📝 **Logs Detalhados:** Gera um arquivo `info.txt` com o resumo de cada conta.

## 🛠️ Instalação

### Pré-requisitos
* Python 3.x instalado.
* Pip (Gerenciador de pacotes).

### Passo a Passo

1.  Clone este repositório:
    ```bash
    git clone [https://github.com/SEU-USUARIO/TikTok-Cookie-Checker-Ultimate.git](https://github.com/SEU-USUARIO/TikTok-Cookie-Checker-Ultimate.git)
    cd TikTok-Cookie-Checker-Ultimate
    ```

2.  Instale as dependências:
    ```bash
    pip install -r requirements.txt
    ```

## ⚙️ Como Usar

1.  **Ativação:** Certifique-se de ter o arquivo de licença/ativador configurado (verifique o código para detalhes do caminho de ativação).
2.  **Cookies:** Coloque seus arquivos `.txt` (formato Netscape) dentro da pasta `cookies`.
3.  **Execução:** Rode o script:
    ```bash
    python tiktok.py
    ```
4.  **Resultados:** Verifique a pasta `lives` gerada automaticamente.

## 📸 Preview

```text
 ▄█████ ██  ██ ██████ ▄█████ ██ ▄█▀   ██████ ██ ██ ▄█▀ 
 ██     ██████ ██▄▄   ██     ████       ██   ██ ████   
 ▀█████ ██  ██ ██▄▄▄▄ ▀█████ ██ ▀█▄     ██   ██ ██ ▀█▄

                    >>> TIKTOK COOKIE CHECKER <<<
⚠️ Aviso Legal (Disclaimer)
Esta ferramenta foi desenvolvida apenas para fins educacionais e de testes de segurança em suas próprias contas. O desenvolvedor não se responsabiliza pelo uso indevido desta ferramenta.

👨‍💻 Desenvolvedor
Telegram: @hansYT

Canal: WatchHits
