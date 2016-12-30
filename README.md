# SAPF - Sistema Para Análise de Ponto de Função

"Análise de Pontos de Função (APF) é uma técnica para a medição de projetos de desenvolvimento de software, visando a estabelecer uma medida de tamanho, em Pontos de Função (PF), considerando a funcionalidade implementada."
_______________________________________________________________________________________________________________________

##Interface Principal
A interface principal do sistema SAPF possui 4 funcionalidades:
* Cadastrar novos projetos
* Consultar projetos ja cadastrados
* Configuração de Parâmetros do sistema
* Informações Sobre o Sistema


![apf_principal](https://cloud.githubusercontent.com/assets/6893004/21557700/55dca79e-ce17-11e6-8601-2e5dc26333e4.png)

_______________________________________________________________________________________________________________________

##Interface Cadastrar Novo Projeto
Para a inclusão de um novo projeto ao sistema se faz necessário informar alguns dados, como: Linguagem; Data Prevista de inicio e Quantidade de desenvolvedores. 

![sapf_cadastrarprojeto](https://cloud.githubusercontent.com/assets/6893004/21557703/6cdb5ecc-ce17-11e6-93cb-a0bfda770b36.png)

Após a inclusão dos dados requeridos, é hora de cadastrar as funções conhecidas do sistema. O usuário deve conhecer toda a parte teórica descrita na literatura sobre análise de pontos de função:
* Tipo de Função (ALI, AIE, EE, SE, CE);
* Tipo de Dados;
* Tipo de Registro;

Mediante a inclusão dessas informações, o sistema calcula a Complexidade e a quantidade de Pontos de Função.

![sapf_cadastrofuncao](https://cloud.githubusercontent.com/assets/6893004/21558178/dc8d764c-ce1c-11e6-8234-9bffe6c5b05b.png)

_______________________________________________________________________________________________________________________

##Interface Consultar Projetos
Por padrão, a pasta xmls, situada dentro do repositório do sistema SAPF, guarda os arquivos dos projetos cadastrados. 
É necessário clicar em IMPORTAR e selecionar a pasta onde se encontra seu projeto.

![sapf_consultarprojetos](https://cloud.githubusercontent.com/assets/6893004/21557704/787c001a-ce17-11e6-81e1-7b77b4ff4204.png)

Os Projetos serão listados. Com um duplo click, a interface de resumo do projeto se abrirá.

_______________________________________________________________________________________________________________________

##Interface Resumo do Projeto

* H/PF: Hora por Ponto de Função;
* C/H:  Custo por Hora; 

![sapf_resumoprojeto](https://cloud.githubusercontent.com/assets/6893004/21557713/87046df2-ce17-11e6-97f2-3032157c0c96.png)

_______________________________________________________________________________________________________________________

##Relatório
* Estimativa de Tempo Por Função;
* Estimativa de Valor por Função para compensar os recursos empregados(Equipe, tempo, complexidade).

OBS: Vale resaltar que os valores encontrados caracterizam uma sujestão retorno financeiro para compensar 
os recursos empregados na produção do software, não necessariamente um preço de venda. 

![relatorio_apf](https://cloud.githubusercontent.com/assets/6893004/21557719/9a7c620e-ce17-11e6-9b07-3051ce9f785d.png)

_______________________________________________________________________________________________________________________

##Interface Parâmetros

* Custo Por Hora (C/H): Valor que se pretende arecardar por hora empenhada ao projeto;
* Quantidade Hora Por Dia: Quantidade de horas dedicadas ao projeto por dia;

Podemos observar que cada projeto é realizado atraves do uso de uma tecnologia de programação (linguagem). Cada linguagem de programação
possui um valor de produtividade. O usuário deve realizar o cadastro e adaptar este valor a sua realidade (ou da sua equipe).
Caso não tenha muita experiência na linguagem, deverá aumentar o valor proporcionalmente a inexperiência.
Caso tenha um amplo conhecimento na linguagem, poderá diminuir o valor usado como referência na TABELA DE PRODUTIVIDADE DAS LINGUAGENS (GOOGLE).


![sapf_parametros](https://cloud.githubusercontent.com/assets/6893004/21557729/bd215ea4-ce17-11e6-9e35-34aa9c91a3aa.png)

_______________________________________________________________________________________________________________________

##Interface Sobre

O sistema SAPF foi desenvolvido pelos alunos da turma M19 do curso de Sistema de informação do Instituto Federal do Espírito Santo com intuito de desenvolver tecnologia para que os profissionais da área possam se beneficiar, fazendo uma estimativa de software adequada para seus projetos.


![sapf_sobre](https://cloud.githubusercontent.com/assets/6893004/21557735/d246812e-ce17-11e6-947d-ee8f944a5adf.png)
