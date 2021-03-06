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

# Introdução ao HTML e CSS

### Entendendo a semântica

- Os elementos no HTML trazem mais significados como.
  - section: representa uma seção genérica de conteúdo.
  - header: é o cabeçalho da página.
  - article: é um conteúdo relevante.
  - aside: é um conteúdo relacionado ao conteúdo principal com links.
  - footer: é o rodapé da página.
  - h1~h6: são os tipos de títulos, cada qual com seu significado.

### Como usar textos e links em HTML

- **tag p** Cria paragrafos que contém textos mais densos.
- **tag a** Cria links. Dentro temos a propriedade **href** que é onde colocamos o link para ser onde seremos levados, se quisermos que seja aberto em uma nova aba é necessário colocar **target="_blank"**.
- É possivel linkar e-mails usando "mailto" dentro do href: href="mailto:e-mail" e telefones usando "tel".

### Como inserir imagens em seu site

- **tag img**: é uma tag sem fechamento e tem dois atributos que são o **src** que é o caminho de onde está a imagem e o **alt** que é o texto alternativo da imagem para fins de acessibilidade.

### Como organizar listas com HTML

- **tag ul**: é usada para cirar listas não ordenadas ou unordered list.
- **tag ol**: é usada para criar listas ordenadas ou ordered list.
- **tag li**: são os itens dessas listas.

### Introdução e conceitos básicos do CSS3

- Foi criado com o objetivo de formatar páginas web.
- Você cria regras de estilos para elementos.
- As regras são formadas por seletores e declarações, as declarações possuem propriedades e valores.
- Há vários seletores, quando utilizamos elementos do HTML é chamado de seletor de tipo, há também seletores de classe e id.
- No CSS um seletor de **classe** é precedido por um "**.**" e o de **id** pela "**#**"
- O navegador representa cada elemento HTML como uma caixa retangular, chamada de boxmodel, a boxmodel tem 4 áreas: 
  - margin: são os espaçamentos entre elementos.
  - border: as bordas circundam o padding e o content.
  - padding: é o espaçamento entre o border e o content.
  - content: é o que o bloco representa.

### Estilizando elementos, textos e listas

- Podemos atribuir valores diferentes para cada lado da boxmodel no padding e margin.
- Bordas podem ser pontilhadas, tracejadas e solidas.
- É uma boa prática adicionarmos margens na mesma direção.

### Estilizando textos

- font-family: é a fonte que utilizaremos no texto
- font-size: altera o tamanho do texto
- font-style: altera o estilo da fonte, se é itálico ou normal. É preciso saber se a fonte usada tem suporte para outros estilos.
- font-weight: é o peso da nossa fonte, quando queremos algo em negrito usamos o valor bold.
- text-transfer: alterna o texto entre maiusculo e minusculo:
  - uppercase: TODO O TEXTO FICA EM CAIXA ALTA.
  - lowcase: todo o texto fica em caixa baixa.
  - capitalize: Todas As Primeiras Letras Ficam Em Maiúsculo.
- text-decoration: é usada para dar destaque ao texto:
  - underline
  - overline
  - line-through

### Estilizando listas

- Existe vários modos de alterar os marcadores das listas usando **list-style-type**, vários valores podem ser utilizados. Em **ul** podemos usar **square** ou até mesmo um emoji pelo seu código como **"\1F44D"** e na **ol** podemos usar **uper-roman** para números romanos em caixa alta.

### Dimensão e alinhamento

- width: largura 
- height: altura
- max-width: largura máxima
- max-height: altura máxima
- margin
- text-align
