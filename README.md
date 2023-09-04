# Pontifícia Universidade Católica do Paraná

## Bacharelado em Ciência da Computação
### Trabalho de Conclusão de Curso - Avaliação 1

Como o estudo considera diversos algoritmos e implementações durante o seu desenvolvimento, dois protótipos estão sendo apresentados.

O primeiro protótipo é a utilização de dados estruturados, especificamente idade, duração do fluxo urinário e ipss score[1] para prever um indicador de alteração no fluxo urinário do paciente. Para isso foi utilizado o KNN em conjunto com outras técnicas de Aprendizado de Máquina, os resultados parciais podem ser vistos no link: [https://github.com/ednakatani/tcc/blob/main/KNN.ipynb].

O segundo protótipo tenta utilizar a extração de espectogramas, em formato de imagem, para a classificação dos áudios utilizando redes neurais, como visto em: [https://github.com/ednakatani/tcc/blob/main/NN.ipynb].

Realizando a avaliação dos resultados, apresentados na entrega anterior, foi possível determinar potencialidades e limitações das técnicas apresentadas. Dentre essas, a utilização dos dados do IPSS SCORE, dado proveniente de um formulário autodeclarado pelo paciente se mostra negativo à generalização do modelo de predição de alteração no fluxo, já que é considerado um dado tendêncioso e impreciso.
Outro ponto elencado foi a existência de uma correlação entre a energia sonora e a curva de fluxo gerado a partir da urofluxometria.

Com base na conclusão da avaliação dos modelos anteriormentes propostos, foi realizada uma nova versão de modelo de predição, tal modelo está contido no link: [https://github.com/ednakatani/tcc/blob/main/KNN_2.ipynb]
