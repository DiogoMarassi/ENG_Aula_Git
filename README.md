# ENG_Aula_Git
-Passo a passo django.

1- Criar Secret Key
- Digitar no Shell:
python
import secrets
secrets.token_urlsafe(32)

2- Criar app
- Digitar no console:
python manage.py starapp <nomedoapp>

3- Criar user do admin
- Digitar no console:
python manage.py createsuperuser
- O console irá solicitar o nome do user, o e-mail e uma senha. Você deve escolher portanto um nome, um e-mail e uma senha para acessar o admin

4- Fazer o import
- Digitar no console:
python manage.py migrate
python manage.py makemigrations
python manage.py migrate
 
- Passo a passo no Git
``` python
git
git clone <link>
```
Este passo é para criar um clone do seu projeto do GitHub

no powershell do windows
```
 cd <pasta do git>
```
Para entrar no diretório da pasta onde está salvo os arquivos do seu programa.

```
git add 
```
Adiciona os arquivos novos à fila de commit.
 
```
git config do email
git config do nome
git commit -m "MENSAGEM QUE VC QUER QUE APAREÇA"
```
Para pegar todos os arquivos da fila e registrar o commit (jogou tudo na caixinha de alterações).
 
```
git push 
```
envia os arquivos do PC pro github.
```
git pull 
```
Pega as alterações que outra pessoa fez dentro do repositório, antes de dar push.
```
git status 
```
Para ver se houve alguma modificacao nos arquivos e se eles estao no commit ou nao.
