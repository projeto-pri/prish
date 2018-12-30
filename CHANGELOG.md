## Versão 1.0 ( Jefferson Rocha )
- Reeconstruido a forma como o menu é imprimido na tela. Agora ele tem 1 menu com subcategorias.

## Versão 0.6a ( Jefferson Rocha )
- Arrumado bug da ajuda, o logo estava entrando antes da ajuda.
- Concertado variável que chava função de ajuda, trocado por array. 

## Versão 0.6 ( Jefferson Rocha )
- Adicionado função de escolha de vozes, agora contando com masculino e feminino.
  usuário pode controlar no arquivo de configuração.
- Retirado a opção -s, --start. Agora o programa executa sem o mesmo. Permanecido o parâmetro
  de ajuda -h, --help.
- Retirado função _HELP e criado uma função principal para impressões de arquivos de textos
  intitulada _PRINT, assim é poupado repetições de código.
- Adicionado logo no inicio do programa com slogan com efeito write utilizando o pv.

## Versão 0.5 ( Jefferson Rocha )
- Substituido play do sox pelo paplay do pulseaudio

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
