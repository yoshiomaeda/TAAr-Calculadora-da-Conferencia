# TAAr-Calculadora-da-Conferencia
Se você não sabe o que é um TAAr essa solução não é para você rsrs (e não é nenhum demérito)

Boa tarde, Turma!

Conferir as recicladoras (TAAr) não é a coisa mais divertida do mundo, muito rabisco, muitas contas e às vezes as contas não batem. Triste isso.

Enfim, para aplacar o meu sofrimento (e quem sabe o seu também) fiz um singelo programinha em javascript para rodar no navegador do celular (mas roda em computadores também) que serve justamente para automatizar as contaiadas das conferências dos TAAr. Programa anexo.

Zero anotações manuscritas, é ir registrando as quantidades nas tabelas que o programa se encarrega das contas e indicar, progressivamente, o sucesso (amém) da contagem.

A TABELA DE CIMA E O SALDO TOTAL

É na primeira tabela (de cima) que informamos as quantidades lógicas (do sistema) para isso é  necessário preenche-la com a composição que consta no totalizador do TAAr, inclusive o saldo total do terminal.

![Visão Geral](/imagens/figura1.png)

Essa tabela tem 3 colunas:
GDisp - é onde são informados os saldos lógicos das gavetas A, B, C e D.
GavE - é onde são registrados os saldos/composição lógicos da gaveta E.
Rejeit - é onde informamos os campos de mesmo nome da fita detalhe.

Se a composição e o saldo total divergirem aparecerá uma mensagem correspondente e o valor da diferença será mostrado. Verifique e corrija. Se o preenchimento ocorreu bem aparecerá a mensagem: "Composição e saldo SOL conferem.". Nesse caso é prosseguir para a conferência.


Figura 2. Primeira tabela preenchida. Composição e saldo total conferem:


Figura 3. Primeira tabela preenchida. Composição e saldo total diferem:


A TABELA DE BAIXO

É na segunda tabela (de baixo) que as quantidades apuradas do terminal são impostadas, não é necessário arrumar/separar as cédulas das gavetas, é só contar. Especial atenção ao cassete 'E': contar no modo MIX da contadora-classificadora e registrar a composição detalhada (tecla DETAIL da contadora).
Os cassetes A, B, C e D, sem detalhes, é só contar e registrar.

Figura 4. As duas tabelas. Cassetes conferidos sem diferença:

Os totais apurados de cada tipo de cédula são mostrados depois da última coluna da tabela e as eventuais diferenças entre as quantidades físicas e lógicas serão mostradas na sequência entre parênteses, se tiver sinal negativo quer dizer falta, senão é sobra. Veja exemplo a seguir.



Figura 5. A segunda tabela com diferenças. Pelas quantidades registradas sobrou uma cédula [notação (1) ❌️] de R$10 mas faltou uma cédula [notação (-1) ❌️] de R$20, resultando numa diferença total de R$10 a menor:


Já  escrevi demais...

Só que não. Observações:
1) o programa não grava os dados em lugar algum, o que é até recomendado haja vista a natureza do assunto.
2) mas enquanto o arquivo estiver aberto no navegador os dados serão preservados.
3) para apagar todos os dados e reiniciar as tabelas é só arrastar o dedo, a partir do centro da tela, para baixo (no Android pelo menos), seria equivalente à tecla F5 nos micros.
4) use por sua própria conta e risco. Tenho usado há uns 4 meses sem problemas.
5) sugestões são bem vindas.
