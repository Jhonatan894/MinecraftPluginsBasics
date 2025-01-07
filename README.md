# Diamond Break Plugin

**Diamond Break Plugin** é um plugin para servidores Bukkit/Spigot que traz funcionalidades dinâmicas e divertidas para jogadores interagirem com blocos e itens no mundo do jogo.

## Funcionalidades

### 1. **Entrada de jogador "usuario"**
- Quando um jogador com o nome **"usuario"** entra no servidor:
  - O servidor envia uma mensagem de aviso para todos os jogadores.
  - Um raio cai no local onde o jogador aparece no mundo.

### 2. **Criação de Raios com Graveto**
- Se o jogador com o nome **"usuario"** estiver segurando um **graveto**:
  - O jogador pode criar raios a qualquer momento, mirando no local desejado e disparando raios.

### 3. **Quebra de Blocos**
- Sempre que um jogador quebra um bloco:
  - O servidor envia uma mensagem informando qual bloco foi quebrado.
  
- **Bloco de Diamante:**
  - Se um jogador **com o nome "usuario"** quebrar um bloco de diamante:
    - O servidor apenas envia uma mensagem no chat dizendo que encontrou diamantes.
  - Se um jogador **com qualquer outro nome** quebrar um bloco de diamante:
    - O jogador morre automaticamente como uma trollagem.

## Requisitos
- Servidor Bukkit ou Spigot 1.21.3 ou superior.
- Java 8 ou superior.

## Como instalar
1. Baixe o arquivo JAR do plugin.
2. Coloque o arquivo JAR na pasta `plugins` do seu servidor.
3. Reinicie ou inicie o servidor.

## Como usar
- O comportamento do plugin é totalmente automático, sem necessidade de comandos adicionais:
  - O jogador com o nome "usuario" terá efeitos especiais ao entrar no servidor e ao usar um graveto.
  - Jogadores comuns (com outro nome) terão efeitos negativos ao quebrar blocos de diamante.

## Tecnologias usadas
- Java
- API Bukkit/Spigot

## Autor
Criado por [Jhon Araujo](https://github.com/Jhonatan894).
