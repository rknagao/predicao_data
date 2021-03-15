# Como (não) fazer previsão de datas

O objetivo deste projeto foi prever os dias dos futuros pregãos para os 40 índices de Bolsa de Valores a partir do histórico obtido de determinados anos. Os índices em sua maioria são artificiais, criados para o fim desta atividade. Os índices empíricos observados na base foram criptografados para dificultar sua identificação.

O método de previsão explorado consistiu em aplicar regras baseadas em (1) dias de semana e (2) feriados, contudo, como é observável no notebook, tal abordagem mostrou-se limitada. Tal abordagem, inspirada nas práticas vigentes de funcionamento da BMF Bovespa, resultou em predições desalinhadas com a realidade observada na base. Uma possível interpretação é que as premissas empregadas não foram suficientemente flexíveis para a diversidade da base de dados, como por exemplo a possibilidade de feriados móveis ao longo do ano.

Em conclusão, este projeto acabou por contribuir como uma das maneiras a se evitar abordar problemas de predição de datas como este presente.

![fail](https://media.giphy.com/media/EXHHMS9caoxAA/giphy.gif)
