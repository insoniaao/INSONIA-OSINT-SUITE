🌑 INSONIA OSINT SUITE

Ferramenta de OSINT e utilitários para terminal Android (Termux).

O INSONIA OSINT SUITE é um projeto em Python desenvolvido para reunir utilitários de consulta de informações públicas, testes com dados fictícios e recursos experimentais em uma interface de terminal.

✨ Recursos

- 🔎 Utilitários de OSINT para pesquisas autorizadas com fontes públicas.
- 📧 Módulo experimental de e-mail temporário, sujeito à disponibilidade da API.
- 🧪 Gerador de dados fictícios para testes de software.
- 📱 Compatibilidade com Android por meio do Termux.
- 🐍 Desenvolvido em Python.

«Aviso: os recursos disponíveis dependem da versão do código instalado. Os dados gerados são destinados exclusivamente a testes. Não use dados fictícios para se passar por outra pessoa, preencher cadastros fraudulentos ou realizar atividades não autorizadas.»

📋 Requisitos

- Celular Android.
- Termux instalado.
- Conexão com a internet.
- Python 3.
- Git.

📥 Instalação no Android (Termux)

1. Instale o Termux

Baixe pela página oficial:

https://github.com/termux/termux-app/releases

2. Atualize os pacotes

Abra o Termux e execute:

pkg update && pkg upgrade -y

3. Instale Python e Git

pkg install python git -y

4. Baixe o projeto


git clone https://github.com/insoniaao/INSONIA-OSINT-SUITE

5. Entre na pasta do projeto

cd INSONIA-OSINT-SUITE

6. Instale as dependências

Se o projeto tiver um arquivo "requirements.txt", execute:

pip install -r requirements.txt

Se não houver esse arquivo, consulte as dependências documentadas no projeto.

7. Inicie o programa

Se o arquivo principal se chamar "main.py", execute:

python main.py

Se o arquivo principal tiver outro nome, use o nome correto.

🔄 Atualização

Para atualizar uma cópia já instalada pelo Git:

git pull

Execute o comando dentro da pasta do repositório.

🛠️ Solução de problemas

Erro: "git: command not found"

pkg install git -y

Erro: "python: command not found"

pkg install python -y

Erro: "can't open file 'main.py'"

Verifique se você está dentro da pasta correta e confira os arquivos disponíveis:

pwd
ls

Erro ao criar e-mail temporário

Verifique a conexão com a internet, a disponibilidade da API e as regras de criação de endereços do serviço.

🔐 Uso responsável

O uso desta ferramenta sera por sua responsabilidade, qualquer atividade feita foi com sua responsabilidade.

📌 Status

Projeto em desenvolvimento. Alguns recursos podem ser experimentais ou depender de serviços externos.

👤 Autor

INSONIA

Consulte o histórico de alterações e os arquivos do repositório para verificar as funcionalidades realmente implementadas.