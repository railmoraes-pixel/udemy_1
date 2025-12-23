Estes documentos são apenas para uso didático do curso de agente de IA, que estou fazendo na Udemy.

# Já aprendemos
- Gemini  canvas - faz Storybook; imagem e videos / IMPORTANTE - faz quiz.
- Usado para fazer aplicativos e site / temos 5 creditos diarios / Link:https://lovable.dev/projects/6726d7ec-7870-43ff-81a7-1da7e1ea4624 

# No git e gitHub
# inicia o repositório Git na pasta atual
git init

Configurar usuário e e-mail (apenas uma vez) - git config --global user.name "seu-usuario"
git config --global user.email "seuemail@exemplo.com"

## Adicionar arquivos ao controle de versão
## adiciona um arquivo específico
git add nome_do_arquivo.py

## adiciona todos os arquivos da pasta
git add .



## Criar um commit
git commit -m "Mensagem explicando a alteração"

## Conectar ao repositório remoto (GitHub)
# adiciona o repositório remoto
git remote add origin https://github.com/seuusuario/seu-repositorio.git

# define a branch principal como 'main'
git branch -M main

## Enviar arquivos para o GitHub
git push -u origin main

## Fluxo completo para subir um arquivo Python
- Crie ou edite seu arquivo Python (ex.: inicio.py).
- Inicialize o repositório:
git init
- Adicione os arquivos:
git add .
- Crie o commit:
git commit -m "Adiciona arquivo inicio.py"
- Conecte ao GitHub:
git remote add origin https://github.com/seuusuario/seu-repositorio.git
git branch -M main

## Faça o push:
git push -u origin main

# Dicas extras
- Para verificar o status dos arquivos:
git status
- Para ver o histórico de commits:
git log
- Para atualizar o repositório local com mudanças do remoto:
git pull


