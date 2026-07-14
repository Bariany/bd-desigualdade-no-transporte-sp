## Desigualdade Social no Transporte Urbano

Este projeto propõe a criação e estruturação de um banco de dados relacional utilizando dados da [Pesquisa Origem e Destino 2023 do Metro SP](https://www.metro.sp.gov.br/pt_BR/pesquisa-od/). O principal objetivo é mostrar como a Engenharia de Dados e a linguagem SQL podem apoiar a tomada de decisão na gestão da mobilidade urbana, produzindo informações que auxiliem na compreensão da desigualdade social no transporte urbano. 

## Status do Projeto
Em desenvolvimento. 

## Documentação do Banco de Dados
### Visão geral das entidades existentes
| Tabela | Representa | Descrição |
|---------|------------|-----------|
| **zona** | Zonas de origem e destino | Zonas de origem e destino da pesquisa |
| **viagem** | Viagens feitas por zona | Registros das viagens entre as zonas de origem e destino |
| **renda** | Renda por zona | Informações de renda associadas às zonas |

### Dicionário de Dados
#### Tabela: `zona`
| Atributo | Tipo | Descrição |
|-----------|------|-----------|
| **id_zona** | INT | Identificador único da zona |
| **nome_zona** | VARCHAR | Nome da zona |
| **domicilio_total** | INT | Quantidade de domicílios |
| **familia_total** | INT | Quantidade de famílias |
| **populacao_total** | INT | População estimada |
| **empregos_internos** | INT | Empregos localizados na zona |
| **automoveis_particulares** | INT | Frota em posse das famílias |
| **emprego_total** | INT | Empregos totais localizados na zona |



## Tecnologias Utilizadas
Armazenamento e Modelagem de Dados: 
• PostgreSQL — Banco de dados relacional para estruturação dos dados.
• pgAdmin 4 — Interface gráfica para administração e execução de queries SQL.

 Processamento:
 • SQL — 
 • Microsoft Excel — 
 • Power Query — Ferramenta para realizar transformação e carga dos dados limpos para o Excel.

 Controle de Versão:
 • GitHub — Repositório do projeto, versionamento dos scripts SQL e documentação.

## Ciclo de Desenvolvimento
Partindo do seguinte questionamento: Trabalhadores de baixa renda gastam o dobro do tempo em deslocamento que os de alta renda em SP. Quais distritos têm os maiores tempos?
Iniciamos nosso processo da seguinte maneira:

1. Modelagem conceitual e logica
2. Modelagem fisica e implemetação
3. Extração, transformação e carregamento
4. Ingestão dos dados (importação em csv)


## Como Instalar e Rodar o Projeto
Pré-requisitos: 
Passo a passo de configuração:

## Estrutura de Pastas do Repositório
 Uma árvore simples mostrando onde estão os dados brutos, os scripts de ETL, as queries SQL e os relatórios/gráficos gerados.

## Equipe    
- [bariany](https://github.com/bariany) 
- [gaby001100](https://github.com/gaby001100)
- [lfsantosnunescomercial-Cremo](https://github.com/lfsantosnunescomercial-Cremo)

## Referências
- [Pesquisa Origem e Destino 2023 do Metro SP](https://www.metro.sp.gov.br/pt_BR/pesquisa-od/)
- [Documentação oficial]

## Licença  
Este projeto foi desenvolvido para fins acadêmicos e educacionais.  
 
