# Projeto de Analise de Dados no SQLite3

Olá, meu nome é Luis Fernando. Fui colaborador em uma empresa têxtil privada, desempenhando uma função onde recebia e libera a produção diária. Minha responsabilidade nessa logística envolve a etapa crucial de armazenamento, na qual os produtos são acondicionados, aguardando a transferência para outros setores. Nesse contexto, é imperativo identificar e armazenar cada item de maneira precisa.

Ao executar essa tarefa diariamente, percebi a oportunidade de aprimorar nosso processo por meio da análise dos dados que passam por mim. Essa iniciativa visa fornecer informações valiosas ao meu superior, contribuindo para uma gestão mais eficiente. Além disso, enxerguei essa experiência como uma chance de aplicar os conhecimentos adquiridos no curso de análise de dados utilizando Python e SQL.

Estou entusiasmado em integrar a prática cotidiana com os aprendizados teóricos, buscando aprimorar meus procedimentos operacionais e agregar valor ao fluxo de trabalho.

Este projeto tem como objetivo importar dados de uma planilha Ods (excel) para um banco de dados SQLite3, para uma leitura mais rápida. Ele utiliza a biblioteca pandas para manipulação de dados e o SQLite3 para visualização dos dados.

## OBJETIVO DO PROJETO É CRIAR INSIGHTS VALIOSOS PARA POSSIVEIS DICISÕES POSSIVEIS.
 

## Requisitos

- Python 3.x
- Bibliotecas: pandas, openpyxl
- Sqlite3

## Instalação

1. Clone o repositório:

    ```bash
    git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/luisfernandogbraga/ANALISE_DE_PRODUCAO_DULOREN.git)
    ```

2. execute o codigo python se houver modificado ao adicionado algum dado a planilha 'controle'. OBS: A planilha é atualizada diáriamente

3. Execute o sql abrindo o arquivo producao.db . Nome da tabel: producao 

  
## Estrutura do Projeto

- `controle.ods`: Planilha Excel contendo os dados.
- `Arquivo.csv`: Arquivo CSV temporário gerado durante a importação.
- `producao.db`: Banco de dados SQLite3 para armazenar os dados.


## Resultados das analises feitas na SQL

Qual é a sua etrutura:

![Captura de tela 2024-01-13 191013](https://github.com/luisfernandogbraga/ANALISE_DE_PRODUCAO_DULOREN/assets/134460985/22d204e4-fad8-4e62-9637-023d1081a368)


Qual é o total de metros que cada artigo á produziu:

![METRAGEM DE CADA ARTIGO](https://github.com/luisfernandogbraga/ANALISE_DE_PRODUCAO_DULOREN/assets/134460985/4e2f658e-1fcd-4889-9dad-b3047b6263dc)

Entre os artigos belles 15 e muriti 14, qual é a metregem:

![entre belles 15 e muriti 14](https://github.com/luisfernandogbraga/ANALISE_DE_PRODUCAO_DULOREN/assets/134460985/3ba2445e-ccf3-40e0-aadb-d77ffd477027)

Qual máquina produziu mais do artigo belles 15:

![Captura de tela 2024-01-13 190533](https://github.com/luisfernandogbraga/ANALISE_DE_PRODUCAO_DULOREN/assets/134460985/8095ee6e-9d08-4157-9799-95c9f8eed155)

Produção do dia 12/01/2024

![Captura de tela 2024-01-13 190629](https://github.com/luisfernandogbraga/ANALISE_DE_PRODUCAO_DULOREN/assets/134460985/7daffac3-1e66-4bf9-a812-33d7b12179d5)

![output](https://github.com/luisfernandogbraga/ANALISE_DE_PRODUCAO_DULOREN/assets/134460985/ea054c8f-ee19-4401-af8c-6084f0a399e1)

![1](https://github.com/luisfernandogbraga/ANALISE_DE_PRODUCAO_DULOREN/assets/134460985/5b18f0c1-4d33-4a06-b88c-21e6ffefaf60)

![1](https://github.com/luisfernandogbraga/ANALISE_DE_PRODUCAO_DULOREN/assets/134460985/fe0283c3-6dd6-471b-ad93-aff740f548b3)

![1](https://github.com/luisfernandogbraga/ANALISE_DE_PRODUCAO_DULOREN/assets/134460985/a838a82f-8231-4632-aea5-e3b29a0fc89b)








## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir um problema ou enviar um pull request.

