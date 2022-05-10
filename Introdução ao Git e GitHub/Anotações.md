# Introdução ao GIT e GitHub

### Entendendo o Git e GitHub :thinking:

- Git é um sistema de versionamento de código
- Git e GitHub são duas tecnologias diferentes mas complementares
- Benefícios de aprender Git e GitHub:
  - Controle de versão
  - Armazenamento em nuvem
  - Trabalhar em equipe
  - Melhorar seu código

### Navegação via command line inteface

- Comandos de navegação
  - Mudar de pastas — cd
  - Listar as pastas — ls
  - Criar pastas / arquivos — dir
  - Deletar pastas / arquivos — del || rmdir
  - Limpar tela — cls
- **TAB** faz auto-complete no terminal bash
- O comando echo printa no terminal, se ele for utilizado com **>** pode redirecionar o texto para um arquivo
- Há diferenças entre del e rmdir, o del apaga todo o conteúdo de um diretório enquanto o rmdir apaga tudo.

### Tópicos fundamentais para entender o funcionamento do GIT

- SHA1
  - É um algoritmo de encriptação que gera hashs identificadoras
- Objetos fundamentais
  - Blobs :droplet:
    - Contém metadados do GIT como tipo do objeto, tamanho do arquivo entre outros
  - Tree :deciduous_tree:
    - Armazena os blobs e aponta tanto para os blobs quanto para outras trees. Ela também guardar o SHA1 dos metadados da blobs
  - Commit
    - É o objeto que vai juntar tudo e vai dar sentido as alterações. o SHA1 desses commits é o hash de todas as informações
- Sistema distribuído
- Segurança

### Iniciando o Git e criando um commit

- git init — Iniciar o repositório git
- git add — Iniciar o versionamento
- git commit — criar um commit

Antes de criarmos um commit precisamos fazer algumas configurações

- $ git config --global user.email "e-mail"
- $ git config --global user.name "username GitHub"

Há um ciclo quando um arquivo está em tracked

- Unmodified
- Modified
- Staged

![Fluxograma - DIO (Ciclo de vida dos arquivos no Git - Passo a passo no ciclo de vida)] (Introdução ao Git e GitHub/fluxograma.png)

