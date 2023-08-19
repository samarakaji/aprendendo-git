# Primeiro passo
## 1. Clonar repositório

1.1 git clone => Busca o código da nuvem (Exemplo: [github](https://github.com)) e salva em sua máquina;


# Segundo passo
## 2. Alterar para um ambiente novo para fazer alterações no código (boa prática)

2.1 git checkout BRANCH => Tenta alterar para a branch (ambiente) que foi informada;

2.2 git checkout -b BRANCH => A flag (-b) vai procurar uma branch, e caso não encontre, irá criar uma com o nome informado;

# Terceiro passo
## 3. Informar ao github o caminho dos arquivos que foram alterados

3.1 git add . => Adiciona as suas alterações de código para uma pasta temporária local;

3.2 git commit -m "MENSAGEM" => Adiciona uma mensagem que será apresentada no repositório, *ATENÇÃO* é necessário usar a flag -m antes da mensagem

3.3 git push => "Empurra" o código adicionado para o ambiente (branch)
no repositório da nuvem

3.4  git push --set-upstream origin BRANCH => Caso seja uma branch recém criada, é necessário adicionar a flag --set-upstream seguido pela origem (branch)


### Crie seu README.md

- Você pode criar seu próprio arquivo README.md usando [esse site](https://readme.so/pt/editor) como referencia