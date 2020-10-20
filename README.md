# CNJ-1

https://user-images.githubusercontent.com/37173966/96637516-2a3f2180-12f5-11eb-9178-ee60045ce233.jpeg

# Híbrida

É um projeto de software livre desenvolvido com recursos próprios, que assegura a redução no tempo de tramitação dos processos, a concretização do princípio da eficiência administrativa, auxilia no descongestionado do sistema judicial, assegura incremento da agilidade associando possiveis códigos de assunto locais com os codigos de assuntos CNJ. 

## Começando

Para executar o projeto, será necessário ter em seu computador o Python. Para instalar acesse o link:

- [Python 3 (ou acima) : Necessário para executar o projeto](https://www.python.org/downloads)

## Desenvolvimento e Execução

*Híbrida* têm uma aplicação relativamente simples, para iniciar o desenvolvimento, basta acessar pelo navegador de sua preferência o link (http://191.235.110.9:8000/)  

O link levará direto ao ambiente executável de *Híbrida* em que o usuário poderá navegar como advogado ou magistrado. 

https://user-images.githubusercontent.com/37173966/96637172-b3098d80-12f4-11eb-83a7-a830fda685e0.png


No comando advogado, é possivel incluir peças digitalizadas ou não, para que a máquina detecte se trata de um Tema repetitivo ou não. Os arquivos enviados serão lidos, os textos e palavras vetorizadas, para então fazer um levantamento otimizado do conjunto de palavras, que caracterizam como atributos necessários para a classificação de um tema repetitivo.

![tela2adv](https://user-images.githubusercontent.com/37173966/96637481-1c899c00-12f5-11eb-9ad3-a287a8b5bd69.png)

Após realizada esta análise, *Híbrida* retorna com uma assertividade maior que 93% de que o texto e seu conjunto de palavras pertencem a um tema repetitivo. (O protótipo analisa apenas o tema repetitivo 1007)

![tela3Conc](https://user-images.githubusercontent.com/37173966/96638347-55764080-12f6-11eb-9efc-233c11ccece7.png)


## Configuração

Para o ótimo desempenho do projeto é impressindivel que os aquivos para a classificação sejam PDF ou txt. O nome do arquivo a ser enviado para a classificação não poder
a conter caracteres especiais e/ou pontuações. 

## Ambiente

*Híbrida* roda no navegador, isto facilita sua utlização, permitindo o uso em qualquer ambiente.

Apos a inserção do arquivo pdf e/ou txt o hibrida classificará se a peça se enquadra em um tema repetitivo do 1007 ou não. Caso seja positiva esta afirmação, a máquina sugegirá códigos de assuntos dos tribunais TRF3, TRF4 e CNJ para a correta classificação da peça.
