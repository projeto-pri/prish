## Versão 0.4 ( Jefferson Rocha )
- Trocado expansões de variáveis na entrada por somente 1 sed.


## Versão 0.3 ( Jefferson Rocha )
- Arrumado bug das casas. Anteriormente funcionava na entrada somente com 1 casa.
  Agora se o limit_menut for maior que 9 ele altera para 2 casas.
- Retirado a função BAR, que exibia a barra. Muita informação na tela não é legal.
- Concertado bug da linha presente no arquivo 'menu.txt' as linhas em branco tbm eram
  interpretadas.
- Concertado bug das linhas que iniciam com simbolos ._!@$ etc... que eram interpretadas
  pelo menu.
- Velocidade da impressão na tela do menu melhorou, substituido grep pela regex do teste
  do bash.
- Adicionado um bloco de carregamento de variáveis padrão se caso o usuário não por chaves númericas
  no arquivo de configuração.

## Versão 0.2 ( Jefferson Rocha )
- Adiciona opções -h, --help
- A documentação de ajuda está agora externamente no diretório
  documentacao/help.txt
- Adicionado opção de colorir a saída diferente, totalmente configuravel
  no arquivo de configuração.
- Criado um limite de menu, customizavel no arquivo de configuração.
