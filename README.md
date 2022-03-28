# Astromatch

Astromatch é um app de relacionamentos inspirado no tinder. Ele é o projeto que inicia o módulo sobre *React Avançado* no curso da **Labenu**.
Foi utilizada a API [Astromatch](https://documenter.getpostman.com/view/7549981/SW12yx56?version=latest) da mesma.

### O que funciona?
Todas as funcionalidades solicitadas funcionam conforme o esperado.
É possível:

 1. Ver uma opção de perfil para escolher.
 2. Escolher entre "Dar Match" (escolha positiva) ou Descartar sugestão (escolha negativa).
 3. Ir para tela de Matches.
 4. Olhar lista de perfis que "deram match".
 5. Resetar lista de matches.

### O que não funciona?
Conforme dito, tudo funciona conforme o esperado.
Funcionalidades extras como chat, cadastro de usuário ou cancelar match não foram implementadas neste projeto.

### Detalhes técnicos
Optei por estruturar o projeto como se fosse algo escalável (o que não é o caso). É o que eu utilizaria hoje em um contexto real. De qualquer forma, venho testando e me adaptando conforme ganho experiência e aprendo novas ferramentas.

![estrutura](https://user-images.githubusercontent.com/62436902/160221337-9f7fb98d-d83f-4378-a8a8-1c64b952fd62.png)

Ainda sobre a organização do projeto, dividi os componentes entre contextos. Existem os reutilizáveis na pasta *components* na raiz do *src*. E tem a pasta *components* no contexto da *Home*, dentro da *pasta* pages. Assim acredito ser mais fácil o entendimento do código.

Apesar de alguns componentes serem "reutilizáveis", por se tratar de um projeto pequeno e com fins de aprendizado, esses mesmos componentes estão imediatamente ligados ao objetivo do trabalho em questão. Sendo assim, sei que existem formas mais adequadas de se fazer um componente reutilizável.

A aplicação pode ser utilizada em dispositivos móveis, ainda que eu não a considere "responsiva". Vi muitas formas interessantes de se trabalhar com media queries e outros elementos para ajudar na responsividade e pretendo apresentar algumas dessas formar em projetos futuros.

### Tecnologias (e dependências) utilizadas

 - React (Hooks, Routes e Context)
 - Axios
 - Styled-Components
 - React-Icons
 - Sweetalert2

#### Deploy e Imagens
[brawny-boundary.surge.sh](https://brawny-boundary.surge.sh/)

![lightHome](https://user-images.githubusercontent.com/62436902/160221250-01c99782-5204-47c5-a119-a7fcd0120820.png)
![lightList](https://user-images.githubusercontent.com/62436902/160221308-f73f2deb-f28e-4bcd-8486-d17727d1aca1.png)
![homeDark](https://user-images.githubusercontent.com/62436902/160221306-995e1341-1451-4ae6-a51d-95fce4983a5d.png)
![darkList](https://user-images.githubusercontent.com/62436902/160221304-ac05a74c-27c6-4c6c-bb76-fc1c663c557d.png)
