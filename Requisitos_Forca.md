### **Requisitos Joga da Forca**

#### **1. Requisitos Funcionais**

- **RF1**: O sistema deve permitir o registro de usuários por meio de um formulário.
- **RF2**: O sistema deve garantir que cada e-mail cadastrado seja único.
- **RF3**: O sistema deve exigir login para acessar as funcionalidades principais (como pontuações e partidas online).
- **RF4**: Após o login, o jogador deve ser direcionado a uma tela que mostre opções de jogo
- **RF5**: O sistema deve permitir que o usuário jogue sozinho contra o computador.
- **RF6**: O sistema deve fornecer uma palavra aleatória, escolhida a partir de um banco de palavras que pode ser dividido por níveis de dificuldade (fácil, médio, difícil).
- **RF7**: O sistema deve exibir a quantidade de tentativas restantes e as letras já tentadas.
- **RF8**: o sistema deve exibir o resultado (vitória ou derrota), a palavra correta e a pontuação obtida.
- **RF9**: O sistema deve permitir que um jogador crie uma sala privada ou pública
- **RF10**: o sistema deve permitir que cada jogador faça suas tentativas de letra em turnos, ou em tempo real
- **RF11**: O sistema deve calcular pontos baseando-se em fatores como número de letras descobertas, número de erros, tempo de jogo e nível de dificuldade.
- **RF12**: O sistema deve manter um ranking geral, por nível de dificuldade e/ou modo de jogo, exibindo as melhores pontuações.
- **RF13**: O sistema deve ter um banco de dados contendo palavras separadas por categoria e por nível de dificuldade.
- **RF14**: O sistema deve permitir exclusão de conta, removendo ou anonimizando dados pessoais.

----

#### **2. Requisitos Não Funcionais**

- **RNF1**: A interface deve ser intuitiva, fornecendo feedback claro sobre acertos ou erros de letra e o estado da partida.
- **RNF2**: O layout deve ser responsivo, permitindo acesso a partir de dispositivos móveis, tablets e desktops.
- **RNF3**: O sistema deve suportar um número definido de usuários simultâneos.
- **RNF4**: Escalabilidade para suportar mais jogadores conforme a demanda, especialmente em partidas multilayer.
- **RNF5**: Senhas devem ser armazenadas de forma segura no banco de dados.
- **RNF6**: O jogo deve ter alta disponibilidade, com servidor online e manutenção planejada em horários de menor uso.
- **RNF7**: O código deve ser bem estruturado, modular e documentado, facilitando correções e atualizações.