# ENG_Aula_Git
-Passo a passo django.

1- Criar Secret Key
- Digitar no Shell:
python
import secrets
secrets.token_urlsafe(32)

1- Criar app
- Digitar no console:
python manage.py starapp <nomedoapp>

1- Criar user do admin
- Digitar no console:
python manage.py createsuperuser
- O console irá solicitar o nome do user, o e-mail e uma senha. Você deve escolher portanto um nome, um e-mail e uma senha para acessar o admin

1- Fazer o import
- Digitar no console:
python manage.py migrate
python manage.py makemigrations
python manage.py migrate
 
- Passo a passo no Git
git
git clone <link>

cd <pasta do git>

git add .   // Adiciona os arquivos novos à fila (COMMIT)
git config do email
git config do nome
git commit -m "MENSAGEM QUE VC QUER QUE APAREÇA" // pegou todos os arquivos da fila e registrou o commit [jogou tudo na caixinha de alterações]
git push // envia do PC pro github

git pull // pega as alterações que outra pessoa fez dentro do repositório, antes de dar push

git status // para ver se houve alguma modificacao nos arquivos e se eles estao no commit ou nao

