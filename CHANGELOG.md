## Versão 1.1 ( Jefferson Rocha )
- Agora todas opções vão de 0-9, assim ganhamos 1 decisão a mais no menu e submenus.
- Iniciado o processo de modularização do programa.
- Adicionado no menu principal "Pedido de Socorro". O mesmo envia a saída de voz e
  um email para pessoa cadastrada.
- Mutt agora é um dependência do PRISh.
- Adicionado verificação se usuário tem internet, se não ter internet nã será enviado o 
  pedido de socorro via email.
- Adicionado opção de sair e voltar entre o menu.


## Versão 1.0a ( Jefferson Rocha )
- Adicionado localização de navegação, acima do menu.
- Agora quando a voz é executada é feita em segundo plano para ser mais ágil.

## Versão 1.0 ( Jefferson Rocha )
- Reconstruída a forma como o menu é imprimido na tela. Agora ele tem 1 menu com subcategorias.

## Versão 0.6a ( Jefferson Rocha )
- Arrumado o bug da ajuda, o logo estava entrando antes da ajuda.
- Consertada a variável que chamava a função de ajuda, trocada por array. 

## Versão 0.6 ( Jefferson Rocha )
- Adicionada a função de escolha de vozes, agora contando com masculino e feminino.
  O usuário pode controlar no arquivo de configuração.
- Retirada a opção -s, --start. Agora o programa executa sem o mesmo. Permanecido o parâmetro
  de ajuda -h, --help.
- Retirada a função _HELP e criada uma função principal para impressões de arquivos de textos
  intitulada _PRINT, assim são poupadas repetições de código.
- Adicionado o logo no início do programa com slogan com efeito write utilizando o pv.

## Versão 0.5 ( Jefferson Rocha )
- Substituído play do sox pelo paplay do pulseaudio.

## Versão 0.4 ( Jefferson Rocha )
- Trocado expansões de variáveis na entrada por somente 1 sed.

## Versão 0.3 ( Jefferson Rocha )
- Arrumado o bug das casas. Anteriormente funcionava na entrada somente com 1 casa.
  Agora se o limit_menut for maior que 9 ele altera para 2 casas.
- Retirada a função BAR, que exibia a barra. Muita informação na tela não é legal.
- Consertado bug da linha presente no arquivo 'menu.txt' as linhas em branco também eram
  interpretadas.
- Consertado bug das linhas que iniciam com símbolos ._!@$ etc... que eram interpretadas
  pelo menu.
- Velocidade de impressão do menu na tela melhorou, substituído grep pela regex do teste
  do bash.
- Adicionado um bloco de carregamento de variáveis padrão se caso o usuário não por chaves númericas
  no arquivo de configuração.

## Versão 0.2 ( Jefferson Rocha )
- Adicionadas as opções -h, --help
- A documentação de ajuda está agora externamente no diretório
  'documentacao/help.txt'.
- Adicionada a opção de colorir a saída diferente, totalmente configurável
  no arquivo de configuração.
- Criado um limite de menu, customizável no arquivo de configuração.
