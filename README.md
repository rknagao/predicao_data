# Como (não) fazer previsão de datas

O objetivo deste projeto foi prever os dias dos futuros pregões para índices de Bolsa de Valores a partir de dados histórico obtido do passado. Basicamente, a predição deveria indicar se uma data futura teria pregão ou não. Apesar da maioria dos índices financeiros terem sido criados para esta atividade, a base também contém índices reais, porém criptografados para dificultar sua identificação.

O método de previsão explorado neste projeto consistiu em aplicar regras baseadas em (1) dias de semana e (2) feriados, contudo, como é observável no notebook, tal abordagem mostrou-se limitada, resultando em predições erradas durante a avaliação das estimações. Tal abordagem, apesar de inspirada nas práticas vigentes de funcionamento da BMF Bovespa, resultou em predições desalinhadas com os dados observados na base. Uma possível interpretação é que as premissas empregadas não foram suficientemente flexíveis para, descpnsiderando, por exemplo, a possibilidade de feriados móveis ao longo do ano.

Em conclusão, este projeto acabou por contribuir como uma maneira de se evitar abordar problemas de predição de datas.

![fail](https://media.giphy.com/media/EXHHMS9caoxAA/giphy.gif)
