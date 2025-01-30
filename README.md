
# Resumo de Git e GitHub
Alguns dos principais conceitos, primeiros comandos e alguns exemplos de como usar as ferramentas de versionamento de código [Git](https://git-scm.com/) e [GitHub](https://github.com/).

## 📚 Documentação
- [Documentação Git](https://git-scm.com/book/pt-br/v2)
- [Documentação GitHub](https://docs.github.com/pt/get-started)

## 💻 Resumos das aulas
| Aula | Resumo |
|------|-------|
|Introdução|Histórico e os tipos|
|Fluxo Básico| Como o Git funciona e seus principais comandos|
|Instalação e Primeiros Comandos| Configurar usuário, e-mail e branch padrão|
|Autenticação (2 aulas)| Autenticação no GitHub via Token e via SSH|
|Primeiros passos| Criar e clonar repositórios|
|     |Salvar alterações no repositório local
|     |Desfazer alterações|
|  |Enviar e baixar alterações no repositório remoto|
|Trabalhar com Branches|Criar, mesclar, deletar, tratar conflitos|
|   | Comandos úteis no dia a dia

## 🔎 Referências
- [Aprenda Git e GitHub em 5 minutos](https://www.youtube.com/watch?v=-l4Aa8wef8s) - [Resumo](#resumo-de-aprenda-git-e-github-em-5-minutos)
- [GIT: Minicurso para Você Sair do Zero! (Aprenda em 45 Minutos)](https://youtu.be/ts-H3W1uLMM?si=sCwisBuSN1OM6KR9) - [Resumo](#resumo-de-git-minicurso-para-sair-do-zero)
- [Curso de Git e Github Completo 2024 [Iniciantes] + Desafios + Muita Prática](https://youtu.be/kB5e-gTAl_s?si=R63vQDWcAg-iviaZ) -  [Resumo](#resumo-de-curso-de-git-e-github-completo-2024)
- [Entendendo Git | (não é um tutorial!)](https://youtu.be/6Czd1Yetaac?si=bewHVQKH2dFiFUTX) -  [Transcrição](https://www.akitaonrails.com/2020/02/05/akitando-70-entendendo-git-nao-e-um-tutorial)

- [Tech Talk: Linus Torvalds on Git](http://www.youtube.com/watch?v=4XpnKHJAok8) - [Transcrição](https://gist.github.com/lorn/1272686)



## 🗄️ Resumos

### Resumo de Aprenda Git e GitHub em 5 minutos

A diferença entre Git e GitHub é fundamental na gestão de código:

- **Git**:
   - **O que é**: Um sistema de controle de versão que permite rastrear mudanças em arquivos e coordenar o trabalho entre várias pessoas.
   - **Uso**: É uma ferramenta que funciona localmente no seu computador, permitindo criar repositórios, realizar commits, branches e merges.
   - **Independência**: Pode ser usado sem uma conexão à internet.

- **GitHub**:
   - **O que é**: Uma plataforma online que hospeda projetos Git, permitindo colaboração, compartilhamento e gerenciamento de repositórios.
   - **Funcionalidades**: Oferece ferramentas adicionais como controle de acesso, problemas (issues), pull requests e integração contínua.
   - **Colaboração**: Facilita o trabalho em equipe, pois permite que vários desenvolvedores contribuam para um projeto de forma organizada.

Em resumo, **Git é a ferramenta de versão em si**, enquanto **GitHub é um serviço que utiliza Git para facilitar a colaboração online**. 

#### Os principais comandos do Git, conforme mencionado no vídeo, incluem:

1. **`git init`**: Inicializa um novo repositório Git em uma pasta.
2. **`git add <arquivo>`**: Adiciona alterações de um arquivo específico à área de staging, preparando-o para o commit.
3. **`git commit -m "mensagem"`**: Registra as alterações na linha do tempo do repositório, com uma mensagem descritiva sobre o que foi alterado.
4. **`git branch <nome>`**: Cria uma nova branch (ramo) no repositório.
5. **`git remote add origin <link>`**: Adiciona um repositório remoto, que é o endereço onde o código será armazenado (como no GitHub).
6. **`git push origin <branch>`**: Envia as alterações da branch local para o repositório remoto.

[[Voltar]](#referencias)

### Resumo de GIT: Minicurso para sair do zero
O mini curso de Git ensina a versionar códigos. Com comandos práticos, o curso aborda desde a configuração inicial até o uso de branches, merges e rebase. O objetivo é facilitar o aprendizado e a recuperação de códigos, promovendo um desenvolvimento organizado e colaborativo.

#### Destaques:
**00:09** Aprender a usar o Git é essencial para programadores, pois permite versionar códigos e facilitar a recuperação de dados. A prática de versionamento ajuda a evitar erros durante o desenvolvimento.  
O Git foi criado para facilitar o controle de versões e colaborar em projetos, permitindo que múltiplos desenvolvedores trabalhem sem conflitos. É uma ferramenta fundamental no desenvolvimento software.  
A instalação do Git é simples e pode ser feita em diferentes sistemas operacionais, garantindo que você possa utilizá-lo independentemente do ambiente. Isso torna o Git acessível a todos os programadores.  
Comandos básicos como 'git init' e 'git clone' são essenciais para iniciar e gerenciar repositórios. Esses comandos ajudam a organizar e versionar projetos de forma eficiente.  
**06:03** O Git possui dois estágios importantes antes de versionar os arquivos no repositório. É necessário indexar os arquivos e, em seguida, confirmar as alterações para criar um histórico.  
A primeira etapa no uso do Git é a organização dos arquivos que irão para o repositório, conhecida como Stage ou palco. Essa fase permite modificar arquivos sem afetar o repositório ainda.  
Após indexar os arquivos, a próxima etapa é a confirmação, que efetivamente salva as alterações no repositório. Isso cria um histórico de mudanças e permite rastrear versões anteriores.  
O comando Git status é fundamental para visualizar o estado dos arquivos entre o working directory e o Stage. Ele ajuda a identificar quais arquivos estão prontos para serem versionados.  
**12:05** Os commits são essenciais para registrar as alterações em um projeto, mostrando quem fez cada modificação e quando. Isso é fundamental para entender a evolução do código ao longo do tempo.  
O comando Git commit é utilizado para salvar as mudanças no repositório, acompanhado de uma mensagem que descreve o que foi alterado. Isso ajuda outros desenvolvedores a entenderem o contexto das mudanças.  
É importante prestar atenção ao usar comandos como 'git commit -a -m', pois ele adiciona automaticamente todos os arquivos modificados. Isso pode incluir alterações indesejadas se não for cuidadosamente revisado.  
Mensagens de commit devem ser claras e informativas, evitando termos vagos como 'Fix' ou 'Update'. Usar padrões como 'Added' ou 'Changed' ajuda a manter um histórico mais compreensível e útil.  
**18:08** O uso de branches no Git permite que os desenvolvedores realizem alterações sem afetar o código principal. Essa prática facilita o trabalho em equipe e a organização do desenvolvimento.  
As branches funcionam como caminhos alternativos para o desenvolvimento, permitindo criar ambientes separados para testar alterações. Isso evita impactos diretos no branch principal.  
A criação de branches novas é simples e pode ser feita de várias formas, como através de comandos específicos. Isso proporciona flexibilidade na organização do código.  
É importante manter as branches atualizadas com o branch principal para evitar conflitos durante a mesclagem. Essa prática garante um desenvolvimento mais fluido e eficiente.  
**24:11** O vídeo explica como utilizar repositórios remotos no GitHub, enfocando comandos como 'git remote', 'git push' e 'git pull'. Esses comandos são essenciais para sincronizar mudanças entre repositórios locais e remotos.  
A adição e remoção de repositórios remotos é simples com os comandos 'git remote add' e 'git remote remove', permitindo fácil gerenciamento. Isso ajuda a manter o controle sobre diferentes origens de código.  
O uso do comando 'git pull' é fundamental para integrar alterações de outros colaboradores antes de fazer um 'git push', evitando conflitos. A prática de sincronizar frequentemente é recomendada.  
Entender como realizar 'merge' e 'rebase' é crucial para unir mudanças em diferentes branches, prevenindo conflitos. Essas operações garantem que o código esteja sempre atualizado e funcional.  
**30:14** O rebase é uma alternativa ao merge no Git, permitindo integrar mudanças de uma branch para outra de forma linear. Ele altera o histórico dos commits, o que pode ser útil para manter um histórico mais limpo.  
A diferença principal entre merge e rebase é que o merge preserva o histórico completo, enquanto o rebase cria uma linha do tempo mais linear. Isso ajuda a evitar confusões em projetos complexos.  
Ao utilizar rebase, é importante ter cuidado, especialmente em branches públicas, pois altera o histórico e pode causar conflitos. Sempre verifique se não há alterações não integradas antes de realizar o rebase.  
As tags no Git são utilizadas para marcar versões específicas no histórico do repositório. Elas podem ser leves ou anotadas, sendo as anotadas mais recomendadas para lançamentos.  
**36:17** As tags no Git são essenciais para marcar versões específicas de um projeto, facilitando o rastreamento e o gerenciamento de alterações. Elas permitem que desenvolvedores identifiquem rapidamente versões e mudanças significativas no código.  
As tags ajudam a rastrear versões de lançamento do software, como v1.0 ou v2.1, permitindo que outros usuários referência essas versões de forma prática.  
Tags podem destacar estados importantes do código, como grandes mudanças ou correções de bugs, fornecendo um histórico claro de progresso e problemas resolvidos.  
Tags assinadas oferecem segurança adicional ao permitir que outros verifiquem a autenticidade da tag, garantindo que ela foi criada por um membro confiável da equipe.  
**42:19** O Git stash é uma ferramenta útil para salvar mudanças temporárias enquanto você muda de branch. Ele permite que você recupere essas alterações posteriormente, evitando perda de dados.  
A diferença entre os comandos Git stash apply e Git stash pop é essencial para gerenciar suas alterações. O apply mantém as mudanças no stash, enquanto o pop as remove completamente.  
Reverter alterações em um repositório remoto requer um Git push com o parâmetro Force. Isso é útil para desfazer commits que já foram enviados para o repositório.  
A documentação do Git é uma excelente fonte para aprender mais sobre comandos avançados. O uso do help no terminal também pode ser uma forma eficaz de obter assistência.  

#### Principais comandos
Os principais comandos do Git incluem:

1. **`git init`**: Inicializa um novo repositório Git.
2. **`git clone <url>`**: Copia um repositório remoto para o seu computador.
3. **`git add <arquivo>`**: Adiciona alterações de um arquivo específico à área de staging.
4. **`git commit -m "mensagem"`**: Registra as alterações no repositório com uma mensagem descritiva.
5. **`git status`**: Mostra o estado dos arquivos no repositório (modificados, não rastreados, etc.).
6. **`git branch <nome>`**: Cria uma nova branch.
7. **`git checkout <branch>`**: Muda para uma branch específica.
8. **`git merge <branch>`**: Mescla as alterações de uma branch em outra.
9. **`git push origin <branch>`**: Envia as alterações da branch local para o repositório remoto.
10. **`git pull`**: Atualiza a branch local com as alterações do repositório remoto.
11. **`git stash`**: Salva temporariamente alterações não confirmadas.
12. **`git tag <nome>`**: Marca uma versão específica no histórico do repositório.

Esses comandos são fundamentais para gerenciar versões e colaborar em projetos de software.

O conceito de branches (ramificações) no Git permite que você trabalhe em diferentes linhas de desenvolvimento de maneira isolada e organizada. Aqui está um resumo de como funciona:

#### O que são Branches?

- **Definição**: Uma branch é uma versão paralela do seu repositório. Usá-las permite que você faça alterações em uma linha de desenvolvimento sem afetar a branch principal, geralmente chamada de "main" ou "master".

##### Como Funcionam as Branches?

1. **Criação**:
   - Você pode criar uma nova branch a partir da linha de desenvolvimento atual usando o comando `git branch <nome-da-branch>`. Essa branch pode ser utilizada para desenvolver novas funcionalidades ou corrigir bugs.

2. **Mudança de Branch**:
   - Para alternar entre branches, você usa `git checkout <nome-da-branch>`. Isso altera o seu diretório de trabalho para refletir o estado da branch escolhida.

3. **Desenvolvimento**:
   - As alterações feitas em uma branch não afetam outras branches até que você as mescle. Isso permite experimentar novos recursos sem comprometer a estabilidade do código em desenvolvimento.

4. **Mesclagem**:
   - Quando você estiver satisfeito com as alterações, pode mesclá-las de volta na branch principal usando `git merge <nome-da-branch>`. Isso combina as alterações da branch de desenvolvimento com a branch atual.

5. **Resolução de Conflitos**:
   - Se houver alterações conflitantes entre as branches, o Git solicitará que você resolva esses conflitos manualmente antes de concluir a mesclagem.

##### Vantagens das Branches

- **Isolamento**: Permite trabalhar em novas funcionalidades ou correções de bugs sem afetar a base de código principal.
- **Organização**: Facilita a organização do trabalho em equipe, permitindo que múltiplos desenvolvedores trabalhem em diferentes aspectos de um projeto simultaneamente.
- **Histórico Limpo**: Ajuda a manter um histórico de commit limpo e compreensível, agrupando mudanças relacionadas em uma branch específica.

##### Exemplo de Uso

1. Criar uma nova branch para uma funcionalidade:
   ```
   git branch nova-funcionalidade
   ```
2. Mudar para a nova branch:
   ```
   git checkout nova-funcionalidade
   ```
3. Fazer alterações e adicionar os arquivos:
   ```
   git add .
   git commit -m "Adiciona nova funcionalidade"
   ```
4. Voltar para a branch principal:
   ```
   git checkout main
   ```
5. Mesclar a nova funcionalidade:
   ```
   git merge nova-funcionalidade
   ```
#### Diferença entre Merge e Rebase
A diferença entre **merge** e **rebase** no Git está principalmente na forma como eles integram alterações de uma branch a outra. Aqui estão os principais pontos:

##### Merge (Mesclagem)

1. **Como funciona**:
   - O `git merge` combina duas branches criando um novo commit de "mesclagem" que une o histórico das duas branches.

2. **Preservação do Histórico**:
   - O merge preserva o histórico completo de ambas as branches. Isso significa que você pode ver claramente onde a branch foi separada e como as alterações foram integradas depois.

3. **Uso**:
   - Geralmente, é usado quando se deseja manter um registro completo de todos os desenvolvimentos e eventos do projeto. É útil em equipes onde a clareza do histórico é importante.

4. **Comando**:
   ```
   git merge <branch>
   ```

5. **Histórico**: 
   - O gráfico do histórico apresentará um formato de árvore, mostrando claramente os commits paralelos.

##### Rebase

1. **Como funciona**:
   - O `git rebase` traz commits de uma branch e os "reaplica" em outra branch. Isso reescreve o histórico, movendo toda a sequência de commits para o ponto final da branch atual.

2. **Reescrita do Histórico**:
   - O rebase altera o histórico de commits. Isso pode resultar em um histórico mais linear, sem a complexidade das mesclagens, mas pode complicar a colaboração se não for bem gerenciado.

3. **Uso**:
   - É comum usar rebase para simplificar o histórico quando se trabalhou em branchs curtas ou para integrar uma branch com muitos commits antes de um merge final (para evitar uma mesclagem complexa).

4. **Comando**:
   ```
   git rebase <branch>
   ```

5. **Histórico**: 
   - O gráfico do histórico será linear, mostrando uma sequência contínua de commits.

##### Resumindo

- **Merge**:
  - Mantém o histórico completo e preserva a estrutura do projeto.
  - Melhora a compreensão de como o projeto evoluiu, mas pode resultar em um histórico mais complicado.

- **Rebase**:
  - Cria um histórico linear, tornando-o mais fácil de seguir.
  - Pode ocultar a complexidade do desenvolvimento paralelo, mas altera o histórico, o que pode causar problemas se as mudanças não forem gerenciadas corretamente.

##### Exemplo

1. **Merge**:
   ```
   git checkout main
   git merge nova-funcionalidade
   ```

2. **Rebase**:
   ```
   git checkout nova-funcionalidade
   git rebase main
   ``` 
   [[Voltar]](#referencias)
### Resumo de Curso de Git e Github Completo 2024
O **Git** é um sistema de controle de versão distribuído que permite que desenvolvedores acompanhem e gerenciem mudanças em projetos de software ao longo do tempo. Aqui estão os conceitos principais sobre o Git e por que ele é importante:

#### O que é o Git?

- **Controle de Versão**: Git permite que você registre alterações feitas nos arquivos de um projeto, facilitando o rastreamento de modificações ao longo do tempo.
- **Distribuído**: Cada desenvolvedor possui uma cópia completa do repositório em sua máquina, o que permite que trabalhe offline e contribua de forma independente.
- **Branching e Merging**: Git facilita a criação de branches, permitindo que você trabalhe em várias funcionalidades ou correções simultaneamente. As branches podem ser mescladas de forma eficiente.
- **Integridade e Performance**: Git usa um hash criptográfico para garantir a integridade dos dados e é otimizado para desempenho, mesmo em projetos grandes.

### Importância do Git

1. **Colaboração**: Git permite que equipes de desenvolvedores trabalhem de forma simultânea em um projeto, facilitando a integração das contribuições de cada um e minimizando conflitos.

2. **Histórico**: Ele mantém um registro completo de todas as alterações, permitindo que você revise o histórico do projeto, recupere versões anteriores e entenda como evoluiu ao longo do tempo.

3. **Segurança**: O uso de hashes criptográficos para identificar commits garante que as alterações não possam ser alteradas sem rastreio, oferecendo segurança adicional.

4. **Flexibilidade**: Git permite que você experimente novas funcionalidades em branches separadas, sem comprometer o código estável na branch principal.

5. **Comunidade e Ecossistema**: Git é suportado por uma ampla gama de ferramentas e plataformas, como GitHub, GitLab e Bitbucket, que oferecem funcionalidades adicionais para colaboração, integração contínua e gerenciamento de projetos.

[[Voltar]](#referencias)


### Resumo de Entendendo Git | (não é um tutorial!

O **Git** é uma ferramenta fundamental para desenvolvedores, e sua importância pode ser destacada em vários aspectos:

 1. **Controle de Versão**  
 O Git permite que desenvolvedores acompanhem e registrem alterações feitas no código, o que é vital para manter um histórico claro e recuperável do projeto.  
   
   2. **Colaboração**  
 Git facilita o trabalho em equipe, permitindo que vários desenvolvedores trabalhem em paralelo em diferentes partes do projeto. As branches permitem que as equipes desenvolvam novas funcionalidades sem interferir no código principal.  

3. **Manejo de Conflitos**  
Ao lidar com merges, Git oferece ferramentas para resolver conflitos que possam surgir quando duas ou mais alterações são feitas simultaneamente, garantindo uma integração mais suave  

4. **Segurança e Integridade**  
O sistema utiliza hashes criptográficos para garantir que os dados não sejam alterados de forma não intencional, aumentando a confiança na integridade dos dados do projeto.  

5. **Backups e Recuperação**  
Como cada desenvolvedor possui uma cópia local do repositório, é fácil recuperar versões anteriores do código e voltar para uma versão estável em caso de problemas.

6. **Experimentação Segura**  
Desenvolvedores podem criar branches para experimentar novas ideias ou funcionalidades sem afetar o código estável. Isso encoraja a inovação e a experimentação. 

7. **Histórico Detalhado**  
O Git fornece um histórico completo de todas as alterações, o que é útil não apenas para auditorias, mas também para entender como e por que determinadas decisões foram tomadas ao longo do desenvolvimento.  

8. **Integração com Ferramentas e Plataformas**  
Git se integra bem com diversas plataformas como GitHub, GitLab e Bitbucket, facilitando a gestão de projetos e a colaboração em um ambiente mais amplo com funcionalidades adicionais, como integração contínua e revisão de código.

Em resumo, o Git é essencial para o desenvolvimento moderno, pois melhora a colaboração, facilita o manejo de versões, garante segurança e integridade, e permite que desenvolvedores trabalhem de forma mais produtiva e organizada. Sua adoção se tornou um padrão na indústria de software, e dominar o Git é uma habilidade indispensável para qualquer desenvolvedor.

[[Voltar]](#referencias)




