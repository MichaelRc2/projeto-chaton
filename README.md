ChatOn - Aplicativo de Chat em Tempo Real
O ChatOn é um projeto de aplicação de chat em tempo real desenvolvido com Python e o framework Flet. Este projeto demonstra o uso de funcionalidades de tempo real (Pub/Sub) para permitir que múltiplos usuários conversem em uma mesma sessão de forma simples e eficiente.

🚀 Tecnologias Utilizadas
Python: Linguagem principal do projeto.

Flet: Framework utilizado para criar a interface gráfica (UI) baseada em Flutter, utilizando apenas Python.

🛠️ Funcionalidades
Interface Intuitiva: Sistema de entrada de usuário via Popup/AlertDialog.

Chat em Tempo Real: Utiliza o padrão Publish-Subscribe (Pub/Sub) para propagar mensagens instantaneamente para todos os usuários conectados.

Design Responsivo: Rodando diretamente no navegador através da visualização web do Flet.

Notificações de Entrada: Avisa a todos os membros quando um novo usuário se conecta à sala.

📋 Como Executar o Projeto
Pré-requisitos
Certifique-se de ter o Python instalado em sua máquina.

Clone este repositório:

Bash
git clone https://github.com/seu-usuario/ChatOn.git
cd ChatOn
Instale o Flet:

Bash
pip install flet
Execute o código:

Bash
python main.py
O aplicativo abrirá automaticamente no seu navegador padrão.

💡 Como Funciona
O projeto utiliza a classe pubsub do Flet. Quando um usuário envia uma mensagem, ela é publicada no "túnel" de comunicação e todos os inscritos (outros usuários) recebem a atualização imediatamente na tela, sem a necessidade de recarregar a página.

🤝 Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para fazer um fork do projeto e enviar um pull request com melhorias.

Desenvolvido com foco em aprendizado e prática de bibliotecas de interface em Python.
