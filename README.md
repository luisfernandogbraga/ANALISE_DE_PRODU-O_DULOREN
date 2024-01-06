# Projeto de Analise de Dados no SQLite3

Olá, meu nome é Luis Fernando. Atualmente, sou colaborador em uma empresa têxtil privada, desempenhando a função de receber e liberar a produção diária. Minha responsabilidade na logística envolve a etapa crucial de armazenamento, na qual os produtos são acondicionados, aguardando a transferência para outros setores. Nesse contexto, é imperativo identificar e armazenar cada item de maneira precisa.

Ao executar essa tarefa diariamente, percebi a oportunidade de aprimorar nosso processo por meio da análise dos dados que passam por mim. Essa iniciativa visa fornecer informações valiosas ao meu superior, contribuindo para uma gestão mais eficiente. Além disso, enxergo essa experiência como uma chance de aplicar os conhecimentos adquiridos no curso de análise de dados utilizando Python e SQL.

Estou entusiasmado em integrar a prática cotidiana com os aprendizados teóricos, buscando aprimorar nossos procedimentos operacionais e agregar valor ao nosso fluxo de trabalho.

Este projeto tem como objetivo importar dados de uma planilha Ods para um banco de dados SQLite3. Ele utiliza a biblioteca pandas para manipulação de dados e o SQLite3 para visualização dos dados.
 
## Requisitos

- Python 3.x
- Bibliotecas: pandas, openpyxl
- Sqlite3

## Instalação

1. Clone o repositório:

    ```bash
    git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/luisfernandogbraga/ANALISE_DE_PRODUCAO_DULOREN.git)
    ```

2. execute o codigo python se houver modificado ao adicionado algum dado a planilha 'controle'

3. Execute o sql abrindo o arquivo producao.db

  
## Estrutura do Projeto

- `controle.ods`: Planilha Excel contendo os dados.
- `Arquivo.csv`: Arquivo CSV temporário gerado durante a importação.
- `producao.db`: Banco de dados SQLite3 para armazenar os dados.
- 'producao': Nome da tabela.

## Resultados das analises feitas na SQL

Qual é a sua etrutura:

![info](https://github.com/luisfernandogbraga/ANALISE_DE_PRODUCAO_DULOREN/assets/134460985/cc2230b6-4220-41de-a24f-d1d2dedf3aa0)

Qual é o total de metros que cada artigo á produziu:

![METRAGEM DE CADA ARTIGO](https://github.com/luisfernandogbraga/ANALISE_DE_PRODUCAO_DULOREN/assets/134460985/4e2f658e-1fcd-4889-9dad-b3047b6263dc)

Entre os artigos belles 15 e muriti 14, qual é a metregem:

![entre belles 15 e muriti 14](https://github.com/luisfernandogbraga/ANALISE_DE_PRODUCAO_DULOREN/assets/134460985/3ba2445e-ccf3-40e0-aadb-d77ffd477027)

Qual maquina produziu mais do artigo belles 15:

![QUAL MAQUINA PRODUZ MAIS ](https://github.com/luisfernandogbraga/ANALISE_DE_PRODUCAO_DULOREN/assets/134460985/8cad7fe5-d77a-4d79-84f0-1ede74c51b9a)




## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir um problema ou enviar um pull request.

