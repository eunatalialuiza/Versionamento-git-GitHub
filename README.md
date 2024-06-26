# DIO | Resumos Git e GitHub

Repositório para armazenar resumos do curso Versionamento de código.

# 📚 Documentação

- [Documentação GIT](https://git-scm.com/doc)
- [Documentação GitHub](https://docs.github.com/pt)

# 💻 Resumos das Aulas

|Comando            | Resumos|
|-------------------|--------|
|/.git              |Inserir esse comando ao final do caminho do arquivo permite a visualização dos arquivos ocultos|
|git config --global user.name"SeuNome"| Para configurar o nome do usuário|
|git config --global user.email "SeuEmail"| Para definir o e-mail do github|

<img src="/hello-world/Captura de tela 2024-06-26 091000.png">

# Trasendo os aquivos para o repositório remoto

- Observação: se certificar que estamos com o local aberto p/ acessar os arquivos de config (MAIN)

```
cd .git
```

- git push -u origin main

# 🚶‍♂️Passo a Passo para clonar um Repositório remoto

- 1° Se localizar no diretório correto
- 2° git init p/ inicializar
- 3° git clone + link +nome_pasta(se quiser que fique com nome diferente)
- 4° entrar dentro do Repositório clonado 

```
cd repo_clonado.git/
```

- 5° cat config (para visualizar o nome do servidor de onde clonamos o arquivo, geralmente ele fica como "origin")
- 6° Se criarmos um novo repositório remoto e quisermos adicionar ao local, utilizar o comando:
```
 git remote add origin +link_caminho_htpps
# em seguida realizar o próximo comando para visualizar os arquivos
 cd .git
 ``` 


# ⌨️ Comandos

- Comandos S.O
```
cd NomePasta/                  # Para entrar em uma nova pasta
cd ~                           # Retorna para home
cd ..                          # retorna para a pasta anterior
ls                             # Lista todos os arquivos dentro do diretorio atual
ls -la                         # Mostra todos os arquivos inclusive os ocultos
cat .NomeArquivo               # Permite ler o arquivo
mkdir                          # Cria uma nova pasta
rm - rf .git                   # Remove o Repositório caso tenha inicicado na pasta errada
```
- Comandos GIT

```
touch NomePasta/NomeArquivo.md # Comando para criar um novo arquivo em branco
touch NomePasta/.gitkeep       # Cria um arq com conversão para igorar que esta vazio
git init                       # Comando utilizado para inicializar novos Repositório
git clone HTTPS                # Para clonar diretorio
git remote add origin +HTTPS   # Para inicluir um Repositório existente GitHub no GitLocal
git status                     # Vizualiza o status do arquivo/se modificado
echo > .gitignore              # Faz com que na leitura do status ignore a leitura do arqv
git add .                      # Insere todos arquivos na area de preparação
git commit -m"DescriçãoAlt"    # Adicionar a mensagem de descriçãao da alteração que fiz
git commit --amend -m ""       # Altera o nome/descriçao do ultimo commit adicionado
git restore NomeArquivo        # Recupera versões anteriores
git restore --staget pasta/arq # para remover da area de preparação
git remote -v                  # Mostra todos os servidores que estamos conectados
git log                        # Visualiza o histórico de commit
git reset soft #docommit       # adiciona na area de preparação
git reset --mixed #docommit    # Add os commites posteriores a arvore de trabalho
git log                        # ignora/apaga todos os commits posterior ao commit indicado
git reflog                     # Permite visualizar todas as alterações realizadas

```



- [Link Git teacher com mais informarções e resumos do curso:] (https://github.com/elidianaandrade/dio-curso-git-github)


