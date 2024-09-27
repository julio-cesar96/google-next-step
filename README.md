
# Exercícios de Git e GitHub

## **1. Crie um novo repositório**

### Exercício 1: Criar um repositório e sincronizá-lo com o GitHub
- Acesse o GitHub e crie um repositório público chamado `projeto-inicial`.
  - **Dica:** Inclua um `README.md` no repositório ao criá-lo.
- Clone o repositório para sua máquina local com o comando `git clone`.
  - **Comando:** `git clone <URL_DO_REPOSITORIO>`
  
### Exercício 2: Criar arquivos e enviar ao GitHub
- Na pasta do repositório clonado, crie os seguintes arquivos e diretórios:
  - Um arquivo `index.html` com algum conteúdo básico de HTML.
  - Um diretório chamado `css` e dentro dele crie o arquivo `style.css` com estilos simples.
- Adicione as mudanças usando o comando `git add`.
  - **Comando:** `git add .`
- Faça o commit das alterações com uma mensagem explicativa.
  - **Comando:** `git commit -m "Adiciona arquivos HTML e CSS"`
- Envie o commit para o GitHub.
  - **Comando:** `git push origin main`
  
**Objetivo:** Certificar-se de que as alterações feitas localmente estão sincronizadas com o repositório remoto no GitHub.

---

## **2. Gerenciar branches**

### Exercício 3: Criar e trabalhar em uma branch
- Crie uma nova branch chamada `melhorias-layout`.
  - **Comando:** `git checkout -b melhorias-layout`
- No arquivo `style.css`, adicione estilos extras, como alterar a cor de fundo do `body`.
  - Exemplo: `body { background-color: #f0f0f0; }`
- Adicione e comite as alterações.
  - **Comando:** `git add .`
  - **Comando:** `git commit -m "Ajusta cor de fundo do layout"`

### Exercício 4: Criar um pull request
- Suba as alterações da nova branch para o GitHub.
  - **Comando:** `git push origin melhorias-layout`
- Acesse o GitHub e crie um **pull request** para mesclar a branch `melhorias-layout` com a branch `main`.
  - **Dica:** Inclua uma descrição explicando o que foi alterado no pull request.

### Exercício 5: Mesclar o pull request
- Mescle o pull request diretamente na interface do GitHub.
- Depois de mesclado, volte à sua máquina local e faça o seguinte:
  - Retorne à branch principal.
    - **Comando:** `git checkout main`
  - Puxe as alterações do repositório remoto.
    - **Comando:** `git pull origin main`

