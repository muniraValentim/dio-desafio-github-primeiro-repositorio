# dio-desafio-github-primeiro-repositorio
Desafio de Projeto sobre Git/ GitHub
## Links Úteis
Syntax Markdown : (https://www.markdownguide.org/basic-syntax/)
Fala, pessoal!

Segue um compilado que fiz com os principais comandos do Git/Github para ajudar a todos:

git --version [verifica a versão instalada]
git status [mostra o estado dos arquivos e diretórios]
git config --global user.name "PrimeiroNome ÚltimoNome" [configura seu nome]
git config --global user.email "email@host.com" [configura seu e-mail]
git init [inicia um repositório local]
git commit meuarquivo.txt [commit somente o arquivo especificado]
git commit arquivo1.txt arquivo2.txt [commit vários arquivos ao mesmo tempo]
git commit meuarquivo.txt -m "mensagem de commit" [commit informando uma mensagem]
git commit --amend -m "nova mensagem de commit" [altera a mensagem de commit realizada]

git add . [adiciona todos os arquivos ou diretórios modificados]
git add meuarquivo.txt [adiciona somente o arquivo especificado]
git add meudiretório [adiciona somente o diretório informado]
git rm meuarquivo.txt [remove somente o arquivo especificado]
git rm -r meudiretório [remove somente o diretório informado]
git push origin main [upload das alterações locais para o repositório online]
git pull origin main [download de todos os arquivos do repositório online]

Chave SSH (via Git Bash)
-----------------------------------
1 - Gerar chave: ssh-keygen -t ed25519 email@host.com
2 - Copiar chave gerada: cd caminhoPastaInformada --> ls --> cat chave.pub --> copiar e colar no site do Github.com (<Settings> --> <SSH and GPG keys> --> <New SSH key>)
3 - Iniciar SSH agent: eval $(ssh-agent -s) --> ssh-add id_ed25519

Windows || Linux [comandos]
-----------------------------------------
 cd  || cd (abre determinada pasta)
 cd .. || cd ..   (sobe um nível de diretório)
 cd / ||  cd / (vai para a pasta raiz)
 dir  || ls (lista os diretórios)
 mkdir ||  mkdir (cria uma pasta. Ex.: mkdir nomeDaPasta)
 del || rm (deleta determinado ARQUIVO. Ex.: rm nomeDaPasta)
 rmdir || rm -rf (deleta determinada PASTA. Ex.: rm -rf nomeDaPasta)
 cls || clear (limpa o terminal)
 tecla TAB || tecla TAB (autocompletar)
