# Jogo da Velha

Aplicação desktop de um jogo da velha desenvolvida em **C#** com **Windows Forms**.

O projeto permite jogar em dois modos: contra outra pessoa no mesmo computador ou contra o computador.

## Funcionalidades

- Tabuleiro tradicional 3x3.
- Modo para dois jogadores.
- Modo jogador contra computador.
- Identificação de vitória por linha, coluna ou diagonal.
- Detecção de empate.
- Botão para iniciar uma nova partida.
- Seleção do modo de jogo pela interface.
- Interface editável pelo Windows Forms Designer do Visual Studio.

## Tecnologias

- C#
- Windows Forms
- .NET Framework 4.7.2
- Visual Studio 2026 ou versão compatível

## Como executar

1. Clone o repositório:

   ```bash
   git clone https://github.com/raphaelsoares01/JogoDaVelha.git
   ```

2. Abra o arquivo `JogoDaVelha.slnx` no Visual Studio.
3. Aguarde o carregamento do projeto.
4. Compile a solução usando **Build > Build Solution**.
5. Execute pressionando `F5` ou clicando em **Start**.

## Como jogar

1. Escolha um modo de jogo:
   - **Dois jogadores**: duas pessoas jogam no mesmo computador.
   - **Jogador contra computador**: o jogador utiliza `X` e o computador utiliza `O`.
2. Clique em uma casa vazia do tabuleiro.
3. O jogo alternará os jogadores automaticamente.
4. Use o botão **Novo jogo** para reiniciar a partida.

## Estrutura principal

```text
JogoDaVelha/
├── JogoDaVelha.slnx
├── JogoDaVelha/
│   ├── Form1.cs                  # Lógica do jogo
│   ├── Form1.Designer.cs         # Controles e layout editáveis
│   ├── Program.cs                # Ponto de entrada da aplicação
│   └── JogoDaVelha.csproj        # Configuração do projeto
└── README.md
```

## Alterando o design

Para editar a interface visualmente:

1. Abra `Form1.cs` no Solution Explorer.
2. Clique com o botão direito no arquivo.
3. Selecione **View Designer** ou **Exibir Designer**.
4. Edite os controles diretamente no formulário.

A lógica do jogo está no arquivo `Form1.cs`, enquanto os controles visuais ficam no arquivo `Form1.Designer.cs`.

## Contribuição

1. Crie uma branch para sua alteração:

   ```bash
   git checkout -b minha-alteracao
   ```

2. Faça as alterações e teste o projeto.
3. Registre um commit:

   ```bash
   git add .
   git commit -m "Descreve a alteração"
   ```

4. Envie a branch para o GitHub:

   ```bash
   git push origin minha-alteracao
   ```

## Licença

Este projeto está disponível para fins educacionais e de estudo.
