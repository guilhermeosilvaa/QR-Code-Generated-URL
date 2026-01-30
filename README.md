🔗 QR Code URL Generator — Python








Um gerador de QR Code em Python que transforma URLs em imagens escaneáveis, permitindo rápida distribuição de links em projetos, automações e sistemas internos.

Este projeto foi desenvolvido com foco em simplicidade, reutilização e portfólio profissional.

📌 Sobre o Projeto

O QR Code URL Generator permite que o usuário informe qualquer URL via terminal e receba automaticamente um QR Code salvo como imagem.

É útil para:

Compartilhamento rápido de links

Automação de processos

Estudos de Python

Demonstração de habilidades em portfólio

📸 Preview

Após a execução, o arquivo será criado:

qrcode.png

Basta escanear com o celular para abrir a URL.

🛠️ Stack Tecnológica

🐍 Python

📦 qrcode

🖼️ Pillow (PIL)

📦 Instalação

Clone o repositório:

git clone https://github.com/guilhermeosilvaa/QR-Code-Generated-URL.git

Acesse a pasta:

cd seu-repositorio

Instale as dependências:

pip install qrcode[pil]
▶️ Execução

Rode o projeto:

python main.py

Informe a URL:

Enter URL: https://www.google.com

O QR Code será salvo como:

qrcode.png
🧠 Funcionamento

Fluxo do sistema:

Importa a biblioteca qrcode.

Solicita uma URL ao usuário.

Gera o QR Code.

Salva a imagem no diretório do projeto.

Retorna mensagem de sucesso.

💻 Código Principal
import qrcode


url = input("Enter URL: ")


img = qrcode.make(url)


img.save("qrcode.png")


print("QR Code Generated")
✅ Exemplo de Uso

Entrada:

https://github.com

Saída:

qrcode.png
🚀 Roadmap (Melhorias Futuras)

✔️ Validação de URL

🎨 Personalização de cores

🖥️ Interface gráfica

📁 Escolha do nome do arquivo

🌐 Suporte para texto e Wi-Fi QR Codes


📄 Licença

Este projeto está sob a licença MIT.
Sinta-se livre para usar, modificar e distribuir.

⭐ Se este projeto te ajudou, deixe uma estrela no repositório!
