# Semana 1: Controle de Versão com Git

## Objetivos da Semana:
- Compreender o conceito de **controle de versão** e sua importância.
- Aprender a usar os **principais comandos do Git** para gerenciar alterações em projetos.
- Entender como criar e trabalhar com **branches** (ramificações) e fazer **merges** (mesclagens).
- Configurar e utilizar **repositórios remotos** no GitHub para colaboração e backup de código.

---

## O que aprendi:

### 1. Controle de Versão:
- O **controle de versão** é uma prática essencial para gerenciar alterações em arquivos ao longo do tempo. Ele permite acompanhar o histórico de modificações, colaborar em equipe e reverter mudanças quando necessário.

### 2. Principais Comandos do Git:
- **`git init`**: Inicializa um repositório Git vazio.
- **`git clone [URL]`**: Clona um repositório remoto para o ambiente local.
- **`git status`**: Verifica o estado atual do repositório (arquivos modificados, não rastreados, etc.).
- **`git add [arquivo]`**: Adiciona arquivos modificados para o próximo commit.
- **`git commit -m "mensagem"`**: Cria um commit com as alterações e uma mensagem descritiva.
- **`git push`**: Envia os commits locais para o repositório remoto.
- **`git pull`**: Atualiza o repositório local com as alterações feitas no repositório remoto.

### 3. Branches e Merges:
- **Branching** permite trabalhar em novas funcionalidades sem afetar o código principal (geralmente na branch `main`).
- **Merge** é o processo de integrar mudanças de uma branch para outra, geralmente da branch de funcionalidade para a `main`.

### 4. Trabalhando com Repositórios Remotos (GitHub):
- **GitHub** é uma plataforma de hospedagem de código onde você pode armazenar repositórios Git remotamente.
- Criei um repositório no GitHub e aprendi a usar o comando **`git remote add origin [URL]`** para conectar meu repositório local com o remoto.
- Usei **`git push origin main`** para enviar as alterações locais para o GitHub.

---

## Desafios e Lições Aprendidas:
- Inicialmente, encontrei dificuldades em entender o conceito de branches, mas praticar a criação e mesclagem de branches me ajudou a compreender melhor como trabalhar com diferentes versões do código sem comprometer a estabilidade do projeto.
- Aprendi que **`git status`** é uma ferramenta muito útil para verificar o que está acontecendo no repositório antes de fazer qualquer ação, como um commit ou push.
- Configurar o repositório remoto no GitHub foi um grande aprendizado, especialmente a importância de sempre fazer o **push** para manter o código sincronizado e acessível.

---

## Próximos Passos:
- Estudar mais sobre **fluxos de trabalho com Git**, como Git Flow e GitHub Flow.
- Praticar a colaboração com outras pessoas em repositórios compartilhados, realizando pull requests e revisões de código.

---

## Links Úteis:
- [Documentação Oficial do Git](https://git-scm.com/doc)
- [GitHub Docs](https://docs.github.com/)

---

## Tarefas da Semana:
- Criar e configurar repositórios locais e remotos.
- Realizar commits, push e pull.
- Trabalhar com branches e mesclar alterações.
