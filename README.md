# PC Build Lab

Projeto de aprendizado para desenvolver um configurador de computadores,
combinando desenvolvimento web, análise de dados e inteligência artificial.

A proposta é ajudar o usuário a escolher componentes conforme orçamento,
finalidade e preferências, apresentando custos e verificações de compatibilidade.

## Estado atual

O projeto está na fase inicial de desenvolvimento.

O repositório possui um programa básico em Python, executado pelo terminal.
Ainda não há interface web, catálogo funcional, banco de dados, integração
com IA ou visualização 3D.

## Funcionalidades planejadas

- Catálogo de componentes e suas especificações.
- Seleção e substituição de peças.
- Cálculo do preço total da configuração.
- Verificação de compatibilidades e indicação de informações ausentes.
- Armazenamento de configurações.
- Recomendação conforme orçamento e finalidade.
- Assistente com IA para interpretar pedidos e explicar sugestões.
- Visualização 3D demonstrativa.

## Etapas de desenvolvimento

1. Definir os dados do catálogo e desenhar a interface.
2. Criar a primeira página com HTML e CSS.
3. Implementar seleção de peças e cálculo do orçamento.
4. Conectar a interface ao backend em Python.
5. Salvar configurações em SQLite.
6. Implementar e testar regras de compatibilidade.
7. Desenvolver a recomendação inicial baseada em regras.
8. Integrar o assistente com IA.
9. Acrescentar a visualização 3D.
10. Avaliar experimentos de Machine Learning com dados adequados.

## Tecnologias previstas

- Python e FastAPI.
- HTML, CSS e JavaScript.
- SQLite.
- model-viewer para exibição 3D.
- pandas e scikit-learn para futuros experimentos com dados e ML.

As tecnologias serão incorporadas conforme o projeto evoluir.

## Como executar a versão atual

É necessário ter Python 3 instalado.

Execute na pasta do projeto:

    python3 main.py

A versão atual apenas exibe uma mensagem inicial no terminal.

## Critérios do projeto

- Preços demonstrativos serão identificados como fictícios.
- Verificações de compatibilidade usarão especificações verificadas.
- Informações ausentes serão sinalizadas, sem aprovação automática.
- A recomendação inicial por regras será diferenciada dos futuros modelos de ML.
- Visualizações 3D ilustrativas serão identificadas como demonstrativas.

## Licença

Consulte o arquivo LICENSE deste repositório.