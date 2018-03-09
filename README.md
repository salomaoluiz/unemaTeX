# unemaTeX
O **unemaTeX** é um modelo desenvolvido baseando-se no modelo [abnTeX2](http://www.abntex.net.br/) inicialmente para a elaboração de trabalhos de conclusão de curso para acadêmicos da Faculdade de Ciências Exatas e Técnologicas (FACET) da Universidade do Estado do Mato Grosso (UNEMAT).

## Realizando o download dos softwares necessários.
Siga o Wiki para realizar o download de todos os softwares que eu utilizei para a elaboração deste projeto, para ir ao Wiki use o seguinte [link](https://github.com/salomaoluiz/LaTeXModel/wiki/Como-Instalar).

## Utilizando o Modelo.
Nós temos um Wiki que explica o funcionamento do trabalho desde os detalhes da capa até a bibliografia, utilize este [link](https://github.com/salomaoluiz/LaTeXModel/wiki/Utilizando-o-Modelo) para acessar.

## Comandos Uteis
Alguns comandos podem ser uteis durante a utilização deste modelo. Apesar de eles serem todos explicados durante o próprio modelo, pode-se usar esse guia para agilizar ou criar macros.
### Inserção de Tabela
```TeX
\begin{table}[htb]
	\IBGEtab{%
		\caption{Nome da Tabela}%
		\label{tab_Cap**}
	}{%
		\begin{tabular}{ccc}
			\toprule
			   Tipo    &     Tipo      &     Tipo      \\ \midrule\midrule
			 article   &     book      &    manual     \\
			   www     &    booklet    &   commented   \\
			  inbook   & incollection  & inproceedings \\
			jurthesis  & mastersthesis &     misc      \\
			periodical &   phdthesis   &  proceedings  \\
			techreport &  unpublished  &               \\ \bottomrule
		\end{tabular}%
	}{%
		\fonte{Insira a Fonte}%
	}
\end{table}
```
### Inserção de Figuras
```TeX
\begin{figure}[htb]
	\begin{center}
		\includegraphics[scale=1]{./Imagens/capitulo_***.png}
	\end{center}
\end{figure}
```

Outros comandos são explicados durante o próprio trabalho, comandos como:
1. Criação de Capítulos, Seções e Subseções.
2. Inserção de Equações, Matrizes, Teoremas, Provas.
3. Apresentação de códigos em linguagens de programação.
4. Utilização de citações.

# Agradecimentos
Possuo alguns agradecimentos a pessoas que me auxiliaram diretamente e indiretamente na elaboração deste trabalho. 
1. [Thiago Nascimento](https://github.com/thiagodnf/) - Seu modelo feito para a UECE foi uma inspiração para eu elaborar este modelo.
2. [Emivan Ferreira da Silva](http://buscatextual.cnpq.br/buscatextual/visualizacv.do?id=K4739409D6) - O primeiro modelo que eu utilizei para a elaboração do meu Projeto de Pesquisa foi feito utilizando o modelo desenvolvido por este professor, graças a isso desenvolvi a paixão pelo LaTeX.
