# 🤖 Automação de WhatsApp - Encaminhamento de Mensagens

Este projeto automatiza o encaminhamento de mensagens no WhatsApp Web para uma lista de contatos ou grupos, utilizando Python e Selenium. As mensagens são encaminhadas em lotes de 5 destinatários por vez.

## 📌 Funcionalidades

- Encaminhamento automático de mensagens no WhatsApp Web
- Suporte para contatos e grupos
- Encaminhamento em lotes (5 por vez)
- Lista de contatos carregada via arquivo `.txt`

## 🚀 Tecnologias Utilizadas

- Python
- Selenium
- Chrome WebDriver

## 📂 Estrutura do Projeto

```

automacao-whatsapp/
├── encaminhador.py
├── contatos.txt
├── README.md
└── requirements.txt

````

## 📥 Pré-requisitos

- Python 3.8 ou superior
- Google Chrome instalado
- ChromeDriver compatível com a versão do seu navegador Chrome

## 🔧 Instalação

1. Clone este repositório:

```bash
git clone https://github.com/seuusuario/automacao-whatsapp.git
cd automacao-whatsapp
````

2. Instale as dependências:

```bash
pip install -r requirements.txt
```

3. Adicione os contatos ou nomes de grupos no arquivo `contatos.txt`, um por linha.

## ▶️ Como Usar

1. Execute o script:

```bash
python encaminhador.py
```

2. Uma janela do Chrome será aberta. Faça login no WhatsApp Web escaneando o QR Code.

3. O envio será feito automaticamente em lotes de 5 contatos/grupos por vez.

## ⚠️ Avisos Importantes

* Use este projeto com responsabilidade.
* Evite spam ou violações dos termos de uso do WhatsApp.
* Ajuste os `sleep()` no código conforme necessário para garantir estabilidade e evitar bloqueios.

## 📄 Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).

---

**Desenvolvido por \[odevthomas]**


