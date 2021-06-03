<h1 align="center">
  <br>
  <a href=""><img src="https://media.giphy.com/media/jVflkGtOAL0qIrZ6nL/giphy.gif" alt="Chatbot" width="200"></a>
  <br>
  Chatbot Matemático
  <br>
</h1>

<h4 align="center">Um chatbot com conteúdos matemáticos <a href="https://rasa.com/" target="_blank">RASA</a>.</h4>


<p align="center">
  <a href="#how-to-use">Como Usar</a> •
</p>

## Como usar
To clone and run this application, you'll need [Git](https://git-scm.com) and [Python](https://www.python.org/) (which comes with [pip](https://pypi.org/project/pip/)) installed on your computer. From your command line:

```bash
# Clone
$ git clone https://github.com/spacexjedi/chatbot
# entre no repositório
$ cd chatbot
# Instalar dependências
$ pip3 install rasa
# Executar na pasta do bot
$ rasa init
# treinar um modelo
$ rasa train
# usar no shell
$ rasa shell
# se tiver ações
$ rasa run actions
# start servidor
$ rasa run -m models --enable-api --cors "*" --debug
```
