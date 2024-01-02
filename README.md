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

Saber o tipo de dados que cada coluna recebe:

![QUERY4](https://github.com/luisfernandogbraga/ANALISE_DE_PRODUCAO_DULOREN/assets/134460985/6dbd56df-f868-47f2-90a6-9f309b92405b)

![4](https://github.com/luisfernandogbraga/ANALISE_DE_PRODUCAO_DULOREN/assets/134460985/659743c1-84fd-4220-bc90-5a06bf2b2e3b)

Saber quais artigos existem na base de dados

![QUERY5](https://github.com/luisfernandogbraga/ANALISE_DE_PRODUCAO_DULOREN/assets/134460985/caad05af-0a73-40c3-9171-a44e540c1953)

![5](https://github.com/luisfernandogbraga/ANALISE_DE_PRODUCAO_DULOREN/assets/134460985/63b4bcf4-4148-4fbc-b98e-bc9d8a6b2fa9)


## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir um problema ou enviar um pull request.

