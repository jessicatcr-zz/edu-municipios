# Conclusão

Inicialmente, nosso objetivo era entender se municípios mineiros maiores tinham um desempenho no IDEB superior ao de municípios menores.
Durante o processo resolvemos introduzir uma nova categoria de municípios, os Pequenos (P), entre os Muito Pequenos (MP) e Grandes (G). Ficando no fim, com três grupos. 

A exploração inicial nos permitiu observar que, a média e a mediana do IDEB dos três grupos é bem parecida, particularmente a de MP e P é quase idêntica. Indicando que talvez nossa divisão dos municípios menores tenha sido desnecessária. E também que há uma certa homogeneidade no desempenho. 
Não obstante, o menor IDEB dos municípios MP e P está consideravelmente abaixo do menor IDEB dos municípios G, respectivamente 3.7, 4.4 e 5.6. Aqui, de certa forma, os municípios MP "se destacam" dos municípios P. Nesse ponto, adquirimos algum indício.
Já nas notas máximas, (8, 8.1, 7.4) novamente os três grupos estão bem próximos. Talvez, esse resultado seja de alguma forma contra intuitivo, mas se pensarmos que o fenômeno da desigualdade é recursivo e ocorre sensivelmente dentro de cidades grandes, talvez isso explique o fato de que municípios grandes não atinjam notas tão maiores do que municípios menores. Uma possível forma de verificar isso, seria analisar o IDEB de cada escola separadamente e fazer comparações em cima disso.

Olhando para as médias fazendo um recorte por mesorregiões mineiras, notamos uma clara correlação entre o desenvolvimento econômico e o IDEB. 
Todas as mesorregiões cuja média do IDEB ficou abaixo da média geral (6.29), com exceção do Vale do Rio Doce, estão entre as mais pobres ou em declínio econômico (considerando os indicadores socioeconômicos da Fundação SEADE*), mais especificamente: Jequitinhonha, Norte de Minas, Vale do Mucuri, Zona da Mata.
Em contrapartida, as que tiveram melhor média foram as regiões Sul/Sudoeste e Oeste de Minas.


Já no que diz respeitos às redes de escola, infelizmente não podemos dizer muita coisa sobre as escolas federais, pois só constam três na base de dados do IDEB.
A título de marcação a média das federais foi de 7.3, acima das municipais e estaduais 6.2 e 6.3, respectivamente.

A aplicação do teste de Kolmogorov-Smirnov (KS) nos permitiu concluir que não havia necessidade em separar os municípios pequenos e muito pequenos e que com relação ao IDEB os dois grupos advêm da mesma distribuição. E que de fato os dois grupos não vem da mesma distribuição que os municípios grandes.

Apesar das médias parecidas, o teste KS também nos permitiu concluir que o IDEB de escolas municipais e estaduais vem de distribuições diferentes. Na comparação das Funções de  Distribuição Acumulada (FDA/ CDF) podemos observar a distribuição da Rede Municipal quase sempre acima da Estadual.

Ademais, tínhamos como objetivo investigar se a mesorregião, o custo aluno (IDEB/matriculados) e a população do município eram suficientes para prever se o IDEB do município seria acima da média ou não. Para isso usamos um classificador KNN com 2 vizinhos. Obtivemos ótimos resultados para prever se um município teria IDEB acima da média, mas resultados pouco significativos para prever municípios abaixo da média. 
Municípios que tem IDEB acima da média compartilham de características parecidas no que diz respeito aos atributos considerados, mas o mesmo não é válido para os que estão abaixo da média. Isso de certa forma nos diz que os fatores que levam municípios a terem baixos desempenhos vão além dessas características e o problema de entendê-los é mais complexo.  

Além disso, concluímos que nem o custo aluno, nem o FUNDEB, nem o total de matriculados, nem a população do município tem uma relação linear com o IDEB.
Dificilmente encontraríamos algum dado que tivesse uma relação linear com o mesmo, já que se trata de um fenômeno complexo.

Por fim, explicitamos a relação linear entre o número de matriculados em um município e o valor recebido por meio do FUNDEB. O que já se é sabido pela fórmula de cálculo do mesmo. Apenas evidenciamos esse fato para uma reflexão sobre essa fórmula e os resultados obtidos anteriormente, que ressaltam uma necessidade de se alavancar esforços em municípios muito pequenos. 

*Fundação SEADE Indicadores Socioeconômicos, disponível em <portal.mec.gov.br/setec/arquivos/pdf/Indicadores%20Scio-econmicos.pdf>
