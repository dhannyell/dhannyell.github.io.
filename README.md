# Bug Report

## Títulos
Tente ser curto e específico, o importante aqui é passar o problema central sem ficar muito poluido<br>
EX: <br>
> <img src="http://www.copytoread.com/wp-content/uploads/2018/10/untick-icon.png" width="15" height="15" /> Não consigo ver as informações de um equipamento quando faço uma leitura porem ao reiniciar o serviço elas aparecem <br/>
> <img src="https://icon-library.net/images/v-icon/v-icon-11.jpg" width="15" height="15"/> [AppName]-Informações do Equipamento não aparecem na tela inicial<br/>

É facil perceber qual app esta com problema e o que é o problema

### Resumo
Informações que não couberam no titulo e são relevantes devem ser ser colocadas aqui 

### Prova Visual
OK, pode ser um pouco dificil descrever um bug de forma clara, então sempre que possivel adicione uma provas visuais.<br>
EX: <br/>
<img src="https://s3-eu-west-1.amazonaws.com/prod.ghost.blog/blog/2018/11/Screen-Shot-on-Nov-15th-at-03_27-PM-700x384.png" />

#### Arquivos de logs támbem ajudar bastante, então se você tem acesso aos logs adicione eles no bug report

### Esperado vs Encontrado
Tente explicar aqui o porque que isso é um bug, mostre de maneira claro qual deveria ser o comportamento padrão da aplicação
e compare com o comportamento do bug <br/>
EX: <br/>
> Antes de atualizar a versão do aplicativo não tive nenhum problema, por isso acredito que é um bug na nova versão.<br/>
> **Resultado Esperado:** *Ao clicar no botão para começar uma leitura a pagina deveria ser atualizada e mostrar a data atual como data da ultima execução* <br/>
> **Resultado Atual:** *A pagina é atualizada mas a data não é a data atual*

### Passos para Reproduzir
Aqui é a hora de descrever detalhadamente passo a passo como o erro acontece, assuma que o desenvolvedor não faz a menor ideia do que é o erro, os passos tem que ser claros, a ideia aqui é que o desenvolvedor consiga reproduzir o erro na primeira vez que ele tentar. talvez a forma mais clara de fazer isso seja com listas númeradas.<br/>
EX: <br/>
> 1 - Na tela Inicial pesquise por YZ na caixa de busca e aperte ENTER <br>
> 2 - Quando a pagina carregar e todos os produtos aparecem, clique no ultimo produto exibido<br>
> 3 - Quando de detalhes do produto carregar clique no botaão "adicionar ao carrinho" ao lado da foto <br>
> 4 - etc <br/>
> 5 - etc ... <br/>

se existir algum passo mas complexo de ser descrito, adicionar uma imagem pode ajudar. Lembre-se que se o erro não for reproduzido ele não será corrigido. <br/>
#### Se você consegue reproduzir o erro varias vezes adicione uma contagem do número de tentativas e quantas dessas tentativas ocausionaram o problema. ex: 12/12 (12 tentativas e o problema aconteceu 12 vezes) taxa de reprodutividade 100%

#### Passo a Passo Reduzido
Existe uma alguma outra maneira de reproduzir o problema? por exemplo se eu elimninar o passo 3 ainda vou conseguir reproduzir o bug? se a resposta for sim é interessante lista isso tambem

### Ambiente 
liste o maximo de informações que julgar relevante, informação de mais é melhor que informação de menos. por exemplo se o erro estiver relacionado a lentidão do sistema, tente listar quais operações estão rodando em background, podem ser serviços da propria aplicação ou de aplicações externas, por exemplo no dia anterior estavam sendo enviados 1000 comandos e hoje foi alterado para 2000 isso por esta afetando indiretamente, enfim são muitas variaveis, ate mesmo a versão do browser pode influnciar no resultados então quanto mais informação melhor.



