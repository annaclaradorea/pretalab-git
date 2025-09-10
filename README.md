# Oficina de Git e GitHub  | Ciclo formativo 14 | PretaLab

## Aula 01 
A  primeira aula apresentou o conceito de Git e a sua importância na comunidade de desenvolvedores (as)

 🏷️ |  Verificação de pastas:  `ls -a`

## Aula 02

OBS: Comandos no Windows utilizando o Git Bash

🏷️ |  Criação do repositório: `cd Desktop`  → `mkdir pretalab` → `git init`

🏷️ |  Chave de segurança: `ls ~/.ssh` - verificação da chave de segurança

- Caso não tenha, utilizar pra criar: `ssh-keygen -t ed25519 -C "seu-email@exemplo.com"`

🏷️ |  Ativação da chave: `eval "$(ssh-agent -s)”`→ `ssh-add ~/.ssh/id_ed25519`

🏷️ |  Adicionar chave no GitHub: `cat ~/.ssh/id_ed25519.pub`→ copia a chave completa 

- **No GitHub:** Icone do perfil → Settings → SSH and GPG keys → New SSH key → Colar a a chave e adicionar um titulo (security_pub-key) → Salvar chave

🏷️ |  Verificação da chave SSH: `ssh -T git@github.com`

## Aula 03

🏷️ |  Verificação da chave SSH: `ssh -T git@github.com`

🏷️ | Criando repositório

No GitHub: Icone do perfil → Repositories → New 
🏷️ | Conectando ao repositório local: `cd Desktop`  →  `cd git-github-pretalab` → `git remote add origin *URL do repositório` →*  `git branch -M main` 

- `git remote -v`  é usado para listar os repositórios remotos associados ao seu projeto Git, mostrando também as URLs usadas para buscar (fetch) e enviar (push) dados.




## Aula 04